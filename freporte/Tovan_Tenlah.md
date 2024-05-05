# Tovan Tenlah



[Tovan Tenlah](/npc/10154) is a level 61 Half Elf GM Rogue that spawns in [East Freeport](/zone/10).



## Dialog

if(eq.get_current_expansion() >= 4.0) then


**You say:** `hail`




>**Tovan Tenlah says:** I suppose you're one of Nestrals new employees, eh? Well if that's the case I can help get you outfitted with some [gear] necessary for people in this [line of work].


**You say:** `gear`




>**Tovan Tenlah says:** The first thing you need is a suit of sturdy traders clothing. Take this note to Verona Rankin and she'll help you with a suit tailored to your needs. Once you have been outfitted in your traders clothing return to me and I will inform you of your [next task].



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_868.png" alt="" /> <a
                                href="/item/19846" data-url="19846" class="tooltip-link link">Note to Verona Rankin</a>


**You say:** `next task`




>**Tovan Tenlah says:** Ready to get to work are you? Listen carefully. Outside Freeports South gate you will find one of our employees, Rigg Nostra, who is acting as an intermediary between the Coalition of Tradefolk and some recently acquired business associates. Give him this card so he knows I've sent you and he will give you further instructions. Do not mention any of our names in public. The Freeport Militia would likely impose high taxes on the Coalition if they found out about the goods being exchanged to us by our new associates.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_648.png" alt="" /> <a
                                href="/item/19917" data-url="19917" class="tooltip-link link">Bent Playing Card</a>

end



## Turn-Ins



local expansion_flag = eq.get_current_expansion();



if(expansion_flag >= 4.0 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_945.png" alt="" /> <a
                                href="/item/19918" data-url="19918" class="tooltip-link link">Rough Blue Gem</a>) then


>**Tovan Tenlah says:** Sharpen this dagger and take it with this gem and a rattlesnake skin to Verona Rankin.


Your faction standing with [Coalition of Tradefolk Underground](/faction/336) got better (<span class='text-success'>+5</span>)


Your faction standing with [Coalition of Tradefolk](/faction/229) got better (<span class='text-success'>+5</span>)


Your faction standing with [Carson McCabe](/faction/329) got better (<span class='text-success'>+1</span>)


Your faction standing with [Corrupt Qeynos Guards](/faction/230) got better (<span class='text-success'>+1</span>)


Your faction standing with [The Freeport Militia](/faction/330) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_945.png" alt="" /> <a
                                href="/item/19919" data-url="19919" class="tooltip-link link">Faceted Blue Gem</a> (+100 exp)

 


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_574.png" alt="" /> <a
                                href="/item/19920" data-url="19920" class="tooltip-link link">Dull Coalition Dirk</a> 

 

**This NPC *should* return incorrect items given.**
;

