# Kanthu M\`Rekkor



[Kanthu M\`Rekkor](/npc/42075) is a level 28 Dark Elf Shopkeeper that spawns in [Neriak - 3rd Gate](/zone/42).






## Dialog

if(eq.get_current_expansion() >= 4.0) then


**You say:** `material`




>**Kanthu M-Rekkor says:** Many species of dangerous creatures, the restless dead, and halfling invaders from Rivervale inhabit the Nektulos Forest. You must defeat these creatures and halflings in order to obtain the materials. The materials you seek depend on the piece of armor you desire. Do you desire to craft [gloves], [boots], a [bracer], a [coif], [leggings], [sleeves], or a [tunic]?


**You say:** `silk thread`




>**Kanthu M-Rekkor says:** Silk thread is sewn by a tailor using a [sewing kit] or a community [loom]. Two spiderling silks combined in the [sewing kit] or community [loom] will create one silk thread.


**You say:** `boot`




>**Kanthu M-Rekkor says:** To craft Ashen Bone Mail Boots you require two [silk thread], two ruined ash drakeling scales, and two halfling foot bones. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Boot Pattern.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19561" data-url="19561" class="tooltip-link link">Tattered Boot Pattern</a>


**You say:** `bracer`




>**Kanthu M-Rekkor says:** To craft an Ashen Bone Mail Bracer you require a [silk thread], a ruined ash drakeling scales, and a halfling ulna bone. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Bracer Pattern.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19558" data-url="19558" class="tooltip-link link">Tattered Wristband Pattern</a>


**You say:** `coif`




>**Kanthu M-Rekkor says:** To craft a Ashen Bone Mail Coif you require two [silk thread], a ruined ash drakeling scales, and a halfling skull. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Cap Pattern.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19555" data-url="19555" class="tooltip-link link">Tattered Cap Pattern</a>


**You say:** `glove`




>**Kanthu M-Rekkor says:** To craft Ashen Bone Mail Gloves you require two [silk thread], a ruined ash drakeling scales, and two halfling finger bones. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Glove Pattern.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19559" data-url="19559" class="tooltip-link link">Tattered Glove Pattern</a>


**You say:** `legging`




>**Kanthu M-Rekkor says:** To craft Ashen Bone Mail Leggings you require three [silk thread], ash drakeling scales, two halfling tibia, and a halfling pelvis bone. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Leggings Pattern.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19560" data-url="19560" class="tooltip-link link">Tattered Pant Pattern</a>


**You say:** `sleeve`




>**Kanthu M-Rekkor says:** To craft Ashen Bone Mail Sleeves you require two [silk thread], ash drakeling scales, and two halfling humerus bones. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Sleeves Pattern.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19557" data-url="19557" class="tooltip-link link">Tattered Sleeve Pattern</a>


**You say:** `tunic`




>**Kanthu M-Rekkor says:** To craft an Ashen Bone Mail Tunic you require four [silk thread], pristine ash drakeling scales, a halfling sternum, and a halfling ribcage. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Tunic Pattern.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19556" data-url="19556" class="tooltip-link link">Tattered Tunic Pattern</a>

end



## Turn-Ins



local expansion_flag = eq.get_current_expansion();



if(expansion_flag >= 4.0 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/2416" data-url="2416" class="tooltip-link link">Note to Kanthuk</a>) then


>**Kanthu M-Rekkor says:** Greetings, Soandso. So you are one of Selzar's new recruits. You are to assist in the construction of the armor you will don as a new Rogue of the House of the Ebon Mask. I have assembled a kit that is used in the crafting of Ashen Bone Mail. You must travel beyond Neriak into the Nektulos Forest for the [materials] that compose the armor.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_730.png" alt="" /> <a
                                href="/item/17124" data-url="17124" class="tooltip-link link">Mail Assembly Kit</a> 

 

**This NPC *should* return incorrect items given.**





