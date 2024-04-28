# Mystic Abomin



## Dialog

**You say:** `Hail`



>**Mystic Abomin says:** The mystics of New Tanaan embrace your presence among us most kindly - regard us as a friend and mentor, should you need our guidance we have offered our services to the shamans of Norrath that venture in our city. Though our guidance is that of spells native to your world, the mystic scribes in this city may hold some convenience for we do not hold the prejudice of the material world's citizens. Beyond these familiar scrolls, I may be able to aid you further should you bring me a fledgling arcane item from the planes. You will know of that which I speak if and when you stumble upon such a rare and seemingly mundane item. Do not be fooled by its plain appearance - the primordial essence of pure magic resides in these arcane relics and I can be the key to unlock them to the shamanistic powers.
end

## Turn-Ins



local ethereal =  **You turn in:**  { [Ethereal Parchment](/item/29112)}

local spectral =  **You turn in:**  { [Spectral Parchment](/item/29131)}

local glyphed =  **You turn in:**  { [Glyphed Rune Word](/item/29132)}

if(ethereal > 0) then


repeat



>*Mystic Abomin carefully takes the planar arcane item from you. With a careful eye, he inspects every portion of the incorporeal item before nodding to himself in satisfaction. The shaman then closes his eyes and chants lowly in an unfamiliar language. You feel the coalescing of spirits around you in the area as the shaman calls them forth to bless the arcane item in his grip. Dark runes of a rusted color begin to carve themselves onto a parchment that grows more real and tangible with each syllable uttered by the shaman. Eventually, his chant comes to a close and the completed item is handed to you without expectation of further aid on your behalf, 'Do not use this power without caution, Soandso. It is quite powerful indeed for it is power forged upon the planar worlds but may affect both astral and prime alike.*



 **You receive:** eq.ChooseRandom( [Spell: True Spirit](/item/28487), 28488, 28489, 28490, 26945, 26946,21660, 21661, 28491, 28492, 28493, 28494) 



ethereal = ethereal - 1;


until ethereal == 0;

if(spectral > 0) then


repeat



>*Mystic Abomin carefully takes the planar arcane item from you. With a careful eye, he inspects every portion of the incorporeal item before nodding to himself in satisfaction. The shaman then closes his eyes and chants lowly in an unfamiliar language. You feel the coalescing of spirits around you in the area as the shaman calls them forth to bless the arcane item in his grip. Dark runes of a rusted color begin to carve themselves onto a parchment that grows more real and tangible with each syllable uttered by the shaman. Eventually, his chant comes to a close and the completed item is handed to you without expectation of further aid on your behalf, 'Do not use this power without caution, Soandso. It is quite powerful indeed for it is power forged upon the planar worlds but may affect both astral and prime alike.*



 **You receive:** eq.ChooseRandom( [Spell: Tears of Saryrn](/item/28495), 28496, 28497, 28498, 28499, 28531, 26910, 26912, 26913, 26914, 26911) 



spectral = spectral - 1;


until spectral == 0;

if(glyphed > 0) then


repeat



>*Mystic Abomin carefully takes the planar arcane item from you. With a careful eye, he inspects every portion of the incorporeal item before nodding to himself in satisfaction. The shaman then closes his eyes and chants lowly in an unfamiliar language. You feel the coalescing of spirits around you in the area as the shaman calls them forth to bless the arcane item in his grip. Dark runes of a rusted color begin to carve themselves onto a parchment that grows more real and tangible with each syllable uttered by the shaman. Eventually, his chant comes to a close and the completed item is handed to you without expectation of further aid on your behalf, 'Do not use this power without caution, Soandso. It is quite powerful indeed for it is power forged upon the planar worlds but may affect both astral and prime alike.*



 **You receive:** eq.ChooseRandom( [Spell: Malos](/item/26915), 26916, 26917, 26918, 26919) 



glyphed = glyphed - 1;


until glyphed == 0;

**This NPC *should* return incorrect items given.**





