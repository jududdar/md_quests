# Cavalier Waut

## Dialog

**You say:** `Hail`



>**Cavalier Waut says:** Good day t'ye, traveler. The adepts of New Tanaan 'ave worked very laboriously t'properly welcome ye t'the Plane of Knowledge. Many of us 'ave delved into the past lives of our ventures upon Norrath an' 'ave brought forth from the recesses of our memories the spells that we once wielded as might t'our cause. Now, we no longer be needin' them, but we understand that ye may very well find them t'be of use yet. Oh, and if ye find an item of arcane nature though it seems t'be mundane or useless t'ye, dinnae disregard it! The planes 'old many items that are not what they seem, friend. Return such incorporeal runes and scrolls t'me and I shall make them spells worhty of any crusading paladin!
end

## Turn-Ins



local ethereal =  **You turn in:**  { [Ethereal Parchment](/item/29112)}

local spectral =  **You turn in:**  { [Spectral Parchment](/item/29131)}

local glyphed =  **You turn in:**  { [Glyphed Rune Word](/item/29132)}

if(ethereal > 0) then


repeat



>*Cavalier Waut accepts the item carefully, studying it with great caution as she handles it in her small hands. The paladin then nods softly to herself as if in recognition or preparation and then closes her eyes. The dwarf's voice begins to spill softly across the area in a divine chant of reverence and prayer. As the dwarf speaks her indeciferable words, the item in her hand seems to grow corporeal and real. Runes form upon it in silvery script that seem to shimmer in the torch-cast light of Myrist. Eventually, she opens her eyes and inspects the item for a final time. Nodding to herself once more in satisfaction, she hands the scroll to you with a warm smile, ''This should de ye good, m'friend, I guarantee! Be careful, though, for this be a powerful spell not t'be underestimated or used without caution or respect.*



 **You receive:** eq.ChooseRandom( [Spell: Greater Immobilize](/item/26945), 21631, 26941, 21652, 26933, 26937) 



ethereal = ethereal - 1;


until ethereal == 0;

if(spectral > 0) then


repeat



>*Cavalier Waut accepts the item carefully, studying it with great caution as she handles it in her small hands. The paladin then nods softly to herself as if in recognition or preparation and then closes her eyes. The dwarf's voice begins to spill softly across the area in a divine chant of reverence and prayer. As the dwarf speaks her indeciferable words, the item in her hand seems to grow corporeal and real. Runes form upon it in silvery script that seem to shimmer in the torch-cast light of Myrist. Eventually, she opens her eyes and inspects the item for a final time. Nodding to herself once more in satisfaction, she hands the scroll to you with a warm smile, ''This should de ye good, m'friend, I guarantee! Be careful, though, for this be a powerful spell not t'be underestimated or used without caution or respect.*



 **You receive:** eq.ChooseRandom( [Spell: Pious Might](/item/26934), 26939, 21654, 26935, 21649) 



spectral = spectral - 1;


until spectral == 0;

if(glyphed > 0) then


repeat



>*Cavalier Waut accepts the item carefully, studying it with great caution as she handles it in her small hands. The paladin then nods softly to herself as if in recognition or preparation and then closes her eyes. The dwarf's voice begins to spill softly across the area in a divine chant of reverence and prayer. As the dwarf speaks her indeciferable words, the item in her hand seems to grow corporeal and real. Runes form upon it in silvery script that seem to shimmer in the torch-cast light of Myrist. Eventually, she opens her eyes and inspects the item for a final time. Nodding to herself once more in satisfaction, she hands the scroll to you with a warm smile, ''This should de ye good, m'friend, I guarantee! Be careful, though, for this be a powerful spell not t'be underestimated or used without caution or respect.*



 **You receive:** eq.ChooseRandom( [Spell: Shackles of Tunare](/item/21653), 26936, 26938) 



glyphed = glyphed - 1;


until glyphed == 0;

**This NPC *should* return incorrect items given.**





