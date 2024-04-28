# Leraena Shelyrak
## Dialog

**You say:** `hail`



>**Leraena Shelyrak says:** Welcome. my child.  I am Leraena Shelyrak. overseer of the Temple of Divine Light. Inside this temple. you may find the path to inner peace.  Introduce yourself to each of the priests and priestesses of the temple as well as the paladins. Together we shall put anto such disruptive influences as the [kobold shamans].


**You say:** `guild coin`



if **Faction** >= Amiable then 



**You say:** `guild coin`





>**Leraena Shelyrak says:** Yes, of course. Here it is. Remember that it is not a form of currency.




**You receive:**  [Peacekeeper Token](/item/13989)



**You say:** `kobold shaman`





>**Leraena Shelyrak says:** The primitive kobold race has begun to show signs of healing ability. No doubt this was granted by some evil deity. Since they are of little power compared to a much more superior race such as ours. we only require the talents of young priests to [slay the kobold shaman].



**You say:** `slay`





>**Leraena Shelyrak says:** You are so young...  Go to Toxxulia and find these kobold shamans. Cut off their paws and return them to me. I require three paws as proof of your worth to our temple.



**You say:** `powerful`





>**Leraena Shelyrak says:** There are obviously other shaman with greater healing ability than those we have yet seen.  Take this pouch and collect some of their odd necklaces so that we may study them.




**You receive:**  [Small Embroidered Sack](/item/17090)



**You say:** `greater kobold`





>**Leraena Shelyrak says:** Return to the Warrens and obtain eight of the bronze symbols worn by the kobolds greater shaman. Place them in this sack that has been blessed by the powers of Quellious to protect you from the evil influence of the evil symbols. Return the full sack with your initiate symbol of Quellious.




**You receive:**  [Small Embroidered Sack](/item/17090)








elseif **Faction** >= Indifferent then



>**Leraena Shelyrak says:** You have not done much to upset the Peacekeepers of this temple, but we must ask you to prove yourself to us before we may discuss things such as this.


else



>**Leraena Shelyrak says:** Leave my sight at once! You are no friend to the Peacekeepers of the Temple of Divine Light.


**You say:** `ready to advance`



>**Leraena Shelyrak says:** You are ready to strike at the body of the kobold shamans power. There is no reasoning with the Kobolds thus there shall be no peace in our beloved lands until their devotion to their wicked deity ceases. Return once again to the Warrens and bring me the unholy symbol worn by the High Shaman.
end

## Turn-Ins



local text = "I require the hieroglyph translations, the doctrine of Rolfron Zek, and your disciple symbol of Quellious.";


if **You turn in:** [A tattered note](/item/18723)


>**Leraena Shelyrak says:** Greetings. and welcome to the Temple of Divine Light! Here is your guild tunic. Serve Quellious well. Please see Lumi Stergnon - he has a task for you.





* __Faction:__ [Peace Keepers](/faction/298) (100)


* __Faction:__ [High Council of Erudin](/faction/266) (25)


* __Faction:__ [Heretics](/faction/265) (-25)


 **You receive:**  [Faded Silver Tunic*](/item/13546) (+20 exp)

elseif( **Faction is** > Indifferent and  **You turn in:** [Odd Cold Iron Necklace](/item/14585)


>**Leraena Shelyrak says:** It is imperative that we discern the nature of these symbols and the source of the kobolds shamanistic powers. There is a citizen of Erudin residing in Freeport named Glyssa Sonshaw. She is quite possibly the most knowledgeable individual in the field of heraldic and hieroglyphic studies. Take the high shamans necklace and this note to her. When you have discovered the nature of the symbols return to me with the documentation and your Disciple Symbol of Quellious.


 **You receive:** None 

elseif **You turn in:** [rolled up strip of cloth](/item/2049)


>**Leraena Shelyrak says:** This is important news indeed. It seems there is a tribe of cat men in the Stonebrunt Mountains that wishes to form an alliance with Erudin. I must alert the High Council of this immediately, thank you for your services.





* __Faction:__ [Peace Keepers](/faction/298) (2)


* __Faction:__ [High Council of Erudin](/faction/266) (1)


* __Faction:__ [Heretics](/faction/265) (-1)


 **You receive:** 0 (+1000 exp)

elseif( **Faction is** > Indifferent and  **You turn in:** [Embroidered Bag of Bone Necklaces](/item/14582)


>**Leraena Shelyrak says:** I am unfamiliar with the markings that adorn these necklaces. You have done well thus far in hindering the kobolds worship of their evil deity. I award you the Initiate Symbol of Quellious. Return to me when you feel you are ready to deal with the [greater kobold shaman].





* __Faction:__ [Peace Keepers](/faction/298) (25)


* __Faction:__ [High Council of Erudin](/faction/266) (6)


* __Faction:__ [Heretics](/faction/265) (-6)


 **You receive:**  [Initiate Symbol of Quellious](/item/1564) (+1000 exp)

elseif( **Faction is** > Indifferent and  **You turn in:** [Odd Kobold Paw](/item/13883), [Odd Kobold Paw](/item/13883), [Odd Kobold Paw](/item/13883)


>**Leraena Shelyrak says:** Fine work. They shall never lay hands upon another kobold again. I mean paws. Here is a small reward for a fine job. Unfortunatly we have recently learned that the shamen in the forest are merely underlings to [more powerful kobold shamen] that reside in the kobold warrens. Continue the work of Quellious.





* __Faction:__ [Peace Keepers](/faction/298) (20)


* __Faction:__ [High Council of Erudin](/faction/266) (5)


* __Faction:__ [Heretics](/faction/265) (-5)


 **You receive:** eq.ChooseRandom( [Spell: Cure Disease](/item/15213), [Spell: Holy Armor](/item/15011)) (+500 exp)

elseif( **Faction is** > Indifferent and  **You turn in:** [Embroidered Bag of Bronze Symbols](/item/14583), [Initiate Symbol of Quellious](/item/1564)





>**Leraena Shelyrak says:** Your service to this temple is commendable. I award you the rank of Disciple for your devotions to The Tranquil. When you are [ready to advance] return to me and I will set you upon another task.


* __Faction:__ [Peace Keepers](/faction/298) (30)


* __Faction:__ [High Council of Erudin](/faction/266) (7)


* __Faction:__ [Heretics](/faction/265) (-7)


 **You receive:**  [Disciple Symbol of Quellious](/item/1565) (+1000 exp)

elseif( **Faction is** > Indifferent and  **You turn in:** [Hieroglyph Translations](/item/1780), [An encrypted document](/item/1781), [Disciple Symbol of Quellious](/item/1565)


>**Leraena Shelyrak says:** You have done well yet again, young disciple. I award you the rank of Regent of the Peacekeepers. With this information we can hopefully gain some insight into the workings of the kobolds' religion.





* __Faction:__ [Peace Keepers](/faction/298) (70)


* __Faction:__ [High Council of Erudin](/faction/266) (17)


* __Faction:__ [Heretics](/faction/265) (-17)


 **You receive:**  [Regent Symbol of Quellious](/item/1566) (+2000 exp)

**This NPC *should* return incorrect items given.**
;

