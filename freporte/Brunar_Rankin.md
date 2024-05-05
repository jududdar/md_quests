# Brunar Rankin



[Brunar Rankin](/npc/10173) is a level 8 Barbarian Rogue that spawns in [East Freeport](/zone/10).



## Dialog

**You say:** `hail`



>**Brunar Rankin says:** How are you? Please excuse my stench. I fish all day and night just to feed my large family. You look like an adventurer. That must be exciting. I am but a humble fisherman. Maybe someday we shall both be rich. You by your treasure and me by my catch.

**You say:** `steal`



>**Brunar Rankin says:** How dare you accuse me of being a thief!? I labor hour after hour trying to catch one fish which will bring me one copper piece to buy one slice of bread which I will split into five pieces to feed me, my sick wife and three little children, one of whom has the plague!! Poor little Repi. Now please, leave this humble little fisherman alone!

**You say:** `Gregor`



>**Brunar Rankin says:** Gregor Nasin is the barkeep at the Seafarer's Roost. He is the man who pays me for the fish I catch. A really good man.

**You say:** `fishing`



>**Brunar Rankin says:** Oh, yes.  It will be a good haul today.  Gregor will pay me plenty today.
end




## Arrive at Waypoint Script

if(e.wp == 13) then


>**Brunar Rankin says:** Here is my catch for today, Gregor


**Signaled to:**  [Gregor Nasin](/npc/10171)

elseif(e.wp == 34) then


>**Brunar Rankin says:** Ho hum, what a lovely day !


e.self:SetRunning(true);

elseif(e.wp == 39) then


e.self:SetRunning(false);

elseif(e.wp == 44) then


e.self:SetRunning(true);

elseif(e.wp == 59) then


e.self:SetRunning(false);
end

