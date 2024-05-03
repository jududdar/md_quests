# Puab Closk


## Dialog

**You say:** `hail`



>**Puab Closk says:** Greetings. I am Puab Closk, Master of the Ashen Order.  Our home is your home, friend. Feel free to stay as long as you like.  Learn our ways as many have done in the past.  To fight like the tiger and strike like the cobra are your goals.

**You say:** `treant fist`



>**Puab Closk says:** You desire the treant fists?  I have them and I will offer them to any [skilled monk of the Ashen House].

**You say:** `who.* clawfist`



if **Faction** >= Amiable then



>**Puab Closk says:** Clawfist is a Kerran, a catman. He braved the dangers of Norrath to reach the Ashen Order. He sought knowledge of our disiples. He learned well.


elseif **Faction** >= Indifferent then



>**Puab Closk says:** I have been watching you, and appreciate the help you've given to the brothers and sisters of the Ashen Order, but I feel that such a vital matter should be left to one of our more trusted members.


else



**Puab Closk says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `where.* clawfist`



if **Faction** >= Amiable then




>**Puab Closk says:** Clawfist has been banished by the Kerrans of Odus. Where they have sent him I am unsure.


elseif **Faction** >= Indifferent then



>**Puab Closk says:** I have been watching you, and appreciate the help you've given to the brothers and sisters of the Ashen Order, but I feel that such a vital matter should be left to one of our more trusted members.


else



**Puab Closk says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `skilled monk.* ashen house`



if **Faction** >= Amiable then



>**Puab Closk says:** Then you shall aid our family. My former pupil [Clawfist] has been banished by his people. You will go to him and hand him this token as proof of your origin. He shall be expecting you.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_646.png" alt="" /> <a
                                href="/item/12369" data-url="12369" class="tooltip-link link">Puab's Token</a>


elseif **Faction** >= Indifferent then



>**Puab Closk says:** I have been watching you, and appreciate the help you've given to the brothers and sisters of the Ashen Order, but I feel that such a vital matter should be left to one of our more trusted members.


else



**Puab Closk says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!

end



## Turn-Ins




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18746" data-url="18746" class="tooltip-link link">A tattered note</a>) then 


>**Puab Closk says:** Welcome to the house of the Ashen Order. We are a small guild of monks who have devoted our lives to refining our minds, souls, and physical beings to their maximum potential. Please see Brother Torresk as soon as you get a chance. He is in charge of helping our newer members begin their training. Good luck, Soandso.


Your faction standing with [Ashen Order](/faction/361) got better (<span class='text-success'>+100</span>)


Your faction standing with [Knights of Truth](/faction/281) got better (<span class='text-success'>+15</span>)


Your faction standing with [Silent Fist Clan](/faction/309) got better (<span class='text-success'>+5</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_678.png" alt="" /> <a
                                href="/item/13507" data-url="13507" class="tooltip-link link">Torn Cloth Tunic*</a> (+20 exp)

 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_864.png" alt="" /> <a
                                href="/item/12370" data-url="12370" class="tooltip-link link">a pawprint</a>) then 


>**Puab Closk says:** You have performed a great service to one who is your brother. Your loyalty shines brightly, as does your skill. Take the treant fists. They are yours now.


Your faction standing with [Ashen Order](/faction/361) got better (<span class='text-success'>+20</span>)


Your faction standing with [Knights of Truth](/faction/281) got better (<span class='text-success'>+3</span>)


Your faction standing with [Silent Fist Clan](/faction/309) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_636.png" alt="" /> <a
                                href="/item/12344" data-url="12344" class="tooltip-link link">Treant Fists</a> (+100 exp)

 

**This NPC *should* return incorrect items given.**
;

