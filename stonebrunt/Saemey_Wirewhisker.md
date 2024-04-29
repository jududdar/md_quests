# Saemey Wirewhisker
## Dialog

**You say:** `hail`



if **Faction** >= Dubious +300 then



>**Saemey Wirewhisker says:** Welcome to Kejek friend. I am the seer of this village for I have been gifted by the spirits with an affinity for their realm. The barrier between the spirit and physical realms is thin in these lands. The heretics know this and must be prevented from committing [atrocities] similar to those that have been committed in the past.


else



>**Saemey Wirewhisker says:** You have done much to anger the spirits thus you are not accepted by our people.


**You say:** `atrocities`



if **Faction** >= Dubious +300 then



>**Saemey Wirewhisker says:** Long ago when our noble ancestors the Vah Shir were destroyed by an explosion that devastated the warring Heretic and Erudin armies an evil creature by the name of Tserrina Syl'Tor was attracted to the sudden abundance of new spirits in these lands. Tserrina was capable of capturing these spirits before they were able to cross over beyond the mortal realm and through her dark magic transformed them into a [crystalline shadow] substance.


else



>**Saemey Wirewhisker says:** You have done much to anger the spirits thus you are not accepted by our people.


**You say:** `crystalline shadow`



if **Faction** >= Dubious +300 then



>**Saemey Wirewhisker says:** The crystalline shadow substance was used as building blocks for Tserrina's tower on an Island near the frozen lands to the south as well as fashioned into armor and weapons for her mindless servants. Emylie Steelclaws has developed a means to purify the armor and weapons using the special properties of our Kejek forge and a smithy hammer blessed by the Titan Spirits. The purifying process transfers the imprisoned spirits into [soul orbs]. Ask Emylie about the purification process.


else



>**Saemey Wirewhisker says:** You have done much to anger the spirits thus you are not accepted by our people.


**You say:** `soul orb`



if **Faction** >= Dubious +300 then



>**Saemey Wirewhisker says:** I have perfected a ritual that will free the imprisoned spirits within the soul orbs. I simply require some kejek [spirit powder] to scrawl the proper sigils and a soul orb upon which to perform the ceremony. My apprentice will perform the ceremony on fading soul orbs. Simply bring him a fading soul orb and some kejek spirit powder.


else



>**Saemey Wirewhisker says:** You have done much to anger the spirits thus you are not accepted by our people.


**You say:** `spirit powder`



if **Faction** >= Dubious +300 then



>**Saemey Wirewhisker says:** The spirit power of which I speak is composed of ground spiritling stones. I will grind some powder for you if you would bring me a Valley Spiritling Stone, a Jungle Spiritling Stone, and a Mountain Spiritling Stone. Collecting the stones does not truly harm the spiritlings for when slain in this realm their essence simply disperses until it eventually reforms into a new spiritling.


else



>**Saemey Wirewhisker says:** You have done much to anger the spirits thus you are not accepted by our people.

end

## Turn-Ins





if **Faction** >= Dubious +300 and  **You turn in:** [Valley Spiritling Stone](/item/6970), [Jungle Spiritling Stone](/item/6971), [Mountain Spiritling Stone](/item/6972)) then 


>*Saemey Wirewhisker grinds the spiritling stones in a mortar and pestle with foreign runes scratched into the ceramic. 'This powder will assist in matters concerning the contacting or freeing of spirits.'*


* __Faction:__ [Kejek Village](/faction/5011) (1)


* __Faction:__ [Peace Keepers](/faction/298) (1)


 **You receive:** GiveAll( [Kejek Spirit Powder](/item/6980),eq.ChooseRandom(0, [Kejek Spirit Powder](/item/6980)) 

elseif **Faction** >= Dubious +300 and  **You turn in:** [Kejek Spirit Powder](/item/6980), [Soul Orb](/item/6977)) then 


>**Saemey Wirewhisker says:** I require a Soul Orb and Kejek Spirit Dust in order to perform the ritual that will free the imprisoned souls.


>*Saemey Wirewhisker scrawls an arcane symbol on the ground with an odd powder and places the orb in its center. He then begins reciting an incantation and waving his arms over the symbol and orb. Moments later the orb shatters and an apparition appears.*


* __Faction:__ [Kejek Village](/faction/5011) (1)


* __Faction:__ [Peace Keepers](/faction/298) (1)


 **You receive:**  [Shattered Soul Orb](/item/2576) (+5000 exp)

**This NPC *should* return incorrect items given.**
