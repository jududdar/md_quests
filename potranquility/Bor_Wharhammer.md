# Bor Wharhammer



[Bor Wharhammer](/npc/203430) is a level 46 Dwarf Warrior that spawns in [Plane of Tranquility](/zone/203).






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




if(**Your level** > 54 and  **You turn in:** platinum = 500) then 


if((e.other:GetClass() >= 1 and e.other:GetClass() <= 5) or (e.other:GetClass() >= 8 and e.other:GetClass() <= 10)) then



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1115.png" alt="" /> <a
                                href="/item/17184" data-url="17184" class="tooltip-link link">Mystical Furnace of Ro</a>


else



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_892.png" alt="" /> <a
                                href="/item/17185" data-url="17185" class="tooltip-link link">Druzzil's Mystical Sewing Kit</a>




if (e.other:GetClass() == 1) then



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_644.png" alt="" /> <a
                                href="/item/16267" data-url="16267" class="tooltip-link link">Warrior Emblem</a>


elseif (e.other:GetClass() == 2) then



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_644.png" alt="" /> <a
                                href="/item/16271" data-url="16271" class="tooltip-link link">Cleric Emblem</a>


elseif (e.other:GetClass() == 3) then



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_644.png" alt="" /> <a
                                href="/item/16269" data-url="16269" class="tooltip-link link">Paladin Emblem</a>


elseif (e.other:GetClass() == 4) then



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_645.png" alt="" /> <a
                                href="/item/16272" data-url="16272" class="tooltip-link link">Ranger Emblem</a>


elseif (e.other:GetClass() == 5) then



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_644.png" alt="" /> <a
                                href="/item/16270" data-url="16270" class="tooltip-link link">Shadowknight Emblem</a>


elseif (e.other:GetClass() == 6) then



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_646.png" alt="" /> <a
                                href="/item/16276" data-url="16276" class="tooltip-link link">Druid Emblem</a>


elseif (e.other:GetClass() == 7) then



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_646.png" alt="" /> <a
                                href="/item/16275" data-url="16275" class="tooltip-link link">Monk Emblem</a>


elseif (e.other:GetClass() == 8) then



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_644.png" alt="" /> <a
                                href="/item/16268" data-url="16268" class="tooltip-link link">Bard Emblem</a>


elseif (e.other:GetClass() == 9) then



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_645.png" alt="" /> <a
                                href="/item/16273" data-url="16273" class="tooltip-link link">Rogue Emblem</a>


elseif (e.other:GetClass() == 10) then



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_645.png" alt="" /> <a
                                href="/item/16274" data-url="16274" class="tooltip-link link">Shaman Emblem</a>


elseif (e.other:GetClass() == 11) then



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_647.png" alt="" /> <a
                                href="/item/16278" data-url="16278" class="tooltip-link link">Necromancer Emblem</a>


elseif (e.other:GetClass() == 12) then



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_647.png" alt="" /> <a
                                href="/item/16279" data-url="16279" class="tooltip-link link">Wizard Emblem</a>


elseif (e.other:GetClass() == 13) then



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_647.png" alt="" /> <a
                                href="/item/16280" data-url="16280" class="tooltip-link link">Magician Emblem</a>


elseif (e.other:GetClass() == 14) then



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_647.png" alt="" /> <a
                                href="/item/16281" data-url="16281" class="tooltip-link link">Enchanter Emblem</a>


elseif (e.other:GetClass() == 15) then



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_646.png" alt="" /> <a
                                href="/item/16277" data-url="16277" class="tooltip-link link">Beastlord Emblem</a>



>**Bor Wharhammer says:** Wonderful! This coin will go towards me fines with the Myrist library. They charge quite a bit fer overdue volumes! 'ere be yer emblem an' a kit in which ye may craft planar armor. The kit only 'as enough magical energy t'craft one piece before the energies expire, be sure ye understand. May the armor ye make with it provide ye with much protection.

**This NPC *should* return incorrect items given.**


if(**Your level** < 55) then


>**Bor Wharhammer says:** Ye look mighty inexperienced t'be in this area. Soandso. Come an' seek me out when ye 'ave more knowledge o'the planes!
end
