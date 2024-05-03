# Brother Qwinn


## Dialog

**You say:** `hail`



>**Brother Qwinn says:** In the name of the [Brotherhood of the Lost Circle], I greet you.

**You say:** `lost circle`



>**Brother Qwinn says:** The [monks of the Whistling Fist] are called the Lost Circle by others. We are an ancient league of monks, long forgotten and nearly extinct. Within this realm, there are only two. [Brother Zephyl] and myself. We seek the items stolen from us. I seek the [Code of Zan Fi].

**You say:** `whistling fist`



>**Brother Qwinn says:** The monks of the Whistling fist were forged from the vision of the great master, Zan Fi. When the Combine Empire reigned supreme, a single bard grew to learn the ways of the monk. This bard was Zan Fi. The brotherhood was all but destroyed in the times that followed. Now only a few remain to carry on Zan Fi's legacy.

**You say:** `code of zan fi`



>**Brother Qwinn says:** The tome called the Code of the Whistling Fist has been stolen from me. It contains many secrets pertaining to our brotherhood. Thankfully, it is magically locked and only a Zan Fi master could unlock it. I require a monk to retrieve it. Would you be an [interested monk]?

**You say:** `interested monk`



>**Brother Qwinn says:** Then venture into the depths beyond the great Solusek Mining Company. There, living among the kobolds, will be Targin the Rock. Get the book from him, then return here and wait for my reappearance. When we meet again, you shall hand me the book and a purple headband earned from the Silent Fist clan. Do so and you shall be closer to joining the brotherhood.

**You say:** `zephyl`



>**Brother Qwinn says:** Brother Zephyl is searching for one who can return the [idol of Zan Fi]. I believe he is somewhere in the vicinity of the Rathe Mountains.

**You say:** `idol of zan fi`



>**Brother Qwinn says:** The idol of Zan Fi is a totem that is sacred to our brotherhood. I cannot share its secrets, but I can tell you that [Brother Zephyl] will offer to you a reward for its return..

**You say:** `return the headband`



>**Brother Qwinn says:** Then you will return that which was earned or the robe.


end



## Turn-Ins



local text = "We had an agreement. The proof of a skilled monk, the purple headband, and the Code of the Whistling Fist.";


if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_789.png" alt="" /> <a
                                href="/item/12316" data-url="12316" class="tooltip-link link">Code of Zan Fi</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_936.png" alt="" /> <a
                                href="/item/10114" data-url="10114" class="tooltip-link link">Purple Headband</a>) then 


>**Brother Qwinn says:** We thank you for the return of the Code of the Whistling Fist. Take this sewing needle. You shall find it useful should you aid [Brother Zephyl] in his quest. His item, the needle, a swatch of shadow silk and a scroll containing Jonathan's Whistling Warsong. Into a sewing kit they will be going. And into the brotherhood will you. I hope you do not wish me to [return the headband]..


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_810.png" alt="" /> <a
                                href="/item/12314" data-url="12314" class="tooltip-link link">Needle of the Void</a> (+2000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_810.png" alt="" /> <a
                                href="/item/12314" data-url="12314" class="tooltip-link link">Needle of the Void</a>) then 


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_936.png" alt="" /> <a
                                href="/item/10114" data-url="10114" class="tooltip-link link">Purple Headband</a> 

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_931.png" alt="" /> <a
                                href="/item/12256" data-url="12256" class="tooltip-link link">Robe of the Lost Circle</a>) then 


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_936.png" alt="" /> <a
                                href="/item/10114" data-url="10114" class="tooltip-link link">Purple Headband</a> 

 

**This NPC *should* return incorrect items given.**

