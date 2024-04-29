# Grand Master Glox
## Dialog

**You say:** `hail`



>*Grand Master Glox 'shows no reaction to your greeting.'*


**Signaled to:**  [Master Niska](/npc/106097)

**You say:** `trial of agility`



>**Grand Master Glox says:** I knew you were not the whiff others claimed you to be, are you sure you are [ready] to be tested in agility?

**You say:** `ready`



if **Faction** >= Amiable then



>**Grand Master Glox says:** We shall spar then, I hope you are as prepared as you think you are.



**Grand Master Glox casts:** [Cabilis Sending](/spell/2064) on target.


elseif **Faction** >= Indifferent then



>**Grand Master Glox says:** The Swifttail Caste desires further service before I can share this with you.


else



>**Grand Master Glox says:** Leave at once!  I will warn you no longer.  You are no friend to the Swifttail Caste.

end

## Turn-Ins



local text1 = "sits, his eyes still closed, and tilts his head in confusion. He then sighs and shakes his head implying disappointment. You suddenly realize that the old master asked for the mole's collar and two star rubies.";




if( **You turn in:** [Guild Summons](/item/18204)) then 


>*Grand Master Glox 'breaks his meditation and quickly grabs your forearms. You feel the raw power in his heavily callused hands. Out of nowhere, his tail sweeps forward and places a shackle upon your wrist. He then points south towards Master Bain and returns to his meditation.'*


* __Faction:__ [Swift Tails](/faction/444) (200)



* __Faction:__ [Legion of Cabilis](/faction/441) (50)






 **You receive:**  [Shackle of Dust](/item/4190) (+1000 exp)


elseif( **You turn in:** [Illegible Note: Helm](/item/14788)) then


>*Grand Master Glox sits whispering incoherently for a long moment before even regarding the note you dropped in front of him. The Grand Master suddenly snatches up the note from Xlixinar, removes a small charcoal marker from a belt pouch, and scrawls some intructions upon it. He drops the note immediately after finishing and resumes his meditation without a word.*


 **You receive:**  [Note from Glox](/item/18980) 

elseif( **You turn in:** [a Tiny Collar](/item/14782), [Star Ruby](/item/10032), [Star Ruby](/item/10032)) then


>*Grand Master Glox nods slightly*


 **You receive:**  [Glox Reference](/item/14783) (+10000 exp)

**This NPC *should* return incorrect items given.**





