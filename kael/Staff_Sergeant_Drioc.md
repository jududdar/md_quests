# Staff Sergeant Drioc


## Dialog

**You say:** `hail`



if **Faction** >= Indifferent then



>*Staff Sergeant Drioc glances over at you with a sneer and says, 'I have much to do and organize. If you have anything of importance to say you had best speak up now or leave before I lose my patience.'*


else



**Staff Sergeant Drioc says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `do`



if **Faction** >= Indifferent then



>**Staff Sergeant Drioc says:** I oversee the deployment and of our staff and handle all mercenary contracts that come through the Militia.If you're looking for work then I may have some for you. If you're not looking for work then get out of my sight before I decide to take my frustrations out on you.


else



**Staff Sergeant Drioc says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `work`



if **Faction** >= Amiable +300 then



>*Staff Sergeant Drioc stops looking over his papers and takes a moment to size you up. You fight the urge to run in fear as the collosal humanoid considers you. After a moment he says, 'Very well. Our campaign to conquer the so called Tunarean Court has need of reinforcements. The Kromrif are already spread to thinly in the Eastern Wastes so mercenaries will have to do. Take these orders to the commanding officer in the field and follow his orders. Payment will be discussed after you complete your assignment.'*



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/1702" data-url="1702" class="tooltip-link link">Mercenary Assignment</a>


elseif **Faction** >= Indifferent then



>**Staff Sergeant Drioc says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Staff Sergeant Drioc says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

end



## Turn-Ins





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_868.png" alt="" /> <a
                                href="/item/1706" data-url="1706" class="tooltip-link link">Krofers Requisition</a>) then 


>*Staff Sergeant Drioc takes the note and begins reading. Seeing a certain passage, he squints and rereads, his brow furrowed. He glances over at you and says, 'Very well. I will assign you a squad lead by Corporal Hlash. They will rendezvous with you out in the field. Oh and take this back to Krofer.'*


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_868.png" alt="" /> <a
                                href="/item/1707" data-url="1707" class="tooltip-link link">Signed Requisition</a> 

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_864.png" alt="" /> <a
                                href="/item/1709" data-url="1709" class="tooltip-link link">Report of Failure</a>) then 


>*Staff Sergeant Drioc reads over the report, his face begins to turn red with anger. Drioc shouts, 'How can this be?! I sent you a squad of some of our best trained men and you had them destroyed!! This was supposed to be a routine raid and you return in FAILURE!! I would crush you under my boot right now if I wasn't so angry but I think I'll send you to my finacier. YOU can explain what happened and why his investments have been lost. Now take your carcass out of here!'*


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_864.png" alt="" /> <a
                                href="/item/1709" data-url="1709" class="tooltip-link link">Report of Failure</a> 

 

**This NPC *should* return incorrect items given.**
