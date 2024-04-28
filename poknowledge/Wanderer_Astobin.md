# Wanderer Astobin

## Dialog

**You say:** `Hail`



e.self:Say("Greetings traveler. I am Wanderer Astobin, warden of nature and guardian of Tunare's most blessed and sacred of treasures 
end

## Turn-Ins



local ethereal =  **You turn in:**  { [Ethereal Parchment](/item/29112)}

local spectral =  **You turn in:**  { [Spectral Parchment](/item/29131)}

local glyphed =  **You turn in:**  { [Glyphed Rune Word](/item/29132)}

if(ethereal > 0) then


repeat



e.self:Emote("respectfully accepts the item, holding it in his hands like one would a delicate and priceless relic. His eyes scan its every surface in a detailed study before he closes his eyes and begins to weave a chant of unknown dialect and origin. As the druid's voice filters softly through the area, the object in his hand begins to fade into this existence, its intangible state destroyed beneath the druid's magic. Runes begin to appear upon the fully manifested scroll 



 **You receive:** eq.ChooseRandom( [Spell: Earthen Roots](/item/26943), 28524, 28525, 28526, 28564, 21656, 28527, 28528, 28529, 28530) 



ethereal = ethereal - 1;


until ethereal == 0;

if(spectral > 0) then


repeat



e.self:Emote("respectfully accepts the item, holding it in his hands like one would a delicate and priceless relic. His eyes scan its every surface in a detailed study before he closes his eyes and begins to weave a chant of unknown dialect and origin. As the druid's voice filters softly through the area, the object in his hand begins to fade into this existence, its intangible state destroyed beneath the druid's magic. Runes begin to appear upon the fully manifested scroll 



 **You receive:** eq.ChooseRandom( [Spell: Protection of the Nine](/item/21658), 21659, 28531, 28532, 28533, 28535, 28536, 28538, 21657, 28534, 28537, 28539, 28540) 



spectral = spectral - 1;


until spectral == 0;

if(glyphed > 0) then


repeat



e.self:Emote("respectfully accepts the item, holding it in his hands like one would a delicate and priceless relic. His eyes scan its every surface in a detailed study before he closes his eyes and begins to weave a chant of unknown dialect and origin. As the druid's voice filters softly through the area, the object in his hand begins to fade into this existence, its intangible state destroyed beneath the druid's magic. Runes begin to appear upon the fully manifested scroll 



 **You receive:** eq.ChooseRandom( [Spell: Legacy of Bracken](/item/28645), 28541, 28542, 28543) 



glyphed = glyphed - 1;


until glyphed == 0;

**This NPC *should* return incorrect items given.**





