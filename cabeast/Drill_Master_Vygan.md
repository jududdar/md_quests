# Drill Master Vygan
## Dialog

**You say:** `hail`



>**Drill Master Vygan says:** I am a Drill Master of the Legion of Cabilis.  I have no time for idle chitchat.  Be off if you were not summoned to this fortress!  Find that guild which was chosen for you as an egg.

**You say:** `militia pike`



if **Faction** >= Amiable then



>**Drill Master Vygan says:** The pike is the prime weapon of Cabilis warriors. It can be upgraded, too, such as from the partisan pike to the militia pike and beyond. All these pikes may be slung on one's back when your hands are needed for other pursuits. To upgrade a pike is something that is learned, but it can never be performed without a [geozite tool]. Do you [desire to upgrade the partisan pike]?


elseif **Faction** >= Indifferent then



>**Drill Master Vygan says:** No Iksar resident will have anything to do with you!


else



>**Drill Master Vygan says:** Hiss!  Fool!  Fear the Legion of Cabilis for you are no ally to us.  Leave while you can.


**You say:** `upgrade the partisan pike`



if **Faction** >= Amiable then



>**Drill Master Vygan says:** It seems as though a traitor is among our people. Someone has smuggled shackle keys to the slaves. The froglok slaves have been escaping into the swamplands and there we can hear the whistle of their contact who escorts them to freedom. We must put a stop to this! I desire three things. Your partisan pike, the head of the Iksar traitor and the whistle of the escort. Bring these to me and I shall give you the militia pike.


elseif **Faction** >= Indifferent then



>**Drill Master Vygan says:** No Iksar resident will have anything to do with you!


else



>**Drill Master Vygan says:** Hiss!  Fool!  Fear the Legion of Cabilis for you are no ally to us.  Leave while you can.


**You say:** `what geozite tool`



if **Faction** >= Amiable then



>**Drill Master Vygan says:** The Geozite Tool is used to sharpen the pikes of the Legion of Cabilis. Only it can produce the serrated edges necessary for these deadly weapons. They are not handed out to just any broodling. The tool is only given to warriors who serve the legion. Do you [want a geozite tool]?


elseif **Faction** >= Indifferent then



>**Drill Master Vygan says:** No Iksar resident will have anything to do with you!


else



>**Drill Master Vygan says:** Hiss!  Fool!  Fear the Legion of Cabilis for you are no ally to us.  Leave while you can.


**You say:** `want a geozite tool`



if **Faction** >= Amiable then



>**Drill Master Vygan says:** Then take this satchel and go to the outer walls of Cabilis and seek out large scorpions. When you can fill and combine the satchel with scorpion pincers, then you shall prove to me that you are truly a warrior and I shall send you off on your true test.



**You receive:**  [Pincer Satchel](/item/17993)


elseif **Faction** >= Indifferent then



>**Drill Master Vygan says:** No Iksar resident will have anything to do with you!


else



>**Drill Master Vygan says:** Hiss!  Fool!  Fear the Legion of Cabilis for you are no ally to us.  Leave while you can.


**You say:** `true warrior of the legion`



if **Faction** >= Amiable then



>**Drill Master Vygan says:** If you are you will have proof; else you will have the wrath of the Legion upon you for such a claim.


elseif **Faction** >= Indifferent then



>**Drill Master Vygan says:** No Iksar resident will have anything to do with you!


else



>**Drill Master Vygan says:** Hiss!  Fool!  Fear the Legion of Cabilis for you are no ally to us.  Leave while you can.


**You say:** `partisan of cabilis`



if **Faction** >= Amiable then



>**Drill Master Vygan says:** Bah! You are but a broodling!  Report to the other Drill Masters and pray that they can help you overcome your incompetence.


elseif **Faction** >= Indifferent then



>**Drill Master Vygan says:** No Iksar resident will have anything to do with you!


else



>**Drill Master Vygan says:** Hiss!  Fool!  Fear the Legion of Cabilis for you are no ally to us.  Leave while you can.

end

## Turn-Ins



local text1 = "You shall wield no militia pike until I have the head of the traitor, the fife of the escort and the partisan pike.";



if( **You turn in:** [Guild Summons](/item/18203)) then 


>**Drill Master Vygan says:** I see they have begun to draft younger broodlings? Hmmph!! No matter. We Drill Masters shall make a warrior of you. Here is your partisan's pike and some coin as your wages. Be sure that you begin your training in blacksmithing and report to the other Drill Masters for any tasks they may have for you. Let them know you are [a partisan of Cabilis]. Perhaps soon you shall be rewarded the [militia pike].


* __Faction:__ [Legion of Cabilis](/faction/441) (100)



* __Faction:__ [Cabilis Residents](/faction/440) (25)



* __Faction:__ [Scaled Mystics](/faction/445) (25)



* __Faction:__ [Crusaders of Greenmist](/faction/442) (25)




* __Faction:__ [Swift Tails](/faction/444) (25)







 **You receive:**  [Partisan's Pike](/item/5130) (+500 exp)


elseif **Faction** >= Amiable and  **You turn in:** [Froglok Escort Fife](/item/12675), [An Iksar Head](/item/12677), [Partisan's Pike](/item/5130)) then


>**Drill Master Vygan says:** You have perfomed just as expected. I bestow upon you the rank of militiaman. Here is your new pike. Past this, you shall require the [geozite tool] to upgrade your future pikes and mancatchers. We see much promise in you, militiaman. Go forth to serve the realm.


* __Faction:__ [Legion of Cabilis](/faction/441) (10)



* __Faction:__ [Cabilis Residents](/faction/440) (2)



* __Faction:__ [Scaled Mystics](/faction/445) (2)



* __Faction:__ [Crusaders of Greenmist](/faction/442) (2)




* __Faction:__ [Swift Tails](/faction/444) (2)



 **You receive:**  [Militia's Pike](/item/5131) (+200 exp)

elseif **Faction** >= Amiable and  **You turn in:** [Full Pincer Satchel](/item/12658)) then


>**Drill Master Vygan says:** You are a true warrior of Cabilis. You obviously are aware that in order to upgrade your pike you shall need a [geozite tool]. Take this note to the Lord of the outer gates. He desires a young warrior for a small task. Do this and he is instructed to reward you with the tool.


* __Faction:__ [Legion of Cabilis](/faction/441) (5)



* __Faction:__ [Cabilis Residents](/faction/440) (1)



* __Faction:__ [Scaled Mystics](/faction/445) (1)



* __Faction:__ [Crusaders of Greenmist](/faction/442) (1)




* __Faction:__ [Swift Tails](/faction/444) (1)



 **You receive:** eq.ChooseRandom( [Note to Iksar Lord](/item/18213), [Note to Iksar Lord](/item/18211), [Note to Iksar Lord](/item/18210)) (+200 exp)

**This NPC *should* return incorrect items given.**





