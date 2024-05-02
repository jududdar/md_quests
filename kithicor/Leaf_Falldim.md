# Leaf Falldim
## Dialog

**You say:** `hail`



>**Leaf Falldim says:** Greetings. Soandso!  Respect the woods and all its inhabitants or face the wrath of the rangers.  Do notup like [Maldyn Greenburn].

**You say:** `maldyn greenburn`



>**Leaf Falldim says:** Maldyn was once one of us.  He was the finest of archers.  Everyone aspired to be like him.  He soon was tempted to hunt.  The animals of these woods found themselves nothing more than moving targets for Maldyn's training.  We held a trial and exiled him to parts unknown.  He would take with him Morin's [Bow of Kithicor].  I was asked to find a worthy ranger to [retrieve the bow].

**You say:** `bow of kithicor`



>**Leaf Falldim says:** The Bow of Kithicor was carved from an ancient tree. It has great powers which were but a portion of the tree's mana. I seek a brave ranger to [retrieve the bow].

**You say:** `retrieve the bow`



>**Leaf Falldim says:** Search the lands of the Unkempt Druids in the Rathe Mountains.  I have heard of his arrows being found inside its territories and  of his death wish to hunt down its leader.  Retrieve the bow and return it to me and I shall give you the ivy etched gauntlets.

**You say:** `ivy etched legging`



>**Leaf Falldim says:** 'I will make you an offer. If you be a ranger, as they are made for only a ranger, you must venture to Faydwer. There you shall seek out Lieutenant Leafstalker of the Kelethin army. He sent a message of his retrieval of the Quiver of Kithicor. Tell him you want it and return it to me. Oh... and one more [small item].

**You say:** `small item`



>**Leaf Falldim says:** Along with the quiver you shall journey to Erudin and purchase a Star of Odus gem to add to the quiver. Consider the coins you shall spend an offering to the woods.

**You say:** `ivy etched boot`



>**Leaf Falldim says:** 'If you wish the ivy etched boots, you shall do me a favor. I am testing new arrow tips and wish a few of the hardest minerals I know of. From the mines of the Temple of Solusek Ro, ronium. From the land of Mistmoore, fetch me Mistmoore granite. Return these to me along with a guild offering of 2000 gold pieces.
end

## Turn-Ins



local text1 = "I asked for a guild donation of 2000 gold coins, Mistmoore granite and a bar of ronium.";


local text2 = "This is but a portion of the bow. I must have the other part.";



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1084.png" alt="" /> <a
                                href="/item/12321" data-url="12321" class="tooltip-link link">Broken Bow Part B</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1084.png" alt="" /> <a
                                href="/item/12320" data-url="12320" class="tooltip-link link">Broken Bow Part A</a>) then


>**Leaf Falldim says:** You have performed well, brave ranger. Put these upon your hands. Protection from the strongest of bowstring and magic are their greatest power. I do believe we have another mission which may yield you the [ivy etched leggings].


Your faction standing with [Kithicor Residents](/faction/269) got better (<span class='text-success'>+10</span>)


Your faction standing with [Protectors of Pine](/faction/302) got better (<span class='text-success'>+1</span>)


Your faction standing with [Jaggedpine Treefolk](/faction/272) got better (<span class='text-success'>+1</span>)


Your faction standing with [Unkempt Druids](/faction/324) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_526.png" alt="" /> <a
                                href="/item/3190" data-url="3190" class="tooltip-link link">Ivy Etched Gauntlets</a> (+10000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_963.png" alt="" /> <a
                                href="/item/10059" data-url="10059" class="tooltip-link link">Star of Odus</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1092.png" alt="" /> <a
                                href="/item/12305" data-url="12305" class="tooltip-link link">A Bar of Ronium</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_767.png" alt="" /> <a
                                href="/item/12306" data-url="12306" class="tooltip-link link">Mistmoore Granite</a>,gold = 1000) then


>**Leaf Falldim says:** You have succeeded!! I believe I owe you the ivy etched boots.


Your faction standing with [Kithicor Residents](/faction/269) got better (<span class='text-success'>+10</span>)


Your faction standing with [Protectors of Pine](/faction/302) got better (<span class='text-success'>+1</span>)


Your faction standing with [Jaggedpine Treefolk](/faction/272) got better (<span class='text-success'>+1</span>)


Your faction standing with [Unkempt Druids](/faction/324) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_545.png" alt="" /> <a
                                href="/item/3192" data-url="3192" class="tooltip-link link">Ivy Etched Boots</a> (+10000 exp)

 

**This NPC *should* return incorrect items given.**






