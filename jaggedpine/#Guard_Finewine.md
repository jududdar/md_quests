# Guard Finewine




## Dialog

**You say:** `hail`



>**Guard Finewine says:** Yeah. Hi. Lovely place this. Humid, dark, wild animals all over the place, man eating plants, snakes and bugs finding their way into my armor and biting me where a man ought not be bit. And if [Bossamir] is right, we're soon to be cut down by ravaging gnolls. Why-oh-why did I get assigned to this job? Why wasn't I assigned to Qeynos where a man can get a decent meal and sleep in a nice bed at night? Oh I'm sorry. Did I say that out loud?

**You say:** `bossamir`



>**Guard Finewine says:** Hmm. . . Yeah, I have this tendency to prattle on when I'm completely miserable. According to what my colleague Bossamir has heard, these gnolls may be tougher then we thought. But that would be par for the course anyway with the way my pitiful life is going. Woe is me. The people in this backward settlement hate me, Sergeant Caelin hates me and I assume Kane hates me too because he sent me to the armpit of Antonica on a suicide mission.

**You say:** `pate`



if( **Faction is** > Indifferent) then



>**Guard Finewine says:** Oh yes! That would be great. Bring me some Pate and let me see that warning again and maybe I can actually read the whole thing without feeling faint.


elseif( **Faction is** > Dubious)then



>**Guard Finewine says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Guard Finewine says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!

end



## Turn-Ins





if( **Faction is** > Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_861.png" alt="" /> <a
                                href="/item/8283" data-url="8283" class="tooltip-link link">Official Warning</a>) then


>**Guard Finewine says:** So he wants to send me to jail simply because I'm not filling out some silly reports? How can I be expected to think in such a decrepit state? Maybe you could help me. If I had a meal worthy of someone of my breeding then maybe I could think. Bring me something elegant, I don't want anything dull and pedestrian. I don't know what I want though. Do you have any suggestions?

elseif( **Faction is** > Indifferent and ( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1006.png" alt="" /> <a
                                href="/item/8199" data-url="8199" class="tooltip-link link">Dryad Pate</a> or  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1006.png" alt="" /> <a
                                href="/item/8198" data-url="8198" class="tooltip-link link">Potameid Pate</a>)) then 


>**Guard Finewine says:** hmm... This is interesting... The taste is very refined but sort of... odd... We're almost there but I don't think you have the recipe quite right. Rather than that peasant Brandy, use this in your recipe instead. And rather than whatever other 'meat' you were using before use a Panther Liver. You do seem to have some skill as a chef, mayhaps you could work for me some day. Prepare some Panther Pate for me. Give me the Panther Pate and let me read that warning again.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_825.png" alt="" /> <a
                                href="/item/8284" data-url="8284" class="tooltip-link link">Finewine Family Brandy</a> 

 


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_861.png" alt="" /> <a
                                href="/item/8283" data-url="8283" class="tooltip-link link">Official Warning</a> 

 

elseif( **Faction is** > Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1006.png" alt="" /> <a
                                href="/item/8278" data-url="8278" class="tooltip-link link">Panther Pate</a>) then 


>**Guard Finewine says:** Ah yes, this is perfect! I feel my head clearing already. Wait, is that the sun poking through the trees there or the moon? Hard to tell in this hideous jungle... Oh wait, yes. My shift reports for the last few weeks. Why don't you go ahead and turn these into Sergeant Caelin for me? I'm going to enjoy this fine pate.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_869.png" alt="" /> <a
                                href="/item/8279" data-url="8279" class="tooltip-link link">Stack of Shift Reports</a> 

 

**This NPC *should* return incorrect items given.**
