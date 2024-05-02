# David
## Dialog

**You say:** `hail`



>**David says:** I, the keeper of the [Bracers of Ro],  welcome you.  Come and rest within our camp.  You have nothing to fear while such righteous might is gathered.

**You say:** `bracers of ro`



if **Faction** >= Indifferent +50 then



>**David says:** When you can swim the waters of Rathe and return two goblin nets from the elusive goblin net masters. then you will be rewarded the bracer mold.


elseif **Faction** >= Indifferent then



>**David says:** You and I are not one yet.   Go to Erudin and serve the Deepwater Knights.  When you can ask Lord Weligon if you are an [honored member] and he answers yes, then this is when we are one with Prexus.




else



>**David says:** We, the Deepwater Knights, know of your vile ways. You had best leave while you can.

end


## Turn-Ins



local text = "Two Deepwater goblin nets are required.";



if **Faction** >= Indifferent +50 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_677.png" alt="" /> <a
                                href="/item/12311" data-url="12311" class="tooltip-link link">Deepwater Goblin Net</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_677.png" alt="" /> <a
                                href="/item/12311" data-url="12311" class="tooltip-link link">Deepwater Goblin Net</a>) then


>**David says:** You have done well. Take the mold for the bracer.  Go forth to speak with Thomas of [Lord Searfire].  Then all components shall be known.


Your faction standing with [Deepwater Knights](/faction/242) got better (<span class='text-success'>+20</span>)


Your faction standing with [High Council of Erudin](/faction/266) got better (<span class='text-success'>+3</span>)



Your faction standing with [Heretics](/faction/265) got worse (<span class='text-danger'>-3</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1151.png" alt="" /> <a
                                href="/item/12301" data-url="12301" class="tooltip-link link">Mold of Ro Bracer</a> 

 

**This NPC *should* return incorrect items given.**
