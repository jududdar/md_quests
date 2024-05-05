# Bren Treeclimber



[Bren Treeclimber](/npc/3027) is a level 7 Human Ranger that spawns in [Surefall Glade](/zone/3).



## Dialog

**You say:** `hail`



>**Bren Treeclimber says:** Hello, Soandso.  My name is Bren Treeclimber and I am a Protector of the Pine.  We have sworn our lives to protecting all the animals of Surefall Glade.  [Poachers], beware!

**You say:** `poacher`



>**Bren Treeclimber says:** Heh?  Oh.  Poachers are constantly after our bears for their valuable skins.  I wish those darn [Millers] would move on. Then, maybe, our bears would be left alone.  I have seen far too many of my friends die.  I will kill anyone I see harming my bears.

**You say:** `millers`



>**Bren Treeclimber says:** The Millers?!  Those butchers!  We have caught that Baobob and his sister trying to poach more than once.  And to think we took them in and gave them shelter when they were in need.  All the while, they were just trying to get to our bears.

**You say:** `mammoth`



>**Bren Treeclimber says:** Mammoth is the oldest bear in these caves. Many poachers have tried to part him from his hide. Many poachers have met their fates at theof my blade, too.

**You say:** `talym`



>**Bren Treeclimber says:** Talym Shoontar is a wanted man.  He is a very infamous poacher.  Hager Sureshot has placed a bounty upon his head.
end



## Arrive at Waypoint Script

if(e.wp == 130) then


e.self:SetRunning(true);

elseif(e.wp == 216 ) then


e.self:SetRunning(false);

elseif(e.wp == 258) then


eq.set_anim(3027,1);


>**Bren Treeclimber says:** Hey there, big bear! Good bear! Keep clear of those mean ol' poachers.

elseif(e.wp == 259) then


eq.set_anim(3027,0);
end
