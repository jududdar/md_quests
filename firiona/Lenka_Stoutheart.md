# Lenka Stoutheart



[Lenka Stoutheart](/npc/10136) is a level 35 Barbarian Warrior that spawns in [Firiona Vie](/zone/84).



## Dialog

**You say:** `hail`



>*Lenka Stoutheart sips on her ale.  'Look what we have here, Bronto!  A would be hero!'*


e.self:DoAnim(39);


**Signaled to:**  [Bronto Thudfoot](/npc/84129)

**You say:** `interesting`



>*Lenka Stoutheart takes a jagged scimitar out of a wrap and lets you hold it.  You feel as though it is linked to the spirit world.  Lenka grabs it back.  'No, no!  You can't keep it.  But I can tell you there are plenty more weapons and armor like this.  Just have to do a little dragon slaying.'*


**Signaled to:**  [Bronto Thudfoot](/npc/84129)


e.self:DoAnim(57);

**You say:** `cabby pale ale`



**Signaled to:**  [Bronto Thudfoot](/npc/84129)


eq.set_timer("hobble",math.random(900000,1800000));

**You say:** `lizardtown`



>**Lenka Stoutheart says:** The trackers of Firiona Vie have come back with reports that the Iksar are back in force and have a city somewhere in the heart of Kunark. There goes the neighborhood...again.
end



## Timer(s)

if(e.timer == "hobble") then


**Spawn NPC:**  [\#Sir Hobble](/npc/84005) at (**y:** -1305, **x:** -3148)


**Stop timer** named *hobble*
end



## Signals

if(e.signal == 1) then


>**Lenka Stoutheart says:** We're just kidding with you, kid. Heh.  Although they are making heroes kinda small these days.  Hey, you [want to see something interesting]?

elseif(e.signal == 2) then


>**Lenka Stoutheart says:** I hear they sell the stuff in only two places. Lizardtown and Neriak. Hmmm. Now, why is that?
end



## Turn-Ins



**This NPC *should* return incorrect items given.**





