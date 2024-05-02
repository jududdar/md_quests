# Leraena Shelyrak
## Dialog

**You say:** `hail`



>**Leraena Shelyrak says:** Welcome. my child.  I am Leraena Shelyrak. overseer of the Temple of Divine Light. Inside this temple. you may find the path to inner peace.  Introduce yourself to each of the priests and priestesses of the temple as well as the paladins. Together we shall put anto such disruptive influences as the [kobold shamans].


**You say:** `guild coin`



if **Faction** >= Amiable then 



**You say:** `guild coin`





>**Leraena Shelyrak says:** Yes, of course. Here it is. Remember that it is not a form of currency.




 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_646.png" alt="" /> <a
                                href="/item/13989" data-url="13989" class="tooltip-link link">Peacekeeper Token</a>



**You say:** `kobold shaman`





>**Leraena Shelyrak says:** The primitive kobold race has begun to show signs of healing ability. No doubt this was granted by some evil deity. Since they are of little power compared to a much more superior race such as ours. we only require the talents of young priests to [slay the kobold shaman].



**You say:** `slay`





>**Leraena Shelyrak says:** You are so young...  Go to Toxxulia and find these kobold shamans. Cut off their paws and return them to me. I require three paws as proof of your worth to our temple.



**You say:** `powerful`





>**Leraena Shelyrak says:** There are obviously other shaman with greater healing ability than those we have yet seen.  Take this pouch and collect some of their odd necklaces so that we may study them.




 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_582.png" alt="" /> <a
                                href="/item/17090" data-url="17090" class="tooltip-link link">Small Embroidered Sack</a>



**You say:** `greater kobold`





>**Leraena Shelyrak says:** Return to the Warrens and obtain eight of the bronze symbols worn by the kobolds greater shaman. Place them in this sack that has been blessed by the powers of Quellious to protect you from the evil influence of the evil symbols. Return the full sack with your initiate symbol of Quellious.




 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_582.png" alt="" /> <a
                                href="/item/17090" data-url="17090" class="tooltip-link link">Small Embroidered Sack</a>








elseif **Faction** >= Indifferent then



>**Leraena Shelyrak says:** You have not done much to upset the Peacekeepers of this temple, but we must ask you to prove yourself to us before we may discuss things such as this.


else



>**Leraena Shelyrak says:** Leave my sight at once! You are no friend to the Peacekeepers of the Temple of Divine Light.


**You say:** `ready to advance`



>**Leraena Shelyrak says:** You are ready to strike at the body of the kobold shamans power. There is no reasoning with the Kobolds thus there shall be no peace in our beloved lands until their devotion to their wicked deity ceases. Return once again to the Warrens and bring me the unholy symbol worn by the High Shaman.
end

## Turn-Ins



local text = "I require the hieroglyph translations, the doctrine of Rolfron Zek, and your disciple symbol of Quellious.";


if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18723" data-url="18723" class="tooltip-link link">A tattered note</a>) then 


>**Leraena Shelyrak says:** Greetings. and welcome to the Temple of Divine Light! Here is your guild tunic. Serve Quellious well. Please see Lumi Stergnon - he has a task for you.





Your faction standing with [Peace Keepers](/faction/298) got better (<span class='text-success'>+100</span>)


Your faction standing with [High Council of Erudin](/faction/266) got better (<span class='text-success'>+25</span>)


Your faction standing with [Heretics](/faction/265) got worse (<span class='text-danger'>-25</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_678.png" alt="" /> <a
                                href="/item/13546" data-url="13546" class="tooltip-link link">Faded Silver Tunic*</a> (+20 exp)

 

elseif( **Faction is** > Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_566.png" alt="" /> <a
                                href="/item/14585" data-url="14585" class="tooltip-link link">Odd Cold Iron Necklace</a>) then 


>**Leraena Shelyrak says:** It is imperative that we discern the nature of these symbols and the source of the kobolds shamanistic powers. There is a citizen of Erudin residing in Freeport named Glyssa Sonshaw. She is quite possibly the most knowledgeable individual in the field of heraldic and hieroglyphic studies. Take the high shamans necklace and this note to her. When you have discovered the nature of the symbols return to me with the documentation and your Disciple Symbol of Quellious.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_682.png" alt="" /> <a
                                href="/item/1772" data-url="1772" class="tooltip-link link">Sealed Parchment</a> 

 


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_566.png" alt="" /> <a
                                href="/item/14585" data-url="14585" class="tooltip-link link">Odd Cold Iron Necklace</a> 

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_864.png" alt="" /> <a
                                href="/item/2049" data-url="2049" class="tooltip-link link">rolled up strip of cloth</a>) then 


