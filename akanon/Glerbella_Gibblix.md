# Glerbella Gibblix


## Dialog

local expansion_flag = eq.get_current_expansion();

if(eq.get_current_expansion() >= 4.0) then


**You say:** `plague raiser helm`




>**Glerbella Gibblix says:** To assemble a Plague Raiser Helm you will need to obtain two bricks of crude bronze and smelt them in a forge with a Water Flask and this Crude Helm Mold. Once that is done combine the Crude Bronze Helm with a Ruined Coyote Pelt and two Yellow Recluse Eyes in the Mail Assembly Kit.



**You receive:**  [Crude Helm Mold](/item/19631)


**You say:** `plague raiser gauntlets`




>**Glerbella Gibblix says:** To assemble Plague Raiser Gauntlets you will need to obtain two bricks of crude bronze and smelt them in a forge with a Water Flask and this crude Gauntlet Mold. Once that is done combine the Crude Bronze Gauntlets with a Ruined Coyote Pelt and two Clockwork Spider Mesh in the Mail Assembly Kit.



**You receive:**  [Crude Gauntlets Mold](/item/19633)


**You say:** `plague raiser bracer`




>**Glerbella Gibblix says:** To assemble a Plague Raiser Mail Bracer you will need to obtain a brick of crude bronze and smelt it in a forge with a Water Flask and this Crude Bracer Mold. Once that is done, combine the Crude Bronze Bracer with a Ruined Coyote Pelt and a Clockwork Spider Mesh in the Mail Assembly Kit.



**You receive:**  [Crude Bracer Mold](/item/19632)


**You say:** `plague raiser boots`




>**Glerbella Gibblix says:** To assemble Plague Raiser Mail Boots you will need to obtain two bricks of crude bronze and smelt them in a forge with a Water Flask and this crude Boot Mold. Once that is done combine the Crude Bronze Boots with two Ruined Coyote Pelts, and two Clockwork Spider Mesh in the Mail Assembly Kit.



**You receive:**  [Crude Boot Mold](/item/19634)


**You say:** `plague raiser vambraces`




>**Glerbella Gibblix says:** To assemble Plague Raiser Vambraces you will need to obtain two bricks of crude bronze and smelt them in a forge with a Water Flask and this Crude Vambrace Mold. Once that is done combine the Crude Bronze Vambraces with a Low Quality Coyote Pelt and three Clockwork Spider Mesh in the Mail Assembly Kit.



**You receive:**  [Crude Vambrace Mold](/item/19635)


**You say:** `plague raiser greaves`




>**Glerbella Gibblix says:** To assemble Plague Raiser Greaves you will need to obtain two bricks of crude bronze and smelt them in a forge with a Water Flask and this Crude Greaves Mold. Once that is done combine the Crude Bronze Greaves with two Low Quality Coyote Pelts and three Clockwork Spider Mesh in the Mail Assembly Kit.



**You receive:**  [Crude Greaves Mold](/item/19636)


**You say:** `plague raiser breastplate`




>**Glerbella Gibblix says:** To assemble a Plague Raiser Breastplate you will need to obtain four bricks of crude bronze and smelt them in a forge with a Water Flask and this Crude Breastplate Mold. Once that is done combine the Crude Bronze Breastplate with a Coyote Pelt, a Clockwork Spider Thorax Plate, and two Ebon Drake Wings in the Mail Assembly Kit.



**You receive:**  [Crude Breastplate Mold](/item/19637)

end

## Turn-Ins

local expansion_flag = eq.get_current_expansion();



if (expansion_flag >= 4.0 and  **You turn in:** [Parchment to Glerbella](/item/10989)) then


>**Glerbella Gibblix says:** Hail Soandso! You must be one of Derthix new disciples. Derthix has asked me to help get you outfitted in a suit of armor to protect you from the weapons of our foes. I have assembled a kit for you that will allow you to construct the armor pieces once you have gathered the necessary components. The required components vary according to which piece of Plague Raiser Armor you are planning on assembling. Do you wish to craft a [plague raiser helm], a [plague raiser bracer], [plague raiser gauntlets], [plague raiser boots], [plague raiser vambraces], [plague raiser greaves], or a [plague raiser breastplate].


 **You receive:**  [Mail Assembly Kit](/item/17124) 

**This NPC *should* return incorrect items given.**
