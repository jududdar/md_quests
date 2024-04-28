# Cindl
## Dialog

**You say:** `hail`



>**Cindl says:** Welcome to my humble shop. I offer fine items fashioned from the skins of the beasts of Everfrost. Leather is my specialty and I can always use [extra hides].

**You say:** `extra hides`



>**Cindl says:** I will offer any hunter some used Tattered Armor for every Polar Bear Skin. I am sure that even you can wrestle the skins from the back of a polar bear cub.

**You say:** `second job`



>**Cindl says:** I have seen the warriors bringing in items called Wrath Orc Wristbands. Apparently they find them upon the lifeless bodies of the snow orc troopers. They are made from a skin I have yet to find. I will gladly reward you with either a Rawhide Tunic or Leggings or even perhaps Leather Gloves. All I ask for are Two Wrath Orc Wristbands.

**You say:** `mammoth hide parchment`



>**Cindl says:** Jinkus must've sent ye fer some more mammoth hide parchment fer his posters. Here, take it, free o' charge, as a donation to teh church and to the will o' the Tribunal as well


**You receive:**  [Mammoth Hide Parchment](/item/12621)







end

## Turn-Ins



local text = "No reward until I've got TWO wrath orc wristbands!";



if **You turn in:** [Polar Bear Skin](/item/13761)


>**Cindl says:** This is much apprreciated! Please accept this used armor in return and a gold piece as well, fer yer troubles. Ye've done well! I may have a [second job] fer ye, if ye like?





* __Faction:__ [Merchants of Halas](/faction/328) (5)


* __Faction:__ [Wolves of the North](/faction/320) (3)


* __Faction:__ [Shamen of Justice](/faction/327) (3)




 **You receive:** None 

elseif **You turn in:** [Wrath Orc Wristbands](/item/12223), [Wrath Orc Wristbands](/item/12223)


>**Cindl says:** Fine work hunter!  As your reward please accept this item which I have fashioned for you.







* __Faction:__ [Merchants of Halas](/faction/328) (10)


* __Faction:__ [Wolves of the North](/faction/320) (7)


* __Faction:__ [Shamen of Justice](/faction/327) (7)




 **You receive:** eq.ChooseRandom( [Large Leather Gloves](/item/2034), 2171, 2164) (+1000 exp)


**This NPC *should* return incorrect items given.**






