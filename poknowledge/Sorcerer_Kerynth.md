# Sorcerer Kerynth

## Dialog

**You say:** `Hail`



if(e.other:Race() == "Dark Elf" or e.other:Race() == "Iksar" or e.other:Race() == "Troll" or e.other:Race() == "Ogre" or e.other:Class() == "Shadowknight" or e.other:Class() == "Necromancer") then



e.self:DoAnim(60)



e.self:Emote("inhales sharply in a very stern study of the dark one before him. 'You travel lightly, I see. Perhaps you are merely lost and my reaction is one of preconceived notions. In any event, the district of Kartis is not too distant a travel from where you stand now and I'm certain that your own kind would be more than helpful in accommodating your immediate needs while within this fair city. If for one reason or another you are here by intent, then we reluctantly welcome you upon the condition that you uphold our ways of neutrality 


else



e.self:DoAnim(48);



e.self:Emote("gives a deep nod of his head in formal and polite recognition of Soandso before him. 'Greetings, traveler, and welcome to the district of Tanaan. In light of your presence among us, we have gathered our knowledge and memories of lives past upon Norrath in hopes that our experiences would benefit you in the present. Do not hesitate to approach all citizens of this district, for we are equally fair and willing to grant you the aid that is within our individual power to provide. In my own personal experience upon Norrath, I was a wizard of some power 

end

## Turn-Ins



local count =  **You turn in:**  { [Carmine Turban](/item/1225),  [Carmine Robe](/item/1226),  [Carmine Sleeves](/item/1227),  [Carmine Trinket](/item/1228),  [Carmine Gloves](/item/1229),  [Carmine Pants](/item/1230),  [Carmine Boots](/item/1231)}

if(count > 0) then


repeat



>**Sorcerer Kerynth says:** Thank you, Soandso.



 **You receive:** eq.ChooseRandom( [Peridot](/item/10028), 10037, 22503, 15981) (+300000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**
