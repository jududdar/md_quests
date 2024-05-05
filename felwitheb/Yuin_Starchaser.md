# Yuin Starchaser



[Yuin Starchaser](/npc/62036) is a level 61 High Elf GM Enchanter that spawns in [Southern Felwithe](/zone/62).





## Dialog


if(eq.get_current_expansion() >= 4.0) then

**You say:** `hail`



>**Yuin Starchaser says:** Welcome to the Keepers of the Art friend Soandso. I am Yuin Starchaser and it is my pleasure to assist new scholars wishing to study the arts of Enchantment, Wizardry, and Magery. Although much can be learned within these halls there is no substitute for experiences gained in the world outside Felwithe. The Koada'Dal have many enemies however, and it is wise to be prepared to face them. If you are new to the Keepers of the Art I will assist you in obtaining a [robe and clothing] suitable for study in the wilds.

**You say:** `robe and clothing`



>**Yuin Starchaser says:** You will need this specially prepared Curing Kit to craft the Art Keepers clothing. The materials required vary depending on the piece of clothing you desire to craft. Once you have been outfitted in the garments return to me and you may be assistance with another [task]. Do you desire to craft a art keepers [cap], [wristband], [gloves], [boots], [sleeves], [pantaloons], or [robe]?


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_730.png" alt="" /> <a
                                href="/item/17125" data-url="17125" class="tooltip-link link">Curing Kit</a>

**You say:** `boots`



>**Yuin Starchaser says:** To craft Art Keepers Boots you require two [silk thread], giant wasp worker pollen, a woven spider silk, and two ruined forest drakeling scales. Once you have the necessary components, combine them in your Curing Kit with this Tattered Boot Pattern.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19561" data-url="19561" class="tooltip-link link">Tattered Boot Pattern</a>

**You say:** `cap`



>**Yuin Starchaser says:** To craft an Art Keepers Cap you will require two [silk thread], giant wasp worker pollen, and a woven spider silk. Once you have the necessary components, combine them in your Curing Kit with this Tattered Cap Pattern.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19555" data-url="19555" class="tooltip-link link">Tattered Cap Pattern</a>

**You say:** `gloves`



>**Yuin Starchaser says:** To craft Art Keepers Gloves you require two [silk thread], giant wasp worker pollen, two woven spider silks, and a ruined forest drakeling scales. Once you have the necessary components, combine them in your Curing Kit with this Tattered Glove Pattern.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19559" data-url="19559" class="tooltip-link link">Tattered Glove Pattern</a>

**You say:** `pantaloons`



>**Yuin Starchaser says:** To craft Art Keepers Pantaloons you require two [silk thread], giant wasp warrior pollen, two woven spider silks, and two forest drakeling scales. Once you have the necessary components, combine them in your Curing Kit with this Tattered Leggings Pattern.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19560" data-url="19560" class="tooltip-link link">Tattered Pant Pattern</a>

**You say:** `robe`



>**Yuin Starchaser says:** To craft an Art Keepers Robe you will require three [silk thread], giant wasp warrior pollen, two woven spider silks, and a pristine forest drakeling scales. Once you have the necessary components, combine them in your Curing Kit with this Tattered Robe Pattern.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/11395" data-url="11395" class="tooltip-link link">Tattered Robe Pattern</a>

**You say:** `sleeves`



>**Yuin Starchaser says:** To craft Art Keepers Sleeves you require two [silk thread], giant wasp warrior pollen, a woven spider silk, and a forest drakeling scales. Once you have the necessary components, combine them in your Curing Kit with this Tattered Sleeves Pattern.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19557" data-url="19557" class="tooltip-link link">Tattered Sleeve Pattern</a>

**You say:** `wristband`



>**Yuin Starchaser says:** To craft an Art Keepers Wristband you require a [silk thread], giant wasp drone pollen, and a woven spider silk. Once you have the necessary components, combine them in your Curing Kit with this Tattered Wristband Pattern.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19558" data-url="19558" class="tooltip-link link">Tattered Wristband Pattern</a>

**You say:** `task`



>**Yuin Starchaser says:** One of the responsibilities of the Keepers of the Art is to weave and maintain powerful magic wards that help protect Felwithe from enemy magic. An understanding of the magic wielded by Felwithes many foes is vital to the success of our protective wards. With the help of the paladins of the Koada'Vie we have discovered many of the secrets of the orcish shaman that reside in the citadel of Clan Crushbone to the north of the Faydarks but there is still much to learn. The task I have to present you will take you into the [Crushbone Citadel] itself.

**You say:** `crushbone citadel`



>**Yuin Starchaser says:** The entrance to the Citadel can be found on the northern edge of the Greater Faydark. Once within the citadel seek out the Orc Thaumaturgist and obtain his book of spells. Once you are in possession of the Orc Thaumaturgists Spell Book return it to me so that the masters of the Keepers of the Art may study its contents.
end



## Turn-Ins



local expansion_flag = eq.get_current_expansion();


if(expansion_flag >= 4.0 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_865.png" alt="" /> <a
                                href="/item/20293" data-url="20293" class="tooltip-link link">Orc Thaumaturgists Spell Book</a>) then 


>**Yuin Starchaser says:** Well done young Art Keeper. Take this Rough Art Keepers Initiate Staff and go forth and gather a Pristine Forest Drakeling Scales and an Arborean Amber. When you have acquired those two items return them to me with the Rough Art Keepers Initiate Staff and I will put the final touches on the staff.


Your faction standing with [Keepers of the Art](/faction/275) got better (<span class='text-success'>+5</span>)


Your faction standing with [King Tearis Thex](/faction/279) got better (<span class='text-success'>+1</span>)


Your faction standing with [Faydarks Champions](/faction/246) got better (<span class='text-success'>+1</span>)


Your faction standing with [The Dead](/faction/239) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_602.png" alt="" /> <a
                                href="/item/20296" data-url="20296" class="tooltip-link link">Rough Art Keepers Initiate Staff</a> (+250 exp)

 



elseif(expansion_flag >= 4.0 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_602.png" alt="" /> <a
                                href="/item/20296" data-url="20296" class="tooltip-link link">Rough Art Keepers Initiate Staff</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1088.png" alt="" /> <a
                                href="/item/20271" data-url="20271" class="tooltip-link link">Pristine Forest Drakeling Scales</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_951.png" alt="" /> <a
                                href="/item/20274" data-url="20274" class="tooltip-link link">Arborean Amber</a>) then


>*Yuin Starchaser fashions a grip for the staff from the pristine forest drakeling scales, places the arborean amber into a mithril fixture and attaches the fixture to oneof the staff. 'Here is your new staff young Art Keeper may it serve you well in the pursuit of your studies.'*


Your faction standing with [Keepers of the Art](/faction/275) got better (<span class='text-success'>+5</span>)


Your faction standing with [King Tearis Thex](/faction/279) got better (<span class='text-success'>+1</span>)


Your faction standing with [Faydarks Champions](/faction/246) got better (<span class='text-success'>+1</span>)


Your faction standing with [The Dead](/faction/239) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_811.png" alt="" /> <a
                                href="/item/20332" data-url="20332" class="tooltip-link link">Art Keepers Initiate Staff</a> (+250 exp)

 

**This NPC *should* return incorrect items given.**
;