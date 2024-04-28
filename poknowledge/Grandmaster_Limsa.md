# Grandmaster Limsa

## Dialog

**You say:** `Hail`



>*Grandmaster Limsa closes his eyes and gives a deep-seated bow before Soandso. 'Greetings, traveler. I am Grand Master Limsa, master of the tranquil order of the Tanaan district of the Plane of Knowledge. Monks of both Norrathian orders may approach me for guidance and knowledge through the long path of self-mastery and discipline.'*
end

## Turn-Ins



local count =  **You turn in:**  { [Shiverback-hide Jerkin](/item/1201),  [Shiverback-hide Armbands](/item/1202),  [Shiverback-hide Wristbands](/item/1203),  [Shiverback-hide Gloves](/item/1204),  [Shiverback-hide Leggings](/item/1205),  [Shiverback-hide Boots](/item/1206)}

if(count > 0) then


repeat



>**Grandmaster Limsa says:** Thank you, Soandso.



 **You receive:** eq.ChooseRandom( [Peridot](/item/10028), 10037, 22503, 15981) (+300000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





