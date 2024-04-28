# Heretic Drahur

## Dialog

**You say:** `Hail`



e.self:Say("Salutations. The keepers of necromancy in New Tanaan are neither your enemy or foe, as they may have been upon the material world of Norrath. Though our natures are in tact, we have elevated ourselves beyond the petty, debased bickering that Norrath has come to embody over the passing eras. All adventurers and intelligent beings are welcome in our midst, for we share only the common goal of knowledge and personal betterment in our power. I have gathered tomes and spells that I no longer have use for, as I have ascended beyond Norrath's limitations of the dark arts. However, you remain a mortal still and your abilities may never reach the esteemed levels of ours, bur do not let this discourage you. Search my tomes and perhaps I hold something of importance or relevance to your current quest for power. There is another realm of magic that I am quite familiar with, as well 
end

## Turn-Ins



local ethereal =  **You turn in:**  { [Ethereal Parchment](/item/29112)}

local spectral =  **You turn in:**  { [Spectral Parchment](/item/29131)}

local glyphed =  **You turn in:**  { [Glyphed Rune Word](/item/29132)}

if(ethereal > 0) then


repeat



>*Heretic Drahur takes the arcane item from you. The erudite inspects the incorporeal item for a brief amount of time. He then closes his eyes and begins a dark chant that causes the air about you to grow cold and stiff - your breathing is briefly impaired and for a single moment, you feel as if you are about to suffocate. As the erudite's voice falls back to silence, the discomfort fades and you look upon the item in his hands. It is corporeal now - tangible in all aspects. Runes of inky black have formed upon the item - runes that you recognize immediately as those of necromantic foundations. The erudite gives a gentle nod of his head and hands the scroll to you, 'This should prove more than useful for your endeavors in the planes. However, it extends beyond such limits and can be applied to the primordial world.*



 **You receive:** eq.ChooseRandom( [Spell: Greater Immobilize](/item/26945), 21638, 21640, 28413, 28417, 26946, 28418, 28419) 



ethereal = ethereal - 1;


until ethereal == 0;

if(spectral > 0) then


repeat



>*Heretic Drahur takes the arcane item from you. The erudite inspects the incorporeal item for a brief amount of time. He then closes his eyes and begins a dark chant that causes the air about you to grow cold and stiff - your breathing is briefly impaired and for a single moment, you feel as if you are about to suffocate. As the erudite's voice falls back to silence, the discomfort fades and you look upon the item in his hands. It is corporeal now - tangible in all aspects. Runes of inky black have formed upon the item - runes that you recognize immediately as those of necromantic foundations. The erudite gives a gentle nod of his head and hands the scroll to you, 'This should prove more than useful for your endeavors in the planes. However, it extends beyond such limits and can be applied to the primordial world.*



 **You receive:** eq.ChooseRandom( [Spell: Force Shield](/item/28414), 28420, 28421, 28422, 28415, 28423, 28424, 28559) 



spectral = spectral - 1;


until spectral == 0;

if(glyphed > 0) then


repeat



>*Heretic Drahur takes the arcane item from you. The erudite inspects the incorporeal item for a brief amount of time. He then closes his eyes and begins a dark chant that causes the air about you to grow cold and stiff - your breathing is briefly impaired and for a single moment, you feel as if you are about to suffocate. As the erudite's voice falls back to silence, the discomfort fades and you look upon the item in his hands. It is corporeal now - tangible in all aspects. Runes of inky black have formed upon the item - runes that you recognize immediately as those of necromantic foundations. The erudite gives a gentle nod of his head and hands the scroll to you, 'This should prove more than useful for your endeavors in the planes. However, it extends beyond such limits and can be applied to the primordial world.*



 **You receive:** eq.ChooseRandom( [Spell: Blood of Thule](/item/28416), 28425, 28427) 



glyphed = glyphed - 1;


until glyphed == 0;

**This NPC *should* return incorrect items given.**






