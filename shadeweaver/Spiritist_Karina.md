# Spiritist Karina
local count = 0;


## On NPC Spawn

**Set a timer** named *karina* for 90 seconds


## Timer(s)

count = count + 1;

if(count == 1) then


>**Spiritist Karina says:** When our companions are wounded, we must call to the spirits and ask for their aid. Kindred spirits are able to protect us and heal our wounds.

elseif(count == 2) then


>**Spiritist Karina says:** Never force a spirit to your aid. You will find that there are many that will come to your side. You need only ask.

elseif(count == 3) then


>**Spiritist Karina says:** Only use your connection to the spiritual realm when you need it. Do not drain yourself unnecessarily, for you will find yourself unable to call for aid when you need it the most. Ration out your spiritual strength carefully, it will be vital to your own survival.

elseif(count == 4) then


>**Spiritist Karina says:** Try not to become the focus of attention in a battle. You will find it much more efficient to strike when the opponent is distracted. Do not hestitate to ask others to join you. You will find that many welcome your ability to cure battle wounds and call forth protection from the spirits around you.

elseif(count == 5) then


>**Spiritist Karina says:** Be sure to maintian your material components. You will need these to perform the necessary rituals to call on the power of many spirits.

elseif(count == 6) then


>**Spiritist Karina says:** Never lead an enemy to your allies. It is considered the greatest dishonor to do so. Remember that you will carry the name you make for yourself in youth all the way to your elder years. Your actions now will determine the outcome of your future.

elseif(count == 7) then


>**Spiritist Karina says:** Try not to waste the hides of the beasts you hunt. It is wise to craft these hides into armor for yourself.

elseif(count == 8) then


>**Spiritist Karina says:** Always pay attention to your surroundings. There are many opponents that will ambush you while you are out in the field. It is wise to take companions with you when venturing far.

elseif(count == 9) then


>**Spiritist Karina says:** Visit your trainer to master new skills as soon as you are able. The longer you tarry about, the harder it will be for you to learn your skill later on. The more you use the skills you learn, the better you will become at using them.


count = 0;


**Set a timer** named *karina* for 90 seconds
end



## Dialog

**You say:** `hail`



>**Spiritist Karina says:** Welcome, friend. Come dance by our warm fire or have a seat and [learn] a little bit about the ways of the spiritist.

**You say:** `learn`



>**Spiritist Karina says:** We are those in tune with the spirits that surround us. Ancestral spirits with knowledge of the ancients dance around us by this very fire. They guide is through the darkness. Protect us from pain. But a terrible [curse] has befallen the spirits of this thicket, and so it is my duty to train these young Dar Khura in order to aid in the battle that lies ahead.

**You say:** `curse`



>**Spiritist Karina says:** The spirits are corrupted by foul magic. The souls of our ancestors have been twisted into an abomination known as [shades]. The corpses of long passed friends and relatives walk through the night seeking to destroy the living. We must destroy the corrupted remains of their old bodies and allow the spirits to roam free once more. Will you help us [release the souls] of our kindred spirits?

**You say:** `shades`



>**Spiritist Karina says:** The shades are a deeper form of corruption of the spirit. I can sense great anguish in the spirits that have been twisted into such a creation. Their horror burns my heart so deeply that I cannot bear it. I would not normally ask another to place themselves in danger, but it is important that the souls are released from these shadowed prisons of torture and darkness. Please help us [release the souls] of our ancestral spirits.

**You say:** `release the souls`



>**Spiritist Karina says:** I am relieved that you have accepted this dangerous task. I can feel the strength of the spirit within you. There are many kindred spirits aiding us in this battle. If you are in tune with the spiritual realm, you will find that your rituals of magic will result in aid from our spiritual allies. Return to me with the [darkened jawbones] of the lesser shades so that I may release the spirit once more.

**You say:** `darkened jawbones`



>**Spiritist Karina says:** The jawbones will aid me in tuning to the essence of the corrupted spirits. When you return to me with them, you are enabling me to place the lost soul to rest. I am able to release four of these spirits at one time in much the same way I am training these four young trainees. It is best to bring me four of them at one time if you are able.


>**Spiritist Karina says:** Always pay attention to your surroundings. There are many opponents that will ambush you while you are out in the field. It is wise to take companions with you when venturing far.

**You say:** `loda kai`



>**Spiritist Karina says:** Loda Kai left Shar Vahl many years ago. He had set off for the distant city of Katta Castellum just north of the tenebrous mountains. We have not seen him since, but the brigands wear his family emblem. [Kedra Kai] has banished himself from our city in shame.

**You say:** `Kedra Kai`



>**Spiritist Karina says:** He stands vigil at the crossroads of the trading routes. Kedra has sworn to destroy the brigands and his brother before returning to Shar Vahl. There are many skeletal brigands within the thicket. If you are able to acquire their rotting jawbones, please bring them to me. I will try to learn what I can from the magic within them.

**You say:** `vampire`



>**Spiritist Karina says:** There are rumors of Vampire appearances within the Tenebrous Mountains. I suspect you will be able to learn more about these horrifying creatures within Katta Castellum.

**You say:** `rebirth`



