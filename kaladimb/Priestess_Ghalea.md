# Priestess Ghalea
## Dialog

**You say:** `hail`



>**Priestess Ghalea says:** Welcome to the Church of Underfoot. Please open your soul to the greatness of Brell Serilis. May he guide you in all your future eavors. And may your soles long for the [Soil of Underfoot].

**You say:** `soil`



if **Faction** >= Kindly then 



>**Priestess Ghalea says:** I can trust you with the soil of Underfoot, but first you must obtain four portions of fairy dust. Return them to me and I shall mix it and pray over it. Then I shall give you a pouch of soil of Underfoot.




else



>**Priestess Ghalea says:** The Clerics of Underfoot have yet to see your faith directed towards our wills. Perhaps you should assist Master Gunlok Jure in the crusade against the undead.


**You say:** `candle`



>**Priestess Ghalea says:** The Candle of Bravery is used for temple ceremonies here in Kaladim. When the candle burns out, I must venture to the frigid village of Halas far to the north of the continent of Antonica. There I will take the candlestick and the [soil of Underfoot] to Dok. He must create the candle in the very ornate candlestick.
end

## Turn-Ins



local text = "I will need four portions of fairy dust to create the soil of Underfoot.";



if **You turn in:** [Dirt Covered Letter](/item/18765)


>**Priestess Ghalea says:** Welcome to the Underfoot Cathedral. I am High Priestess Ghalea. Here is your guild tunic. Now. let's get you started helping us spread the will of Brell.


* __Faction:__ [Clerics of Underfoot](/faction/227) (100)


* __Faction:__ [Kazon Stormhammer](/faction/274) (100)


* __Faction:__ [Miners Guild 249](/faction/293) (75)


 **You receive:**  [Dusty Tunic*](/item/13514) (+20 exp)

elseif **Faction** >= Kindly and  **You turn in:** [Fairy Dust](/item/12106), [Fairy Dust](/item/12106), [Fairy Dust](/item/12106), [Fairy Dust](/item/12106)


>**Priestess Ghalea says:** May the mighty power of Brell saturate this soil with his divinity.  Here you are, my noble friend.  You may have a pouch of the soil of Underfoot.





* __Faction:__ [Clerics of Underfoot](/faction/227) (5)


* __Faction:__ [Kazon Stormhammer](/faction/274) (5)


* __Faction:__ [Miners Guild 249](/faction/293) (3)


 **You receive:**  [Soil of Underfoot](/item/12282) (+1000 exp)

**This NPC *should* return incorrect items given.**
