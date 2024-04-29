# Abigail
## Dialog

**You say:** `Hail`



>**Abigail says:** Greetings!  I am the holder of the secret of the [Breastplate of Ro].  You may rest here.  You are quite safe within this camp of paladins.


**You say:** `breastplate of ro`



if **Faction** >= Indifferent +50 then 



>**Abigail says:** The Breastplate of Ro mold will be awarded to you.  First, you will perform a test of strength.  Go to Faydwer.  There you shall seek out and destroy the Teir'Dal who carry the dark cauldrons!!  They have been venturing into our lands and capturing many Koada'Dal and Fier'Dal for cooking purposes!  Bring to me two of their dark cauldrons.


elseif **Faction** >= Indifferent then



>**Abigail says:** You need to prove your loyalty to my temple.  Go to Felwithe and seek out the Clerics of Tunare.  Prove to them your faith.  Then ask the leader of this church if you are a [honored member].


else



>**Abigail says:** You have some nerve to approach a loyal member of the Paladins of Tunare! Run, while you can!

end

## Turn-Ins



local text = "I instructed you to return with no less than two dark pots.";


if **Faction** >= Indifferent +50 and  **You turn in:** [A Dark Cauldron](/item/12309), [A Dark Cauldron](/item/12309)) then 


>**Abigail says:** You have earned the mold.  You will now need go and speak with Thomas about [Lord Searfire].


* __Faction:__ [Clerics of Tunare](/faction/226) (20)


* __Faction:__ [King Tearis Thex](/faction/279) (20)


* __Faction:__ [Anti-mage](/faction/5002) (15)


 **You receive:**  [Mold of Ro Breastplate](/item/12299) 

**This NPC *should* return incorrect items given.**






