# Crusader Difur

## Dialog

**You say:** `Hail`



>*Crusader Difur kneels before Soandso in humble recognition. The clang of his spotless, dwarven crafted armor against the stone floor briefly chimes through the hall. The song of steel and marble is echoed by his gruff, iron voice. 'I am Difur, Crusader of Brell Serillis and master of the paladins in the district of Tanaan. If ye seek knowledge and wisdom of the justly knights of Norrath than I, most humbly, am at yer service, traveler.'*
end

## Turn-Ins



local count =  **You turn in:**  { [Valorium Helmet](/item/4851),  [Valorium Chestplate](/item/4852),  [Valorium Vambraces](/item/4853),  [Valorium Bracers](/item/4854),  [Valorium Gauntlets](/item/4855),  [Valorium Greaves](/item/4856),  [Valorium Boots](/item/4857)}

if(count > 0) then


repeat



>**Crusader Difur says:** Thank you, Soandso.



 **You receive:** eq.ChooseRandom( [Peridot](/item/10028), 10037, 22503, 15981) (+300000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





