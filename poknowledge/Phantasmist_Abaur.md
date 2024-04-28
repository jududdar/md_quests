# Phantasmist Abaur

## Dialog

**You say:** `Hail`



e.self:Emote("closes his eyes and in a graceful motion, gives a low, sweeping bow. 'Greetings to you, friend, and welcome to the district of Selia. We are the beacon of light and justice, of all that is good and kind. As Tanaan is the cornerstone of neutrality, we are the shining jewel of righteousness, valor, and honor. I am Phantasmist Abaur and in my years upon Norrath, served as an enchanter within the arcane council of Freeport. Then, the city was in a fledgling state of being 
end

## Turn-Ins



local count =  **You turn in:**  { [Insidious Halo](/item/1246),  [Insidious Robe](/item/1247),  [Insidious Sleeves](/item/1248),  [Insidious Manacle](/item/1249),  [Insidious Gloves](/item/1250),  [Insidious Pantaloons](/item/1251),  [Insidious Slippers](/item/1252)}

if(count > 0) then


repeat



>**Phantasmist Abaur says:** Thank you, Soandso.



 **You receive:** eq.ChooseRandom( [Peridot](/item/10028), 10037, 22503, 15981) (+300000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





