# Phantasmist Salkith

## Dialog

**You say:** `Hail`



e.self:Emote("tilts his head back, a sneer crossing his features in unmasked disgust toward Soandso. 'What exactly are you doing here, Soandso? Don't you know that this is the district of Kartis 


e.self:Emote("ponders a moment, then continues. 'Yes, Soandso, your god does not exist 
end

## Turn-Ins



local count =  **You turn in:**  { [Insidious Halo](/item/1246),  [Insidious Robe](/item/1247),  [Insidious Sleeves](/item/1248),  [Insidious Manacle](/item/1249),  [Insidious Gloves](/item/1250),  [Insidious Pantaloons](/item/1251),  [Insidious Slippers](/item/1252)}

if(count > 0) then


repeat



>**Phantasmist Salkith says:** Thank you, Soandso.



 **You receive:** eq.ChooseRandom( [Peridot](/item/10028), 10037, 22503, 15981) (+300000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





