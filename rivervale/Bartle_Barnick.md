# Bartle Barnick



[Bartle Barnick](/npc/19043) is a level 35 Halfling Shopkeeper that spawns in [Rivervale](/zone/19).



## Dialog

if(eq.get_current_expansion() >= 4.0) then


**You say:** `hail`




>**Bartle Barnick says:** Good day! If you are a new Druid of the Storm Reapers I have promised Hibbs that I would assist in getting you outfitted for ventures beyond Rivervale but you must bring me a note from Reebo as proof that he sent you. There are many dangers outside of the shire so often leather clothing and a weapon become necessities for a traveling druid.


**You say:** `moss toe cap`




>**Bartle Barnick says:** To assemble a Moss Toe Cap you will require two [silk thread], a ruined mossy rat pelt, and a giant thicket rat skull. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Cap Pattern.







 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19555" data-url="19555" class="tooltip-link link">Tattered Cap Pattern</a>


**You say:** `moss toe bracer`




>**Bartle Barnick says:** To assemble a Moss Toe Bracer you will require a [silk thread], a ruined mossy rat pelt, and a large wood spider tibia. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Wristband Pattern.







 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19558" data-url="19558" class="tooltip-link link">Tattered Wristband Pattern</a>


**You say:** `moss toe gloves`




>**Bartle Barnick says:** To assemble Moss Toe Gloves you will require two [silk thread], a ruined mossy rat pelt, and two large wood spider tarsus. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Glove Pattern.







 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19559" data-url="19559" class="tooltip-link link">Tattered Glove Pattern</a>


**You say:** `moss toe boots`




>**Bartle Barnick says:** To assemble Moss Toe Boots you will require two [silk thread], two ruined mossy rat pelts, and two giant wood spider hairs. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Boot Pattern.







 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19561" data-url="19561" class="tooltip-link link">Tattered Boot Pattern</a>


**You say:** `moss toe sleeves`




>**Bartle Barnick says:** To assemble Moss Toe Sleeves you will require two [silk thread], a mossy rat pelt, and two giant wood spider patella. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Sleeves Pattern.







 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19557" data-url="19557" class="tooltip-link link">Tattered Sleeve Pattern</a>


**You say:** `moss toe leggings`




>**Bartle Barnick says:** To assemble Moss Toe Leggings you will require three [silk thread], two mossy rat pelts, and two giant wood spider femurs. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Pants Pattern.







 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19560" data-url="19560" class="tooltip-link link">Tattered Pant Pattern</a>


**You say:** `moss toe tunic`




>**Bartle Barnick says:** To assemble a Moss Toe Tunic you will require four [silk thread], an undamaged mossy rat pelt, and a giant wood spider thorax. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Tunic Pattern.







 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19556" data-url="19556" class="tooltip-link link">Tattered Tunic Pattern</a>


**You say:** `silk thread`




>**Bartle Barnick says:** Silk Thread is sewn by a tailor using a [sewing kit] or a community [loom]. Two spiderling silks combined in the sewing kit or loom will create one silk thread.


**You say:** `sewing kit`




>**Bartle Barnick says:** Meeka Diggs in the center of Rivervale behind the Fools Gold Tavern may be able to provide you with a sewing kit. There is also a loom near where she peddles her goods.


**You say:** `loom`




>**Bartle Barnick says:** Meeka Diggs in the center of Rivervale behind the Fools Gold Tavern may be able to provide you with a sewing kit. There is also a loom near where she peddles her goods.

end
 




## Turn-Ins



local expansion_flag = eq.get_current_expansion();



if(expansion_flag >= 4.0 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_868.png" alt="" /> <a
                                href="/item/19629" data-url="19629" class="tooltip-link link">Letter to Bartle Barnick</a>) then


>**Bartle Barnick says:** It is good to see another of our young people choose the humble life of a druid of Karana. I have assembled patterns that will allow you to construct some protective leather garments to keep you comfortable in the wilds and help turn aside the weapons of the Storm Reapers enemies. The required components for the leather vary according to which piece of Moss Toe Leather your are planning on crafting. Do you wish to craft a [moss toe cap], a [moss toe bracer], [moss toe gloves], [moss toe boots], [moss toe sleeves], [moss toe leggings], or a [moss toe tunic]?


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_730.png" alt="" /> <a
                                href="/item/17124" data-url="17124" class="tooltip-link link">Mail Assembly Kit</a> 

 

**This NPC *should* return incorrect items given.**
;

