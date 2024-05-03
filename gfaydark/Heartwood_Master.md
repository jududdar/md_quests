# Heartwood Master


## Dialog

**You say:** `hail`



if **Faction** >= Amiable then



>**Heartwood Master says:** Greetings, child of Tunare. As druids of the Mother of all, we may only use blunt weapons and the scimitar, all other blades are forbidden. Prove your devotion by bringing me a [rusty short sword], a [rusty long sword], a [rusty broad sword], and a [rusty bastard sword]. I will destroy them and reward your faith.


elseif **Faction** >= Indifferent then



>**Heartwood Master says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Heartwood Master says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!

end



## Turn-Ins



local text = "Tunare be praised! Do you have the rest I requested?";



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18786" data-url="18786" class="tooltip-link link">A tattered note</a>) then 


>**Heartwood Master says:** Welcome! We are the Soldiers of Tunare, the sworn protectors of Faydark. I thank you for joining our cause, we can always use the help. Here, put on this tunic, and let's get started.. you have much to learn.


Your faction standing with [Soldiers of Tunare](/faction/310) got better (<span class='text-success'>+100</span>)


Your faction standing with [King Tearis Thex](/faction/279) got better (<span class='text-success'>+15</span>)


Your faction standing with [Faydarks Champions](/faction/246) got better (<span class='text-success'>+15</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_678.png" alt="" /> <a
                                href="/item/13537" data-url="13537" class="tooltip-link link">Green and Tan Tunic*</a> (+20 exp)

 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_580.png" alt="" /> <a
                                href="/item/5013" data-url="5013" class="tooltip-link link">Rusty Short Sword</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_605.png" alt="" /> <a
                                href="/item/5016" data-url="5016" class="tooltip-link link">Rusty Broad Sword</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_590.png" alt="" /> <a
                                href="/item/5019" data-url="5019" class="tooltip-link link">Rusty Long Sword</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_577.png" alt="" /> <a
                                href="/item/5022" data-url="5022" class="tooltip-link link">Rusty Bastard Sword</a>) then


>**Heartwood Master says:** You have done well, child! Take this as a blessing from Tunare for doing her will.


Your faction standing with [Soldiers of Tunare](/faction/310) got better (<span class='text-success'>+1</span>)


Your faction standing with [King Tearis Thex](/faction/279) got better (<span class='text-success'>+1</span>)


Your faction standing with [Faydarks Champions](/faction/246) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_604.png" alt="" /> <a
                                href="/item/5047" data-url="5047" class="tooltip-link link">Tarnished Scimitar</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_602.png" alt="" /> <a
                                href="/item/6012" data-url="6012" class="tooltip-link link">Worn Great Staff</a>) (+250 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-9 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-9 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-9 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**