>**Spiritist Karina says:** When you free a spirit from the shades that corrupt them, they will return to the spiritual realm and live again in harmony. The [skeletal hunters] of the thickets are a corruption of a different nature than the shades. There are no spirits trapped within these animated remains. Nevertheless, they are a danger to us and must be destroyed. If you are able, please return four of their sharp jawbones to me. I will need them to decipher the nature of the magic that animates them.
end



## Turn-Ins



local text = "Thank you for your aid Soandso. I will place this spirit to peaceful rest and give these remains a proper burial. It is a shame you could only return with one. It takes four of these to make a real difference. Nevertheless your efforts are appreciated. Thank you.";



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_906.png" alt="" /> <a
                                href="/item/30872" data-url="30872" class="tooltip-link link">A Darkened Jawbone</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_906.png" alt="" /> <a
                                href="/item/30872" data-url="30872" class="tooltip-link link">A Darkened Jawbone</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_906.png" alt="" /> <a
                                href="/item/30872" data-url="30872" class="tooltip-link link">A Darkened Jawbone</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_906.png" alt="" /> <a
                                href="/item/30872" data-url="30872" class="tooltip-link link">A Darkened Jawbone</a>) then


>**Spiritist Karina says:** I can see that you have a brave heart. You have rescued many of the fallen spirits with little regard to your own welfare. Such selfless acts should not go unrewarded. Please take these gloves and wear them with pride. It is a symbol of [rebirth].


Your faction standing with [Guardians of Shar Vahl](/faction/1513) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_636.png" alt="" /> <a
                                href="/item/30879" data-url="30879" class="tooltip-link link">Rebirth Leather Gloves</a> (+1000 exp)

 

elseif(**Your level** > 4 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_906.png" alt="" /> <a
                                href="/item/30873" data-url="30873" class="tooltip-link link">A Sharp Toothed Jawbone</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_906.png" alt="" /> <a
                                href="/item/30873" data-url="30873" class="tooltip-link link">A Sharp Toothed Jawbone</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_906.png" alt="" /> <a
                                href="/item/30873" data-url="30873" class="tooltip-link link">A Sharp Toothed Jawbone</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_906.png" alt="" /> <a
                                href="/item/30873" data-url="30873" class="tooltip-link link">A Sharp Toothed Jawbone</a>) then


>**Spiritist Karina says:** Thank you for bringing these to me Soandso.' Karina closes her eyes and meditates over the jawbones for a moment. 'I can sense the mark of Loda Kai within these bones. This is a horror, for [Loda Kai] was once member of my people. I do not know how he came about these strange magical forces, but it cannot be good news. Please, wear these sleeves for protection. This new discovery worries me deeply.


Your faction standing with [Guardians of Shar Vahl](/faction/1513) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_634.png" alt="" /> <a
                                href="/item/30877" data-url="30877" class="tooltip-link link">Rebirth Leather Sleeves</a> (+1000 exp)

 

elseif(**Your level** > 5 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_906.png" alt="" /> <a
                                href="/item/30874" data-url="30874" class="tooltip-link link">A Rotting Jawbone</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_906.png" alt="" /> <a
                                href="/item/30874" data-url="30874" class="tooltip-link link">A Rotting Jawbone</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_906.png" alt="" /> <a
                                href="/item/30874" data-url="30874" class="tooltip-link link">A Rotting Jawbone</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_906.png" alt="" /> <a
                                href="/item/30874" data-url="30874" class="tooltip-link link">A Rotting Jawbone</a>) then


>**Spiritist Karina says:** These are the right ones, thank you Soandso' Karina calls to the spirits as she meditates over the jawbones of the brigands. After a brief pause, she opens her eyes once more and begins to speak, 'The magic in these bones are elusive. Their rotted state has corroded the spiritual essences within them. I have noticed much larger skeletal thugs roaming the hills beyond the road. If you can retrieve their jaws for me, perhaps I will have better luck with them. Please wear these leggings for protection.


Your faction standing with [Guardians of Shar Vahl](/faction/1513) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_635.png" alt="" /> <a
                                href="/item/30880" data-url="30880" class="tooltip-link link">Rebirth Leather Leggings</a> (+1000 exp)

 

elseif(**Your level** > 6 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_906.png" alt="" /> <a
                                href="/item/30875" data-url="30875" class="tooltip-link link">A Thick Jawbone</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_906.png" alt="" /> <a
                                href="/item/30875" data-url="30875" class="tooltip-link link">A Thick Jawbone</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_906.png" alt="" /> <a
                                href="/item/30875" data-url="30875" class="tooltip-link link">A Thick Jawbone</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_906.png" alt="" /> <a
                                href="/item/30875" data-url="30875" class="tooltip-link link">A Thick Jawbone</a>) then


>**Spiritist Karina says:** I was worried about your safety Soandso. I am glad you have returned in one piece. While you were away I have made arrangements to supply you with these boots. Now then, let us see what we can learn from these remains.' Karina cups her hands over the thick jawbones and calls to the spirits for guidance. As her meditation ends, she looks drained and short of breath. 'It is as I have feared. There is a [vampire] within this thicket.


Your faction standing with [Guardians of Shar Vahl](/faction/1513) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_633.png" alt="" /> <a
                                href="/item/30881" data-url="30881" class="tooltip-link link">Rebirth Leather Boots</a> (+1000 exp)

 

**This NPC *should* return incorrect items given.**
