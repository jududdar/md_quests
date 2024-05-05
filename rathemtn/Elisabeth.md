# Elisabeth



[Elisabeth](/npc/50233) is a level 20 Half Elf Paladin that spawns in [Rathe Mountains](/zone/50).



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




if **Faction** >= Indifferent +50 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_980.png" alt="" /> <a
                                href="/item/12313" data-url="12313" class="tooltip-link link">A Nightfall Giant's Head</a>) then


>**Elisabeth says:** You have done well.  These giants shall soon be purged from the Commonlands and the inns will be filled once again.  Here is the mold for the Ro Greaves.  For the final component, go and ask Thomas of [Lord Searfire].


Your faction standing with [Knights of Truth](/faction/281) got better (<span class='text-success'>+20</span>)


Your faction standing with [Priests of Marr](/faction/362) got better (<span class='text-success'>+4</span>)


Your faction standing with [Steel Warriors](/faction/311) got better (<span class='text-success'>+2</span>)


Your faction standing with [Dismal Rage](/faction/271) got worse (<span class='text-danger'>-3</span>)


Your faction standing with [The Freeport Militia](/faction/330) got worse (<span class='text-danger'>-3</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1151.png" alt="" /> <a
                                href="/item/12303" data-url="12303" class="tooltip-link link">Mold of Ro Greaves</a> 

 

**This NPC *should* return incorrect items given.**





