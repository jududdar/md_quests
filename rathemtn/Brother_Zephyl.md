# Brother Zephyl



[Brother Zephyl](/npc/50321) is a level 61 Human GM Monk that spawns in [Rathe Mountains](/zone/50).



## Dialog

**You say:** `hail`



>**Brother Zephyl says:** Greetings. I am one with the [Lost Circle]. You have found me. What is it you desire?

**You say:** `lost circle`



>**Brother Zephyl says:** The [monks of the Whistling Fist] are called the Lost Circle by others. We are an ancient league of monks. Long forgotten and few yet remain. Within this realm there are only two. [Brother Qwinn] and I. We seek the items stolen from us. I seek the [idol of Zan Fi].

**You say:** `interested monk`



>**Brother Zephyl says:** Then venture to the lands of evil. The swamps of the trolls and ogres. There, seek out a monk called Raster. He has the idol. You will return here and wait for my reappearance. When we meet again, you shall hand me the idol and a red sash earned from the Ashen Order. Do so and you shall be closer to joining the brotherhood.

**You say:** `idol of zan fi`



>**Brother Zephyl says:** The idol of Zan Fi is a totem that is sacred to our brotherhood. I cannot share its secrets, but I can offer to you a reward for its return. Are you an [interested monk]?

**You say:** `brother qwinn`



>**Brother Zephyl says:** Brother Qwinn is searching for one who can return the [Code of the Whistling Fist]. I believe he is in the vicinity of the Plains of Karana.

**You say:** `code of the whistling fist`



>**Brother Zephyl says:** The tome called the Code of the Whistling Fist has been stolen from [Brother Qwinn]. It contains many secrets pertaining to our brotherhood. Thankfully, it is magically locked and only a Zan Fi master could unlock it. Still, Qwinn must see its safe return.

**You say:** `return the sash`



>**Brother Zephyl says:** Very well. Give to me that which you have been rewarded or the robe, if you have a tailored one.
end



## Turn-Ins



local text = "We had an agreement. The proof of a skilled monk, the red sash, and the idol of Zan Fi.";



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_893.png" alt="" /> <a
                                href="/item/12317" data-url="12317" class="tooltip-link link">The Idol</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_935.png" alt="" /> <a
                                href="/item/10133" data-url="10133" class="tooltip-link link">Red Sash of Order</a>) then 


>**Brother Zephyl says:** We thank you for the return of the idol of Zan Fi. Take this rare robe pattern. You shall find it useful should you aid [Brother Qwinn] in his quest. His item, the rare robe pattern, a swatch of shadow silk and a scroll containing Jonathan's Whistling Warsong. Into a sewing kit they will be going. And into the brotherhood will you. I hope you do not wish me to [return the sash].


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_790.png" alt="" /> <a
                                href="/item/12315" data-url="12315" class="tooltip-link link">Rare Robe Pattern</a> (+2000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_790.png" alt="" /> <a
                                href="/item/12315" data-url="12315" class="tooltip-link link">Rare Robe Pattern</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_935.png" alt="" /> <a
                                href="/item/10133" data-url="10133" class="tooltip-link link">Red Sash of Order</a>) then 


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_935.png" alt="" /> <a
                                href="/item/10133" data-url="10133" class="tooltip-link link">Red Sash of Order</a> 

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_931.png" alt="" /> <a
                                href="/item/12256" data-url="12256" class="tooltip-link link">Robe of the Lost Circle</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_935.png" alt="" /> <a
                                href="/item/10133" data-url="10133" class="tooltip-link link">Red Sash of Order</a>) then 


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_935.png" alt="" /> <a
                                href="/item/10133" data-url="10133" class="tooltip-link link">Red Sash of Order</a> 

 

**This NPC *should* return incorrect items given.**
