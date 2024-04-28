# Konem Matse
## Dialog

**You say:** `hail`



>**Konem Matse says:** Ah, greetings, young Soandso, how are you on this fine day? Perfect day for a nice stroll through the hills, if I do say so myself.

## Arrive at Waypoint Script

if(e.wp == 2 or e.wp == 5) then


eq.set_anim(4072,1);

elseif(e.wp == 3) then


eq.set_anim(4072,0);
end

## Turn-Ins




if **You turn in:** [Message to Konem](/item/18921)


>**Konem Matse says:** Oh I see.. Phin's always after me about something.  I mean, it's not my fault the order hasn't come in yet.  Hey, since I'm so busy right now, why don't you be a friend and take this back to Phin for me, huh?





* __Faction:__ [Silent Fist Clan](/faction/309) (5)


* __Faction:__ [Guards of Qeynos](/faction/262) (1)


* __Faction:__ [Ashen Order](/faction/361) (1)


 **You receive:**  [Grathins Invoice](/item/18922) (+50 exp)

**This NPC *should* return incorrect items given.**
