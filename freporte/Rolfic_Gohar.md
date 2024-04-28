# Rolfic Gohar
## Dialog

if(eq.get_current_expansion() >= 4.0) then


**You say:** `hail`




>**Rolfic Gohar says:** I am but a poor peddler of trinkets living amongst the rats and beggars of these slums. Perhaps you will purchase some of my wares and help a struggling merchant?


**You say:** `forge`




>**Rolfic Gohar says:** You can find forges all over freeport.


**You say:** `dismal warrior breastplate`




>**Rolfic Gohar says:** 'To assemble a Dismal Warrior Breastplate you will need to obtain four bricks of crude iron and smelt them in a [forge] with a Water Flask and this Crude Breastplate Mold. Once that is done combine the Crude Iron Breastplate with a Coyote Pelt, a Dune Tarantula Thorax, and a Dune Tarantula Abdomen in the Mail Assembly Kit.



**You receive:**  [Crude Breastplate Mold](/item/19637)


**You say:** `dismal warrior helm`




>**Rolfic Gohar says:** To assemble a Dismal Warrior Helm you will need to obtain two bricks of crude iron and smelt them in a [forge] with a Water Flask and this Crude Helm Mold. Once that is done combine the Crude Iron Helm with a Ruined Coyote Pelt and two Desert Tarantula Eyes in the Mail Assembly Kit.



**You receive:**  [Crude Helm Mold](/item/19631)


**You say:** `dismal warrior bracer`




>**Rolfic Gohar says:** To assemble a Dismal Warrior Mail Bracer you will need to obtain a brick of crude iron and smelt it in a [forge] with a Water Flask and this Crude Bracer Mold. Once that is done, combine the Crude Iron Bracer with a Ruined Coyote Pelt and a Dune Spiderling Tibia in the Mail Assembly Kit.



**You receive:**  [Crude Bracer Mold](/item/19632)


**You say:** `dismal warrior gauntlet`




>**Rolfic Gohar says:** To assemble Dismal Warrior Gauntlets you will need to obtain two bricks of crude iron and smelt them in a [forge] with a Water Flask and this crude Gauntlet Mold. Once that is done combine the Crude Iron Gauntlets with a Ruined Coyote Pelt and two Dune Spiderling Tarsi in the Mail Assembly Kit.



**You receive:**  [Crude Gauntlets Mold](/item/19633)


**You say:** `dismal warrior boot`




>**Rolfic Gohar says:** To assemble Dismal Warrior Mail Boots you will need to obtain two bricks of crude iron and smelt them in a [forge] with a Water Flask and this crude Boot Mold. Once that is done combine the Crude Iron Boots with two Ruined Coyote Pelts, and two Dune Spiderling Hairs in the Mail Assembly Kit.



**You receive:**  [Crude Boot Mold](/item/19634)


**You say:** `dismal warrior vambrace`




>**Rolfic Gohar says:** To assemble Dismal Warrior Vambraces you will need to obtain two bricks of crude iron and smelt them in a [forge] with a Water Flask and this Crude Vambrace Mold. Once that is done combine the Crude Iron Vambraces with a Low Quality Coyote Pelt and two Desert Tarantula Patella in the Mail Assembly Kit.



**You receive:**  [Crude Vambrace Mold](/item/19635)


**You say:** `dismal warrior greave`




>**Rolfic Gohar says:** To assemble Dismal Warrior Greaves you will need to obtain two bricks of crude iron and smelt them in a [forge] with a Water Flask and this Crude Greaves Mold. Once that is done combine the Crude Iron Greaves with two Low Quality Coyote Pelts and two Desert Tarantula Femurs in the Mail Assembly Kit.



**You receive:**  [Crude Greaves Mold](/item/19636)

end

## Turn-Ins



local expansion_flag = eq.get_current_expansion();



if(expansion_flag >= 4.0 and  **You turn in:** [Note to Rolfic Gohar](/item/19843)


>**Rolfic Gohar says:** I see now we have similar interests. I will help you get outfitted in an affordable suit of armor to help you in your endeavors. You will need this Mail Assembly Kit to aid you in the construction of the armor. The materials required depend on the armor section you desire to craft. Do you plan to construct a [dismal warrior helm], a [dismal warrior bracer], [dismal warrior gauntlets], [dismal warrior boots], [dismal warrior vambraces], [dismal warrior greaves], or a [dismal warrior breastplate].


 **You receive:**  [Mail Assembly Kit](/item/17124) 

**This NPC *should* return incorrect items given.**
