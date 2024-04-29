# Errin Pinewhisper
## Dialog

if(eq.get_current_expansion() >= 4.0) then


**You say:** `hail`




>**Errin Pinewhisper says:** Welcome to Surefall Glade friend. I am Errin Pinewhisper, Ranger of Karana the Storm Lord. You will find worshipers of both Karana and Tunare residing here in harmony. I train young rangers of both faiths and assist them in getting prepared for work in the often dangerous lands beyond the glade. If you are in need of a [sturdy outfit] suitable for work as a young ranger then I will gladly instruct you on the means to obtain one.


**You say:** `sturdy outfit`




>**Errin Pinewhisper says:** This specially prepared curing kit will allow you to craft an outfit that will protect you in the wilds of Norrath. The materials required for the outfit vary depending on the piece you desire to craft. Do you desire to craft Pine Scout [Gloves], Pine Scout [Boots], a Pine Scout [Bracer], a Pine Scout [Cap], Pine Scout [Leggings], Pine Scout [Sleeves], or a Pine Scout [Tunic]? Once you are properly outfitted there is an [issue] that you may be of assistance in resolving.



**You receive:**  [Curing Kit](/item/17125)


**You say:** `boots`




>**Errin Pinewhisper says:** To craft Pine Scout Boots you require two [silk thread], ruined gnoll chain boots, two giant field rat whiskers, and a large whiskered bat fur. Once you have the necessary components combine them in your Curing Kit with this Tattered Boot Pattern.



**You receive:**  [Tattered Boot Pattern](/item/19561)


**You say:** `bracer`




>**Errin Pinewhisper says:** To craft an Pine Scout Bracer you require a [silk thread], a ruined gnoll chain bracer, and a giant field rat whiskers. Once you have the necessary components combine them in your Curing Kit with this Tattered Wristband Pattern.



**You receive:**  [Tattered Wristband Pattern](/item/19558)


**You say:** `cap`




>**Errin Pinewhisper says:** To craft a Pine Scout Cap you require two [silk thread], a ruined gnoll chain cap, a large whiskered bat fur, and a large field rat pelt. Once you have the necessary components combine them in your Curing Kit with this Tattered Coif Pattern.



**You receive:**  [Tattered Cap Pattern](/item/19555)


**You say:** `gloves`




>**Errin Pinewhisper says:** To craft Pine Scout Gloves you require two [silk thread], ruined gnoll chain gloves, two giant field rat whiskers, and a large whiskered bat fur. Once you have the necessary components combine them in your Curing Kit with this Tattered Glove Pattern.



**You receive:**  [Tattered Glove Pattern](/item/19559)


**You say:** `leggings`




>**Errin Pinewhisper says:** To craft Pine Scout Leggings you require three [silk thread], ruined gnoll chain leggings, two large whiskered bat furs, and a giant field rat pelt. Once you have the necessary components combine them in your Curing Kit with this Tattered Pant Pattern.



**You receive:**  [Tattered Pant Pattern](/item/19560)


**You say:** `sleeves`




>**Errin Pinewhisper says:** To craft Pine Scout Sleeves you require two [silk thread], ruined gnoll chain sleeves, two large whiskered bat furs, and a giant field rat pelt. Once you have the necessary components combine them in your Curing Kit with this Tattered Sleeves Pattern.



**You receive:**  [Tattered Sleeve Pattern](/item/19557)


**You say:** `tunic`




>**Errin Pinewhisper says:** To craft a Pine Scout Tunic you require four [silk thread], a ruined gnoll chain tunic, a giant whiskered bat fur, and a giant field rat pelt. Once you have the necessary components combine them in your Curing Kit with this Tattered Tunic Pattern.



**You receive:**  [Tattered Tunic Pattern](/item/19556)


**You say:** `silk thread`




>**Errin Pinewhisper says:** Silk thread is created from two spiderling silks woven together in a sewing kit or loom.


**You say:** `issue`




>**Errin Pinewhisper says:** A poacher was recently discovered hunting the bears in Surefall Glade and Qeynos Hills. This poacher has been identified as Yollis Jenkin and it appears that he has fled to Western Plains of Karana to escape retribution by the Jaggedpine Treefolk for his murders. Find Yollis Jenkin and tell him the Jaggedpine Treefolk sent you. He is wanted dead or alive so if he resists capture then bring me his head.

end

## Turn-Ins



local expansion_flag = eq.get_current_expansion();

if(expansion_flag >= 4.0 and  **You turn in:** [Yollis Jenkin's Head](/item/19949)) then


>**Errin Pinewhisper says:** It is a shame when human blood must be shed in the defense of our brother wolves and bears. I thank you for your dedication to the Jaggedpine Treefolk. Take this rusty pine scout sword and sharpen it in a forge with a sharpening stone. It may take you several attempts if you are unfamiliar with the process. Once that is done return the sharpened sword to me with a gnoll fang and a large king snake skin and I will put the finishing touches on the weapon.





* __Faction:__ [Jaggedpine Treefolk](/faction/272) (10)


* __Faction:__ [Protectors of Pine](/faction/302) (2)


* __Faction:__ [QRG Protected Animals](/faction/343) (1)


* __Faction:__ [Unkempt Druids](/faction/324) (-2)


* __Faction:__ [Guards of Qeynos](/faction/262) (1)


 **You receive:**  [Rusty Pine Scout Sword](/item/19950) (+1000 exp)

elseif(expansion_flag >= 4.0 and  **You turn in:** [Sharpened Pine Scout Sword](/item/20104), [Gnoll Fang](/item/13915), [Large King Snake Skin](/item/19945)) then


>*Errin Pinewhisper fashions a grip from the large king snake skin, attaches the gnoll fang to the heel of the swords hilt, and polishes the blade of the sword with a luminescent green polish. 'Here is your new weapon young ranger. May it serve you well.'*


* __Faction:__ [Jaggedpine Treefolk](/faction/272) (5)


* __Faction:__ [Protectors of Pine](/faction/302) (1)


* __Faction:__ [QRG Protected Animals](/faction/343) (1)


* __Faction:__ [Unkempt Druids](/faction/324) (-1)


* __Faction:__ [Guards of Qeynos](/faction/262) (1)


 **You receive:**  [Pine Scout Longsword](/item/20263) (+1000 exp)

**This NPC *should* return incorrect items given.**
;

