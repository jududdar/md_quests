# Captain Karim
local count = 0;
## On NPC Spawn

**Set a timer** named *karim* for 175 seconds
## Timer(s)

count = count + 1;

if(count == 1) then


>**Captain Karim says:** Maintain your focus on the attack. Let the Taruun dance around the enemies while you keep them distracted. Working together like this will be to your advantage.

if(count == 2) then


>**Captain Karim says:** Do not let the enemy attack your unarmored companions. Your heavy armor will protect you much more efficiently than cloth or leather.

if(count == 3) then


>**Captain Karim says:** Try to lure your enemy to a strategic location for battle. Your are at a disadvantage when you attack them in their lair.

if(count == 4) then


>**Captain Karim says:** You there! Pay attention! Do not lose focus. Losing focus in battle can result in the death of your comrades. Be aware of your surroundings at all times. You never know when an enemy will leap at you from behind.

if(count == 5) then


>**Captain Karim says:** If the enemy mutters mystical words, a swift bash in the face with your shield is likely to shut its yap. Remember this young ones, for this advice will one day save your lives.

if(count == 6) then


>**Captain Karim says:** Be sure to stock yourself with plenty of food and water before forming a battle group. It is not wise to leave your companions without your aid while you return home for more supplies. There is plenty of time to relax at the tavern when your mission is accomplished.

if(count == 7) then


>**Captain Karim says:** They raid our trade routes even as I speak. We cannot afford to let the Gor Taku supply them with even more aid!

if(count == 8) then


>**Captain Karim says:** It is our duty to protect the roads. We need to maintain a steady flow of supplies from the furless ones.

if(count == 9) then


>**Captain Karim says:** It is wise to make use of your enemy's equipment. Our supply is short as it is.

if(count == 10) then


>**Captain Karim says:** Kick your enemy to throw them off balance. Then strike with your blade. It is important to stay on your toes.


count = 0;


**Set a timer** named *karim* for 175 seconds
end

## Dialog

**You say:** `Hail`



>**Captain Karim says:** Greetings, adventurer. Pay no heed to Captain Koldar should you see him. Our true enemy are the Gor Taku. It is very apparent that they are in league with the Loda Kai Brigands. We need to show the Shak Dratha that we are not their enemy. Help me destroy the Gor Taku clan, return to me with four of their earthcaller stones and I will help you however I can.
end

## Turn-Ins





if( **You turn in:** [Gor Taku Earthcaller's Stone](/item/30835), [Gor Taku Earthcaller's Stone](/item/30835), [Gor Taku Earthcaller's Stone](/item/30835), [Gor Taku Earthcaller's Stone](/item/30835)) then


>**Captain Karim says:** Well done Soandso, your efforts are invaluable. Perhaps we can convince the Shak Dratha that we are not their enemy after all. Alas, with the turmoil in these parts I am afraid that I cannot part with any military supplies as they are needed by my troops. I can, however, at least send you off with a bit of coin and my thanks. Take care my friend!


* __Faction:__ [Guardians of Shar Vahl](/faction/1513) (2)


 **You receive:** 0 (+5000 exp)

**This NPC *should* return incorrect items given.**
