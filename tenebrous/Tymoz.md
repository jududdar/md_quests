# Tymoz


## Dialog

**You say:** `hail`



if **Faction** >= Dubious then



>**Tymoz says:** So " .. e.other:Race() .. ", you dare to stand before the mighty Tymoz?  I am the Governor of this village of the Coterie of the Eternal Night.  Do you wish to assist the Coterie, or will you better serve us as sustenance for our eternal lives?


else



**Tymoz says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `assist the coterie`



if **Faction** >= Dubious then



>**Tymoz says:** You have made an intelligent decision my friend.  Our primary foe is the meddling Validus Custodus, the militia of Katta Castellum.  I will reward you for every two damaged custodus legionnaire helms or two damaged custodus centurion helms that you present to me as proof that you have slain members of our enemies ranks.


else



**Tymoz says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

end

## Turn-Ins



local text = "I require two damaged custodus helms as proof of your deeds.";



if **Faction** >= Dubious and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_550.png" alt="" /> <a
                                href="/item/31748" data-url="31748" class="tooltip-link link">Damaged Custodus Legionnaire Helm</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_550.png" alt="" /> <a
                                href="/item/31748" data-url="31748" class="tooltip-link link">Damaged Custodus Legionnaire Helm</a>) then


>**Tymoz says:** Excellent! Two less of those self righteous Validus Custodus goons to worry about!


Your faction standing with [Coterie of the Eternal Night](/faction/1506) got better (<span class='text-success'>+1</span>)


Your faction standing with [Validus Custodus](/faction/1503) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Nathyn Illuminious](/faction/1505) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Valdanov Zevfeer](/faction/1507) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:** GiveAll( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_591.png" alt="" /> <a
                                href="/item/31750" data-url="31750" class="tooltip-link link">Blood Dipped Dart</a>,eq.ChooseRandom(0, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_591.png" alt="" /> <a
                                href="/item/31750" data-url="31750" class="tooltip-link link">Blood Dipped Dart</a>) 

 

elseif **Faction** >= Dubious and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_550.png" alt="" /> <a
                                href="/item/31749" data-url="31749" class="tooltip-link link">Damaged Custodus Centurion Helm</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_550.png" alt="" /> <a
                                href="/item/31749" data-url="31749" class="tooltip-link link">Damaged Custodus Centurion Helm</a>) then


>**Tymoz says:** Excellent! Two less of those self righteous Validus Custodus goons to worry about!


Your faction standing with [Coterie of the Eternal Night](/faction/1506) got better (<span class='text-success'>+1</span>)


Your faction standing with [Validus Custodus](/faction/1503) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Nathyn Illuminious](/faction/1505) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Valdanov Zevfeer](/faction/1507) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1157.png" alt="" /> <a
                                href="/item/31833" data-url="31833" class="tooltip-link link">Potent Vitae</a> (+5000 exp)

 

**This NPC *should* return incorrect items given.**
