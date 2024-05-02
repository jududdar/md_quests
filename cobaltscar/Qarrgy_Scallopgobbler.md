# Qarrgy Scallopgobbler
## Dialog

**You say:** `hail`



>*Qarrgy Scallopgobbler sets down several large crustacean shells covered in foreign runes, then extends his large, coarse hands in a gesture of friendship. 'I am pleased to see friendly visitors to our villages. I am the head craftsman of the village. The crustacean shell armor worn by the warriors of our village was crafted by me and by my apprentices. I will craft other materials as well when they are available.'*

**You say:** `crustacean shell armor`



>**Qarrgy Scallopgobbler says:** It takes awhile to make each piece. It has to go through a long burning process to clean away all old meat and dirt. Then it needs shaping and etching with runes.

**You say:** `burning process`



>**Qarrgy Scallopgobbler says:** Usually I use a mixture made from the livers of barraccudas. Their liquids are very strong and make good burning liquid. If you want some you need to bring me two barraccuda livers.

**You say:** `other material`



>**Qarrgy Scallopgobbler says:** I am able to craft dragon scale armor but it has been a long time since I have had the opportunity to do so for my people. What kind of scales do you wish for me to craft?
 
**You say:** `emerald dragon scale`



>**Qarrgy Scallopgobbler says:** I will craft an emerald dragonscale tunic for emerald dragon scales, ulthork tusks, and an unstained fine plate breastplate.

**You say:** `sea dragon scale`



>**Qarrgy Scallopgobbler says:** Should you slay Kelorek'Dar, the sea dragon, I would craft you a sea dragon bracer from his scales. All I ask for are the scales of the dragon, an ornately runed shell necklace, and an unstained bracer crafted of the metal you strange ones call fine steel.
end

## Turn-Ins



local text1 = "I'm sorry strange one. That is not a sufficient barter.";




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1236.png" alt="" /> <a
                                href="/item/30059" data-url="30059" class="tooltip-link link">Barracuda Liver</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1236.png" alt="" /> <a
                                href="/item/30059" data-url="30059" class="tooltip-link link">Barracuda Liver</a>) then


>*Qarrgy Scallopgobbler slams a knife into the various livers and squeezes out all of their various goos and juices.  Eventually he separates a bit of it and pours it into a protective bladder.  'Excellent work.  This good catch.  Here, you have sack of ooze.  Its good for burning things off or etching metals.  Thank you for your help.*


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1236.png" alt="" /> <a
                                href="/item/30060" data-url="30060" class="tooltip-link link">Bladder of Acidic Ooze</a> 

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1088.png" alt="" /> <a
                                href="/item/22823" data-url="22823" class="tooltip-link link">Emerald Dragon Scales</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_807.png" alt="" /> <a
                                href="/item/24874" data-url="24874" class="tooltip-link link">Ulthork Tusks</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_624.png" alt="" /> <a
                                href="/item/21004" data-url="21004" class="tooltip-link link">Fine Plate Breastplate</a>) then


>*Qarrgy Scallopgobbler skillfully crafts the Emerald Dragon Scales into a tunic, hands it to Soandso, and claps enthusiastically.*


Your faction standing with [Othmir](/faction/432) got better (<span class='text-success'>+5</span>)


Your faction standing with [Ulthork](/faction/431) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_621.png" alt="" /> <a
                                href="/item/11635" data-url="11635" class="tooltip-link link">Emerald Dragonscale Tunic</a> (+5000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1088.png" alt="" /> <a
                                href="/item/22814" data-url="22814" class="tooltip-link link">Sea Dragon Scales</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_998.png" alt="" /> <a
                                href="/item/28515" data-url="28515" class="tooltip-link link">Ornately Runed Shell Necklace</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_516.png" alt="" /> <a
                                href="/item/21009" data-url="21009" class="tooltip-link link">Fine Plate Bracer</a>) then


>*Qarrgy Scallopgobbler skillfully crafts the Sea Dragon Scales into a bracer, hands it to Soandso, and claps enthusiastically.*


Your faction standing with [Othmir](/faction/432) got better (<span class='text-success'>+5</span>)


Your faction standing with [Ulthork](/faction/431) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_516.png" alt="" /> <a
                                href="/item/11589" data-url="11589" class="tooltip-link link">Sea Dragonscale Bracer</a> (+5000 exp)

 

**This NPC *should* return incorrect items given.**
