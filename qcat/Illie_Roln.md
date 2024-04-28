# Illie Roln
## Dialog

if(eq.get_current_expansion() >= 4.0) then


**You say:** `hail`




>**Illie Roln says:** A healthy young " .. e.other:Race() .. " you appear to be. The Plague Bringer has not yet blessed you with his greatest of gifts. What can I do for you young one?


**You say:** `gauntlet`




>**Illie Roln says:** To assemble scourge warrior gauntlets you will need to obtain two bricks of crude iron and smelt them in a [forge] with a Water Flask and this crude Gauntlet Mold. Once that is done combine the Crude Iron Gauntlets with a Ruined Wolf Pelt and two Gnoll Finger Bones in the Mail Assembly Kit.



**You receive:**  [Crude Gauntlets Mold](/item/19633)


**You say:** `boot`




>**Illie Roln says:** To assemble scourge warrior boots you will need to obtain two bricks of crude iron and smelt them in a [forge] with a Water Flask and this crude Boot Mold. Once that is done combine the Crude Iron Boots with two Ruined Wolf Pelts, and two Gnoll Foot Bones in the Mail Assembly Kit.



**You receive:**  [Crude Boot Mold](/item/19634)


**You say:** `bracer`




>**Illie Roln says:** To assemble a scourge warrior bracer you will need to obtain a brick of crude iron and smelt it in a [forge] with a Water Flask and this Crude Bracer Mold. Once that is done, combine the Crude Iron Bracer with a Ruined Wolf Pelt and a Gnoll Ulna Bone in the Mail Assembly Kit.



**You receive:**  [Crude Bracer Mold](/item/19632)


**You say:** `helm`




>**Illie Roln says:** To assemble a Scourge Warrior Helm you will need to obtain two bricks of crude iron and smelt them in a [forge] with a Water Flask and this Crude Helm Mold. Once that is done combine the Crude Iron Helm with a Ruined Wolf Pelt and a Gnoll Skull in the Mail Assembly Kit.



**You receive:**  [Crude Helm Mold](/item/19631)


**You say:** `greave`




>**Illie Roln says:** To assemble scourge warrior greaves you will need to obtain two bricks of crude iron and smelt them in a [forge] with a Water Flask and this Crude Greaves Mold. Once that is done combine the Crude Iron Greaves with two Low Quality Wolf Pelts and two Gnoll Tibia in the Mail Assembly Kit.



**You receive:**  [Crude Greaves Mold](/item/19636)


**You say:** `vambrace`




>**Illie Roln says:** To assemble scourge warrior vambraces you will need to obtain two bricks of crude iron and smelt them in a [forge] with a Water Flask and this Crude Vambrace Mold. Once that is done combine the Crude Iron Vambraces with a Low Quality Wolf Pelt and two Gnoll Humerus Bones in the Mail Assembly Kit.



**You receive:**  [Crude Vambrace Mold](/item/19635)


**You say:** `breastplate`




>**Illie Roln says:** To assemble a scourge warrior breastplate you will need to obtain four bricks of crude iron and smelt them in a [forge] with a Water Flask and this Crude Breastplate Mold. Once that is done combine the Crude Iron Breastplate with a Medium Quality Wolf Pelt, a Gnoll Sternum, and a Gnoll Ribcage in the Mail Assembly Kit.



**You receive:**  [Crude Breastplate Mold](/item/19637)

end

## Turn-Ins




local expansion_flag = eq.get_current_expansion();

if(expansion_flag >= 4.0 and  **You turn in:** [Note to Illie Roln](/item/20205)


>**Illie Roln says:** Ah, so you are in need of a suit of armor fitting a young scourge warrior of the Bloodsabers. I will assist you. You will use this Mail Assembly Kit to construct the pieces of armor. Each piece will require different materials for its proper construction. Do you seek to assemble [Gauntlets of the Scourge Warrior], [Boots of the Scourge Warrior], a [Bracer of the Scourge Warrior], a [Helm of the Scourge Warrior], [Greaves of the Scourge Warrior], [Vambraces of the Scourge Warrior], or a [Breastplate of the Scourge Warrior]?


 **You receive:**  [Mail Assembly Kit](/item/17124) 

elseif(expansion_flag >= 4.0 and  **You turn in:** [Sharp Scourge Warrior Broadsword](/item/20177), [Giant King Snake Skin](/item/19946)


>**Illie Roln says:** Excellent work. Use this sword to further our mission.


 **You receive:**  [Scourge Warrior Broadsword](/item/20262) (+500 exp)

**This NPC *should* return incorrect items given.**





