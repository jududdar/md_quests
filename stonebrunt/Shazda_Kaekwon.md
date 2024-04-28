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



**You receive:**  [Burlap Satchel](/item/17883)


else



>**Shazda Kaekwon says:** You have done much to anger the spirits thus you are not accepted by our people.


**You say:** `rognarog`



if **Faction** >= Dubious +300 then



>**Shazda Kaekwon says:** Rognarog the Infuriated was once a mighty warrior for Clan Kolbok until his devotion to the kobold god Rolfron Zek devoured his spirit and drove him mad with anguish. Now he wanders the mountains and valleys of Stonebrunt shedding the blood of whatever creatures cross his path. Should you face Rognarog and release him from this life I will reward you for his severed head.


else



>**Shazda Kaekwon says:** You have done much to anger the spirits thus you are not accepted by our people.

end

## Turn-Ins





if **Faction** >= Dubious +300 and  **You turn in:** [Satchel of Heretic Heads](/item/6969)


>**Shazda Kaekwon says:** Less heretics to defile the lands and spirits. You have the gratitude of Kejek for your assistance in repelling the heretic threat.


* __Faction:__ [Kejek Village](/faction/5011) (8)


* __Faction:__ [Peace Keepers](/faction/298) (1)


 **You receive:** None 

elseif **Faction** >= Dubious +300 and  **You turn in:** [Kobold Head](/item/6968)


>**Shazda Kaekwon says:** By slaying Rognarog you have spared the lives of those who would have crossed his path. I thank you for your assistance, the spirits have noticed your actions and are pleased.


* __Faction:__ [Kejek Village](/faction/5011) (3)


* __Faction:__ [Peace Keepers](/faction/298) (1)


 **You receive:** None 

**This NPC *should* return incorrect items given.**
