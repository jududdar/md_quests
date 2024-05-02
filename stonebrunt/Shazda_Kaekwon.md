# Shazda Kaekwon
## Dialog

**You say:** `hail`



if **Faction** >= Dubious +300 then



>**Shazda Kaekwon says:** Shalom, Soandso! I welcome you to our humble village in these [trying times].


else



>**Shazda Kaekwon says:** You have done much to anger the spirits thus you are not accepted by our people.


**You say:** `trying time`



if **Faction** >= Dubious +300 then



>**Shazda Kaekwon says:** There are many threats currently facing this village. The kobolds of Clan Kolbok are becoming bolder in pushing the boundaries of the territory in which they usually hunt. A few of the kobolds now hunt recklessly, killing for pleasure instead of sustenance. [Rognarog] the Infuriated is the most murderous of such kobolds. Then there are the [heretics] that have been invading both Clan Kolbok and Kejek territories alike, practicing their dark sorceries as a show of devotion to their faceless god.


else



>**Shazda Kaekwon says:** You have done much to anger the spirits thus you are not accepted by our people.


**You say:** `heretic`



if **Faction** >= Dubious +300 then



>**Shazda Kaekwon says:** The heretics have not only corrupted their own spirits but they defile the spirits of the dead with their evil sorceries. Fill this satchel with the heads of invading heretics and I shall reward you for your allegiance to Kejek.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_690.png" alt="" /> <a
                                href="/item/17883" data-url="17883" class="tooltip-link link">Burlap Satchel</a>


else



>**Shazda Kaekwon says:** You have done much to anger the spirits thus you are not accepted by our people.


**You say:** `rognarog`



if **Faction** >= Dubious +300 then



>**Shazda Kaekwon says:** Rognarog the Infuriated was once a mighty warrior for Clan Kolbok until his devotion to the kobold god Rolfron Zek devoured his spirit and drove him mad with anguish. Now he wanders the mountains and valleys of Stonebrunt shedding the blood of whatever creatures cross his path. Should you face Rognarog and release him from this life I will reward you for his severed head.


else



>**Shazda Kaekwon says:** You have done much to anger the spirits thus you are not accepted by our people.

end

## Turn-Ins





if **Faction** >= Dubious +300 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_690.png" alt="" /> <a
                                href="/item/6969" data-url="6969" class="tooltip-link link">Satchel of Heretic Heads</a>) then


>**Shazda Kaekwon says:** Less heretics to defile the lands and spirits. You have the gratitude of Kejek for your assistance in repelling the heretic threat.


Your faction standing with [Kejek Village](/faction/5011) got better (<span class='text-success'>+8</span>)


Your faction standing with [Peace Keepers](/faction/298) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_935.png" alt="" /> <a
                                href="/item/6955" data-url="6955" class="tooltip-link link">Kejekan Tribal Headband</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_938.png" alt="" /> <a
                                href="/item/6953" data-url="6953" class="tooltip-link link">Swiftclaw Sash</a>) (+5000 exp)

**You receive coin:** 1-3 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-9 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-9 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-9 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif **Faction** >= Dubious +300 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_744.png" alt="" /> <a
                                href="/item/6968" data-url="6968" class="tooltip-link link">Kobold Head</a>) then


>**Shazda Kaekwon says:** By slaying Rognarog you have spared the lives of those who would have crossed his path. I thank you for your assistance, the spirits have noticed your actions and are pleased.


Your faction standing with [Kejek Village](/faction/5011) got better (<span class='text-success'>+3</span>)


Your faction standing with [Peace Keepers](/faction/298) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_591.png" alt="" /> <a
                                href="/item/6982" data-url="6982" class="tooltip-link link">Titan Blessed Tanto</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1169.png" alt="" /> <a
                                href="/item/6983" data-url="6983" class="tooltip-link link">Titan Blessed Tachi</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1189.png" alt="" /> <a
                                href="/item/6984" data-url="6984" class="tooltip-link link">Titan Blessed Bokken</a>) (+5000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-9 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-9 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-9 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**
