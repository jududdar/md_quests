# Shamus Felligan



[Shamus Felligan](/npc/29060) is a level 61 Barbarian GM Shaman that spawns in [Halas](/zone/29).




## Dialog

**You say:** `Hail`



>**Shamus Felligan says:** Greetin's! Justice speaks through us. We're the followers o' the Tribunal. We act as judge. jury and executioner fer all misled Northmen. Sometimes we must also execute our swift justice upon evil races. such as th' [ice goblins].

**You say:** `ice goblins`



>**Shamus Felligan says:** The ice goblins are a weak race. They pose no threat to our community. but lately we've heard rumors of ice goblins that can cast spells. They're said to be as weak as the goblin warriors. so I seek to employ the talents of our young shamans to [hunt the goblin casters].

**You say:** `hunt the goblin casters`



if( **Faction is** > Indifferent) then 



>**Shamus Felligan says:** Aye. ye'll serve justice. I must find the source o' their recent spellcasting ability. I hear reports o' glowing necklaces upon these wicked beasts' necks. Get me one o' these casters' necklaces. Return them in any condition at all. Go! Justice awaits yer return.


elseif( **Faction is** == Indifferent) then



>**Shamus Felligan says:** Ye're no criminal to the Shamans o' Justice, but ye've yet to prrove yer devotion to justice.


elseif( **Faction is** < Indifferent) then





>**Shamus Felligan says:** The scales o' the Shamans o' Justice dinnae tip in yer favor. Ye'd best flee while ye still have the chance.

end



## Turn-Ins



if( **Faction is** > Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_848.png" alt="" /> <a
                                href="/item/13968" data-url="13968" class="tooltip-link link">Shattered Caster Beads</a>) then 


>**Shamus Felligan says:** Shattered! This has happened frequently! These beads are very delicate. They're useless to me now, however, I'll reward ye fer the execution of yet more goblin casters. Continue yer work. The Tribunal watches ye!





Your faction standing with [Shamen of Justice](/faction/327) got better (<span class='text-success'>+10</span>)

















Your faction standing with [Merchants of Halas](/faction/328) got better (<span class='text-success'>+1</span>)

















Your faction standing with [Circle of Unseen Hands](/faction/223) got worse (<span class='text-danger'>-1</span>)

















Your faction standing with [Coalition of Tradefolk Underground](/faction/336) got worse (<span class='text-danger'>-1</span>)

















Your faction standing with [Ebon Mask](/faction/244) got worse (<span class='text-danger'>-2</span>)



















 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15270" data-url="15270" class="tooltip-link link">Spell: Drowsy</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15275" data-url="15275" class="tooltip-link link">Spell: Frost Rift</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15075" data-url="15075" class="tooltip-link link">Spell: Sicken</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15271" data-url="15271" class="tooltip-link link">Spell: Fleeting Fury</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15279" data-url="15279" class="tooltip-link link">Spell: Spirit of Bear</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15212" data-url="15212" class="tooltip-link link">Spell: Cure Blindness</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15079" data-url="15079" class="tooltip-link link">Spell: Spirit Sight</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15050" data-url="15050" class="tooltip-link link">Spell: Summon Food</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15224" data-url="15224" class="tooltip-link link">Spell: Endure Fire</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15036" data-url="15036" class="tooltip-link link">Spell: Gate</a>) (+1600 exp)

**You receive coin:** 1 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif( **Faction is** > Indifferent and   **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_848.png" alt="" /> <a
                                href="/item/13969" data-url="13969" class="tooltip-link link">Caster Beads</a>) then



>**Shamus Felligan says:** Finally! Intact! This IS good news! I can continue me investigation now. As fer yer loyal deed, I'll offer ye this, the Gavel of Justice. May ye employ it well in the service o' justice.





Your faction standing with [Shamen of Justice](/faction/327) got better (<span class='text-success'>+25</span>)

















Your faction standing with [Merchants of Halas](/faction/328) got better (<span class='text-success'>+3</span>)

















Your faction standing with [Circle of Unseen Hands](/faction/223) got worse (<span class='text-danger'>-3</span>)

















Your faction standing with [Coalition of Tradefolk Underground](/faction/336) got worse (<span class='text-danger'>-3</span>)

















Your faction standing with [Ebon Mask](/faction/244) got worse (<span class='text-danger'>-5</span>)



















 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_567.png" alt="" /> <a
                                href="/item/6028" data-url="6028" class="tooltip-link link">Gavel of Justice</a> (+6400 exp)

**You receive coin:** 0-2 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 


**This NPC *should* return incorrect items given.**
