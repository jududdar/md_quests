# Annous Pineshadow



[Annous Pineshadow](/npc/181166) is a level 60 Human Cleric that spawns in [Jaggedpine Forest](/zone/181).





## Dialog

**You say:** `hail`



if( **Faction is** > Warmly) then



**You say:** `hail`





>**Annous Pineshadow says:** Good day to you, Soandso. I am Annous Pineshadow, high priest of The Rainkeeper and ambassador of Qeynos. It has been a [long] time since I last set foot within the Jaggedpine, and although not surprised, I am amazed and awestruck at the untouched purity of these sacred grounds. It is very much a relief to know that the forest has been sparred the taint of the venomous world that has become Norrath.



**You say:** `long`





e.self:Say("Sixty years 



**You say:** `sacred way`





e.self:Say("There are hundreds of different rites, ceremonies, prayers, and rituals that are performed in one's devotion to The Rainkeeper. Many of these can be as simple as the performance of a duty, as a druid would protect their forest, while some may be as complex and consuming as a several day ceremony to usher in the changing seasons. Aaaah. . . but there is truly so much that in the time that's left for me here could not give proper justice for in my explanations 



**You say:** `faith in my heart`





e.self:Say("I would not dare challenge that, my friend, but is your faith strong enough to withstand the greatest of consequences 



**You say:** `willing`





e.self:Say("Excellent, child. I am pleased to know that you are willing to go so far as to test your faith 



**You say:** `azure idol of karana`





e.self:Say("When the order was first founded by the Hierophant known as Tanirun Galeweaver, he bestowed upon all of his brethren a sacred idol carved by his own hands. It is said that when Tanirun blessed the Shrine of Karana with his gift of the storm, that the remaining essence of Karana's witness was divided among the idols. In the passing times, the idols were handed down when an old member passed beyond into the Eye of Karana's Storm and a new member was inducted in their predecessor's memory and honor. You will seek one of these idols 




elseif( **Faction is** > Apprehensive) then



>**Annous Pineshadow says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Annous Pineshadow says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `prove myself worthy`



if( **Faction is** > Warmly and eq.get_qglobals(e.self,e.other)["galeweaver"] == "1") then



**You say:** `prove myself worthy`





e.self:Say("Then your endeavor shall continue, my child. Take this scroll 




 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_863.png" alt="" /> <a
                                href="/item/8962" data-url="8962" class="tooltip-link link">Ancient White Scroll</a>



**You say:** `dormant crystal sphere`





>**Annous Pineshadow says:** There are several magical spheres throughout Norrath but this sphere is [unique to The Rainkeeper]. It is said that when Karana blessed this area with his first storm in acceptance of the nomadic tribe that would settle here, that the droplets of rain left upon the pines and blades of grass was gathered by one of these nomads and stored in a plain clay jar that was then buried as a symbol of their own gratitude toward the storm. Nearly a century later when Karana's Shrine and the Throne of Karana's Thunder were near completion, one known as Tanirun Galeweaver found the jar. The water was still inside, preserved by means unexplainable through simple reason. It is said that Tanirun poured the water into his own hands and wove a spell, sealing the wind within the orb of this ancient rain that was now crystallized by Tanirun's spell.



**You say:** `unique to the rainkeeper`





e.self:Say("Tanirun's orb was used to make the first symbol that to this day is wielded by the members of the sacred order. His effects were duplicated by the first order and each bore an orb identical to Tanirun's. These orbs, as the idols, were passed down from member to member. As with the idol, we held an orb that had no bearer. However, before the Jaggedpine was sealed, the orb disappeared. We are not certain as to how or why, but we do know that if it lies within the hands of one who is not of Karana's faithful priests, it shall become dormant until awoken. I have heard rumors, distant whispers upon the wind and storm that the orb lies within the depths of Solusek's Eye 



**You say:** `writ`





>**Annous Pineshadow says:** When the order of The Gale Weavers was established, Tanirun and his brethren of the order constructed a sacred writ similar to a spell, but it cannot be invoked at the priest's whim. Like the storm, it is chaos. When the words are spoken, the elements of the storm will come as they wish, when they wish. This writ was used to conjure the essence of the storm into the orbs, creating the mirror of a sky where a storm rages eternally. The writ was lost to us sometime before the Jaggedpine was sealed. One known as Naundruar, a former high priest of our order, took the writ. He was furious, enraged that the order had been asked to divide and leave our sacred homeland. None are ultimately certain what horrible fate befell him, for his hatred toward Qeynos had infected his being like an incurable disease. In the southern plain of Karana you will find the remnants of this once great priest and with him, you shall find the writ.
 



elseif( **Faction is** > Apprehensive) then



>**Annous Pineshadow says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Annous Pineshadow says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!

end



## Turn-Ins





if( **Faction is** > Warmly and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1007.png" alt="" /> <a
                                href="/item/8956" data-url="8956" class="tooltip-link link">Azure Idol of Karana</a>) then


e.self:Say("Marvelously done, my friend. The idol's return by your hand bodes well indeed toward the success of your quest. Now, it shall remain without a hand to possess it 


Your faction standing with [Residents of Jaggedpine](/faction/1597) got better (<span class='text-success'>+5</span>)


Your faction standing with [Jaggedpine Treefolk](/faction/272) got better (<span class='text-success'>+2</span>)


Your faction standing with [Protectors of Pine](/faction/302) got better (<span class='text-success'>+2</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:** 0 (+10000 exp)

 


eq.set_global("galeweaver","1",1,"F");

elseif( **Faction is** > Warmly and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_683.png" alt="" /> <a
                                href="/item/8964" data-url="8964" class="tooltip-link link">The Rainkeepers Writ</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_507.png" alt="" /> <a
                                href="/item/8963" data-url="8963" class="tooltip-link link">Dormant Crystal Sphere</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_863.png" alt="" /> <a
                                href="/item/8962" data-url="8962" class="tooltip-link link">Ancient White Scroll</a>) then 


e.self:Say("You have done well, my child. The ancient scroll has impressed upon it a small mirror of your faith. As it was with you through your travels, the runes have changed to reflect your own heart and what lies within it. I have woven for you the Orb of the Gale 


Your faction standing with [Residents of Jaggedpine](/faction/1597) got better (<span class='text-success'>+5</span>)


Your faction standing with [Jaggedpine Treefolk](/faction/272) got better (<span class='text-success'>+2</span>)


Your faction standing with [Protectors of Pine](/faction/302) got better (<span class='text-success'>+2</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/17135" data-url="17135" class="tooltip-link link">Dormant Gale Stone</a> (+10000 exp)

 


eq.delete_global("galeweaver");

elseif( **Faction is** > Warmly and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_752.png" alt="" /> <a
                                href="/item/8966" data-url="8966" class="tooltip-link link">Orb of the Gale</a>) then 


e.self:Say("You astound me, my child. Well done indeed, and I am very pleased to know that you have been successful in these endeavors. It is an honor to bestow upon you this, our sacred symbol, and welcome you into the order of The Gale Weavers. Bear it proudly, but do not flaunt pride. Keep your sacred duties to The Rainkeeper first and foremost in your thoughts and actions 


Your faction standing with [Residents of Jaggedpine](/faction/1597) got better (<span class='text-success'>+15</span>)


Your faction standing with [Jaggedpine Treefolk](/faction/272) got better (<span class='text-success'>+7</span>)


Your faction standing with [Protectors of Pine](/faction/302) got better (<span class='text-success'>+7</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_734.png" alt="" /> <a
                                href="/item/8967" data-url="8967" class="tooltip-link link">The Gale Weaver</a> (+10000 exp)

 

**This NPC *should* return incorrect items given.**
