# Priestess Jahnda
## Dialog

**You say:** `hail`



>**Priestess Jahnda says:** Welcome to the Temple of Life, where the will of Rodcet Nife, the Prime Healer, is carried out.  I am the High Priestess Jahnda.  If you require any training in our ways, please talk to any of our priests or any of the paladins of the Temple of Life.

**You say:** `blessed oil`



>**Priestess Jahnda says:** I do not distribute the blessed oil of life. Please speak with Nomsoe Jusagta. Tell Nomsoe that Brother Estle needs the blessed oil.

**You say:** `hayle mool`



>**Priestess Jahnda says:** Brother Hayle Mool is one of our finest clerics. He could convert anyone to the ways of Rodcet Nife. Recently, he has been out in the [Plains of Karana] trying to befriend the [Splitpaw clan]. I pray he has not become their prisoner or even worse, their dinner.

**You say:** `paw`



>**Priestess Jahnda says:** Paw is a gnoll burrow. It is said to be located somewhere in the Plains of Karana. The gnolls of this burrow is rarely seen. The fur of these gnolls is white, unlike their brothers in Blackburrow.

**You say:** `bertoxxulous`



>**Priestess Jahnda says:** Bertoxxulous is the evil Lord of Disease. It is he who demeans life with his wicked maladies.  It is said there are some who follow this monster.  They are called the [Bloodsabers].

**You say:** `bloodsaber`



>**Priestess Jahnda says:** So you too have heard the rumors of the Bloodsabers?  These are followers of the lord of disease, Bertoxxulous.  It is our belief that they have begun to spread disease among the animals of Qeynos Hills.  We have yet to confirm their existence.  Please speak with Suuspa Clanim and the others.

**You say:** `rodcet`



>**Priestess Jahnda says:** The Prime Healer, the giver of all life.  Rodcet Nife is the power which flows through every living being, be he good or evil.  It is in honor of Him that the Temple of Life was constructed.  It is for Him that we devote our lives to the extermination of all who would taint the glory of life.

**You say:** `heal`



>**Priestess Jahnda says:** I cannot help you with your request.   You must speak with Brother Tonmerk Plorsin.

**You say:** `honored member`



if **Faction** >= Indifferent +50 then



>**Priestess Jahnda says:** Yes.  The light of righteousness shines from within you.


elseif **Faction** >= Indifferent then



>**Priestess Jahnda says:** The Temple of Life smiles upon you, friend... but such a delicate matter can only be entrusted to our most loyal members.


else



>**Priestess Jahnda says:** Your mere presence disgusts me. Please remove yourself from my sight. Until you change yourself and your ways, you are unwelcome in the Temple of Life.

end

## Turn-Ins



if( **You turn in:** [A tattered note](/item/18714)) then 


>**Priestess Jahnda says:** Welcome to the Temple of Life. I am Jahnda, the High Priestess of the Clerics of Nife. Wear this tunic with pride and carry out the will of Nife. Please, see Tonmerk Plorsin or Nomsoe Jusagta. They will help get you started spreading the will of The Prime Healer.


* __Faction:__ [Priests of Life](/faction/341) (100)


* __Faction:__ [Knights of Thunder](/faction/280) (30)


* __Faction:__ [Guards of Qeynos](/faction/262) (50)


* __Faction:__ [Bloodsabers](/faction/221) (-25)


* __Faction:__ [Antonius Bayle](/faction/219) (15)


 **You receive:**  [Faded Tunic*](/item/13506) (+100 exp)

elseif( **You turn in:** [Pouch of Evidence](/item/13724)) then


>**Priestess Jahnda says:** Excellent work! You are surely under the protection and guidance of the Prime Healer. This evidence will help us greatly to convince Antonious and the guild leaders of Qeynos that the Bloodsabers are here and seek to destroy all we have worked so long for.





* __Faction:__ [Priests of Life](/faction/341) (50)


* __Faction:__ [Knights of Thunder](/faction/280) (15)


* __Faction:__ [Guards of Qeynos](/faction/262) (25)


* __Faction:__ [Bloodsabers](/faction/221) (-12)


* __Faction:__ [Antonius Bayle](/faction/219) (7)


if(math.random(100) > 5) then



 **You receive:** eq.ChooseRandom( [Potion of Light Healing](/item/14007), [Potion of Disease Warding](/item/14003)) (+4000 exp)


else



 **You receive:** eq.ChooseRandom( [Skullcap of Rodcet Nife](/item/13723), [Shield of Nife](/item/13720)) (+4000 exp)


elseif( **You turn in:** [PrayerBeads](/item/13911)) then 


>**Priestess Jahnda says:** Oh my word!! This is terrible news. This belongs to Hayle Mool. He has been captured by the Splitpaw Clan while in Karana. You must go to his aid. We cannot do so at this time. Here. Be sure to hand him this summons. I will need to speak with him.


 **You receive:**  [Temple Summons](/item/18927) 

**This NPC *should* return incorrect items given.**
