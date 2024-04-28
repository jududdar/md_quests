# Jimji Bottletoe
## Dialog

if(eq.get_current_expansion() >= 4.0) then


**You say:** `bravefoot helm`




>**Jimji Bottletoe says:** To assemble a Bravefoot Helm you will need to obtain two bricks of crude iron ore and smelt them in a [forge] with a Water Flask and this Crude Helm Mold. Once that is done combine the Crude Iron Helm with a Ruined Wolf Pelt and a Large Yellowjacket Tergite in the Mail Assembly Kit.



**You receive:**  [Crude Helm Mold](/item/19631)


**You say:** `forge`




>**Jimji Bottletoe says:** There is a forge at the Tagglefoots Farm near the vegetable stand and the main house of the farm.


**You say:** `bravefoot mail bracer`




>**Jimji Bottletoe says:** To assemble a Bravefoot Mail Bracer you will need to obtain a brick of crude iron ore and smelt it in a [forge] with a Water Flask and this Crude Bracer Mold. Once that is done. combine the Crude Iron Bracer with a Ruined Wolf Pelt and a Large Yellowjacket Sternite in the Mail Assembly Kit.



**You receive:**  [Crude Bracer Mold](/item/19632)


**You say:** `bravefoot gauntlets`




>**Jimji Bottletoe says:** To assemble Bravefoot Gauntlets you will need to obtain two bricks of crude iron ore and smelt them in a [forge] with a Water Flask and this crude Gauntlet Mold. Once that is done combine the Crude Iron Gauntlets with a Ruined Wolf Pelt and two Large Yellowjacket Tarsi in the Mail Assembly Kit.



**You receive:**  [Crude Gauntlets Mold](/item/19633)


**You say:** `bravefoot vambraces`




>**Jimji Bottletoe says:** To assemble Bravefoot Vambraces you will need to obtain two bricks of crude iron ore and smelt them in a [forge] with a Water Flask and this Crude Vambrace Mold. Once that is done combine the Crude Iron Vambraces with a Low Quality Wolf Pelt and two Giant Yellowjacket Tergites in the Mail Assembly Kit.



**You receive:**  [Crude Vambrace Mold](/item/19635)


**You say:** `bravefoot greaves`




>**Jimji Bottletoe says:** To assemble Bravefoot Greaves you will need to obtain two bricks of crude iron ore and smelt them in a [forge] with a Water Flask and this Crude Greaves Mold. Once that is done combine the Crude Iron Greaves with two Low Quality Wolf Pelts and two Giant Yellowjacket Sternites in the Mail Assembly Kit.



**You receive:**  [Crude Greaves Mold](/item/19636)


**You say:** `bravefoot breastplate`




>**Jimji Bottletoe says:** To assemble a Bravefoot Breastplate you will need to obtain four bricks of crude iron ore and smelt them in a [forge] with a Water Flask and this Crude Breastplate Mold. Once that is done combine the Crude Iron Breastplate with a Medium Quality Wolf Pelt and a Giant Yellowjacket Thorax in the Mail Assembly Kit.



**You receive:**  [Crude Breastplate Mold](/item/19637)


**You say:** `bravefoot mail boots`




>**Jimji Bottletoe says:** To assemble Bravefoot Mail Boots you will need to obtain two bricks of crude iron ore and smelt them in a [forge] with a Water Flask and this crude Boot Mold. Once that is done combine the Crude Iron Boots with two Ruined Wolf Pelts. and two Giant Yellowjacket Tarsi in the Mail Assembly Kit.



**You receive:**  [Crude Boot Mold](/item/19634)

end

## Turn-Ins



local expansion_flag = eq.get_current_expansion();

if(expansion_flag >= 4.0 and  **You turn in:** [Letter to Jimji Bottletoe](/item/19628)


>**Jimji Bottletoe says:** Pleased to meet you Soandso! You must be one of Kayas new trainees. Kaya has asked me to help get you outfitted in a suit of armor to protect you from the vile weapons of Rivervales foes. I have assembled a kit for you that will allow you to construct the armor pieces once you have gathered the necessary components. The required components vary according to which piece of Bravefoot Mail armor you are planning on assembling. Do you wish to craft a [bravefoot helm]. a [bravefoot mail bracer]. [bravefoot gauntlets]. [bravefoot mail boots]. [bravefoot vambraces]. [bravefoot greaves]. or a [bravefoot breastplate].


 **You receive:**  [Mail Assembly Kit](/item/17124) 

**This NPC *should* return incorrect items given.**

