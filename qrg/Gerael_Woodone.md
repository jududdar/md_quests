# Gerael Woodone
## Dialog

**You say:** `hail`



>**Gerael Woodone says:** It is good to meet you, Soandso. You, my friend, are an adventurer. The rugged look of you testifies to that. Let me know if you plan to adventure in the Plains of Karana. I have need of a person such as yourself to [deliver a flask].

**You say:** `deliver a flask`



if **Faction** >= Amiable then 



>**Gerael Woodone says:** That is splendid! I thought I would have to take the long journey to the western Plains of Karana myself. Here you are, my friend. Take this flask of nitrates to a woman named Linaya Sowlin. It will help her crops grow stronger. You will find her farm alongside the road to Highpass Hold. She should pay you well for the delivery. Farewell.



**You receive:**  [Flask of Nitrates](/item/13945)


elseif **Faction** >= Indifferent then



>**Gerael Woodone says:** We, the Jaggedpine Treefolk, appreciate the help you've given us in the past. But, we must trust you more before allowing you to handle such important matters.




else



>**Gerael Woodone says:** You are an enemy of the Jaggedpine Treefolk, this forest, and the residents of it. Begone, before I am forced to take drastic measures!




**You say:** `Jale Phlintoes`



>**Gerael Woodone says:** Jale Phlintoes was trained in the ways of the Jaggedpine Treefolk since his birth. He was only eight when his parents were killed by poachers. Young Jale would have had his throat slit also if he were not off fishing at the lake. Unfortunate. The now orphaned Jale was brought up by us druids. After many conflicts with our council, he ran off to start his own sect somewhere in the nearby lands. For his terrorist activities his head now brings a high price.

**You say:** `Unkempt Druid`



>**Gerael Woodone says:** The Unkempt Druids are a radical splinter group of druids. Their beliefs have been contorted by the mad druid [Jale Phlintoes]. It is he who engineers and coordinates the druids' transgressions. From setting lumbermills aflame to murdering any man who dares to wear a bearhide. They must be stopped!! Citizens must learn to understand Tunare's will, not fear it.

**You say:** `leader`



>**Gerael Woodone says:** The land of Surefall Glade is ruled by no single hand other than Tunare, but if guidance is what you seek, I would suggest you speak with Te\`Anara.  She is the head of the Jaggedpine Treefolk.  Otherwise, you could speak with Hager Sureshot of the Protectors of the Pine.

**You say:** `poacher`



>**Gerael Woodone says:** Poachers have been plaguing our land.  We do our best to stop them.  If you wish to join the fight, seek the masters of the Protectors of the Pine.

**You say:** `mammoth`



>**Gerael Woodone says:** That information is best kept secret.

**You say:** `druid guild`



>**Gerael Woodone says:** The Jaggedpine Treefolk are the local druids.  The masters can be found here within the great tree.

**You say:** `forge`



>**Gerael Woodone says:** We have nothing like that here in Surefall Glade.  You must venture to Qeynos.

**You say:** `armor`



>**Gerael Woodone says:** Oftentimes you can find a traveling merchant in one of the nearby houses.  Other than that you would have to travel to Qeynos.

**You say:** `qeynos`



>**Gerael Woodone says:** The great city of Qeynos can be found by walking along the path outside of Surefall Glade.  Many of our rangers and druids serve alongside the Qeynos Guard when the need arises.

**You say:** `bank`



>**Gerael Woodone says:** There is no need for a vault among our people.  You could try the Qeynos Hold in Qeynos.

**You say:** `talym`



>**Gerael Woodone says:** Talym Shoontar is a wanted man.  He is a very infamous poacher.  Hager Sureshot has placed a bounty upon his head.

**You say:** `chanda`



>**Gerael Woodone says:** The entire Miller family are nothing more than scum.  It is they who entice poachers to continue with their slaughter so they can profit from the skins of the wildlife.


**You say:** `tunarbos`



>**Gerael Woodone says:** Long ago, centuries before the Combine Era even, there grew a great tree upon Norrath.  It stretched to the stars and was as wide as the span of Erud's Crossing.  From the roots of this tree sprung all the woodlands of Norrath.  An unknown force struck it down.  Some say it was the great dragon, Veeshan!  Whatever the force, the Great Tunarbos was shattered.  Lost forever.  Now the wood chips lie scattered across the face of Norrath.  To hold a shard of the Great Tunarbos is to hold the hand of Tunare.
end

## Turn-Ins




if **Faction** >= Dubious and  **You turn in:** [A Tattered Cloth Note](/item/18911)) then


>**Gerael Woodone says:** Oh my!! Our Qeynos Ambassador, Gash, is in danger. Please take the note over to Captain Tillin of the Qeynos Guard then find Gash and inform him [they are trying to kill him]. Go!!


 


* __Faction:__ [Jaggedpine Treefolk](/faction/272) (15)


* __Faction:__ [Protectors of Pine](/faction/302) (3)


* __Faction:__ [QRG Protected Animals](/faction/343) (2)


* __Faction:__ [Unkempt Druids](/faction/324) (-3)


* __Faction:__ [Guards of Qeynos](/faction/262) (2)


 **You receive:**  [A Tattered Cloth Note](/item/18912) (+10 exp)

elseif **Faction** >= Dubious and  **You turn in:** [Black Wood Chip](/item/12141)) then 


>**Gerael Woodone says:** So the Unkempt Druids are alive and well.  We shall keep a watchful eye out as should you.  Take this for your bravery and defense of the Jaggedpine.


* __Faction:__ [Protectors of Pine](/faction/302) (20)


* __Faction:__ [Jaggedpine Treefolk](/faction/272) (5)


* __Faction:__ [QRG Protected Animals](/faction/343) (3)


* __Faction:__ [Unkempt Druids](/faction/324) (-5)


* __Faction:__ [Guards of Qeynos](/faction/262) (3)


 **You receive:** eq.ChooseRandom( [Rusty Short Sword](/item/5013), [Rusty Axe](/item/5014), [Rusty Scythe](/item/5015), [Rusty Broad Sword](/item/5016), [Minotaur Battle Axe](/item/5017), [Pick](/item/5018), [Rusty Long Sword](/item/5019), [Rusty Battle Axe](/item/5020), [Rusty Scimitar](/item/5021), [Rusty Bastard Sword](/item/5022), [Rusty Two Handed Sword](/item/5023), [Rusty Halberd](/item/5024)) (+10 exp)

**This NPC *should* return incorrect items given.**
