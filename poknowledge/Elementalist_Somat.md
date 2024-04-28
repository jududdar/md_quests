# Elementalist Somat

## Dialog

**You say:** `hail`



e.self:Say("Greetings, traveler! I am Somat, Elementalist extraordinaire and one of several of my trade here in New Tanaan. We have all spent much time preparing for your arrival and hope that our time is not in vain. If you are a wielder of the elemental forces, then come and browse my inventory, friend! I may hold a spell or two that might pique your interest. Also, if you perhaps hold a seemingly mundane item of arcane relation that you found in your travels upon the planes, then do not hesitate to let me have a look at it. Don't worry 
end

## Turn-Ins



local ethereal =  **You turn in:**  { [Ethereal Parchment](/item/29112)}

local spectral =  **You turn in:**  { [Spectral Parchment](/item/29131)}

local glyphed =  **You turn in:**  { [Glyphed Rune Word](/item/29132)}

if(ethereal > 0) then


repeat



e.self:Emote("takes the planar arcane item and examines it with a strange glance in his eye. At first he seems overly excited 



 **You receive:** eq.ChooseRandom( [Spell: Belt of Magi'Kot](/item/21641), 21642, 32411, 29357, 29358, 29359, 29360, 29361, 28413, 28428, 28440, 21637, 21643, 21646, 21669, 28430, 28431) 



ethereal = ethereal - 1;


until ethereal == 0;

if(spectral > 0) then


repeat



e.self:Emote("takes the planar arcane item and examines it with a strange glance in his eye. At first he seems overly excited 



 **You receive:** eq.ChooseRandom( [Spell: Blade of The Kedge](/item/21644), 29362, 28432, 28433, 28497, 16341, 29363, 21645, 21659, 21668, 28415, 28434) 



spectral = spectral - 1;


until spectral == 0;

if(glyphed > 0) then


repeat



e.self:Emote("takes the planar arcane item and examines it with a strange glance in his eye. At first he seems overly excited 



 **You receive:** eq.ChooseRandom( [Spell: Rathe's Son](/item/28435), 28436, 16342) 



glyphed = glyphed - 1;


until glyphed == 0;

**This NPC *should* return incorrect items given.**






