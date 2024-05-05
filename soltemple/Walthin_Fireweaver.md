# Walthin Fireweaver



[Walthin Fireweaver](/npc/80011) is a level 35 Half Elf Bard that spawns in [Temple of Solusek Ro](/zone/80).





## Dialog

if **Faction** >= Indifferent then


**You say:** `hail`




>**Walthin Fireweaver says:** Greetings, Soandso. I am Walthin Fireweaver of the Temple of Solusek Ro. I am the protector of an ancient armor invented by long dead bards of the temple. This armor will help any bard in their journey across Norrath. Are you a bard that would desire to own some of this armor?


**You say:** `no`




>**Walthin Fireweaver says:** Very well.


**You say:** `yes`




>**Walthin Fireweaver says:** Very well. I craft a type of bardic armor that I invented called Lambent Armor. I can craft for you [boots], [gauntlets], and [greaves]. My friend Cryssia Stardreamer will craft for you the other pieces. I require a special kind of lambent stone for each of my armor pieces.  Find my friends Orstorm, Genni, Gardern, and Vilissia within the temple and they will help you create them.


**You say:** `boots`




>**Walthin Fireweaver says:** Alright, I will require some items. Go and get me some Firewalker Boots, a Lambent Sapphire, and the middle piece of the Rune of the One Eye. Return to me with these items and I will craft your boots.


**You say:** `gauntlets`




>**Walthin Fireweaver says:** Alright, I need you to retrieve for me some Black Silk Gloves, a Lambent Star Ruby, and Shin Gauntlets. Return to me with these and I will craft your gauntlets.


**You say:** `greaves`




>**Walthin Fireweaver says:** Very well, return to me with these items and I will craft them. A set of Icy Greaves, a Lambent Fire Opal, and Shin Greaves.


else


**Walthin Fireweaver says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!
end



## Turn-Ins



local text = "Wait, Soandso, are you not forgetting something?";



if **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_633.png" alt="" /> <a
                                href="/item/2318" data-url="2318" class="tooltip-link link">Firewalker Boots</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_963.png" alt="" /> <a
                                href="/item/10119" data-url="10119" class="tooltip-link link">Lambent Sapphire</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/10561" data-url="10561" class="tooltip-link link">Rune of the One Eye</a>) then


>**Walthin Fireweaver says:** Quality boots for a quality bard. Well done, Soandso.


Your faction standing with [Temple of Solusek Ro](/faction/415) got better (<span class='text-success'>+10</span>)




Your faction standing with [Shadowed Men](/faction/416) got worse (<span class='text-danger'>-1</span>)
   


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_524.png" alt="" /> <a
                                href="/item/4159" data-url="4159" class="tooltip-link link">Lambent Boots</a> (+1000 exp)

 

elseif **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_636.png" alt="" /> <a
                                href="/item/2319" data-url="2319" class="tooltip-link link">Black Silk Gloves</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_961.png" alt="" /> <a
                                href="/item/10117" data-url="10117" class="tooltip-link link">Lambent Star Ruby</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_846.png" alt="" /> <a
                                href="/item/4114" data-url="4114" class="tooltip-link link">Shin Gauntlets</a>) then


>**Walthin Fireweaver says:** Well done, Soandso, you have justly earned your pair of lambent gauntlets.


Your faction standing with [Temple of Solusek Ro](/faction/415) got better (<span class='text-success'>+10</span>)




Your faction standing with [Shadowed Men](/faction/416) got worse (<span class='text-danger'>-1</span>)
   


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_531.png" alt="" /> <a
                                href="/item/4157" data-url="4157" class="tooltip-link link">Lambent Gauntlets</a> (+1000 exp)

 

elseif **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_541.png" alt="" /> <a
                                href="/item/4115" data-url="4115" class="tooltip-link link">Icy Greaves</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_960.png" alt="" /> <a
                                href="/item/10128" data-url="10128" class="tooltip-link link">Lambent Fire Opal</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_845.png" alt="" /> <a
                                href="/item/4116" data-url="4116" class="tooltip-link link">Shin Greaves</a>) then


>**Walthin Fireweaver says:** I always knew that you would earn these lambent greaves, Soandso, you just had that look about you. Well done!


Your faction standing with [Temple of Solusek Ro](/faction/415) got better (<span class='text-success'>+10</span>)




Your faction standing with [Shadowed Men](/faction/416) got worse (<span class='text-danger'>-1</span>)
   


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_540.png" alt="" /> <a
                                href="/item/4158" data-url="4158" class="tooltip-link link">Lambent Greaves</a> (+1000 exp)

 

**This NPC *should* return incorrect items given.**
