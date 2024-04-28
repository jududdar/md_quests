# Master Niska
## Dialog

**You say:** `hail`



>*Master Niska bows with elegance and grace. You can see her arms rippling with muscles. 'Greetings. We are the Swifttails. We are the harnessers of the elements. We are the tails of discipline. To achieve rebirth into our caste is a great honor indeed. We can be identified by our adornments. You should display that which we have given you to adorn your arms with pride. You do have your Shackle of Dust, correct?'*

**You say:** `no`



>**Master Niska says:** You dare disgrace us?' She hisses at you. 'If you have truely lost the marking of our caste, you will need to take this note and speak to the Toilmaster immediately. Read it on the way and praise the will of Cazic Thule.


**You receive:**  [A Ragged Book](/item/18271)

**You say:** `yes`



>**Master Niska says:** Very good Broodling. Display your adornment with pride so that the enemies of the Brood may see our might as you rip through the weak will of their ranks. Now be gone from my sight.

**You say:** `shackle of rock`



if **Faction** >= Amiable then



>*Master Niska strikes within inches of your snout with amazing speed. 'The Shackle of Rock is your interest? Then learn well our ways and prepare yourself. If the stone embraces your wrist, you are ready indeed. To complete the second rung you must find for me the [Fists of Talon].'*


elseif **Faction** >= Indifferent then



>**Master Niska says:** The Swifttail Caste desires further service before I can share this with you.


else



>**Master Niska says:** Leave at once!  I will warn you no longer.  You are no friend to the Swifttail Caste.


**You say:** `fists of talon`



if **Faction** >= Amiable then



>*Master Niska points to the Court Chronicler. 'All that is known of Talon has been chronicled. Should you obtain the fists then you shall hand them to me. This shall earn you the Shackle of Rock.'*


elseif **Faction** >= Indifferent then



>**Master Niska says:** The Swifttail Caste desires further service before I can share this with you.


else



>**Master Niska says:** Leave at once!  I will warn you no longer.  You are no friend to the Swifttail Caste.


**You say:** `troubles with.* outlander`



if **Faction** >= Amiable then



>**Master Niska says:** It seems Klok Ephmir has encountered an outlander who was hunting the food we lizards enjoy. The legion will not act without proof of this outlanders existence. We were asked by the Baron to find this proof. We shall do this. You shall provide me with the outlanders head and the Shackles of Rock and Stone!!


elseif **Faction** >= Indifferent then



>**Master Niska says:** The Swifttail Caste desires further service before I can share this with you.


else



>**Master Niska says:** Leave at once!  I will warn you no longer.  You are no friend to the Swifttail Caste.


**You say:** `will be your personal courier`



if **Faction** >= Amiable then



>*Master Niska grabs a tin box resting by her feet. 'Take this to Master Rinmark and be quick about it!!'*



**You receive:**  [A Tin Box](/item/12829)


elseif **Faction** >= Indifferent then



>**Master Niska says:** The Swifttail Caste desires further service before I can share this with you.


else



>**Master Niska says:** Leave at once!  I will warn you no longer.  You are no friend to the Swifttail Caste.

end

## Turn-Ins



local text1 = "Tsk, tsk, tsk. There were more of Talon's Fists than this. Only by gathering all of his fists shall you earn the shackle of rock and bring you closer to the third rung.";

local text2 = "This is not all. Bring me the item this caste seeks and the shackles of stone and rock.";


if **Faction** >= Amiable and  **You turn in:** [Iksar Right Hand =|-](/item/12797), [Iksar Left Hand =|-](/item/12798), [Iksar Left Hand =|-](/item/12799)


>*Master Niska removes a crudley hewn shackle. 'This is yours. It is one of the keys to the third rung. I see that you are truely a great monk and have studied your disciplines well. I have need of one as you. I have heard of [troubles with an outlander].'*


* __Faction:__ [Swift Tails](/faction/444) (10)


* __Faction:__ [Legion of Cabilis](/faction/441) (2)


 **You receive:**  [Shackle of Rock](/item/4193) (+20000 exp)


elseif **Faction** >= Amiable and  **You turn in:** [An Outlander's Head](/item/12821), [Shackle of Stone](/item/4192), [Shackle of Rock](/item/4193)


>**Master Niska says:** Very good!! Here is your Shackle of Copper. The Emperor shall be pleased that I, Mistress Niska, have slain the outlander. Do you have some time? I need someone to be my [personal courier]. Will you?


* __Faction:__ [Swift Tails](/faction/444) (10)


* __Faction:__ [Legion of Cabilis](/faction/441) (2)


 **You receive:**  [Shackle of Copper](/item/4194) (+40000 exp)


elseif **You turn in:** [Light Grey Tome](/item/18466), [Kromdul Bracelet](/item/22921)


>*Master Niska smiles at your dedication to Cazic Thule and hands you a small gem.*


* __Faction:__ [Swift Tails](/faction/444) (5)


* __Faction:__ [Legion of Cabilis](/faction/441) (1)


 **You receive:**  [Mark of Clarity](/item/7881) (+20000 exp)


elseif **You turn in:** [Greyed Tome](/item/18465), [Ring of the Construct](/item/22920)


>*Master Niska smiles at your dedication to Cazic Thule and hands you a small gem.*


* __Faction:__ [Swift Tails](/faction/444) (5)


* __Faction:__ [Legion of Cabilis](/faction/441) (1)


 **You receive:**  [Mark of Clarity](/item/7881) (+20000 exp)

elseif **You turn in:** [Rites of Exoneration](/item/18272), [Filled Penance Bag](/item/24770)


>**Master Niska says:** You dare disgrace us?' She hisses at you. 'If you have truly lost the marking of our caste, you will need to take this note and speak to the Toilmaster immediately. Read it on the way and praise the will of Cazic-Thule.


* __Faction:__ [Swift Tails](/faction/444) (100)


* __Faction:__ [Legion of Cabilis](/faction/441) (25)


 **You receive:**  [Shackle of Dust](/item/4190) (+500 exp)


**This NPC *should* return incorrect items given.**

## Signals

>**Master Niska says:** You dare disgrace us?' She hisses at you. 'If you have truly lost the marking of our castle, you will need to take this note and speak to the Toilmaster immediatley. Read it on the way and praise the will of Cazic-Thule.'