# Crusader Gimil

## Dialog

**You say:** `Hail`



>**Crusader Gimil says:** kneels low before Soandso, offering a humble gesture of respect and greetings. 'The light of Selia embraces thee, my friend. If you reside in our midst in searching for knowledge and guidance, then know that we are your servants in that quest. Should you be a paladin, and your object of faith is of no consequence in this matter, then my services are humbly at your disposal should you need or wish them.'
end

## Turn-Ins



local count =  **You turn in:**  { [Valorium Helmet](/item/4851),  [Valorium Chestplate](/item/4852),  [Valorium Vambraces](/item/4853),  [Valorium Bracers](/item/4854),  [Valorium Gauntlets](/item/4855),  [Valorium Greaves](/item/4856),  [Valorium Boots](/item/4857)}

if(count > 0) then


repeat



>**Crusader Gimil says:** Thank you, Soandso.



 **You receive:** eq.ChooseRandom( [Peridot](/item/10028), 10037, 22503, 15981) (+300000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





