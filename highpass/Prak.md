# Prak
## Signals

if(e.signal == 1) then


>**Prak says:** The boss might need some help!


local stanos = eq.get_entity_list():GetMobByNpcTypeID(5088); 


if ( stanos.valid ) then



e.self:MoveTo(stanos:GetX(), stanos:GetY(), stanos:GetZ(), -1, false);

end

## Dialog

**You say:** `hail`



>**Prak says:** Yeah, hello. I'm Prak, co-owner of the Golden Rooster. If you're thirsty, we have some great imported ales at our bar. If you're looking for a little excitement, try your hand at a little King's Court. We aim to please, my friend.

**You say:** `rid of stald`



>**Prak says:** Good.. Zannsin said you had a special talent for this sort of thing, so here's your chance to prove it. What you need to do is follow Stald on his patrol, and when the coast is clear, take him down. Good luck. Oh yeah.. not that I don't trust you or anything, but bring me back some sorta proof that Stald is dead, got it?
end

## Turn-Ins




if **Faction** >= Amiable and  **You turn in:** [Letter for Prak](/item/18795)) then


>**Prak says:** Hmm, I see. We think we've found out who the mole is in Carson's guards, some guy named Stald. We need to get rid of this guy as quickly, and as quietly, as possible. Carson doesn't want to cause a stink by eliminating one of his own men, so he asked us to do it. What about you? Do you think [you could get rid of Stald] for us?


* __Faction:__ [Carson McCabe](/faction/329) (50)


* __Faction:__ [Coalition of Tradefolk Underground](/faction/336) (37)


* __Faction:__ [Ring of Scale](/faction/304) (-12)


* __Faction:__ [Highpass Guards](/faction/332) (50)


* __Faction:__ [Merchants of Highpass](/faction/331) (50)


**Spawn NPC:**  [Guard Stald](/npc/5119) at (**y:** 127, **x:** 464)


 **You receive:** 0 (+500 exp)

elseif **Faction** >= Amiable +100 and  **You turn in:** [Stald's Badge](/item/13793)) then


>**Prak says:** Ah, boy! Looks like I owe Kaden two plat... I thought you'd fumble it up for sure. Well, you've impressed me friend. Here, take this back to Zan... I'll make sure note your fine works to Carson, too, next time we speak.


* __Faction:__ [Carson McCabe](/faction/329) (50)


* __Faction:__ [Coalition of Tradefolk Underground](/faction/336) (37)


* __Faction:__ [Ring of Scale](/faction/304) (-12)


* __Faction:__ [Highpass Guards](/faction/332) (50)


* __Faction:__ [Merchants of Highpass](/faction/331) (50)


 **You receive:**  [Message to Zannsin](/item/18028) (+0 exp)

**This NPC *should* return incorrect items given.**
