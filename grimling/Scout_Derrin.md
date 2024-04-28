# Scout Derrin
## Dialog

**You say:** `hail`



>**Scout Derrin says:** Greetings, Soandso. What brings you to the battlegrounds? Looking to raid a grimling camp perhaps?

**You say:** `looking to raid`



>**Scout Derrin says:** I can lead a dozen men of my strength on a raid against a well fortified grimling encampment. It's a risky mission, but one that has the potential to yield substantial rewards. If you have the manpower and the courage, give me a glowing acrylia sphere and we'll get started.
end

## Turn-Ins

if ( **spawned NPC:**  [\#\#Scout Derrin](/npc/167682) ) then 


return;







if **You turn in:** [Glowing Acrylia Sphere](/item/4376)


 **You receive:** 0 (+1000 exp)


>**Scout Derrin says:** Draw your best weapons, memorize your most deadly spells and cast your best enhancements. Prepare yourselves for a fierce battle!


**Spawn NPC:**  [\#Scout Derrin](/npc/167036) at this location.


**Scout Derrin despawns.**

**This NPC *should* return incorrect items given.**

