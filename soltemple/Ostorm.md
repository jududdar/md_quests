# Ostorm



[Ostorm](/npc/80013) is a level 34 Erudite Wizard that spawns in [Temple of Solusek Ro](/zone/80).






## Dialog

if **Faction** >= Indifferent then


**You say:** `hail`




>**Ostorm says:** I am Ostorm of the Temple of Solusek Ro, guardian of the sacred crystal of Kintaz.  Be wary and keep your distance, lest the proximity of the crystal [steal] your [memories].


**You say:** `steal`




>**Ostorm says:** It is the nature of the crystal of Kintaz to steal the memories of those around it. Only I am safe, and then only because of the strong wardings placed on me by Solusek Ro himself. Are you interested in [losing] any [memories]?


**You say:** `losing`




>**Ostorm says:** Recently, I have been experimenting with the crystal, and have found that those exposed to ruby light filtered through it tend to lose the memories of their most specialized arcane skills. Are you sure you want to [lose advanced memory] of specialization?


**You say:** `advanced`




>**Ostorm says:** Be warned that once exposed to the crystal, I can not reverse the effects. If you desire exposure, fetch me a ruby.


**You say:** `gold`




>**Ostorm says:** You do not remember?  You promised me fifty gold coins for allowing you to be exposed to the sacred crystal of Kintaz.


else


**Ostorm says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!
end



## Turn-Ins



local text = "Solusek Ro does not believe in half measures.";



if **Faction** >= Indifferent and (e.other:GetClass() == 2 or e.other:GetClass() == 6 or e.other:GetClass() == 10 or e.other:GetClass() == 11 or e.other:GetClass() == 12 or e.other:GetClass() == 13 or e.other:GetClass() == 14) and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_964.png" alt="" /> <a
                                href="/item/10035" data-url="10035" class="tooltip-link link">Ruby</a>) then


>**Ostorm says:** ..hear me? Ah, you seem to be coming out of your stupor. I think you have been exposed to the crystal long enough. By the time you leave the temple, your memories should have faded. Do you have the [fifty gold] coins that you owe me?


Your faction standing with [Temple of Solusek Ro](/faction/415) got better (<span class='text-success'>+1</span>)


Your faction standing with [Shadowed Men](/faction/416) got worse (<span class='text-danger'>-1</span>)


for skill=43,47,1 do



e.other:SetSkill(skill,49);



**Message:** <span class="text-warning">*Your specialize skills have all been set to 49.*</span>


 &#127873; **You receive:** 0 (+1000 exp)

 

elseif( **You turn in:** gold = 50) then


>**Ostorm says:** Thank you.


Your faction standing with [Temple of Solusek Ro](/faction/415) got better (<span class='text-success'>+2</span>)


Your faction standing with [Shadowed Men](/faction/416) got worse (<span class='text-danger'>-2</span>)


e.other:Ding();


elseif **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_960.png" alt="" /> <a
                                href="/item/10031" data-url="10031" class="tooltip-link link">Fire Opal</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_960.png" alt="" /> <a
                                href="/item/10031" data-url="10031" class="tooltip-link link">Fire Opal</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_945.png" alt="" /> <a
                                href="/item/10000" data-url="10000" class="tooltip-link link">Lambent Stone</a>) then


>**Ostorm says:** Here is your prize - a lambent fire opal.


Your faction standing with [Temple of Solusek Ro](/faction/415) got better (<span class='text-success'>+1</span>)


Your faction standing with [Shadowed Men](/faction/416) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_960.png" alt="" /> <a
                                href="/item/10128" data-url="10128" class="tooltip-link link">Lambent Fire Opal</a> (+1000 exp)

 


elseif **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1092.png" alt="" /> <a
                                href="/item/16507" data-url="16507" class="tooltip-link link">Enchanted Platinum Bar</a>) then


>**Ostorm says:** I see that Gavel has sent you to me.  Very well, I have magnetized your platinum bar - take it.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1091.png" alt="" /> <a
                                href="/item/19049" data-url="19049" class="tooltip-link link">Magnetized Platinum Bar</a> 

 

**This NPC *should* return incorrect items given.**






