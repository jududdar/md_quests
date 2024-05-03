# Iramai Sacredsoul





## Dialog

**You say:** `hail`



>**Iramai Sacredsoul says:** Oh, hello. I am sorry, I did not see you approach. I have been giving all of my attention to poor [Phanti] here.

**You say:** `phanti`



>**Iramai Sacredsoul says:** A few days ago Phanti started to get very ill, while she was preparing herself for another trip into [Saryrn's domain]. We are not sure exactly was caused her to fall into this malaise, although we do have our [suspicions].

**You say:** `suspicions`



>**Iramai Sacredsoul says:** Torment, the Plane of Pain. She was doing some research on the denizens there, should you [help] us, I could grant you and your companions entry. The key will not do Phanti any good for quite some time.

**You say:** `help`



>**Iramai Sacredsoul says:** Recently, the portal from the Plane of Disease has been unusually active. People have been reporting strange sounds from around the portal at night, and a few of our trackers have seen strange, almost rodent like, footprints. Our best guess is that one of the denizens of the Plane of Disease managed to make its way into our plane. If this is true, it may explain the unnaturally quick manifestation of the disease. Perhaps, the bile from one of the rodents will help us learn of the cause, and hopefully a cure.
end



## Turn-Ins



local text = "Hmm, it looks like I will need both the cure and the purified bile in order to heal Phanti.";





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_808.png" alt="" /> <a
                                href="/item/29295" data-url="29295" class="tooltip-link link">Vial of Opaque Fluid</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1134.png" alt="" /> <a
                                href="/item/29302" data-url="29302" class="tooltip-link link">Purified Bubonian Bile</a>) then 


>**Iramai Sacredsoul says:** You've done it! Praise the Tranquil! I can already see Phanti's condition improving. Take these, Phanti is not going to be doing any planar exploration any time soon. She was planning on using them to bring her research party into Torment, make good use of them, and stay safe. Thank you again for your help.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_619.png" alt="" /> <a
                                href="/item/29213" data-url="29213" class="tooltip-link link">Symbol of Torment</a> (+6250 exp)

 




elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1006.png" alt="" /> <a
                                href="/item/29315" data-url="29315" class="tooltip-link link">Bubonian Bile</a>) then


>*Iramai Sacredsoul pours the bile into a small flask, there is a puff of green smoke, which turns white as it floats into the sky. 'This is good news. It appears that this is the cause for her disease, but I have neither the tools, nor the knowledge to create a cure. There is rumor of an indigo orc who may prove useful to us in this area, but he is imprisoned in the Plane of Justice. Ask him about rare diseases. He was known to have cured many, prior to his imprisonment.*


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1134.png" alt="" /> <a
                                href="/item/29302" data-url="29302" class="tooltip-link link">Purified Bubonian Bile</a> (+50000 exp)

 

**This NPC *should* return incorrect items given.**
 