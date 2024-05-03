# Sergeant Caelin




## Dialog

**You say:** `hail`



>**Sergeant Caelin says:** Hail, Soandso. You have nothing to fear from the gnolls. My men and I have been sent from Qeynos to help defend Fort Jaggedpine should those worthless curs make the mistake of assuming this will be a place of easy plunder. I've fought and slain scores of gnolls in my time. Were I not bound to my post here I would go forth and drive them from their dark cave to the north myself. However, I can offer you a [bounty], should you choose to take such a mission upon yourself.

**You say:** `bounty`



>**Sergeant Caelin says:** If you choose to go and fight against the gnolls, I shall offer a bounty for every gnoll canine that you return to me. You look a bit more adventurous then many of those that live in this settlement. They seem a bit [docile].

**You say:** `docile`



>**Sergeant Caelin says:** Perhaps it comes from living in harmony with nature for an extended period of time but they are more concerned with trading food recipes and doing arts and crafts. I have offered to give them some basic training in the arts of war but they seem to have no interest. This is a dangerous world in which we live and failure to acknowledge that has meant the downfall of many a society. I won't let this happen on my watch, provided my [men] are on their toes.

**You say:** `men`



>**Sergeant Caelin says:** Guard Bossamir is a model soldier and a good man. I'm happy to have him watching my back. That Finewine character however, he is not worth the cost of the sword he wields! All he does is whine and complain. He was born with a silver spoon in his mouth and his family enrolled him in the guard to teach him some discipline but I've had no luck with him. He hasn't even turned in a [shift report] for weeks. Captain Tillin will bust me down to private if I don't deliver those soon.

**You say:** `shift report`



if( **Faction is** > Indifferent) then



>**Sergeant Caelin says:** You have been helpful in our defense efforts. However, I can not be too careful about whom I trust with carrying this information. If you truly consider yourself an ally to Qeynos then no doubt you have assisted the city in its defense before. Show me your Qeynos Badge of Honor and I'll know I can trust you fully. I'll place my mark upon it should anyone question your authority to do this service for me.


elseif( **Faction is** > Dubious)then



>**Sergeant Caelin says:** I'm not quite sure I can trust you with that information yet.


else



**Sergeant Caelin says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!

end



## Turn-Ins





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1002.png" alt="" /> <a
                                href="/item/2388" data-url="2388" class="tooltip-link link">Qeynos Badge of Honor</a>) then 


if( **Faction is** > Indifferent) then 



>**Sergeant Caelin says:** Very well. Were we within the city limits I would have had Guard Finewine court-martialed by now. Unfortunately, I don't have such a luxury out in the wild. I have written an Official Warning for Guard Finewine that states in no uncertain terms that he will most assuredly be court-martialed and spend the rest of his youth in jail unless he turns in his missing shift reports. Deliver this warning to him and return to me with his shift reports.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1002.png" alt="" /> <a
                                href="/item/8285" data-url="8285" class="tooltip-link link">Marked Qeynos Badge of Honor</a> 

 



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_861.png" alt="" /> <a
                                href="/item/8283" data-url="8283" class="tooltip-link link">Official Warning</a> 

 


elseif( **Faction is** > Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_869.png" alt="" /> <a
                                href="/item/8279" data-url="8279" class="tooltip-link link">Stack of Shift Reports</a>) then 


>**Sergeant Caelin says:** Oh praise Karana, how did you manage to get these out of him? Never mind, I don't really care. Here, take this Compiled Report to Captain Tillin in Qeynos at once.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/8280" data-url="8280" class="tooltip-link link">Compiled Report</a> 

 

elseif( **Faction is** > Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_863.png" alt="" /> <a
                                href="/item/8287" data-url="8287" class="tooltip-link link">Orders for Sergeant Caelin</a>) then 


>*Sergeant Caelin face grows pale as he reads the orders. 'Bossamir was right. The gnolls are far stronger than we expected. We lack the resources for a frontal assault so we have no choice to but to resort to covert operations and strike teh gnolls at their heart. Their leader must fall and you look like the one for the job. Take this Writ of Execution and carry out the sentence. Your target is the leader of the gnolls, Barducks Darkpaw. Affix the Writ of Execution to the Head of Barducks Darkpaw and seal it in this Black Satchel. Return to me with the Closed Black Satchel and your Marked Qeynos Badge of Honor for your just reward.*


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_862.png" alt="" /> <a
                                href="/item/8282" data-url="8282" class="tooltip-link link">Writ of Execution</a> 

 


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_689.png" alt="" /> <a
                                href="/item/17160" data-url="17160" class="tooltip-link link">Black Satchel</a> 

 

elseif( **Faction is** > Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_689.png" alt="" /> <a
                                href="/item/8286" data-url="8286" class="tooltip-link link">Closed Black Satchel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1002.png" alt="" /> <a
                                href="/item/8285" data-url="8285" class="tooltip-link link">Marked Qeynos Badge of Honor</a>) then 


>**Sergeant Caelin says:** A job well done! Perhaps now that will throw the gnolls into disarray and show them that we are not to be trifled with! The people of Qeynos and it's surrounding territories are in a great debt to you. You have prove time and again your willingness to take great risks to protect those who can't protect themselves. I am hereby empowered to grant to you an honorary rank of nobility. Take this badge and wear it proudly.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1002.png" alt="" /> <a
                                href="/item/8968" data-url="8968" class="tooltip-link link">Qeynos Badge of Nobility</a> 

 

else


local canine =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_800.png" alt="" /> <a
                                href="/item/8264" data-url="8264" class="tooltip-link link">Gnoll Canine</a>}


if(canine > 0) then



repeat




>**Sergeant Caelin says:** Good work, that is one less gnoll we need to worry about




Your faction standing with [Residents of Jaggedpine](/faction/1597) got better (<span class='text-success'>+5</span>)




Your faction standing with [Jaggedpine Treefolk](/faction/272) got better (<span class='text-success'>+2</span>)




Your faction standing with [Protectors of Pine](/faction/302) got better (<span class='text-success'>+2</span>)




Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+1</span>)




 &#127873; **You receive:** 0 (+1000 exp)

 




canine = canine - 1;



until canine == 0;


**This NPC *should* return incorrect items given.**
