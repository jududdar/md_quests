# Norlta Zamish



[Norlta Zamish](/npc/201416) is a level 42 Gnome Magician that spawns in [Plane of Justice](/zone/201).



## Dialog

**You say:** `hail`



>**Norlta Zamish says:** Hmm, is someone there?  I've been [wrongfully imprisoned] I'm waiting for appeal, but its been a long time.  Where, in the name of Brell, is my appeal?

**You say:** `wrongfully imprisoned`



>**Norlta Zamish says:** They have me here for a little [white lie], how can that be justice?  What is this, the Plane of Injustice? The Plane of Unfarity?

**You say:** `white lie`



>*Norlta Zamish blushes. 'Well maybe a little more than a little white lie, but I still don't deserve to be here with murderers and crazy people, and the like.  You look like a fair person, why don't you tell me if you think I should be here, want to [know what happened]?'*

**You say:** `know what happened`



>**Norlta Zamish says:** I was an apprentice for Varkon Theardor in Ak'Anon, and he sent me to scout the minotaur caves, to make sure the hero wasn't out and about.  Well I made it out to Steamfont, and it was one of the most beautiful days I'd ever seen, halfway to the caves I set down to watch some clouds go by.  Next thing I know it was hours later, I didn't rightly have time to make it to the caves and back, so I went to [Varkon] and told him the hero wasn't around.

**You say:** `Varkon`



>**Norlta Zamish says:** Well little did I know, Varkon was planning a trip to the caves, I guess I should have figured it, but I just wasn't thinking.  Hours passed, until finally word came that the minotaur hero had squished poor Varkon.  When news reached Larkon, Varkon's brother, that I was responsible for Varkon's death he asked that I be set before the Tribunal.
end



## Arrive at Waypoint Script

if(e.wp == 2) then


e.self:SetAppearance(1);
end
