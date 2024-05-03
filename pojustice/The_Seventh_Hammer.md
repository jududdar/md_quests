# The Seventh Hammer
local INVIS_TRIBUNAL_TYPE = 201423; 
local VIS_TRIBUNAL_TYPE = 201427; 

local skipAggroText;

function AnimateTribunal(animationId)

local npcList = eq.get_entity_list():GetNPCList();


if ( npcList ) then


for npc in npcList.entries do



if ( npc.valid and npc:GetNPCTypeID() == VIS_TRIBUNAL_TYPE ) then




npc:DoAnim(animationId);



end



## Dialog

**You say:** `hail`



>**The Seventh Hammer says:** Greetings mortal, it seems the council has deemed you worthy of the challenge, are you ready to face judgement?




**You say:** `ready to face`



>**The Seventh Hammer says:** Very well mortals, Now begins the test of your very souls!


skipAggroText = true;


e.self:AddToHateList(e.other);
end



## Combat

if  The Seventh Hammer enters combat  then


if ( not skipAggroText ) then



>**The Seventh Hammer says:** Prepare for judgement mortals!



eq.set_timer("verdict", math.random(181, 190) * 1000);


eq.set_timer("tremor", math.random(86, 95) * 1000);


**Stop timer** named *stop*

else


skipAggroText = false;


**Set a timer** named *stop* for 600 seconds
end



## Timer(s)


if ( e.timer == "verdict" ) then


**Set a timer** named *verdict* for 187 seconds


AnimateTribunal(42);


eq.get_entity_list():GetMobByNpcTypeID(INVIS_TRIBUNAL_TYPE):CastSpell(1108, e.self:GetID()); 




elseif ( e.timer == "tremor" ) then


**Set a timer** named *tremor* for 187 seconds


AnimateTribunal(1);


eq.get_entity_list():GetMobByNpcTypeID(INVIS_TRIBUNAL_TYPE):CastSpell(1107, e.self:GetID()); 




elseif ( e.timer == "stop" ) then


**Stop timer** named *stop*


**Stop timer** named *verdict*


**Stop timer** named *tremor*
end
