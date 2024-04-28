# Virtuoso Legilwan


## Dialog

**You say:** `Hail`



if(e.other:Race() == "Dark Elf" or e.other:Race() == "Iksar" or e.other:Race() == "Troll" or e.other:Race() == "Ogre" or e.other:Class() == "Shadowknight" or e.other:Class() == "Necromancer") then



e.self:DoAnim(60)



>*Virtuoso Legilwan raises a brow sharply and gains a face of almost belittling amusement as he eyes Soandso before him. 'Do you not think yourself out of place here, dark one? Please, do not be offended, for that is not my intent in the least, of course. I would rather see your needs fulfilled to the utmost of your necessity than see you leave this place no more knowledgeable than before your arrival. The library of Myrist in the center of our city is home to the scholars of New Tanaan, who believe themselves to have ascended beyond the 'petty mortal squabbles*


else



e.self:DoAnim(48);



>*Virtuoso Legilwan gives a gentle, though formal nod of his head in warm greetings. 'Welcome, Soandso, to the district of Tanaan. We have the utmost faith that this humble place will accommodate your every need most generously. The merchants in scattered throughout our region are quite useful to any tradesmen or adventurer seeking to restock on supplies and the devises of teleportation found in this district should be more than suitable for one of your ilk. If you have come to Tanaan seeking guidance in the ways of mentorship and skills, then know only success in your search for we are more than prepared to accommodate the needs of almost any adventurer. The bards of Norrath who seek guidance without the ravings of a philosophical, political, or religious zealot will find myself to be a most formidable suitor to their needs.'*

end

## Turn-Ins



local count =  **You turn in:**  { [Imbrued Platemail Helm](/item/4861),  [Imbrued Platemail Breastplate](/item/4862),  [Imbrued Platemail Vambraces](/item/4863),  [Imbrued Platemail Bracer](/item/4864),  [Imbrued Platemail Gauntlets](/item/4865),  [Imbrued Platemail Greaves](/item/4866),  [Imbrued Platemail Boots](/item/4867)}

if(count > 0) then


repeat



>**Virtuoso Legilwan says:** Thank you, Soandso.



 **You receive:** eq.ChooseRandom( [Peridot](/item/10028), 10037, 22503, 15981) (+300000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





