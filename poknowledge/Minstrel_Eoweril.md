# Minstrel Eoweril

## Dialog

**You say:** `Hail`



>**Minstrel Eoweril says:** Hail and well met, my friend. New Tanaan greets you most warmly and is grateful to have you in our midst. All residents of this great Plane of Knowledge have come together in recent times with the unexpected, though warmly embraced presence of Norrathian visitors. We hope that we might be able to aid you in lending our wisdom and timeless knowledge wherever possible to your cause. I wish I could do more, my friend, but I am but a humble bard and my services may only benefit those of like profession. However, if you believe that my services could be of use, then do not hesitate to peruse my inventory and purchase what you will. If by chance you come across a curious parchment or other arcane item of seemingly unidentifiable purpose, then do not hesitate to bring it to me. Besides having composed many a song in my day, I do know a thing or two regarding mysteries of the planes' magics.
end

## Turn-Ins



local ethereal =  **You turn in:**  { [Ethereal Parchment](/item/29112)}

local spectral =  **You turn in:**  { [Spectral Parchment](/item/29131)}

local glyphed =  **You turn in:**  { [Glyphed Rune Word](/item/29132)}

if(ethereal > 0) then


repeat



>*Minstrel Eoweril takes the item from you and begins to humm softly, the item changes in his hands as the words take form into melody.*



 **You receive:** eq.ChooseRandom( [Song: Silent Song of Quellious](/item/28471), 28473, 21636, 28474, 28475, 28484, 16391) 



ethereal = ethereal - 1;


until ethereal == 0;

if(spectral > 0) then


repeat



>*Minstrel Eoweril takes the item from you and begins to humm softly, the item changes in his hands as the words take form into melody.*



 **You receive:** eq.ChooseRandom( [Song: Psalm of Veeshan](/item/28478), 28480, 28483, 28472, 28479, 28481, 28482, 21650) 



spectral = spectral - 1;


until spectral == 0;

if(glyphed > 0) then


repeat



>*Minstrel Eoweril takes the item from you and begins to humm softly, the item changes in his hands as the words take form into melody.*



 **You receive:** eq.ChooseRandom( [Song: Tuyen's Chant of Fire](/item/28477), 28485, 28486) 



glyphed = glyphed - 1;


until glyphed == 0;

**This NPC *should* return incorrect items given.**






