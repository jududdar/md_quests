# Pathfinder Viliken

## Dialog

**You say:** `Hail`



>**Pathfinder Viliken says:** Greetings, friend, and welcome to New Tanaan. We have worked hard to properly greet you into our midst, and hope that our efforts shall not be in vain. As a ranger of Tunare in my former life upon Norrath, I have joined my fellow Pathfinders in scribing spells from memory of our journeys upon your world. These spells are not unique to the Plane of Knowledge, for they are the same as those Norrath offers to its guardians. However, they may be convenient for you to purchase here while you are browsing our libraries and engaging in the wonders of our beautiful, peaceful city. However, do not forget the scholars whilst you are engaging in the planes. You may stumble across a piece of pure arcane manifestation that may appear mundane at first, but with my help can become a spell of great power to all of nature's wardens.
end

## Turn-Ins



local ethereal =  **You turn in:**  { [Ethereal Parchment](/item/29112)}

local spectral =  **You turn in:**  { [Spectral Parchment](/item/29131)}

local glyphed =  **You turn in:**  { [Glyphed Rune Word](/item/29132)}

if(ethereal > 0) then


repeat



e.self:Emote("takes the arcane item from you. Carefully, he inspects it 



 **You receive:** eq.ChooseRandom( [Spell: Earthen Roots](/item/26943), 21628, 21627) 



ethereal = ethereal - 1;


until ethereal == 0;

if(spectral > 0) then


repeat



e.self:Emote("takes the arcane item from you. Carefully, he inspects it 



 **You receive:** eq.ChooseRandom( [Spell: Frozen Wind](/item/26931), 26929, 26930, 21626) 



spectral = spectral - 1;


until spectral == 0;

if(glyphed > 0) then


repeat



e.self:Emote("takes the arcane item from you. Carefully, he inspects it 



 **You receive:** eq.ChooseRandom( [Spell: Protection of the Wild](/item/21655), 26932) 



glyphed = glyphed - 1;


until glyphed == 0;

**This NPC *should* return incorrect items given.**





