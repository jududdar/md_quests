# Kanthu M-Rekkor



## Dialog

if(eq.get_current_expansion() >= 4.0) then


**You say:** `material`




>**Kanthu M-Rekkor says:** Many species of dangerous creatures, the restless dead, and halfling invaders from Rivervale inhabit the Nektulos Forest. You must defeat these creatures and halflings in order to obtain the materials. The materials you seek depend on the piece of armor you desire. Do you desire to craft [gloves], [boots], a [bracer], a [coif], [leggings], [sleeves], or a [tunic]?


**You say:** `silk thread`




>**Kanthu M-Rekkor says:** Silk thread is sewn by a tailor using a [sewing kit] or a community [loom]. Two spiderling silks combined in the [sewing kit] or community [loom] will create one silk thread.


**You say:** `boot`




>**Kanthu M-Rekkor says:** To craft Ashen Bone Mail Boots you require two [silk thread], two ruined ash drakeling scales, and two halfling foot bones. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Boot Pattern.



**You receive:**  [Tattered Boot Pattern](/item/19561)


**You say:** `bracer`




>**Kanthu M-Rekkor says:** To craft an Ashen Bone Mail Bracer you require a [silk thread], a ruined ash drakeling scales, and a halfling ulna bone. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Bracer Pattern.



**You receive:**  [Tattered Wristband Pattern](/item/19558)


**You say:** `coif`




>**Kanthu M-Rekkor says:** To craft a Ashen Bone Mail Coif you require two [silk thread], a ruined ash drakeling scales, and a halfling skull. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Cap Pattern.



**You receive:**  [Tattered Cap Pattern](/item/19555)


**You say:** `glove`




>**Kanthu M-Rekkor says:** To craft Ashen Bone Mail Gloves you require two [silk thread], a ruined ash drakeling scales, and two halfling finger bones. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Glove Pattern.



**You receive:**  [Tattered Glove Pattern](/item/19559)


**You say:** `legging`




>**Kanthu M-Rekkor says:** To craft Ashen Bone Mail Leggings you require three [silk thread], ash drakeling scales, two halfling tibia, and a halfling pelvis bone. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Leggings Pattern.



**You receive:**  [Tattered Pant Pattern](/item/19560)


**You say:** `sleeve`




>**Kanthu M-Rekkor says:** To craft Ashen Bone Mail Sleeves you require two [silk thread], ash drakeling scales, and two halfling humerus bones. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Sleeves Pattern.



**You receive:**  [Tattered Sleeve Pattern](/item/19557)


**You say:** `tunic`




>**Kanthu M-Rekkor says:** To craft an Ashen Bone Mail Tunic you require four [silk thread], pristine ash drakeling scales, a halfling sternum, and a halfling ribcage. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Tunic Pattern.



**You receive:**  [Tattered Tunic Pattern](/item/19556)

end

## Turn-Ins



local expansion_flag = eq.get_current_expansion();



if(expansion_flag >= 4.0 and  **You turn in:** [Note to Kanthuk](/item/2416)) then


>**Kanthu M-Rekkor says:** Greetings, Soandso. So you are one of Selzar's new recruits. You are to assist in the construction of the armor you will don as a new Rogue of the House of the Ebon Mask. I have assembled a kit that is used in the crafting of Ashen Bone Mail. You must travel beyond Neriak into the Nektulos Forest for the [materials] that compose the armor.


 **You receive:**  [Mail Assembly Kit](/item/17124) 

**This NPC *should* return incorrect items given.**





