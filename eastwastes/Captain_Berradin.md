# Captain Berradin
## Turn-Ins





if **You turn in:** [Tainted Avalanche Ale](/item/1459)


>**Captain Berradin says:** You gotta be kiddin me, Avalanche Ale? Haven't had a bottle a this stuff in ages. Brell bless you, Soandso! Glug, glug, glug...


**Set a timer** named *doanim* for 53 seconds

**This NPC *should* return incorrect items given.**

## Timer(s)

if(e.timer == "doanim") then


e.self:DoAnim(15);


**Stop timer** named *doanim*


**Set a timer** named *depop* for 5 seconds

elseif(e.timer == "depop") then


>**Captain Berradin says:** Uhhh... I'm not feeling so good. Someone call for a cleric.





**Spawn NPC:**  [\#Captain Berradin](/npc/116037) at (**y:** -61, **x:** 2365)


**Stop timer** named *depop*


**Captain Berradin despawns.**
end