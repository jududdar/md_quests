# Bipdo Hargin
## Dialog

**You say:** `hail`



>**Bipdo Hargin says:** I am busy right now. Please leave me alone.

**You say:** `thorn mail coif`



>**Bipdo Hargin says:** To assemble a Thorn Mail Coif you will require two [silk thread], ruined thorn drakeling scales, and a giant thicket rat skull. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Coif Pattern.


**You receive:**  [Tattered Cap Pattern](/item/19555)

**You say:** `thorn mail bracer`



>**Bipdo Hargin says:** To assemble a Thorn Mail Bracer you will require a [silk thread], ruined thorn drakeling scales, and a large fruit bat wing. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Bracer Pattern.


**You receive:**  [Tattered Wristband Pattern](/item/19558)

**You say:** `thorn mail gloves`



>**Bipdo Hargin says:** To assemble Thorn Mail Gloves you will require two [silk thread], ruined thorn drakeling scales, and two large fruit bat furs. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Glove Pattern.


**You receive:**  [Tattered Glove Pattern](/item/19559)

**You say:** `thorn mail boots`



>**Bipdo Hargin says:** To assemble Thorn Mail Boots you will require two [silk thread], two ruined thorn drakeling scales, and two giant thicket rat pelts. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Boot Pattern.


**You receive:**  [Tattered Boot Pattern](/item/19561)

**You say:** `thorn mail sleeves`



>**Bipdo Hargin says:** To assemble Thorn Mail Sleeves you will require two [silk thread], thorn drakeling scales, and two giant fruit bat wings. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Sleeves Pattern.


**You receive:**  [Tattered Sleeve Pattern](/item/19557)

**You say:** `thorn mail leggings`



>**Bipdo Hargin says:** To assemble Thorn Mail Leggings you will require three [silk thread], two thorn drakeling scales. and two giant fruit bat furs. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Leggings Pattern.


**You receive:**  [Tattered Pant Pattern](/item/19560)

**You say:** `thorn mail tunic`



>**Bipdo Hargin says:** To assemble a Thorn Mail Tunic you will require four [silk thread], pristine thorn drakeling scales, a giant fruit bat rib cage, and a giant fruit bat fur. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Tunic Pattern.


**You receive:**  [Tattered Tunic Pattern](/item/19556)

**You say:** `silk thread`



>**Bipdo Hargin says:** To make silk thread, take 2 spiderling silks and combine them together in a loom or in your handy sewing kit.
end

## Turn-Ins



if  **You turn in:** [Letter to Bipdo Hargin](/item/19627)


e.self:Say(string.format("Pleased to meet you %s! You must be one of Megosh's new trainees. Megosh has asked me to help get you outfitted in a suit of armor to protect you from the vile weapons of Rivervales foes. I have assembled a kit for you that will allow you to construct the armor pieces once you have gathered the necessary components. The required components vary according to which piece of Thorn Mail armor you are planning on assembling. Do you wish to craft a [thorn mail coif], a [thorn mail bracer], [thorn mail gloves], [thorn mail boots], [thorn mail sleeves], [thorn mail leggings], or a [thorn mail tunic].", e.other:GetCleanName()));


 **You receive:** None 

else


**This NPC *should* return incorrect items given.**
;
end
