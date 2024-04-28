# Emylie Steelclaws
## Dialog

**You say:** `hail`



if **Faction** >= Dubious +300 then



>**Emylie Steelclaws says:** Shalom friend. My mate Kalaaro is the primary blacksmith of our village. I mostly create his tools, do touch ups and refurbishes, and maintain the [kejek forge].


else



>**Emylie Steelclaws says:** You have done much to anger the spirits thus you are not accepted by our people.


**You say:** `kejek forge`



if **Faction** >= Dubious +300 then



>**Emylie Steelclaws says:** Our forge has received the blessings of the Titan Spirits to burn with a supernatural flame! This flame has many beneficial properties but most importantly it can aid in freeing the spirits that have been imprisoned in materials by evil sorcerers.


else



>**Emylie Steelclaws says:** You have done much to anger the spirits thus you are not accepted by our people.


**You say:** `purification process`



if **Faction** >= Dubious +300 then



>**Emylie Steelclaws says:** The crystalline shadow must be purified in the kejek forge using a special hammer blessed by the Titan Spirits. I will craft a hammer for you to take to the Titans for their blessings if you bring me a Large Brick of High Quality Ore and an Oak Shaft. Once the hammer is blessed you may use it in the kejek forge to purify the crystalline shadow and transfer the spirits contained within it to a Soul Orb that must be taken to our village seer.


else



>**Emylie Steelclaws says:** You have done much to anger the spirits thus you are not accepted by our people.

end

## Turn-Ins





if **Faction** >= Dubious +300 and  **You turn in:** [Large Brick of High Quality Ore](/item/10469), [Oak Shaft](/item/10456)


>*Emylie Steelclaws takes the supplies and begins to work on the hammer. She works swiftly and efficiently then cools the finished hammer and hands it to you.*


* __Faction:__ [Kejek Village](/faction/5011) (2)


* __Faction:__ [Peace Keepers](/faction/298) (1)


 **You receive:**  [Kejekan Smithy Hammer](/item/6981) (+5000 exp)

**This NPC *should* return incorrect items given.**
