# Unmuz Tukore
## Dialog

if(eq.get_current_expansion() >= 4.0) then


**You say:** `hail`




>**Unmuz Tukore says:** Your eyes betray your eagerness and your naivety young one. I am Unmuz Tukore. Scourge Knight of the Bloodsabers. If you have come seeking the [training as a Shadowknight] then I will offer you guidance.


**You say:** `training as a shadowknight`




>**Unmuz Tukore says:** We Scourge Knights of the Bloodsabers, often refered to as shadowknights by those less knowledgeable of our sect, are gifted by Bertoxxulous with prowess in combat and powers over the spirits and bodies of the dead. It is through discipline, training, and devotion to the Plague Lord that we are granted our powers. You must first equip yourself with a [suit of armor] to defend you in battle from the weapons of our [enemies].


**You say:** `suit of armor`




>**Unmuz Tukore says:** Take this note to Wellis Pestule. He will assist you in obtaining your armor. Once you have been properly outfitted return to me. I will allow you to assist me with a [pressing matter].



**You receive:**  [Note to Wellis Pestule](/item/20206)


**You say:** `pressing matter`




>**Unmuz Tukore says:** The Knights of Thunder, the order of paladins loyal to Karana, the Storm Lord, have been paying close attention for signs of us Bloodsabers in the streets of Qeynos. By orders of Antonius Bayle known disciples of the Plague Lord are to be executed by the Knights of Thunder. A particular knight, Grennet Stormhands, has recently discovered the loyalties of a Bloodsaber member that held a valuable position among the merchants of Qeynos. Grennet is to be hunted and slain for our loss. Find this Knight of Thunder and bring me his head.


**You say:** `enemies`




>**Unmuz Tukore says:** The Knights of Thunder and the Priests of Life are our primary foes. and the power behind the throne of Antonius Bayle IV. If it were not for their presence this city would have been claimed in the name of the Plague Lord long ago. Instead we are forced to hide our temple in the catacombs and move through the sewers to avoid the patrols of Qeynos Guards in the streets. Be mindful of your words when not within the walls of this temple. The Qeynos Guards would execute you for your allegiance to the Bloodsabers.

end

## Turn-Ins



local expansion_flag = eq.get_current_expansion();

if(expansion_flag >= 4.0 and  **You turn in:** [Grennet Stormhand's Head](/item/20186)) then


>**Unmuz Tukore says:** Excellent, the Knights of Thunder must learn that by beginning an inquisition of the Bloodsabers they are effectively declaring war. Take this Rusty Scourge Knight Saber to a forge and sharpen it with a sharpening stone. It may take you several attempts if you are unfamiliar with the process. Once that is done take the Tarnished Scourge Knight Saber and a Giant King Snake Skin to Wellis Pestule and he will put the finsihing touches on the weapon.


* __Faction:__ [Bloodsabers](/faction/221) (10)


* __Faction:__ [Guards of Qeynos](/faction/262) (-1)


* __Faction:__ [Opal Darkbriar](/faction/296) (1)


* __Faction:__ [Priests of Life](/faction/341) (-2)


* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (1)


 **You receive:**  [Rusty Scourge Knight Saber](/item/20187) (+500 exp)

**This NPC *should* return incorrect items given.**






