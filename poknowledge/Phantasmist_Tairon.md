# Phantasmist Tairon

## Dialog

**You say:** `Hail`



if(e.other:Race() == "Dark Elf" or e.other:Race() == "Iksar" or e.other:Race() == "Troll" or e.other:Race() == "Ogre" or e.other:Class() == "Shadowknight" or e.other:Class() == "Necromancer") then



e.self:DoAnim(48)



e.self:Emote("gives a soft, though polite nod of greetings. 'You stand within the district of Tanaan 


else



e.self:DoAnim(70);



e.self:Emote("gives a deep, sweeping bow of proper and formal greetings. 'Welcome, Heiggan, to the district of Tanaan 

end

## Turn-Ins



local count =  **You turn in:**  { [Insidious Halo](/item/1246),  [Insidious Robe](/item/1247),  [Insidious Sleeves](/item/1248),  [Insidious Manacle](/item/1249),  [Insidious Gloves](/item/1250),  [Insidious Pantaloons](/item/1251),  [Insidious Slippers](/item/1252)}

if(count > 0) then


repeat



>**Phantasmist Tairon says:** This looks good, thank you Soandso.







 **You receive:** eq.ChooseRandom( [Peridot](/item/10028), 10037, 22503, 15981) (+300000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





