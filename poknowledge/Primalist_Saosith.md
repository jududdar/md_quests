# Primalist Saosith

## Dialog

**You say:** `hail`



e.self:Say("Welcome, traveler, to New Tanaan. All citizens of New Tanaan have come together in welcoming Norrath's curious travelers who crave knowledge and a path to better themselves individually. What little help I alone can offer is extended to the Beastlords of Norrath, for as I was once one of them in a time long since past. If you are a Beastlord, then perhaps what spells that I have penned, though neither unique nor rare to your world, would be of use. If through your endeavors upon the planes you happen to come across fledgling manuscripts 
end

## Turn-Ins



local ethereal =  **You turn in:**  { [Ethereal Parchment](/item/29112)}

local spectral =  **You turn in:**  { [Spectral Parchment](/item/29131)}

local glyphed =  **You turn in:**  { [Glyphed Rune Word](/item/29132)}

if(ethereal > 0) then


repeat



>**Primalist Saosith says:** The magic you have given me is quite potent, it should be a simple task to use primal forces to focus its magic into a spell.



>*Primalist Saosith closes her eyes and the object glows slightly in her hands.*



>**Primalist Saosith says:** Here, I hope this will prove of some use to you.



 **You receive:** eq.ChooseRandom( [Spell: Infusion of Spirit](/item/28544), 28545, 21629, 28547, 28548) 



ethereal = ethereal - 1;


until ethereal == 0;

if(spectral > 0) then


repeat



>**Primalist Saosith says:** The magic you have given me is quite potent, it should be a simple task to use primal forces to focus its magic into a spell.



>*Primalist Saosith closes her eyes and the object glows slightly in her hands.*



>**Primalist Saosith says:** Here, I hope this will prove of some use to you.



 **You receive:** eq.ChooseRandom( [Spell: Arag's Celerity](/item/28549), 28550, 21630, 28551, 28552) 



spectral = spectral - 1;


until spectral == 0;

if(glyphed > 0) then


repeat



>**Primalist Saosith says:** The magic you have given me is quite potent, it should be a simple task to use primal forces to focus its magic into a spell.



>*Primalist Saosith closes her eyes and the object glows slightly in her hands.*



>**Primalist Saosith says:** Here, I hope this will prove of some use to you.



 **You receive:** eq.ChooseRandom( [Spell: Sha's Revenge](/item/28553), 28554) 



glyphed = glyphed - 1;


until glyphed == 0;

**This NPC *should* return incorrect items given.**





