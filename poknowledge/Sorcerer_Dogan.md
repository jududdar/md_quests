# Sorcerer Dogan

## Dialog

**You say:** `Hail`



e.self:Emote("sneers darkly, revealing a row of unmanaged teeth beneath his grim visage. 'You travel too leniently, child of the light. Return to Selia, for you will find no welcoming here 
end

## Turn-Ins



local count =  **You turn in:**  { [Carmine Turban](/item/1225),  [Carmine Robe](/item/1226),  [Carmine Sleeves](/item/1227),  [Carmine Trinket](/item/1228),  [Carmine Gloves](/item/1229),  [Carmine Pants](/item/1230),  [Carmine Boots](/item/1231)}

if(count > 0) then


repeat



>**Sorcerer Dogan says:** Thank you, Soandso.



 **You receive:** eq.ChooseRandom( [Peridot](/item/10028), 10037, 22503, 15981) (+300000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





