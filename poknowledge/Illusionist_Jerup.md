# Illusionist Jerup
## Dialog

**You say:** `hail`



e.self:Say("Greetings traveler and welcome to the Plane of Knowledge! I am so pleased to see so many eager minds among us 
end

## Turn-Ins



local ethereal =  **You turn in:**  { [Ethereal Parchment](/item/29112)}

local spectral =  **You turn in:**  { [Spectral Parchment](/item/29131)}

local glyphed =  **You turn in:**  { [Glyphed Rune Word](/item/29132)}

if(ethereal > 0) then


repeat



e.self:Emote("accepts the item quite eagerly. With wide-eyes, the enchanter carefully examines every aspect of the fledgling arcane item. Eventually, she begins to weave a soft chant of arcane words 



 **You receive:** eq.ChooseRandom( [Spell: Greater Fetter](/item/26944), 28413, 28643, 28644, 28452, 28453, 26947, 21665, 21667, 28455, 28457, 28469, 21639) 



ethereal = ethereal - 1;


until ethereal == 0;

if(spectral > 0) then


repeat



e.self:Emote("accepts the item quite eagerly. With wide-eyes, the enchanter carefully examines every aspect of the fledgling arcane item. Eventually, she begins to weave a soft chant of arcane words 



 **You receive:** eq.ChooseRandom( [Spell: Night's Dark Terror](/item/21666), 28458, 28460, 28461, 28464, 28415, 28459, 28465, 28468) 



spectral = spectral - 1;


until spectral == 0;

if(glyphed > 0) then


repeat



e.self:Emote("accepts the item quite eagerly. With wide-eyes, the enchanter carefully examines every aspect of the fledgling arcane item. Eventually, she begins to weave a soft chant of arcane words 



 **You receive:** eq.ChooseRandom( [Spell: Illusion Froglok](/item/21648), 21664, 28470) 



glyphed = glyphed - 1;


until glyphed == 0;

**This NPC *should* return incorrect items given.**






