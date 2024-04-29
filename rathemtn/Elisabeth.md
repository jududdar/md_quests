# Elisabeth
## Dialog

**You say:** `hail`



>**Elisabeth says:** Very good to meet you. Soandso.  I am the keeper of the [Greaves of Ro].  Please feel free to rest and recuperate here.  We shall see that you are safe from the evils of the Rathe Mountains.

**You say:** `greaves of ro`



if **Faction** >= Indifferent +50 then



>**Elisabeth says:** Go to the countryside of Freeport.  There, you shall seek out any nightfall giants .  They have terrorized the countryside for too long.  They have protection from common weapons.  Rely on magic.  I failed in tracking them down.  You shall succeed and when return any single head to me. you shall be awarded the mold for the greaves.


elseif **Faction** >= Indifferent then



>**Elisabeth says:** Go to Freeport.  There you shall find the Hall of Truth.  Within its walls you shall be instructed on how to better serve Mithaniel Marr.  When High Lord Dushire answers yes to the question, am [I an honored member], then you and I can become allies.




else



>**Elisabeth says:** Leave my presence at once. Your ways of life are not acceptable to one who follows the Truthbringer.

end

## Turn-Ins




if **Faction** >= Indifferent +50 and  **You turn in:** [A Nightfall Giant's Head](/item/12313)) then


>**Elisabeth says:** You have done well.  These giants shall soon be purged from the Commonlands and the inns will be filled once again.  Here is the mold for the Ro Greaves.  For the final component, go and ask Thomas of [Lord Searfire].


* __Faction:__ [Knights of Truth](/faction/281) (20)


* __Faction:__ [Priests of Marr](/faction/362) (4)


* __Faction:__ [Steel Warriors](/faction/311) (2)


* __Faction:__ [Dismal Rage](/faction/271) (-3)


* __Faction:__ [The Freeport Militia](/faction/330) (-3)


 **You receive:**  [Mold of Ro Greaves](/item/12303) 

**This NPC *should* return incorrect items given.**





