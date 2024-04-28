# Marv Orilis
## Dialog

if(eq.get_current_expansion() >= 4.0) then


**You say:** `hail`




>**Marv Orilis says:** Yes? I am a very busy man. I assist new necromancers, wizards, magicians, and enchanters that have joined the Dismal Rage. Are you a sorcerer that has [recently joined] us? 


**You say:** `recently joined`




>**Marv Orilis says:** Then I welcome you to the path of rage. We sorcerers fulfill a crucial role within the Dismal Rage. Under the guidance of Opal Darkbriar, a founder of our order, we study the darkest aspects of the various sorcerous arts so that we may aid and bring power to others who follow our patron deity, Innoruuk, the Prince of Hate. If you desire I will help you obtain a suit of [protective clothing] suitable for a practitioner of the sorcerous arts. Once you have been properly outfitted, return to me and I will aid you in obtaining a [Staff of Dismal Rage].


**You say:** `protective clothing`




>**Marv Orilis says:** You will require this Curing Kit to craft your clothing and robe. The materials required vary depending on the article of clothing you desire to craft. Do you desire to craft a [rage sorcerer cap], [rage sorcerer wristband], [rage sorcerer gloves], [rage sorcerer boots], [rage sorcerer sleeves], [rage sorcerer pantaloons], or [rage sorcerer robe]?



**You receive:**  [Curing Kit](/item/17125)


**You say:** `rage sorcerer cap`




>**Marv Orilis says:** To craft a Rage Sorcerer Cap you will require two [silk thread], gila monster hatchling bile, and a young gila monster skin. Once you have the necessary components combine them in your Curing Kit with this Tattered Cap Pattern.



**You receive:**  [Tattered Cap Pattern](/item/19555)


**You say:** `rage sorcerer wristband`




>**Marv Orilis says:** To craft a Rage Sorcerer Wristband you require a [silk thread], gila monster hatchling bile, and a rattlesnake skin. Once you have the necessary components combine them in your Curing Kit with this Tattered Wristband Pattern.



**You receive:**  [Tattered Wristband Pattern](/item/19558)


**You say:** `rage sorcerer gloves`




>**Marv Orilis says:** To craft Rage Sorcerer Gloves you require two [silk thread], gila monster hatchling bile, two desert spiderling hairs, and a young gilla monster skin. Once you have the necessary components combine them in your Curing Kit with this Tattered Glove Pattern.



**You receive:**  [Tattered Glove Pattern](/item/19559)


**You say:** `rage sorcerer boots`




>**Marv Orilis says:** To craft Rage Sorcerer Boots you require two [silk thread], gila monster hatchling bile, and two ruined coyote pelts. Once you have the necessary components combine them in your Curing Kit with this Tattered Boot Pattern.



**You receive:**  [Tattered Boot Pattern](/item/19561)


**You say:** `rage sorcerer sleeves`




>**Marv Orilis says:** To craft Rage Sorcerer Sleeves you require two [silk thread], young gila monster bile, and two young gilla monster skins. Once you have the necessary components combine them in your Curing Kit with this Tattered Sleeves Pattern.



**You receive:**  [Tattered Sleeve Pattern](/item/19557)


**You say:** `rage sorcerer pantaloons`




>**Marv Orilis says:** To craft Rage Sorcerer Pantaloons you require two [silk thread], young gila monster bile, and four young gila monster skins. Once you have the necessary components combine them in your Curing Kit with this Tattered Leggings Pattern.



**You receive:**  [Tattered Pant Pattern](/item/19560)


**You say:** `rage sorcerer robe`




>**Marv Orilis says:** To craft a Rage Sorcerer Robe you will require three [silk thread], gila monster bile, two gila monster skins, and a desert tarantula hairs. Once you have the necessary components combine them in your Curing Kit with this Tattered Robe Pattern.



**You receive:**  [Tattered Robe Pattern](/item/11395)


**You say:** `staff of dismal rage`




>**Marv Orilis says:** The Dismal Rage has many enemies still here in Freeport that would uncover us and see us destroyed. Lately a wizard of the Arcane Scientists, Yovik Splegle, has been asking questions about Opal Darkbriar. Find this inquisitive wizard and silence him for good. When you have completed the task return to me with the wizards head.

end

## Turn-Ins



local expansion_flag = eq.get_current_expansion();



if(expansion_flag >= 4.0 and  **You turn in:** [Yovik Splegle's Head](/item/19935)


>**Marv Orilis says:** Poor, poor Yovik Splegle. Haha! Excellent work, Soandso. Quickly, fetch me a giant rattlesnake skin and a giant leaf scarab eye along with your Rough Hewn Dismal Staff and I will construct you the Staff of Dismal Rage before your very eyes.


* __Faction:__ [Dismal Rage](/faction/271) (10)


* __Faction:__ [Knights of Truth](/faction/281) (-1)


* __Faction:__ [Opal Darkbriar](/faction/296) (2)


 **You receive:**  [Rough Hewn Dismal Staff](/item/19924) 

elseif(expansion_flag >= 4.0 and  **You turn in:** [Rough Hewn Dismal Staff](/item/19924), [Giant Rattlesnake Skin](/item/19852), [Giant Leaf Scarab Eye](/item/19936)


* __Faction:__ [Dismal Rage](/faction/271) (10)


* __Faction:__ [Knights of Truth](/faction/281) (-1)


* __Faction:__ [Opal Darkbriar](/faction/296) (2)


 **You receive:**  [Staff of Dismal Rage](/item/19941) (+250 exp)

**This NPC *should* return incorrect items given.**
