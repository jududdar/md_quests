# Yeolarn Bronzeleaf
## Dialog

**You say:** `hail`



if **Faction** >= Indifferent then




>**Yeolarn Bronzeleaf says:** Hail, Soandso! We of Tunare are charged with protecting the Great Mother from the forces of Innoruuk. Even now, the evil minions of this foul deity are despoiling our great forest. Will you help us [protect the Mother]?


else



>**Yeolarn Bronzeleaf says:** One such as yourself has nothing to offer the Clerics of Tunare. Remove yourself from this sacred temple!


**You say:** `protect`



if **Faction** >= Indifferent then



>**Yeolarn Bronzeleaf says:** Just outside the gates of Felwithe, the forces of Innoruuk gather in the guise of decaying skeletons. Bring me four sets of bone chips as proof of your vigilance. I assure you, your faith shall not go unrewarded.


else



>**Yeolarn Bronzeleaf says:** One such as yourself has nothing to offer the Clerics of Tunare. Remove yourself from this sacred temple!


**You say:** `initiate of tunare`



>**Yeolarn Bronzeleaf says:** The Teir'Dal behind the undead plague in our forest have discovered a means of creating a terrible undead called a Ghast. These Ghasts have been sighted in the Lesser Faydark and must be destroyed. Bring me four of the vile creatures hearts.

**You say:** `slay the necromancer`



>**Yeolarn Bronzeleaf says:** The Fier'Dal rangers that inhabit the Lesser Faydark have spotted a courier making deliveries to the Teir'Dal camp near Castle Mistmoore and to a necromancer that lingers near the ancient obelisk. We believe that the crates he carries are supplies needed for the creation of more Ghasts. Another shipment should be arriving soon. Seek out the necromancer at the obelisk and take his head then take the head of the courier and return them to me with the crate that the courier carries and your Initiate Symbol of Tunare.

**You say:** `warden of tunare`



>**Yeolarn Bronzeleaf says:** The crate that the you recovered from the Courier contained this black candlestick that radiates an aura of great magical power. I request that you deliver the candlestick to Lady Trilani who is studying with the High Men in Erudin. Perhaps she can divine the nature of the candlestick and offer aid in defeating its power. The remaining contents of the crate have been given to Crusader Swiftmoon to be delivered to a gnome in steamfont that is purchasing them on behalf of the Eldrich Collective. When you return be sure to present your Disciple Symbol to me with anything that Trilani may ask you to deliver.


**You receive:**  [Black Stone Candlestick](/item/1598)
end

## Turn-Ins



local text1 = "I requested four Ghast hearts!";


if **Faction** >= Indifferent and  **You turn in:** [Bone Chips](/item/13073), [Bone Chips](/item/13073), [Bone Chips](/item/13073), [Bone Chips](/item/13073)


>**Yeolarn Bronzeleaf says:** Praise Tunare! I knew you would be victorious. I reward you with this spell, and pray that it will help you in your fight against the unholy forces of Innoruuk. When you are ready you will make a fine [Initiate of Tunare].


* __Faction:__ [Clerics of Tunare](/faction/226) (2)


* __Faction:__ [King Tearis Thex](/faction/279) (2)


* __Faction:__ [Anti-mage](/faction/5002) (1)


 **You receive:**  [Spell: Strike](/item/15014) (+4400 exp)

elseif **Faction** >= Indifferent and  **You turn in:** [Putrescent Heart](/item/10199), [Putrescent Heart](/item/10199), [Putrescent Heart](/item/10199), [Putrescent Heart](/item/10199)


>**Yeolarn Bronzeleaf says:** Praise Tunare!! You have done well young Initiate. Here the symbol of your station within our faith. Return to me when you are ready to [slay the necromancer] that has been creating the undead.


* __Faction:__ [Clerics of Tunare](/faction/226) (15)


* __Faction:__ [King Tearis Thex](/faction/279) (15)


* __Faction:__ [Anti-mage](/faction/5002) (11)


 **You receive:**  [Initiate Symbol of Tunare](/item/1570) (+3250 exp)

elseif **Faction** >= Indifferent and  **You turn in:** [Initiate Symbol of Tunare](/item/1570), [Teir\`Dal Courier's Head](/item/12514), [Teir\`Dal Crate](/item/19065), [Larik Z\`Vole's Head](/item/12513)


>**Yeolarn Bronzeleaf says:** Praise Tunare! The Mother smiles on you this day Disciple Soandso! I present you with the symbol of your new station among the Priests of Tunare. Return to me when you are ready to become a [Warden of Tunare]?


* __Faction:__ [Clerics of Tunare](/faction/226) (30)


* __Faction:__ [King Tearis Thex](/faction/279) (30)


* __Faction:__ [Anti-mage](/faction/5002) (22)


 **You receive:**  [Disciple Symbol of Tunare](/item/1571) (+4000 exp)

elseif **Faction** >= Indifferent and  **You turn in:** [Disciple Symbol of Tunare](/item/1571), [Powder of Unanimation](/item/1599)


>**Yeolarn Bronzeleaf says:** Praise Tunare!! I will have our sorcerers examine this power immediately to see if we can reproduce it in quantities enough to eliminate the undead plague. I award you the rank of Warden of Tunare, the All Mother smiles upon you, Soandso!


* __Faction:__ [Clerics of Tunare](/faction/226) (40)


* __Faction:__ [King Tearis Thex](/faction/279) (40)


* __Faction:__ [Anti-mage](/faction/5002) (30)


 **You receive:**  [Warden Symbol of Tunare](/item/1572) (+5000 exp)

elseif **Faction** >= Indifferent and  **You turn in:** [A tattered note](/item/18780)


>**Yeolarn Bronzeleaf says:** Welcome, friend, to the Clerics of Tunare. I am Yeolarn Bronzeleaf, head of the guild and devout follower of Tunare. Here is your guild tunic - it will help to protect you against this world's evils.


* __Faction:__ [Clerics of Tunare](/faction/226) (100)


* __Faction:__ [King Tearis Thex](/faction/279) (100)


* __Faction:__ [Anti-mage](/faction/5002) (75)


 **You receive:**  [Faded Gold Training Tunic*](/item/13590) (+20 exp)

else


>**Yeolarn Bronzeleaf says:** Your faith has not grown strong enough to undertake that task young one.

**This NPC *should* return incorrect items given.**
;

