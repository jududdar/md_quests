# Bor Wharhammer



## Dialog

e.self:DoAnim(49);  

**You say:** `hail`



>**Bor Wharhammer says:** Greetin's t'ye Soandso! Isn't the area 'round 'ere so nice an' quiet? Such a departure from me old days; slaving o'er the forge t'create masterpieces! T'be 'onest. at times I do miss the old forge. but after I created me finest breastplate, it seemed as if nothing else I made could ever live up t'it. So I left me home to'wander the land an' see what I could learn o'the world. I 'ave learned quite a bit from the elders 'ere an' the skilled craftspeople in New Tanaan. I 'ave even devised a type o'emblem that will impart the magic o'tranquility into the user t'create planar armors from pieces o'energy found in the planes.

**You say:** `emblem`



if (**Your level** < 55) then



>**Bor Wharhammer says:** Ye look mighty inexperienced t'be in this area. Soandso. Come an' seek me out when ye 'ave more knowledge o'the planes!


else



>**Bor Wharhammer says:** Well, the emblems dinnae be easy t'craft but I will gladly give ye one fer the price of 500 platinum pieces. They allow a planes traveler with no craftin' skills t'create many fine pieces o'planar armor in a special, magical kit I also 'ave an' will throw in with the price. The kit acts as a focal point fer the wild magic energy o'the Planes. Ye will only be able t'use each emblem an' kit once when ye create the piece, 'owever I dinnae be goin' anywhere soon! Just venture back when ye need another an' dinnae ferget the coin!


**You say:** `chain`



>**Bor Wharhammer says:** Ahhhhh Soandso! Chain armors, while not as sturdy as plate, provide so much more mobility if constructed properly. T'construct a piece o'chain armor, ye need t'combine a chain pattern, an emblem, various amounts of ethereal metal rings an' use one o'those crafty Tanaan smithin' 'ammers all within a furnace touched by Ro. Ethereal metal ring construction is another matter. Ye will need to combine a brick o'ethereal energy, an ethereal temper an' a file within a Tanaan forge. I would seek a skilled craftsperson t'make the rings fer ye; the emblem will enable ye t'craft the final armor piece no matter what yer skill be.

**You say:** `silk`



>**Bor Wharhammer says:** Har! It be quite funny that we be referin' t'silk as armor, fer the amount o'protection it provides be miniscule at best. The planar armor made from strands o'ether can still be quite useful fer its magical properties, 'owever. Ye will need t'take up a Tanaan embroidery needle, a pattern, an emblem an' various amounts o'ether silk swatches t'create a piece. Craft it all within a sewing kit boilin' with magical energy.

**You say:** `leather`



>**Bor Wharhammer says:** Leather armor provides little protection due t'the make-up o'the materials. We shall do our best, 'owever, t'see ye make a quality piece. T'do so, ye must combine a pattern, an emblem, various pieces o'cured ethereal energy an' a Tanaan embroidery needle all within a sewing kit boilin' with magical energy. The cured energy may be problematic fer an unskilled craftsman, 'owever. Just sew two silk ethereal swatches together using a Tanaan embroidery needle within a Tanaan loom. I can just imagine yer next question t'be about swatches, aye?

**You say:** `plate`



>**Bor Wharhammer says:** Ahhhhh Soandso! The fine rigid armor that can stop a shaft from piercing yer heart! Too bad it be so cumbersome an' difficult t'move about in. To construct a piece o'plate armor, ye need t'combine a plate mold, an emblem, various amounts o'sheet metal an' use one o'those crafty Tanaan smithin' 'ammers all within a furnace touched by Ro. Ethereal metal sheet construction is another matter. Ye will need t'combine two bricks o'ethereal energy, an ethereal temper an' a Tanaan smithin' 'ammer within a Tanaan forge. I would seek a skilled craftsperson t'make the metal sheets fer ye; the emblem will enable ye t'craft the final armor piece no matter what yer skill be.

**You say:** `swatch`



>**Bor Wharhammer says:** T'make a swatch, ye need t'combine two strands o'ether along with a curing agent in a Tanaan loom. Ye will need t'seek a skilled brew master t'make the curing agent fer ye. Just 'ave them create it by using two celestial essences, soda an' paeala sap
end

## Turn-Ins




if(**Your level** > 54 and  **You turn in:** platinum = 500


if((e.other:GetClass() >= 1 and e.other:GetClass() <= 5) or (e.other:GetClass() >= 8 and e.other:GetClass() <= 10)) then



**You receive:**  [Mystical Furnace of Ro](/item/17184)


else



**You receive:**  [Druzzil's Mystical Sewing Kit](/item/17185)




if (e.other:GetClass() == 1) then



**You receive:**  [Warrior Emblem](/item/16267)


elseif (e.other:GetClass() == 2) then



**You receive:**  [Cleric Emblem](/item/16271)


elseif (e.other:GetClass() == 3) then



**You receive:**  [Paladin Emblem](/item/16269)


elseif (e.other:GetClass() == 4) then



**You receive:**  [Ranger Emblem](/item/16272)


elseif (e.other:GetClass() == 5) then



**You receive:**  [Shadowknight Emblem](/item/16270)


elseif (e.other:GetClass() == 6) then



**You receive:**  [Druid Emblem](/item/16276)


elseif (e.other:GetClass() == 7) then



**You receive:**  [Monk Emblem](/item/16275)


elseif (e.other:GetClass() == 8) then



**You receive:**  [Bard Emblem](/item/16268)


elseif (e.other:GetClass() == 9) then



**You receive:**  [Rogue Emblem](/item/16273)


elseif (e.other:GetClass() == 10) then



**You receive:**  [Shaman Emblem](/item/16274)


elseif (e.other:GetClass() == 11) then



**You receive:**  [Necromancer Emblem](/item/16278)


elseif (e.other:GetClass() == 12) then



**You receive:**  [Wizard Emblem](/item/16279)


elseif (e.other:GetClass() == 13) then



**You receive:**  [Magician Emblem](/item/16280)


elseif (e.other:GetClass() == 14) then



**You receive:**  [Enchanter Emblem](/item/16281)


elseif (e.other:GetClass() == 15) then



**You receive:**  [Beastlord Emblem](/item/16277)



>**Bor Wharhammer says:** Wonderful! This coin will go towards me fines with the Myrist library. They charge quite a bit fer overdue volumes! 'ere be yer emblem an' a kit in which ye may craft planar armor. The kit only 'as enough magical energy t'craft one piece before the energies expire, be sure ye understand. May the armor ye make with it provide ye with much protection.

**This NPC *should* return incorrect items given.**


if(**Your level** < 55) then


>**Bor Wharhammer says:** Ye look mighty inexperienced t'be in this area. Soandso. Come an' seek me out when ye 'ave more knowledge o'the planes!
end
