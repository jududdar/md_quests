# Sheriff Roglio
## Dialog

**You say:** `hail`



if **Faction** >= Amiable +100 then



>**Sheriff Roglio says:** Hail, Soandso! Stand tall whenever you are speaking to the Sheriff of Rivervale. I command the warriors of this vale. You must be new to the ranks of the Guardians of the Vale, so be sure to report to your squad at once. We must protect our people. The [danger] has come closer to home. If you are not a deputy, then please leave these halls.


else



>**Sheriff Roglio says:** Please come back when you have proven yourself more and I may have a task for you.



**You say:** `danger`



if **Faction** >= Amiable then



>**Sheriff Roglio says:** What danger?!! You must be new to the community. The goblins of Clan Runnyeye have been scaling our wall somehow. You must join our forces in exterminating every one of those beasts. Your wages are earned with every four bloody goblin warbead necklaces you return to me. Now be off and fight the good fight.


elseif **Faction** >= Indifferent then



>**Sheriff Roglio says:** You are in good standing with the Guardians of the Vale. Continue with your good work and then we may speak.


else



**Sheriff Roglio says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

>Oh look, a talking lump of refuse.  How novel!


end

## Turn-Ins




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18733" data-url="18733" class="tooltip-link link">Recruitment Summons</a>) then 


>**Sheriff Roglio says:** Welcome to the Guardians of the Vale. I'm Roglio Bruth, and I run this proud little outfit. You seem to be of hearty stock, let's put you to work. Here's your guild tunic - hope it fits. Start your training right away.  Speak with the marshals of this guild.


Your faction standing with [Guardians of the Vale](/faction/263) got better (<span class='text-success'>+100</span>)


Your faction standing with [Mayor Gubbin](/faction/286) got better (<span class='text-success'>+15</span>)


Your faction standing with [Storm Reapers](/faction/355) got better (<span class='text-success'>+10</span>)


Your faction standing with [Merchants of Rivervale](/faction/292) got better (<span class='text-success'>+15</span>)


Your faction standing with [Dreadguard Outer](/faction/334) got worse (<span class='text-danger'>-15</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_678.png" alt="" /> <a
                                href="/item/13540" data-url="13540" class="tooltip-link link">Old Tan Tunic*</a> (+20 exp)

 

elseif( **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_848.png" alt="" /> <a
                                href="/item/13931" data-url="13931" class="tooltip-link link">RunnyEye Warbeads</a>}, 4) > 0


>**Sheriff Roglio says:** Good work, Deputy Soandso! We shall soon rid our countryside of the goblin threat. Here are your wages. Eat well tonight!


Your faction standing with [Guardians of the Vale](/faction/263) got better (<span class='text-success'>+1</span>)


Your faction standing with [Mayor Gubbin](/faction/286) got better (<span class='text-success'>+1</span>)


Your faction standing with [Storm Reapers](/faction/355) got better (<span class='text-success'>+1</span>)


Your faction standing with [Merchants of Rivervale](/faction/292) got better (<span class='text-success'>+1</span>)


Your faction standing with [Dreadguard Outer](/faction/334) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_717.png" alt="" /> <a
                                href="/item/13024" data-url="13024" class="tooltip-link link">Tagglefoot Tingle Drink</a> (+5000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1021.png" alt="" /> <a
                                href="/item/13023" data-url="13023" class="tooltip-link link">Bixie Berry Buns</a> 

 

**This NPC *should* return incorrect items given.**


