# Reaver Nydlil


## Dialog

**You say:** `hail`



>*Reaver Nydlil 's voice spills forth in a piercing hiss, the pitch high and accented in the tones of the Iksarian Empire of old.*


>**Reaver Nydlil says:** Welcome to New Tanaan, and stand before us as enemies not, but as equals. Your mind should be open to us, for we wish only to guide you where we have been led in our years beyond Norrath. If you are a knight of the shadows, then perhaps I may be of service in guiding you further to power. The adepts of New Tanaan, the scholars, have come forward and penned spells of our former lives in memory. We wish to share this knowledge with you without bias or judgment. There is more beyond the mortal limits of magic that I can aid you to attain should you wield the blade of the shadow. If you happen across a seemingly mundane arcane item of incorporeal material, do not discard it. Return it to me and I shall carve for you from its essence a most powerful spell conceived in the divine realms of pure magic.
end

## Turn-Ins



local ethereal =  **You turn in:**  { [Ethereal Parchment](/item/29112)}

local spectral =  **You turn in:**  { [Spectral Parchment](/item/29131)}

local glyphed =  **You turn in:**  { [Glyphed Rune Word](/item/29132)}

if(ethereal > 0) then


repeat



e.self:Emote("accepts the item carefully, his scaled hand delicate in its grasp. The iksar takes note of every detail upon the untainted planar arcane item before closing his eyes and giving forth a drawled, hissing chant of sounds and foreign words. The object in the shadowknight's hands begins to radiate in a dark aura as it pulses in and out of reality 



 **You receive:** eq.ChooseRandom( [Spell: Festering Darkness](/item/26920), 26924, 26921, 26925, 26937) 



ethereal = ethereal - 1;


until ethereal == 0;

if(spectral > 0) then


repeat



e.self:Emote("accepts the item carefully, his scaled hand delicate in its grasp. The iksar takes note of every detail upon the untainted planar arcane item before closing his eyes and giving forth a drawled, hissing chant of sounds and foreign words. The object in the shadowknight's hands begins to radiate in a dark aura as it pulses in and out of reality 



 **You receive:** eq.ChooseRandom( [Spell: Shroud of Chaos](/item/21651), 26922, 26923, 21632, 21634, 21633) 



spectral = spectral - 1;


until spectral == 0;

if(glyphed > 0) then


repeat



e.self:Emote("accepts the item carefully, his scaled hand delicate in its grasp. The iksar takes note of every detail upon the untainted planar arcane item before closing his eyes and giving forth a drawled, hissing chant of sounds and foreign words. The object in the shadowknight's hands begins to radiate in a dark aura as it pulses in and out of reality 



 **You receive:** eq.ChooseRandom( [Spell: Voice of Thule](/item/26926), 26927, 26928, 21635) 



glyphed = glyphed - 1;


until glyphed == 0;

**This NPC *should* return incorrect items given.**





