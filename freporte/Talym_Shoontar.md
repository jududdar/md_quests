# Talym Shoontar
local factionId = 0;

## Dialog

**You say:** `hail`



>**Talym Shoontar says:** How are you, friend?  It is a good day to be alive in Antonica!  If you should happen to visit Surefall Glade, say hello to Hager Sureshot for me.

**You say:** `hager`



>**Talym Shoontar says:** Hager Sureshot is that know-nothing ranger in charge of the Protectors of the Pine. He thinks he can protect all of Surefall Glade. He is wrong.

**You say:** `poach`



>**Talym Shoontar says:** Excuse me! I am a HUNTER. A hunter of profit, not glory. Have you come to [collect the bounty] on my head? For your sake, the answer had better be [no].

**You say:** `collect`



>**Talym Shoontar says:** Then do your best, whelp! I need the practice. I hope for your sake that my gypsy friends are not nearby.

**You say:** `no`



>**Talym Shoontar says:** Too bad. I heard there is a new market for skins of your kind.
end

## Combat

if ( not e.joined and factionId ~= 0 ) then


e.self:CastToNPC():SetNPCFactionID(factionId);


end

## Signals

if ( e.self:IsEngaged() ) then


return;


local turn, bard;



if(e.signal == 1) then


>**Talym Shoontar says:** What kind of girly song was that? It stank as bas as a troll's breath.


turn = true;

elseif(e.signal == 2) then


>**Talym Shoontar says:** Ha!! That's right. Them ogres are as thick as they come.


turn = true;

elseif(e.signal == 3) then


>**Talym Shoontar says:** I ain't clappin' for no man.


turn = true;

elseif(e.signal == 4) then


>**Talym Shoontar says:** Antonius Bayle is a blithering fool.


turn = true;


**Signaled to:**  [Tlin Bowfright](/npc/10186)

elseif(e.signal == 5) then


>**Talym Shoontar says:** My grandma can outdrink any Erudite.


turn = true;

elseif(e.signal == 6) then


>**Talym Shoontar says:** Get off the stage, lass! Can't ye see he left because ye can't carry a tune?!


turn = true;

elseif(e.signal == 7) then


>**Talym Shoontar says:** Yeah!!  Sir Lucan is nothing more than a glorymonger.


turn = true;

elseif(e.signal == 10) then


factionId = e.self:CastToNPC():GetNPCFactionID();


e.self:CastToNPC():SetNPCFactionID(0);




>**Talym Shoontar says:** All right, Tlin! I am going to smash your face in!


e.self:AddToHateList(eq.get_entity_list():GetMobByNpcTypeID( [Tlin Bowfright](/npc/10186)),100); 


if ( turn ) then


bard = eq.get_entity_list():GetMobByNpcTypeID(10141);





if ( not bard.valid ) then



bard = eq.get_entity_list():GetMobByNpcTypeID(10158);





if ( not bard.valid ) then 



bard = eq.get_entity_list():GetMobByNpcTypeID(10165);





if ( bard.valid ) then



e.self:FaceTarget(bard);

end





