# Sentry Kale 



[Sentry Kale ](/npc/114003) is a level 39 Golem Cleric that spawns in [Skyshrine](/zone/114).



## Dialog

**You say:** `hail`



>**Sentry Kale  says:** Ah, the strangers, I have heard word of you. Why come you to the Skyshrine? Do you wish to be of assistance to the kin? If so, I may have a task, if you are willing.

**You say:** `willing`



>**Sentry Kale  says:** Very well, should you complete this task you will be doing a great service to the kin. As of late our supplies of velium ore have been growing short. We need to restock this supply but our normal source has run dry for the most part.  Word has come to us that the Coldain are sitting on a large source of this ore and while we have no love for these Coldain, we have arranged a deal with one of their velium miners. Deliver this note along with a payment of 50 platinum to Ungdin, in the Coldain mines. Bring the velium shipment back to me and I will see about a reward.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_860.png" alt="" /> <a
                                href="/item/1725" data-url="1725" class="tooltip-link link">Velium Delivery Note</a>
end



## Turn-Ins



local hammerrew = 0;



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_608.png" alt="" /> <a
                                href="/item/29064" data-url="29064" class="tooltip-link link">A shipment of Velium Ore</a>) then


>**Sentry Kale  says:** You have shown us yet again your loyalty to our people. Please accept this token of our gratitude. This velium is badly needed, thank you, Soandso.


Your faction standing with [Claws of Veeshan](/faction/430) got better (<span class='text-success'>+5</span>)



Your faction standing with [Yelinak](/faction/436) got better (<span class='text-success'>+1</span>)



Your faction standing with [Kromzek](/faction/448) got worse (<span class='text-danger'>-2</span>)



if(math.random(1,3) == 1) then



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_671.png" alt="" /> <a
                                href="/item/1727" data-url="1727" class="tooltip-link link">Bracer of Hammerfal</a> 

 



note = Items not always given



 &#127873; **You receive:** 0 (+5000 exp)

**You receive coin:** 0-10 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**
