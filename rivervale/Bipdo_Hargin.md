# Bipdo Hargin



[Bipdo Hargin](/npc/19041) is a level 35 Halfling Shopkeeper that spawns in [Rivervale](/zone/19).



## Dialog

**You say:** `hail`



>**Bipdo Hargin says:** I am busy right now. Please leave me alone.

**You say:** `thorn mail coif`



>**Bipdo Hargin says:** To assemble a Thorn Mail Coif you will require two [silk thread], ruined thorn drakeling scales, and a giant thicket rat skull. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Coif Pattern.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19555" data-url="19555" class="tooltip-link link">Tattered Cap Pattern</a>

**You say:** `thorn mail bracer`



>**Bipdo Hargin says:** To assemble a Thorn Mail Bracer you will require a [silk thread], ruined thorn drakeling scales, and a large fruit bat wing. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Bracer Pattern.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19558" data-url="19558" class="tooltip-link link">Tattered Wristband Pattern</a>

**You say:** `thorn mail gloves`



>**Bipdo Hargin says:** To assemble Thorn Mail Gloves you will require two [silk thread], ruined thorn drakeling scales, and two large fruit bat furs. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Glove Pattern.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19559" data-url="19559" class="tooltip-link link">Tattered Glove Pattern</a>

**You say:** `thorn mail boots`



>**Bipdo Hargin says:** To assemble Thorn Mail Boots you will require two [silk thread], two ruined thorn drakeling scales, and two giant thicket rat pelts. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Boot Pattern.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19561" data-url="19561" class="tooltip-link link">Tattered Boot Pattern</a>

**You say:** `thorn mail sleeves`



>**Bipdo Hargin says:** To assemble Thorn Mail Sleeves you will require two [silk thread], thorn drakeling scales, and two giant fruit bat wings. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Sleeves Pattern.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19557" data-url="19557" class="tooltip-link link">Tattered Sleeve Pattern</a>

**You say:** `thorn mail leggings`



>**Bipdo Hargin says:** To assemble Thorn Mail Leggings you will require three [silk thread], two thorn drakeling scales. and two giant fruit bat furs. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Leggings Pattern.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19560" data-url="19560" class="tooltip-link link">Tattered Pant Pattern</a>

**You say:** `thorn mail tunic`



>**Bipdo Hargin says:** To assemble a Thorn Mail Tunic you will require four [silk thread], pristine thorn drakeling scales, a giant fruit bat rib cage, and a giant fruit bat fur. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Tunic Pattern.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19556" data-url="19556" class="tooltip-link link">Tattered Tunic Pattern</a>

**You say:** `silk thread`



>**Bipdo Hargin says:** To make silk thread, take 2 spiderling silks and combine them together in a loom or in your handy sewing kit.
end



## Turn-Ins



if ( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_868.png" alt="" /> <a
                                href="/item/19627" data-url="19627" class="tooltip-link link">Letter to Bipdo Hargin</a>) then


e.self:Say(string.format("Pleased to meet you %s! You must be one of Megosh's new trainees. Megosh has asked me to help get you outfitted in a suit of armor to protect you from the vile weapons of Rivervales foes. I have assembled a kit for you that will allow you to construct the armor pieces once you have gathered the necessary components. The required components vary according to which piece of Thorn Mail armor you are planning on assembling. Do you wish to craft a [thorn mail coif], a [thorn mail bracer], [thorn mail gloves], [thorn mail boots], [thorn mail sleeves], [thorn mail leggings], or a [thorn mail tunic].", e.other:GetCleanName()));


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_730.png" alt="" /> <a
                                href="/item/17124" data-url="17124" class="tooltip-link link">Mail Assembly Kit</a> 

 

else


**This NPC *should* return incorrect items given.**
;
end
