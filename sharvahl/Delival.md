# Delival
## On NPC Spawn

**Set a timer** named *depop* for 300 seconds
## Signals

if(e.signal==1) then


>*Delival sighs and says, 'My hands are full right now hon.'  Delival looks your way curiously and asks, 'I don't suppose you would want to [tuck] her in for me if I give you a blanket?'*

elseif(e.signal==2) then


>**Delival says:** Yes, yes, goodnight now sweetheart.


**Delival despawns.**
end

## Dialog

**You say:** `tuck`



>**Delival says:** Thank you again, have been a great help.  Here is her favorite blanket, just give it to her and she should be fine.  G'night Shainai.


 **You receive:**  [Shainais Blanket](/item/4478) 
end

## Turn-Ins



if( **You turn in:** [Shainais Bag](/item/4460)) then


>**Delival says:** Well I wish there was more I could do to repay you. Take this old compass and what change I can spare with my most sincere thanks. Now off to bed Shainai, you have had a busy day.


* __Faction:__ [Guardians of Shar Vahl](/faction/1513) (4)


**Set a timer** named *goodnight* for 10 seconds


 **You receive:**  [Compass](/item/12000) (+100 exp)

**This NPC *should* return incorrect items given.**

## Timer(s)

if(e.timer == "depop") then


**Stop timer** named *depop*


**Delival despawns.**

elseif(e.timer == "goodnight") then


**Signaled to:**  [Shainai](/npc/155339)
end
