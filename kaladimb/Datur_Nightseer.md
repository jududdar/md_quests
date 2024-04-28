# Datur Nightseer
## Dialog

**You say:** `hail`



>**Datur Nightseer says:** Welcome to our temple. We are the paladins of the Church of Underfoot. I am lord of our holy order. I call upon you to assist us in the defense of Kaladim. Speak with the master paladins or priests and find ways to prove your allegiance to Brell.

**You say:** `honored member`



if **Faction** >= Indifferent +50 then



>**Datur Nightseer says:** Yes.  The light of righteousness shines from within you.


elseif **Faction** >= Indifferent then



>**Datur Nightseer says:** The Clerics of Underfoot have yet to see your faith directed towards our wills.  Perhaps you should assist Master Gunlok Jure in the crusade against the undead.


else



>**Datur Nightseer says:** How dare you approach a member of the Clerics of Underfoot?!  Dogs such as you lie in the same bed as aviaks and ogres!

end

## Turn-Ins



if **You turn in:** [Folded Parchment](/item/18768)


>**Datur Nightseer says:** Welcome, we are the Paladins of the Underfoot. I am Datur, and I will help teach you the word and will of the Duke of Below, Brell Serilis. Here is our guild tunic. Let's get started, shall we?


* __Faction:__ [Clerics of Underfoot](/faction/227) (100)


* __Faction:__ [Kazon Stormhammer](/faction/274) (100)


* __Faction:__ [Miners Guild 249](/faction/293) (75)


 **You receive:**  [Dusty Tunic*](/item/13514) (+20 exp)

elseif(( **Faction is** > Indifferent) and  **You turn in:** [Chalice Case](/item/12279)


>**Datur Nightseer says:** The chalice is returned!! Praise be to Brell!! You have proven yourself to our church and have earned our respect. Let me welcome you into our brotherhood with the Cape of Underfoot. Wear it with pride as all of our finest paladins do.





* __Faction:__ [Clerics of Underfoot](/faction/227) (15)


* __Faction:__ [Kazon Stormhammer](/faction/274) (15)


* __Faction:__ [Miners Guild 249](/faction/293) (11)


 **You receive:** None 

**This NPC *should* return incorrect items given.**
