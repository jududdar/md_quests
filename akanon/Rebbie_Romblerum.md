# Rebbie Romblerum


## Dialog

if(eq.get_current_expansion() >= 4.0) then


**You say:** `hail`




>**Rebbie Romblerum says:** Hail Soandso!


**You say:** `silk thread`




>**Rebbie Romblerum says:** Silk Thread is created by combineing two spiderling silk in a sewing kit.


**You say:** `boot`




>**Rebbie Romblerum says:** To assemble Plague Rust Boots you will require two [silk thread], two ruined ebon drakeling scales, and two rebel clockwork foot plates. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Boot Pattern.



**You receive:**  [Tattered Boot Pattern](/item/19561)


**You say:** `bracer`




>**Rebbie Romblerum says:** To assemble a Plague Rust Bracer you will require a [silk thread], ruined ebon drakeling scales, and a rebel clockwork wrist section. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Wristband Pattern.



**You receive:**  [Tattered Wristband Pattern](/item/19558)


**You say:** `glove`




>**Rebbie Romblerum says:** To assemble Plague Rust Gloves you will require two [silk thread], ruined ebon drakeling scales, and two rebel clockwork hand plates. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Glove Pattern.



**You receive:**  [Tattered Glove Pattern](/item/19559)


**You say:** `legging`




>**Rebbie Romblerum says:** To assemble Plague Rust Leggings you will require three [silk thread], two ebon drakeling scales, and two rebel clockwork leg sections. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Leggings Pattern.



**You receive:**  [Tattered Pant Pattern](/item/19560)


**You say:** `sleeve`




>**Rebbie Romblerum says:** To assemble Plague Rust Sleeves you will require two [silk thread], ebon drakeling scales, and two rebel clockwork arm sections. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Sleeves Pattern.



**You receive:**  [Tattered Sleeve Pattern](/item/19557)


**You say:** `tunic`




>**Rebbie Romblerum says:** To assemble a Plague Rust Tunic you will require four [silk thread], pristine ebon drakeling scales, a giant rat pelt, and a rebel clockwork chest plate. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Tunic Pattern.



**You receive:**  [Tattered Tunic Pattern](/item/19556)


**You say:** `coif`




>**Rebbie Romblerum says:** To assemble a Plague Rust Coif you will require two [silk thread], ruined ebon drakeling scales, and a rebel clockwork head plate. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Cap Pattern.



**You receive:**  [Tattered Cap Pattern](/item/19555)

end

## Turn-Ins

local expansion_flag = eq.get_current_expansion();



if (expansion_flag >= 4.0 and  **You turn in:** [Parchment to Rebbie](/item/10988)


>**Rebbie Romblerum says:** Hail Soandso! You must be one of Kaxon's new trainees. Kaxon has asked me to help get you outfitted in a suit of armor to protect you from the weapons of our foes. I have assembled a kit for you that will allow you to construct the armor pieces once you have gathered the necessary components. The required components vary according to which piece of Plague Rust Mail you are planning on assembling. Do you wish to craft a [plague rust coif], a [plague rust bracer], [plague rust gloves], [plague rust boots], [plague rust sleeves], [plague rust leggings], or a [plague rust tunic].


 **You receive:**  [Mail Assembly Kit](/item/17124) 

**This NPC *should* return incorrect items given.**
