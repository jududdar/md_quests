# Waltor Felligan



[Waltor Felligan](/npc/29058) is a level 61 Barbarian GM Shaman that spawns in [Halas](/zone/29).



## Dialog

**You say:** `Hail`



>**Waltor Felligan says:** Hello, me friend! I'm the resident healer o' Halas. Please inform me when ye've a need fer me talents to [bind wounds], [cure disease] or [cure poison]. Might I add, if ye're a young shaman o' Halas, ye can also [assist in gathering fungus].

**You say:** `assist in gathering fungus`



if( **Faction is** > Indifferent) then 



>**Waltor Felligan says:** As the wooly spiderlings get ready to molt, they'll carry wooly fungus. Oftentimes, one can find wooly fungus growing on their bellies. I use this in me healing practices. I'll reward ye if ye can fill this jar full o' the valuable fungus. Don't forget to combine them before ye return it to me. And have yerself some rations handy, or ye may find yerself snacking on this tasteless food source.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1018.png" alt="" /> <a
                                href="/item/17946" data-url="17946" class="tooltip-link link">Empty Jar</a>


elseif( **Faction is** == Indifferent) then



>**Waltor Felligan says:** Ye're no criminal to the Shamans o' Justice, but ye've yet to prrove yer devotion to justice.




else



>**Waltor Felligan says:** The scales o' the Shamans o' Justice dinnae tip in yer favor. Ye'd best flee ye still have the chance.




**You say:** `cure disease`



if( **Faction is** > Apprehensive) then 



**You say:** `cure disease`





>**Waltor Felligan says:** Two small quantities o' wooly fungus are needed before we can cure yer malady.



**You say:** `bind wounds`





>**Waltor Felligan says:** Before I bind yer wounds, ye must pay tribute to the Tribunal in the amount of ten gold coins.



**You say:** `cure poison`





>**Waltor Felligan says:** I'll be needing mammoth steaks to feed the unfortunate.  Then we'll drain the poison from yer veins.




else






>**Waltor Felligan says:** The scales o' the Shamans o' Justice dinnae tip in yer favor. Ye'd best flee ye still have the chance.

end



## Turn-Ins



if( **Faction is** > Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1018.png" alt="" /> <a
                                href="/item/13966" data-url="13966" class="tooltip-link link">Jar of Fungus</a>) then 








>**Waltor Felligan says:** Aye! Ye've filled the jar. I'll see to it that Holana locks this away. Tis difficult to obtain and we can only spare the talents of our young shamans. Allow me to give ye a reward. Thank ye kindly fer yer service.





Your faction standing with [Shamen of Justice](/faction/327) got better (<span class='text-success'>+10</span>)



Your faction standing with [Merchants of Halas](/faction/328) got better (<span class='text-success'>+1</span>)



Your faction standing with [Circle of Unseen Hands](/faction/223) got worse (<span class='text-danger'>-1</span>)



Your faction standing with [Coalition of Tradefolk](/faction/229) got worse (<span class='text-danger'>-1</span>)




Your faction standing with [Ebon Mask](/faction/244) got worse (<span class='text-danger'>-2</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15203" data-url="15203" class="tooltip-link link">Spell: Cure Poison</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15270" data-url="15270" class="tooltip-link link">Spell: Drowsy</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15271" data-url="15271" class="tooltip-link link">Spell: Fleeting Fury</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15275" data-url="15275" class="tooltip-link link">Spell: Frost Rift</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15036" data-url="15036" class="tooltip-link link">Spell: Gate</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15075" data-url="15075" class="tooltip-link link">Spell: Sicken</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15224" data-url="15224" class="tooltip-link link">Spell: Endure Fire</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15269" data-url="15269" class="tooltip-link link">Spell: Feet like Cat</a>) (+3000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif( **You turn in:** gold = 10) then


>**Waltor Felligan says:** The scales have been balanced and the Tribunal has spoken. Yer body shall be saved.


**Waltor Felligan casts:** [Light Healing](/spell/17) on target.

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_816.png" alt="" /> <a
                                href="/item/13445" data-url="13445" class="tooltip-link link">Mammoth Steaks</a>) then


**Waltor Felligan casts:** [Cure Poison](/spell/203) on target.


>**Waltor Felligan says:** The scales have been balanced and the Tribunal has spoken. Yer body shall be saved.

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_855.png" alt="" /> <a
                                href="/item/13967" data-url="13967" class="tooltip-link link">Wooly Fungus</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_855.png" alt="" /> <a
                                href="/item/13967" data-url="13967" class="tooltip-link link">Wooly Fungus</a>) then


**Waltor Felligan casts:** [Cure Disease](/spell/213) on target.


>**Waltor Felligan says:** The scales have been balanced and the Tribunal has spoken. Yer body shall be saved.

**This NPC *should* return incorrect items given.**





