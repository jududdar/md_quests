# Master Bain
## Dialog

**You say:** `Hail`



>**Master Bain says:** Welcome.  Who has [sent] you to me?

**You say:** `Grand Master Glox`



if **Faction** >= Amiable then



>**Master Bain says:** So Grand Master Glox has sent you?  You must be new to the court.  We are of the Swifttail caste as are you.  Under the guidance of masters such as I. You will forge your body into a weapon of pure destruction.  Do not bother the Grand Master.  He is in constant meditation and is bothered with only the most paramount of concerns.  Are you [ready to train]?


elseif **Faction** >= Indifferent then



>**Master Bain says:** The Swifttail Caste desires further service before I can share this with you.


else



>**Master Bain says:** Leave at once!  I will warn you no longer.  You are no friend to the Swifttail Caste.


**You say:** `ready to train`



if **Faction** >= Amiable then



>**Master Bain says:** Then I can offer training in the martial arts as well as other skills.  Please remember to obtain knowledge from our court chronicler.  You shall also begin to aid your brothers and sisters with [menial tasks].  All begin upon the rung of dust and all have done these tasks in order to climb to the next rung.


elseif **Faction** >= Indifferent then



>**Master Bain says:** The Swifttail Caste desires further service before I can share this with you.


else



>**Master Bain says:** Leave at once!  I will warn you no longer.  You are no friend to the Swifttail Caste.


**You say:** `menial tasks`



if **Faction** >= Amiable then



>**Master Bain says:** We have a few menial tasks we require our young members to perform.  Young members must [tailor training bags] for our court.


elseif **Faction** >= Indifferent then



>**Master Bain says:** The Swifttail Caste desires further service before I can share this with you.


else



>**Master Bain says:** Leave at once!  I will warn you no longer.  You are no friend to the Swifttail Caste.


**You say:** `tailor training bags`



if **Faction** >= Amiable then



>**Master Bain says:** Then take this leech husk pouch and fill it with the obvious.  Once done, combine the skins and take the full leech husk pouch to a local tailor by the name of Klok Mugruk.  He is the one who cleans and toughens the husks for us. He shall hand you a ready-made training bag husk.  He will instruct you further.



**You receive:**  [Leech Husk Pouch](/item/17998)


elseif **Faction** >= Indifferent then



>**Master Bain says:** The Swifttail Caste desires further service before I can share this with you.


else



>**Master Bain says:** Leave at once!  I will warn you no longer.  You are no friend to the Swifttail Caste.


**You say:** `master rinmark`



>**Master Bain says:** Seeking Master Rinmark? He has left the Court of Pain. Gone to focus his thoughts on the elements of wind and thunder. I believe he was headed toward the Overthere. That was the last I heard of his trek.
end

## Turn-Ins



if( **You turn in:** [Pale White Tome](/item/18468), [Vine Woven Basket](/item/22923)) then


>*Master Bain smiles at your dedication to Cazic Thule and hands you a small gem.*


* __Faction:__ [Swift Tails](/faction/444) (5)


* __Faction:__ [Legion of Cabilis](/faction/441) (1)


 **You receive:**  [Mark of Clarity](/item/7881) (+20000 exp)

elseif( **You turn in:** [Dim White Tome](/item/18467), [Earthenware Bowl](/item/22922)) then


>*Master Bain smiles at your dedication to Cazic Thule and hands you a small gem.*


* __Faction:__ [Swift Tails](/faction/444) (5)


* __Faction:__ [Legion of Cabilis](/faction/441) (1)


 **You receive:**  [Mark of Clarity](/item/7881) (+20000 exp)

elseif **Faction** >= Amiable and  **You turn in:** [Monk Training Bag](/item/12688)) then 










>**Master Bain says:** We thank you, young " .. e.other:Class() .. ". In exchange for your prompt service, please accept this piece of training armor. Please continue with your training.





* __Faction:__ [Swift Tails](/faction/444) (5)


* __Faction:__ [Legion of Cabilis](/faction/441) (1)


 **You receive:** eq.ChooseRandom( [Sparring Headgear](/item/4350), [Sparring Facemask](/item/4351), [Sparring Collar](/item/4352), [Sparring Harness](/item/4353), [Sparring Shoulder Pads](/item/4354), [Sparring Rib Pad](/item/4355), [Sparring Arm Guards](/item/4356), [Sparring Grappler Gloves](/item/4357), [Sparring Shin Guards](/item/4358), [Sparring Clogs](/item/4359)) (+500 exp)

**This NPC *should* return incorrect items given.**





