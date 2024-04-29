# Salmekia Treherth
## Dialog

if(eq.get_current_expansion() >= 4.0) then


**You say:** `hail`




e.self:Say(string.format("Welcome to Surefall Glade, %s, the home of the Jaggedpine Treefolk. I help teach young druids the ways of our people. We have worshipers of both Karana, the Storm Lord, and Tunare, the All Mother, living here in the glade. If you are a new druid I will help you obtain a [suit of clothing] that will offer comfort and protection while working in the wilds and help protect you from the weapons of the Gnolls that wish to take these lands.",e.other:GetName()));


**You say:** `suit of clothing`




>**Salmekia Treherth says:** You must use this specially prepared Curing Kit to craft the clothing. Each article of clothing requires different materials for its construction. Do you plan on crafting Pine Druid [Gloves], Pine Druid [Boots], a Pine Druid [Bracer], a Pine Druid [Cap], Pine Druid [Leggings], Pine Druid [Sleeves], or a Pine Druid [Tunic]? When you have been outfitted and are ready I will tell you of a [task] that you can assist with.



**You receive:**  [Curing Kit](/item/17125)


**You say:** `glove`




>**Salmekia Treherth says:** To craft Pine Druid Gloves you require two [silk thread], ruined gnoll leather gloves, two giant field rat whiskers, and a large king snake skin. Once you have the necessary components combine them in your Curing Kit with this Tattered Glove Pattern.



**You receive:**  [Tattered Glove Pattern](/item/19559)


**You say:** `boot`




>**Salmekia Treherth says:** To craft Pine Druid Boots you require two [silk thread], ruined gnoll leather boots, two giant field rat whiskers, and a large whiskered bat fur. Once you have the necessary components combine them in your Curing Kit with this Tattered Boot Pattern.



**You receive:**  [Tattered Boot Pattern](/item/19561)


**You say:** `bracer`




>**Salmekia Treherth says:** To craft an Pine Druid Bracer you require a [silk thread], a ruined gnoll leather bracer, and a giant field rat whiskers. Once you have the necessary components combine them in your Curing Kit with this Tattered Wristband Pattern.



**You receive:**  [Tattered Wristband Pattern](/item/19558)


**You say:** `cap`




>**Salmekia Treherth says:** To craft a Pine Druid Cap you require two [silk thread], a ruined gnoll leather cap, a large whiskered bat fur, and a large field rat pelt. Once you have the necessary components combine them in your Curing Kit with this Tattered Cap Pattern.



**You receive:**  [Tattered Cap Pattern](/item/19555)


**You say:** `legging`




>**Salmekia Treherth says:** To craft Pine Druid Leggings you require three [silk thread], ruined gnoll leather leggings, two large whiskered bat furs, and a giant field rat pelt. Once you have the necessary components combine them in your Curing Kit with this Tattered Pant Pattern.



**You receive:**  [Tattered Pant Pattern](/item/19560)


**You say:** `sleeve`




>**Salmekia Treherth says:** To craft Pine Druid Sleeves you require two [silk thread], ruined gnoll leather sleeves, two large whiskered bat furs, and a giant field rat pelt. Once you have the necessary components combine them in your Curing Kit with this Tattered Sleeves Pattern.



**You receive:**  [Tattered Sleeve Pattern](/item/19557)


**You say:** `tunic`




>**Salmekia Treherth says:** To craft a Pine Druid Tunic you require four [silk thread], a ruined gnoll leather tunic, a giant whiskered bat fur, and a giant field rat pelt. Once you have the necessary components combine them in your Curing Kit with this Tattered Tunic Pattern.



**You receive:**  [Tattered Tunic Pattern](/item/19556)


**You say:** `silk thread`




>**Salmekia Treherth says:** Silk thread is created from two spiderling silks woven together in a sewing kit or loom.


**You say:** `task`




>**Salmekia Treherth says:** We druids seek to live in harmony with nature, taking only what we need from the land and the creatures that inhabit it. Although the City of Qeynos is a noble place, there are people in the city that do not share our reverence for nature and poach the animals of the Karanas needlessly. Even worse than these poachers, whom the rangers of the Jaggedpine Treefolk constantly seek to deter, are the despicable worshipers of Bertoxxulous that hide in the sewers and catacombs of Qeynos. These wicked individuals are known as the [Bloodsabers].


**You say:** `bloodsabers`




>**Salmekia Treherth says:** The Bloodsabers are responsible for a number of atrocities including the spreading of the diseases which have been inflicting the wolves and bears of the Qeynos Hills and the recent poisoning of the farmers fields in the Plains of Karana. Recently we have discovered that a Bloodsaber defiler has been attempting to poison the waters of Surefall Glade. Find this individual and deal with him accordingly, I doubt that this individual will surrender willingly. If need be eliminate them and bring me their head.

end

## Turn-Ins



local expansion_flag = eq.get_current_expansion();

if(expansion_flag >= 4.0 and  **You turn in:** [Bloodsaber Defilers Head](/item/20268)) then


>**Salmekia Treherth says:** It is a shame that some people decide to throw away their humanity with the worship of evil deities. Your actions have saved the lives of many creatures that rely on the waters of this glade. Take this Rusty Pine Druid Scimitar and sharpen it in a forge with a sharpening stone. It may take you several attempts if you are unfamiliar with the process. Once that is done return to me with the Sharpened Pine Druid Scimitar, a Gnoll Fang, and a Large King Snake Skin.





* __Faction:__ [Jaggedpine Treefolk](/faction/272) (10)


* __Faction:__ [Protectors of Pine](/faction/302) (2)


* __Faction:__ [QRG Protected Animals](/faction/343) (1)


* __Faction:__ [Unkempt Druids](/faction/324) (-2)


* __Faction:__ [Guards of Qeynos](/faction/262) (1)


 **You receive:**  [Rusty Pine Druid Scimitar](/item/20258) (+1000 exp)

elseif(expansion_flag >= 4.0 and  **You turn in:** [Sharp Pine Druid Scimitar](/item/20259), [Gnoll Fang](/item/13915), [Large King Snake Skin](/item/19945)) then


>*Salmekia Treherth fashions a grip from the large king snake skin, attaches the gnoll fang to the heel of the swords hilt, and polishes the blade of the sword with a luminescent green polish. 'Here is your new weapon young druid. May it serve you well.'*





* __Faction:__ [Jaggedpine Treefolk](/faction/272) (5)


* __Faction:__ [Protectors of Pine](/faction/302) (1)


* __Faction:__ [QRG Protected Animals](/faction/343) (1)


* __Faction:__ [Unkempt Druids](/faction/324) (-1)


* __Faction:__ [Guards of Qeynos](/faction/262) (1)


 **You receive:**  [Pine Druid Scimitar](/item/20265) (+1000 exp)

**This NPC *should* return incorrect items given.**
