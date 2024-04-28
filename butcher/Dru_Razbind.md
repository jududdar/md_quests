# Dru Razbind
## Dialog

**You say:** `hail`



>**Dru Razbind says:** Greetings, my friend. What brings you so far from the trodden path? I hope you do not plan on stealing my [fishing spot].

**You say:** `fishing spot`



>**Dru Razbind says:** I need this spot!! I fish to feed my growling tummy. I can no longer [venture into Kaladim] and eat in its fine taverns.

**You say:** `venture into kaladim`



>**Dru Razbind says:** I have been disgraced!! I used to be a respected paladin of the Church of Underfoot until I failed to complete a very [important task] for Lord Datur Nightseer. He stripped me of my Cape of Underfoot. I cannot walk the halls of Kaladim without my cape.

**You say:** `important task`



>**Dru Razbind says:** I was ordered by Lord Nightseer to carry the [Chalice of Conquest] to a noble band of paladins in the mountains of Rathe. While there, the entire camp was overtaken by a band of orcs. During the battle there was a [strange occurrence].

**You say:** `chalice of conquest`



>**Dru Razbind says:** The Chalice of Conquest is said to have been delivered to the Church of Underfoot by Brell himself. It is said that whoever drinks from the chalice is assured victory in battle. It is also said that only good-natured creatures may safely drink from it and only a comatose state is assured to any evil creature who dares to sip from it.

**You say:** `strange occurrence`



>**Dru Razbind says:** A large fray raged. Brave, valiant paladins fought vile, green-skinned orcs and while this happened, I spied the [Chalice of Conquest] being taken away from the camp. I was then distracted by a well placed orcish blade. After I defeated the orcs in my way, I turned to see a blue orc running toward the horizon. I gave chase to no avail. I lost the chalice and all respect. If only a [noble Paladin of Underfoot] would assist me...

**You say:** `candle of bravery`



>**Dru Razbind says:** The Candle of Bravery is ceremonial and is lit when one sips from the [Chalice of Conquest]. The candlestick was left with a fellow Paladin of Underfoot in the Rathe Mountains. The candle itself was lost and I do not know where Priestess Ghalea purchases them.

**You say:** `noble paladin of underfoot`



if **Faction** >= Amiable then 



>**Dru Razbind says:** Yes, you shall do, noble Soandso. Take this. This is the Chalice Case. It is intended for the Chalice of Conquest and the [Candle of Bravery]. If you should get both, be sure to place them within the Chalice Case and combine them. Take the full Chalice Case to Lord Nightseer in Kaladim and I shall be redeemed and you shall surely earn a fine paladin's reward. Let your quest begin in the mountains of Rathe.



**You receive:**  [Chalice Case - empty](/item/17976)


elseif( **Faction is** == Indifferent) then



>**Dru Razbind says:** The Clerics of Underfoot have yet to see your faith directed towards our wills.  Perhaps you should assist Master Gunlok Jure in the crusade against the undead.


else



>**Dru Razbind says:** How dare you approach a member of the Clerics of Underfoot?!  Dogs such as you lie in the same bed as aviaks and ogres!

end

## Turn-Ins



if( **Faction is** > Indifferent and  **You turn in:** [Cape of Underfoot](/item/12281)


>**Dru Razbind says:** I thank you, my friend. You are truly a great paladin and noble addition to our ranks. I now can walk in Kaladim. Take this as a reward. It is the Holy Partisan of Underfoot. It is now yours. I believe it still has a couple of charges. Use it wisely as the only cleric able to recharge it was lost amid the lava filled lands of Antonica.





* __Faction:__ [Paladins of Underfoot](/faction/297) (10)


* __Faction:__ [Kazon Stormhammer](/faction/274) (7)


* __Faction:__ [Clerics of Underfoot](/faction/227) (10)


* __Faction:__ [Veeshan](/faction/216) (1)


 **You receive:**  [Holy Partisan of Underfoot](/item/5376) (+7500 exp)

**This NPC *should* return incorrect items given.**
