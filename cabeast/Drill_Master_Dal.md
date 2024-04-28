# Drill Master Dal
## Dialog

**You say:** `Hail`



>**Drill Master Dal says:** Yes, yes!!  What do I have here?!!  Another [new recruit]?  If so, then speak up!  If not, then leave and do not waste my time nor risk your life.  I also seek a [legion soldier] if you be one.

**You say:** `new recruit`



if **Faction** >= Amiable then



>**Drill Master Dal says:** Yes.  You have the look of the Partisan.  I trust you have begun your blacksmith training.  If not, then do so.  Also, you should read all the books available to you in Fortress Talishan.  We are not dimwitted broodlings here.  You shall need the knowledge soon. That, or a coffin.  Ha!!  Here is your task, are you [ready for your task]?


elseif **Faction** >= Indifferent then



>**Drill Master Dal says:** No Iksar resident will have anything to do with you!


else



>**Drill Master Dal says:** Hiss!  Fool!  Fear the Legion of Cabilis for you are no ally to us.  Leave while you can.


**You say:** `soldier`



if **Faction** >= Amiable then



>**Drill Master Dal says:** Good news to my ears!!  I seek to prove to the War Baron that the infamous forsaken band of thieves who call themselves Marrtail's Marauders are operating within earshot of our city.  You must bring me proof that you encountered no fewer than four of these thieves.  Do so and I shall offer you an armor item unavailable to most.


elseif **Faction** >= Indifferent then



>**Drill Master Dal says:** No Iksar resident will have anything to do with you!


else



>**Drill Master Dal says:** Hiss!  Fool!  Fear the Legion of Cabilis for you are no ally to us.  Leave while you can.


**You say:** `ready`



if **Faction** >= Amiable then



>**Drill Master Dal says:** Yes. yes!!  It does not matter.  You must be ready.  I will hand you the Partisan pack.  Into it you shall combine one giant blood sac of the giant leech;  scout beads from a goblin scout; one sabertooth kitten canine and finally, three bone shards from decaying skeletons.  Hopefully, you will survive your attempt to obtain these items.  Return the full Partisan pack and you shall be rewarded with a curscale shield.



**You receive:**  [Partisan Pack](/item/17997)


elseif **Faction** >= Indifferent then



>**Drill Master Dal says:** No Iksar resident will have anything to do with you!


else



>**Drill Master Dal says:** Hiss!  Fool!  Fear the Legion of Cabilis for you are no ally to us.  Leave while you can.

end

## Turn-Ins




if **Faction** >= Amiable and  **You turn in:** [Marauder Snout Ring 'MM'](/item/12915), [Marauder Snout Ring 'MM'](/item/12915), [Marauder Snout Ring 'MM'](/item/12915), [Marauder Snout Ring 'MM'](/item/12915)


>*Drill Master Dal hands you a shimmering black piece of armor which smells quite horrid. You find it hard to keep it from slithering out of your hand. 'Here is the armor the tailors have been working on for the legion. You may test it for us. Keep up your fine work and I may have other pieces available for you to test.'*


* __Faction:__ [Legion of Cabilis](/faction/441) (5)


* __Faction:__ [Cabilis Residents](/faction/440) (1)


* __Faction:__ [Scaled Mystics](/faction/445) (1)


* __Faction:__ [Crusaders of Greenmist](/faction/442) (1)


* __Faction:__ [Swift Tails](/faction/444) (1)


 **You receive:** eq.ChooseRandom( [Leech Husk Tunic](/item/12917), [Leech Husk Leggings](/item/12918), [Leech Husk Gloves](/item/12919), [Leech Husk Wrist Bands](/item/12920), [Leech Husk Boots](/item/12921)) (+1000 exp)

elseif **Faction** >= Amiable and  **You turn in:** [Full Partisan Pack](/item/12673)


>**Drill Master Dal says:** Fantastic work, Partisan Soandso. Here is your reward. You may continue to perform this task as the baron has found it aids in our defense. I shall always pay for a good day's work. Just let me know if you are still [ready for the task]. As for the curskin shield, you may only have one. Perhaps soon you will prove yourself a formidable fighter and you can earn a militia pike from Drill Master Vygan.


* __Faction:__ [Legion of Cabilis](/faction/441) (5)


* __Faction:__ [Cabilis Residents](/faction/440) (1)


* __Faction:__ [Scaled Mystics](/faction/445) (1)


* __Faction:__ [Crusaders of Greenmist](/faction/442) (1)


* __Faction:__ [Swift Tails](/faction/444) (1)


 **You receive:**  [Curscale Buckler](/item/12674) (+250 exp)

**This NPC *should* return incorrect items given.**
