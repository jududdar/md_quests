# command
function command_endurance(e)

local tar = e.self:GetTarget();

if(tar.null) then


tar = e.self;



tar:SetEndurance(tar:GetMaxEndurance());
local commands = { };
commands["endurance"] = { 50, command_endurance };

function eq.DispatchCommands(e)

local command = commands[e.command];

if(command) then


local access = command[1];


if(access > e.self:Admin()) then



e.self:Message(13, "Access level not high enough.");



return 1;






local func = command[2];


func(e);


return 1;


return 0;
end