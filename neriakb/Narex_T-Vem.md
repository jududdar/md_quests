# Narex T-Vem



## Dialog

**You say:** `Hail`



>**Narex T-Vem says:** Welcome to the Cauldron of Hate. If you are a young warrior, you have come to the right place. There are many [duties] to be performed. If you are a veteran of the blade, we welcome your return to service. Perhaps you return with a [Leatherfoot] skullcap?

**You say:** `duties`



if **Faction** >= Amiable then



>**Narex T-Vem says:** I am so glad you asked. There is one matter of importance with which you may be able to assist. It seems an Erudite has made camp in Lavastorm. He is powerful and we do not expect you to slay him. Your mission is to cut off his supply line. I hope you will [accept the mission].


elseif **Faction** >= Indifferent then



>**Narex T-Vem says:** Go! Return when you have done more to serve the Indigo Brotherhood of Neriak. Fewer Leatherfoot Raiders in Nektulos and a few Leatherfoot skullcaps in the palms of Master Narex shall prove your true warrior nature and loyalty to our house.


else



>**Narex T-Vem says:** Your head will make a fine trophy in the halls of the Indigo Brotherhood.




**You say:** `accept the mission`



if **Faction** >= Amiable then



>**Narex T-Vem says:** Go to the Lavastorm Mountain Range. It is a dangerous place, but the one you seek must leave by the direction you entered. He is a goblin. Apparently the Erudite is employing their strength. The fire goblin runner shall be an easy kill for you. At least, he should be. Return his runner pouch to me.


elseif **Faction** >= Indifferent then



>**Narex T-Vem says:** Go! Return when you have done more to serve the Indigo Brotherhood of Neriak. Fewer Leatherfoot Raiders in Nektulos and a few Leatherfoot skullcaps in the palms of Master Narex shall prove your true warrior nature and loyalty to our house.


else



>**Narex T-Vem says:** Your head will make a fine trophy in the halls of the Indigo Brotherhood.




**You say:** `leatherfoot`



if **Faction** >= Amiable then



>**Narex T-Vem says:** Where have you been? The halflings of Rivervale have an elite force of warriors. They are called the Leatherfoot Raiders. They have been infiltrating our glorious city of Neriak for quite some time. They must be exterminated! I must hire strong warriors who wish to [collect the bounty].


elseif **Faction** >= Indifferent then



>**Narex T-Vem says:** Go! Return when you have done more to serve the Indigo Brotherhood of Neriak. Fewer Leatherfoot Raiders in Nektulos and a few Leatherfoot skullcaps in the palms of Master Narex shall prove your true warrior nature and loyalty to our house.


else



>**Narex T-Vem says:** Your head will make a fine trophy in the halls of the Indigo Brotherhood.




**You say:** `collect the bounty`



if **Faction** >= Amiable then



>**Narex T-Vem says:** So you wish to collect the bounty on Leatherfoot Raiders? Then go into Nektulos and hunt them down. I shall pay a reward for no fewer than four Leatherfoot Raider skullcaps.


elseif **Faction** >= Indifferent then



>**Narex T-Vem says:** Go! Return when you have done more to serve the Indigo Brotherhood of Neriak. Fewer Leatherfoot Raiders in Nektulos and a few Leatherfoot skullcaps in the palms of Master Narex shall prove your true warrior nature and loyalty to our house.


else



>**Narex T-Vem says:** Your head will make a fine trophy in the halls of the Indigo Brotherhood.



end

## Turn-Ins



local text = "Fool! There shall be no reward until I have four skullcaps in my hands!";



if **Faction** >= Amiable and  **You turn in:** [Goblin Supply Pouch](/item/13886)


>**Narex T-Vem says:** Fine work. I trust the denizens of Lavastorm were not unkind. Please take this featherweight pouch as a reward. May it keep you fleet of foot.


* __Faction:__ [Indigo Brotherhood](/faction/270) (25)


* __Faction:__ [Emerald Warriors](/faction/326) (-3)


* __Faction:__ [Steel Warriors](/faction/311) (-1)


* __Faction:__ [Primordial Malice](/faction/1522) (-50)


 **You receive:**  [Featherweight Pouch](/item/17972) (+17150 exp)

elseif **You turn in:** [Leatherfoot Raider Skullcap](/item/13113), [Leatherfoot Raider Skullcap](/item/13113), [Leatherfoot Raider Skullcap](/item/13113), [Leatherfoot Raider Skullcap](/item/13113)


>**Narex T-Vem says:** I had my doubts, but you have proven them false. You are a fine warrior. You must continue to refine you talents. I reward you with the footman's voulge! Welcome into our house of warriors. Let us share skills as we share foes.


* __Faction:__ [Indigo Brotherhood](/faction/270) (50)


* __Faction:__ [Emerald Warriors](/faction/326) (-7)


* __Faction:__ [Steel Warriors](/faction/311) (-2)


* __Faction:__ [Primordial Malice](/faction/1522) (-100)


 **You receive:**  [Footmans Voulge](/item/12257) (+25000 exp)

**This NPC *should* return incorrect items given.**






