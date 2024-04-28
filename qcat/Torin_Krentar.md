# Torin Krentar


## Dialog

if(eq.get_current_expansion() >= 4.0) then


**You say:** `hail`




>**Torin Krentar says:** The dead are watching you young one, yet you are safe under their otherworldly gaze. Is there something I can do for you?


**You say:** `gauntlet`




>**Torin Krentar says:** To assemble pestilence priest gauntlets you will need to obtain two bricks of crude iron and smelt them in a forge with a Water Flask and this crude Gauntlet Mold. Once that is done combine the Crude Iron Gauntlets with a Large King Snake Skin and two Gnoll Finger Bones in the Mail Assembly Kit.



**You receive:**  [Crude Gauntlets Mold](/item/19633)


**You say:** `boot`




>**Torin Krentar says:** To assemble pestilence priest boots you will need to obtain two bricks of crude iron and smelt them in a forge with a Water Flask and this crude Boot Mold. Once that is done combine the Crude Iron Boots with two Large King Snake Skins, and two Gnoll Foot Bones in the Mail Assembly Kit.



**You receive:**  [Crude Boot Mold](/item/19634)


**You say:** `bracer`




>**Torin Krentar says:** To assemble a pestilence priest bracer you will need to obtain a brick of crude iron and smelt it in a forge with a Water Flask and this Crude Bracer Mold. Once that is done, combine the Crude Iron Bracer with a Large King Snake Skin and a Gnoll Ulna Bone in the Mail Assembly Kit.



**You receive:**  [Crude Bracer Mold](/item/19632)


**You say:** `helm`




>**Torin Krentar says:** To assemble a pestilence priest helm you will need to obtain two bricks of crude iron and smelt them in a forge with a Water Flask and this Crude Helm Mold. Once that is done combine the Crude Iron Helm with a Large King Snake Skin and a Gnoll Skull in the Mail Assembly Kit.



**You receive:**  [Crude Helm Mold](/item/19631)


**You say:** `greaves`




>**Torin Krentar says:** To assemble pestilence priest greaves you will need to obtain two bricks of crude iron and smelt them in a forge with a Water Flask and this Crude Greaves Mold. Once that is done combine the Crude Iron Greaves with two Giant King Snake Skins and two Gnoll Tibia in the Mail Assembly Kit.



**You receive:**  [Crude Greaves Mold](/item/19636)


**You say:** `vambrace`




>**Torin Krentar says:** To assemble pestilence priest vambraces you will need to obtain two bricks of crude iron and smelt them in a forge with a Water Flask and this Crude Vambrace Mold. Once that is done combine the Crude Iron Vambraces with a Giant King Snake Skin and two Gnoll Humerus Bones in the Mail Assembly Kit.



**You receive:**  [Crude Vambrace Mold](/item/19635)


**You say:** `breastplate`




>**Torin Krentar says:** To assemble a pestilence priest breastplate you will need to obtain four bricks of crude iron and smelt them in a forge with a Water Flask and this Crude Breastplate Mold. Once that is done combine the Crude Iron Breastplate with a Giant King Snake Skin, a Gnoll Sternum, and a Gnoll Ribcage in the Mail Assembly Kit.



**You receive:**  [Crude Breastplate Mold](/item/19637)

end

## Turn-Ins



local expansion_flag = eq.get_current_expansion();




if(expansion_flag >= 4.0 and  **You turn in:** [Note to Torin Krentar](/item/20207)


>**Torin Krentar says:** Well met young disciple of Bertoxxulous. Perhaps one day you shall serve the Plague Lord in his realm, but for now you will serve the Bloodsabers, his mortal agents on Norrath. The armor you seek must be assembled using this Mail Assembly Kit. The materials necessary to construct the armor vary depending on the piece being crafted. Do you wish to craft [Gauntlets] of the Pestilence Priests, [Boots] of the Pestilence Priests, a [Bracer] of the Pestilence Priests, a [Helm] of the Pestilence Priests, [Greaves] of the Pestilence Priests, [Vambraces] of the Pestilence Priests, or a [Breastplate] of the Pestilence Priests?


 **You receive:**  [Mail Assembly Kit](/item/17124) 

elseif(expansion_flag >= 4.0 and  **You turn in:** [Refined Bloodsaber Mace](/item/20199), [Giant King Snake Skin](/item/19946)


>*Torin Krentar fashions a grip from the giant king snake skin and polishes the mace with a strange dark substance. 'Wield it with pride young priest, may you spread the disease!*


* __Faction:__ [Bloodsabers](/faction/221) (5)


* __Faction:__ [Guards of Qeynos](/faction/262) (-1)


* __Faction:__ [Opal Darkbriar](/faction/296) (-1)


* __Faction:__ [Priests of Life](/faction/341) (-2)


* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (1)


 **You receive:**  [Pestilence Priest Mace](/item/20261) (+500 exp)

**This NPC *should* return incorrect items given.**