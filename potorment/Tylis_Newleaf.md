# Tylis Newleaf



[Tylis Newleaf](/npc/203373) is a level 55 Wood Elf Warrior that spawns in [Torment, the Plane of Pain](/zone/207).

local KEY_ITEM_ID = 22954; 

function RaidHasKey(client)

local group = client:GetGroup();

local raid = client:GetRaid();


if ( raid and raid.valid ) then


local member;


for i = 0, 71 do



member = raid:GetMember(i);







if ( member and member.valid ) then




if ( member:KeyRingCheck(KEY_ITEM_ID) or member:HasItem(KEY_ITEM_ID) ) then





return true;










elseif ( group and group:GroupCount() > 0 ) then


for i = 0, 5 do



local member = group:GetMember(i):CastToClient();




if ( member.valid ) then




if ( member:KeyRingCheck(KEY_ITEM_ID) or member:HasItem(KEY_ITEM_ID) ) then





return true;







else


if ( client:KeyRingCheck(KEY_ITEM_ID) or client:HasItem(KEY_ITEM_ID) ) then



return true;



return false;


## Dialog


**You say:** `hail`




>*Tylis Newleaf doesn't move, but struggles to whisper, '...help ..this torment ...will you come?  I can show you the pain... it moves in the shadows of my mind... will you assist me?'*


else




local qglobals = eq.get_qglobals(e.other);


local noflag = false;





**You say:** `will assist you`







if ( qglobals.tylis and RaidHasKey(e.other) ) then




>**Tylis Newleaf says:** Please tell me when you are ready.  I do not know if I have enough energy to channel all of you, but I can try.  When you are ready, I will channel you into my pain.



else




noflag = true;







**You say:** `we are ready`







if ( qglobals.tylis and RaidHasKey(e.other) ) then




**Tylis Newleaf casts:** [Insanity of Tylis](/spell/1134) on target.



else




noflag = true;









if ( noflag ) then



**Message:** <span class="text-warning">*Tylis Newleaf tells you, 'I sense the desire in you to help, but I don't know if you possess the kind of power needed to release me from my anguish.  Please seek out my companion Fahlia and see if she can offer you a way to better yourself before undertaking this task.'*</span>

end
