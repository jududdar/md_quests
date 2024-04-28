# Alex McDarnin
## Dialog

**You say:** `Hail`



>**Alex McDarnin says:** Hail! Do you by chance bring news from the North? I sure do miss the cold. It is just a bit too warm for me down here. Well, I wish you the best of luck in your travels. Tomorrow is a new day and I am off in search of [new writings] to take back to the Tribunal.

**You say:** `new writings`



>**Alex McDarnin says:** There have been tales of new writings being found in some of the ancient ruins that abound outside of this outpost. These writings will be very valuable to my church. The sooner I can return with the writings, the sooner the Tribunal can put the teachings to work. I am always in need of aides so if [you want to help], just say so.

**You say:** `I want to help`



>**Alex McDarnin says:** We won't be traveling together, but here is what I need. There are four writings that still elude me. Return one of these and I'll spare one of the four extra writings I have. I am looking for the writings called Talisman of Jasinth, Spirit of Scale, Cripple, and Cannibalize III. Be off, and may your travels be safe!
end

## Turn-Ins



local count =  **You turn in:**  { [Spell: Cripple](/item/19269),  [Spell: Spirit of Scale](/item/19238),  [Spell: Talisman of Jasinth](/item/19264),  [Spell: Cannibalize III](/item/19272)}

if(count > 0) then


repeat



>**Alex McDarnin says:** Here is the scroll that I promised. We have both gained much knowledge today. I hope to do business with you again soon. Farewell!



 **You receive:** eq.ChooseRandom( [Spell: Talisman of Shadoo](/item/19267), [Spell: Shroud of the Spirits](/item/19271), [Spell: Torrent of Poison](/item/19274), [Spell: Insidious Decay](/item/19266)) (+1000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