>**Leraena Shelyrak says:** This is important news indeed. It seems there is a tribe of cat men in the Stonebrunt Mountains that wishes to form an alliance with Erudin. I must alert the High Council of this immediately, thank you for your services.





Your faction standing with [Peace Keepers](/faction/298) got better (<span class='text-success'>+2</span>)


Your faction standing with [High Council of Erudin](/faction/266) got better (<span class='text-success'>+1</span>)


Your faction standing with [Heretics](/faction/265) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:** 0 (+1000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-5 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif( **Faction is** > Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_582.png" alt="" /> <a
                                href="/item/14582" data-url="14582" class="tooltip-link link">Embroidered Bag of Bone Necklaces</a>) then 


>**Leraena Shelyrak says:** I am unfamiliar with the markings that adorn these necklaces. You have done well thus far in hindering the kobolds worship of their evil deity. I award you the Initiate Symbol of Quellious. Return to me when you feel you are ready to deal with the [greater kobold shaman].





Your faction standing with [Peace Keepers](/faction/298) got better (<span class='text-success'>+25</span>)


Your faction standing with [High Council of Erudin](/faction/266) got better (<span class='text-success'>+6</span>)


Your faction standing with [Heretics](/faction/265) got worse (<span class='text-danger'>-6</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_850.png" alt="" /> <a
                                href="/item/1564" data-url="1564" class="tooltip-link link">Initiate Symbol of Quellious</a> (+1000 exp)

 

elseif( **Faction is** > Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_743.png" alt="" /> <a
                                href="/item/13883" data-url="13883" class="tooltip-link link">Odd Kobold Paw</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_743.png" alt="" /> <a
                                href="/item/13883" data-url="13883" class="tooltip-link link">Odd Kobold Paw</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_743.png" alt="" /> <a
                                href="/item/13883" data-url="13883" class="tooltip-link link">Odd Kobold Paw</a>) then 


>**Leraena Shelyrak says:** Fine work. They shall never lay hands upon another kobold again. I mean paws. Here is a small reward for a fine job. Unfortunatly we have recently learned that the shamen in the forest are merely underlings to [more powerful kobold shamen] that reside in the kobold warrens. Continue the work of Quellious.





Your faction standing with [Peace Keepers](/faction/298) got better (<span class='text-success'>+20</span>)


Your faction standing with [High Council of Erudin](/faction/266) got better (<span class='text-success'>+5</span>)


Your faction standing with [Heretics](/faction/265) got worse (<span class='text-danger'>-5</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15213" data-url="15213" class="tooltip-link link">Spell: Cure Disease</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15011" data-url="15011" class="tooltip-link link">Spell: Holy Armor</a>) (+500 exp)

 

elseif( **Faction is** > Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_582.png" alt="" /> <a
                                href="/item/14583" data-url="14583" class="tooltip-link link">Embroidered Bag of Bronze Symbols</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_850.png" alt="" /> <a
                                href="/item/1564" data-url="1564" class="tooltip-link link">Initiate Symbol of Quellious</a>) then 





>**Leraena Shelyrak says:** Your service to this temple is commendable. I award you the rank of Disciple for your devotions to The Tranquil. When you are [ready to advance] return to me and I will set you upon another task.


Your faction standing with [Peace Keepers](/faction/298) got better (<span class='text-success'>+30</span>)


Your faction standing with [High Council of Erudin](/faction/266) got better (<span class='text-success'>+7</span>)


Your faction standing with [Heretics](/faction/265) got worse (<span class='text-danger'>-7</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_850.png" alt="" /> <a
                                href="/item/1565" data-url="1565" class="tooltip-link link">Disciple Symbol of Quellious</a> (+1000 exp)

 

elseif( **Faction is** > Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_682.png" alt="" /> <a
                                href="/item/1780" data-url="1780" class="tooltip-link link">Hieroglyph Translations</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_682.png" alt="" /> <a
                                href="/item/1781" data-url="1781" class="tooltip-link link">An encrypted document</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_850.png" alt="" /> <a
                                href="/item/1565" data-url="1565" class="tooltip-link link">Disciple Symbol of Quellious</a>) then 


>**Leraena Shelyrak says:** You have done well yet again, young disciple. I award you the rank of Regent of the Peacekeepers. With this information we can hopefully gain some insight into the workings of the kobolds' religion.





Your faction standing with [Peace Keepers](/faction/298) got better (<span class='text-success'>+70</span>)


Your faction standing with [High Council of Erudin](/faction/266) got better (<span class='text-success'>+17</span>)


Your faction standing with [Heretics](/faction/265) got worse (<span class='text-danger'>-17</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_850.png" alt="" /> <a
                                href="/item/1566" data-url="1566" class="tooltip-link link">Regent Symbol of Quellious</a> (+2000 exp)

 

**This NPC *should* return incorrect items given.**
;

