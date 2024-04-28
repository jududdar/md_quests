# Harbinger Glosk
## Dialog

**You say:** `hail`



>*Harbinger Glosk halts his chanting. 'You dare to interrupt me? You had best have a good reason. I care not for small talk.'*

**You say:** `keepers grotto`



>**Harbinger Glosk says:** Keepers Grotto is where you shall find the Keepers. They study and scribe the spells of our dark circle. The grotto is not far from here, near the arena called the Gauntlet.

**You say:** `new revenant`



if **Faction** >= Amiable +100 then



>**Harbinger Glosk says:** Yes. You are. You shall do as I command. Take this. It is incomplete and must be ready for the emperor within the half season. You must find the [Four Missing Gems]. When you have them, then you will have to Quest for the [Grand Forge of Dalnir]. Within it's fire, all shall combine. Return the Sceptre to me with your Revenant Skullcap. Go.



**You receive:**  [Unfinished Sceptre](/item/12873)










elseif **Faction** >= Indifferent then



>**Harbinger Glosk says:** When you have shown more devotion to the Brood of Kotiz, we can discuss such things.


else



>**Harbinger Glosk says:** You are a true simpleton to think you can speak to me.  You are no ally to the Brood of Kotiz.  Begone, before I make your blood boil!


**You say:** `four missing gems`



if **Faction** >= Amiable +100 then



>**Harbinger Glosk says:** The missing sceptre gems are: an Eye of Rokgus, a Gem of Yet to Come, a Heart of Torsis and the Crown Jewel of Ganak.


elseif **Faction** >= Indifferent then



>**Harbinger Glosk says:** When you have shown more devotion to the Brood of Kotiz, we can discuss such things.


else



>**Harbinger Glosk says:** You are a true simpleton to think you can speak to me.  You are no ally to the Brood of Kotiz.  Begone, before I make your blood boil!


**You say:** `forge of dalnir`



if **Faction** >= Amiable +100 then



>*Harbinger Glosk scratches his chin. 'I know little of it other than that it once belonged to the ancient Haggle Baron, Dalnir. From what I have read, its fires require no skill, but will melt any common forge hammer used. Dalnir was said to have called upon the ancients for a hammer which could tolerate the magical flames.'*


elseif **Faction** >= Indifferent then



>**Harbinger Glosk says:** When you have shown more devotion to the Brood of Kotiz, we can discuss such things.


else



>**Harbinger Glosk says:** You are a true simpleton to think you can speak to me.  You are no ally to the Brood of Kotiz.  Begone, before I make your blood boil!

end

## Turn-Ins



local text = "I await both the sceptre and your revenant skullcap.";




if **You turn in:** [Guild Summons](/item/18207)



>**Harbinger Glosk says:** Another apprentice has reached rebirth. You now have become one with the Brood of Kotiz. We study the ancient writing of Kotiz. Through his writing we have found the power of the dark circles. Listen well to the scholars within this tower and seek the [Keepers Grotto] for knowledge of our spells. This drape shall be the sign to all Iksar that you walk with the Brood. Now go speak with Xydoz.


* __Faction:__ [Brood of Kotiz](/faction/443) (100)










* __Faction:__ [Legion of Cabilis](/faction/441) (25)













 **You receive:**  [Drape of the Brood](/item/12407) (+500 exp)




elseif **Faction** >= Amiable and  **You turn in:** [Sceptre of Emperor Vekin](/item/12874), [Revenant Skullcap](/item/4265)


>*Harbinger Glosk presents to you a glowing skullcap. 'This is the treasured cap of the sorcerers of this tower. Let all gaze upon you in awe. You are what others aspire to be. I look forward to reading of your adventures, Sorceror Soandso.'*


* __Faction:__ [Brood of Kotiz](/faction/443) (10)


* __Faction:__ [Legion of Cabilis](/faction/441) (2)


 **You receive:**  [Sorcerer Skullcap](/item/4266) (+10000 exp)












elseif **You turn in:** [Illegible Note: Boots](/item/14794)


>*Harbinger Glosk hisses and says venomously, 'And I am disturbed yet again. I hope for your sake it is important.'*


>*Harbinger Glosk The gaunt necromancer looks down at the paper in his hands and after reading a few lines gasps, then falls into a violent coughing fit. After recovering he takes a deep breath, puffs his chest out and hands the paper back to you. With his head held high, he says in a raspy voice, 'Show this to Rixiz. He will test you.'*


 **You receive:**  [Illegible Note: Boots](/item/14794) 

elseif **You turn in:** [Illegible Note: Greaves](/item/14793)


>*Harbinger Glosk snatches the note out of your hands, obviously irritated. After reading a few lines, he glances up at you, his brow furrowed, then looks down again to continue reading. When he's finished, he hands the note back to you and takes a deep breath, shuddering slightly. He then says, 'Xydoz. Take this to Xydoz. He will test you.'*


>*Harbinger Glosk watches you carefully as you leave.*


 **You receive:**  [Illegible Note: Greaves](/item/14793) 

**This NPC *should* return incorrect items given.**
 



