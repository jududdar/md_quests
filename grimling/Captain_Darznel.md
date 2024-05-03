# Captain Darznel


## Dialog

**You say:** `hail`



>**Captain Darznel says:** Well met, friend. May I be of assistance?
end

function FieldPackTurnIn(e)

>**Captain Darznel says:** This documentation is a great start.  Judging by the amount of material here, we'll be able to formulate a new battle within the week.  It shouldn't take our linguists too long to decipher this scribble.

>**Captain Darznel says:** I cannot help but think that your presence and leadership are what made those missions such wonderful successes.  I have been authorized to give you a field promotion for your valor and bravery in combat.  You're ability to lead was the keystone in the success of those engagements.  Welcome to the rank of Garrison Officer, Soandso!

>**Captain Darznel says:** We can celebrate your promotion when we make it back to the rear.  Right now, I need you to lead another set of missions into the grunt occupied territory.  Speak to Captain Necin and show him the Soldier's chest that you've filled with the medals that you earned from the first set of raids.  He will direct you through the next several mission.  Once you have completed the missions, combine the Medallion of the Hero of Shar Vahl and your Officer's cloak in this Satchel.  Take the Locked Satchel to Sergeant Cursah.  He will assist you from that point forward.

 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_689.png" alt="" /> <a
                                href="/item/17132" data-url="17132" class="tooltip-link link">Security Satchel</a> 

 


## Turn-Ins




if ( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_869.png" alt="" /> <a
                                href="/item/8471" data-url="8471" class="tooltip-link link">Garrison Enlistment Forms</a>) then 


>**Captain Darznel says:** Let's see, yes... yes...  It looks like you signed everything in the correct spot.  That can only mean that you're not only brave, but you have some wits as well.  If you have all of your teeth and can stand on one leg until the count of five, I think we can make use of you.


>**Captain Darznel says:** Take this Polished Acrylia Sphere and give it to Scout Husman.  He's been leading raiding parties against the grunt camps.  Adventurers are great, but we need a real soldier to assist him this time.  Perhaps we will get better results with your help.


>**Captain Darznel says:** After you complete that raid, please go with Scouts Danarin and Derrin.  Once you secure those camps, bring me any grimling intelligence reports or documents that you may have found.  Place the documents and your Garrison cloak in this bag and bring them back to me.  Complete this task and you may even get a promotion.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_691.png" alt="" /> <a
                                href="/item/17130" data-url="17130" class="tooltip-link link">Garrison Field Pack</a> 

 


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_734.png" alt="" /> <a
                                href="/item/3681" data-url="3681" class="tooltip-link link">Polished Acrylia Sphere</a> 

 




elseif ( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_690.png" alt="" /> <a
                                href="/item/8480" data-url="8480" class="tooltip-link link">Sealed Field Pack</a>) then 


FieldPackTurnIn(e);


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_841.png" alt="" /> <a
                                href="/item/8414" data-url="8414" class="tooltip-link link">Jharin Officers Cloak</a> 

 




elseif ( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_690.png" alt="" /> <a
                                href="/item/8483" data-url="8483" class="tooltip-link link">Sealed Field Pack</a>) then 


FieldPackTurnIn(e);


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_841.png" alt="" /> <a
                                href="/item/8415" data-url="8415" class="tooltip-link link">Khati Sha Officers Cloak</a> 

 




elseif ( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_690.png" alt="" /> <a
                                href="/item/8481" data-url="8481" class="tooltip-link link">Sealed Field Pack</a>) then 


FieldPackTurnIn(e);


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_841.png" alt="" /> <a
                                href="/item/8416" data-url="8416" class="tooltip-link link">Khala Dun Officers Cloak</a> 

 




elseif ( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_690.png" alt="" /> <a
                                href="/item/8472" data-url="8472" class="tooltip-link link">Sealed Field Pack</a>) then 


FieldPackTurnIn(e);


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_841.png" alt="" /> <a
                                href="/item/8417" data-url="8417" class="tooltip-link link">Dar Khura Officers Cloak</a> 

 




elseif ( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_690.png" alt="" /> <a
                                href="/item/8482" data-url="8482" class="tooltip-link link">Sealed Field Pack</a>) then 


FieldPackTurnIn(e);


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_841.png" alt="" /> <a
                                href="/item/8418" data-url="8418" class="tooltip-link link">Taruun Officers Cloak</a> 

 


item_lib.return_items(e.self,e.other,e.trade);