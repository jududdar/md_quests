# Grandmaster Chendra

## Dialog

**You say:** `Hail`



>*Grandmaster Chendra gives a deep-seated bow of respect and humble greetings. Her voice is gentle and calm, like the soothing melody of a grandmother with the youth of a newborn wind. 'Greetings, my friend, and may the light watch over your path. The district of Selia is one of light and upholds its virtues fervently, though we do not seek to impose upon others in our humble plane. You will find many whom, upon your world, are enemies but here, though they look upon you with disdain, are ultimately your equals in the quest for knowledge and enlightenment. If you are a student of the disciplines of the monk, then I shall lend my knowledge to you whenever you are in need of lessons in the martial skills of our order.'*
end

## Turn-Ins



local count =  **You turn in:**  { [Shiverback-hide Jerkin](/item/1201),  [Shiverback-hide Armbands](/item/1202),  [Shiverback-hide Wristbands](/item/1203),  [Shiverback-hide Gloves](/item/1204),  [Shiverback-hide Leggings](/item/1205),  [Shiverback-hide Boots](/item/1206)}

if(count > 0) then


repeat



>**Grandmaster Chendra says:** Thank you, Soandso.



 **You receive:** eq.ChooseRandom( [Peridot](/item/10028), 10037, 22503, 15981) (+300000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





