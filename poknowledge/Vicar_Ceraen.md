# Vicar Ceraen

## Dialog

**You say:** `Hail`



>**Vicar Ceraen says:** Greetings, Soandso. I am Ceraen, priest of Tunare and resident of New Tanaan for over three centuries of my existence. Do not fear those whom may have been your enemy upon the prime. The scholars are equal and without bias toward one another, thus there is no safer place in the cosmos than New Tanaan. Each resident strives to bring knowledge closer to the curious and willing, and I am not exempt from this.


e.self:Say("If you are a priest in your world and seek to gain a higher understanding of the divine power that your faith has allowed you to wield, then perhaps what spells I have penned from memory of your world would be of use. I have also mastered levels in the workings of planar magic and its chaotic ways of forming upon the manifested planes. If by chance you come across a fledgling arcane item 
end

## Turn-Ins



local ethereal =  **You turn in:**  { [Ethereal Parchment](/item/29112)}

local spectral =  **You turn in:**  { [Spectral Parchment](/item/29131)}

local glyphed =  **You turn in:**  { [Glyphed Rune Word](/item/29132)}

if(ethereal > 0) then


repeat



e.self:Emote("takes the arcane item with great care and respect from you. For several moments the priest seems to enter a state of contemplative meditiation upon the arcane planar item. Suddenly, he begins a slow, soft chant 



 **You receive:** eq.ChooseRandom( [Spell: Faith](/item/28646), 28557, 28561, 28572, 21690, 26945,26946,28558, 28563, 28566, 28567, 28564, 26947) 



ethereal = ethereal - 1;


until ethereal == 0;

if(spectral > 0) then


repeat



e.self:Emote("takes the arcane item with great care and respect from you. For several moments the priest seems to enter a state of contemplative meditiation upon the arcane planar item. Suddenly, he begins a slow, soft chant 



 **You receive:** eq.ChooseRandom( [Spell: Mark of Kazad](/item/21647), 28569, 28571, 28573, 28559, 28560, 28562) 



spectral = spectral - 1;


until spectral == 0;

if(glyphed > 0) then


repeat



e.self:Emote("takes the arcane item with great care and respect from you. For several moments the priest seems to enter a state of contemplative meditiation upon the arcane planar item. Suddenly, he begins a slow, soft chant 



 **You receive:** eq.ChooseRandom( [Spell: Yaulp VI](/item/21689), 28555, 28565, 28568, 28570) 



glyphed = glyphed - 1;


until glyphed == 0;

**This NPC *should* return incorrect items given.**





