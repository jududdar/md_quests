# Uner Gnarltrunk


## Dialog

**You say:** `hail`



>**Uner Gnarltrunk says:** Hello there, Soandso. Please watch where you are stepping when you're out in the field.  Nothing is more frustrating than having some fine jumjum ruined by our own careless feet. That reminds me, [Deputy Tagil] still owes us for that jumjum he stomped on the other day!

**You say:** `deputy tagil`



if **Faction** >= Amiable then 



>**Uner Gnarltrunk says:** Deputy Tagil is a fine young halfling who serves the vale well. But the other day, chasing that dirty Nillipuss, he trampled some fresh Jumjum.  He promised to make amends but it must have slipped his mind.  Please take this note to him as a friendly reminder.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18013" data-url="18013" class="tooltip-link link">A Note</a>


elseif **Faction** >= Indifferent then



>**Uner Gnarltrunk says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Uner Gnarltrunk says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

>Oh look, a talking lump of refuse.  How novel!



end



## Turn-Ins




if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_645.png" alt="" /> <a
                                href="/item/13240" data-url="13240" class="tooltip-link link">Deputy Tagils Payment</a>) then


>**Uner Gnarltrunk says:** I knew that Deputy Tagil had simply forgotten. He really is a good young halfling. Here, take this as a small payment for your time.





Your faction standing with [Storm Reapers](/faction/355) got better (<span class='text-success'>+5</span>)


Your faction standing with [Mayor Gubbin](/faction/286) got better (<span class='text-success'>+1</span>)


Your faction standing with [Merchants of Rivervale](/faction/292) got better (<span class='text-success'>+1</span>)


Your faction standing with [Unkempt Druids](/faction/324) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_921.png" alt="" /> <a
                                href="/item/13977" data-url="13977" class="tooltip-link link">Carrot</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_749.png" alt="" /> <a
                                href="/item/13100" data-url="13100" class="tooltip-link link">Fishing Pole</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_796.png" alt="" /> <a
                                href="/item/13083" data-url="13083" class="tooltip-link link">Pine Needles</a>) (+10 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-6 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**


