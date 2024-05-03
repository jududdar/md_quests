# Salmekia Treherth


## Dialog

if(eq.get_current_expansion() >= 4.0) then


**You say:** `hail`




e.self:Say(string.format("Welcome to Surefall Glade, %s, the home of the Jaggedpine Treefolk. I help teach young druids the ways of our people. We have worshipers of both Karana, the Storm Lord, and Tunare, the All Mother, living here in the glade. If you are a new druid I will help you obtain a [suit of clothing] that will offer comfort and protection while working in the wilds and help protect you from the weapons of the Gnolls that wish to take these lands.",e.other:GetName()));


**You say:** `suit of clothing`




>**Salmekia Treherth says:** You must use this specially prepared Curing Kit to craft the clothing. Each article of clothing requires different materials for its construction. Do you plan on crafting Pine Druid [Gloves], Pine Druid [Boots], a Pine Druid [Bracer], a Pine Druid [Cap], Pine Druid [Leggings], Pine Druid [Sleeves], or a Pine Druid [Tunic]? When you have been outfitted and are ready I will tell you of a [task] that you can assist with.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_730.png" alt="" /> <a
                                href="/item/17125" data-url="17125" class="tooltip-link link">Curing Kit</a>


**You say:** `glove`




>**Salmekia Treherth says:** To craft Pine Druid Gloves you require two [silk thread], ruined gnoll leather gloves, two giant field rat whiskers, and a large king snake skin. Once you have the necessary components combine them in your Curing Kit with this Tattered Glove Pattern.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19559" data-url="19559" class="tooltip-link link">Tattered Glove Pattern</a>


**You say:** `boot`




>**Salmekia Treherth says:** To craft Pine Druid Boots you require two [silk thread], ruined gnoll leather boots, two giant field rat whiskers, and a large whiskered bat fur. Once you have the necessary components combine them in your Curing Kit with this Tattered Boot Pattern.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19561" data-url="19561" class="tooltip-link link">Tattered Boot Pattern</a>


**You say:** `bracer`




>**Salmekia Treherth says:** To craft an Pine Druid Bracer you require a [silk thread], a ruined gnoll leather bracer, and a giant field rat whiskers. Once you have the necessary components combine them in your Curing Kit with this Tattered Wristband Pattern.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19558" data-url="19558" class="tooltip-link link">Tattered Wristband Pattern</a>


**You say:** `cap`




>**Salmekia Treherth says:** To craft a Pine Druid Cap you require two [silk thread], a ruined gnoll leather cap, a large whiskered bat fur, and a large field rat pelt. Once you have the necessary components combine them in your Curing Kit with this Tattered Cap Pattern.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19555" data-url="19555" class="tooltip-link link">Tattered Cap Pattern</a>


**You say:** `legging`




>**Salmekia Treherth says:** To craft Pine Druid Leggings you require three [silk thread], ruined gnoll leather leggings, two large whiskered bat furs, and a giant field rat pelt. Once you have the necessary components combine them in your Curing Kit with this Tattered Pant Pattern.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19560" data-url="19560" class="tooltip-link link">Tattered Pant Pattern</a>


**You say:** `sleeve`




>**Salmekia Treherth says:** To craft Pine Druid Sleeves you require two [silk thread], ruined gnoll leather sleeves, two large whiskered bat furs, and a giant field rat pelt. Once you have the necessary components combine them in your Curing Kit with this Tattered Sleeves Pattern.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19557" data-url="19557" class="tooltip-link link">Tattered Sleeve Pattern</a>


**You say:** `tunic`




>**Salmekia Treherth says:** To craft a Pine Druid Tunic you require four [silk thread], a ruined gnoll leather tunic, a giant whiskered bat fur, and a giant field rat pelt. Once you have the necessary components combine them in your Curing Kit with this Tattered Tunic Pattern.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19556" data-url="19556" class="tooltip-link link">Tattered Tunic Pattern</a>


**You say:** `silk thread`




>**Salmekia Treherth says:** Silk thread is created from two spiderling silks woven together in a sewing kit or loom.


**You say:** `task`




>**Salmekia Treherth says:** We druids seek to live in harmony with nature, taking only what we need from the land and the creatures that inhabit it. Although the City of Qeynos is a noble place, there are people in the city that do not share our reverence for nature and poach the animals of the Karanas needlessly. Even worse than these poachers, whom the rangers of the Jaggedpine Treefolk constantly seek to deter, are the despicable worshipers of Bertoxxulous that hide in the sewers and catacombs of Qeynos. These wicked individuals are known as the [Bloodsabers].


**You say:** `bloodsabers`




>**Salmekia Treherth says:** The Bloodsabers are responsible for a number of atrocities including the spreading of the diseases which have been inflicting the wolves and bears of the Qeynos Hills and the recent poisoning of the farmers fields in the Plains of Karana. Recently we have discovered that a Bloodsaber defiler has been attempting to poison the waters of Surefall Glade. Find this individual and deal with him accordingly, I doubt that this individual will surrender willingly. If need be eliminate them and bring me their head.

end



## Turn-Ins



local expansion_flag = eq.get_current_expansion();

if(expansion_flag >= 4.0 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_982.png" alt="" /> <a
                                href="/item/20268" data-url="20268" class="tooltip-link link">Bloodsaber Defilers Head</a>) then


>**Salmekia Treherth says:** It is a shame that some people decide to throw away their humanity with the worship of evil deities. Your actions have saved the lives of many creatures that rely on the waters of this glade. Take this Rusty Pine Druid Scimitar and sharpen it in a forge with a sharpening stone. It may take you several attempts if you are unfamiliar with the process. Once that is done return to me with the Sharpened Pine Druid Scimitar, a Gnoll Fang, and a Large King Snake Skin.





Your faction standing with [Jaggedpine Treefolk](/faction/272) got better (<span class='text-success'>+10</span>)


Your faction standing with [Protectors of Pine](/faction/302) got better (<span class='text-success'>+2</span>)


Your faction standing with [QRG Protected Animals](/faction/343) got better (<span class='text-success'>+1</span>)


Your faction standing with [Unkempt Druids](/faction/324) got worse (<span class='text-danger'>-2</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_604.png" alt="" /> <a
                                href="/item/20258" data-url="20258" class="tooltip-link link">Rusty Pine Druid Scimitar</a> (+1000 exp)

 

elseif(expansion_flag >= 4.0 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_604.png" alt="" /> <a
                                href="/item/20259" data-url="20259" class="tooltip-link link">Sharp Pine Druid Scimitar</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_800.png" alt="" /> <a
                                href="/item/13915" data-url="13915" class="tooltip-link link">Gnoll Fang</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_813.png" alt="" /> <a
                                href="/item/19945" data-url="19945" class="tooltip-link link">Large King Snake Skin</a>) then


>*Salmekia Treherth fashions a grip from the large king snake skin, attaches the gnoll fang to the heel of the swords hilt, and polishes the blade of the sword with a luminescent green polish. 'Here is your new weapon young druid. May it serve you well.'*





Your faction standing with [Jaggedpine Treefolk](/faction/272) got better (<span class='text-success'>+5</span>)


Your faction standing with [Protectors of Pine](/faction/302) got better (<span class='text-success'>+1</span>)


Your faction standing with [QRG Protected Animals](/faction/343) got better (<span class='text-success'>+1</span>)


Your faction standing with [Unkempt Druids](/faction/324) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_604.png" alt="" /> <a
                                href="/item/20265" data-url="20265" class="tooltip-link link">Pine Druid Scimitar</a> (+1000 exp)

 

**This NPC *should* return incorrect items given.**
