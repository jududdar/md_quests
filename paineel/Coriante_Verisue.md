# Coriante Verisue


## Dialog

**You say:** `hail`



if **Faction** >= Apprehensive then 



>**Coriante Verisue says:** Greetings, young one! There are many tasks to be performed aside from your studies to truly harness the powers passed down to us by our ancestor [Miragul]. The most basic of these tasks is the gathering of bat wings and snake fangs from the yard outside our city. I will reward you for every two bat wings and two snake fangs you bring to me.


else



**Coriante Verisue says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `miragul`



if **Faction** >= Apprehensive then 



>**Coriante Verisue says:** You do not know of Miragul?!! You have more to learn of the heritage of the Dark Truth than at first I thought. Miragul was the first High Man to unlock the secrets of necromancy and is the founder of our city as well as the creator of the treacherous Hole.


else



**Coriante Verisue says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!

end



## Turn-Ins



local text = "You must gather all four of the required items in order to receive your reward. I expect more reliability from you in the future."



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_682.png" alt="" /> <a
                                href="/item/18018" data-url="18018" class="tooltip-link link">Dark Truth Guild Note</a>) then 


>**Coriante Verisue says:** You are welcomed into the fold.  Now go out, and prove yourself, young one.  You have much to learn about the Dark Truth.


Your faction standing with [Heretics](/faction/265) got better (<span class='text-success'>+100</span>)


Your faction standing with [Deepwater Knights](/faction/242) got worse (<span class='text-danger'>-100</span>)


Your faction standing with [Gate Callers](/faction/254) got worse (<span class='text-danger'>-100</span>)


Your faction standing with [Craftkeepers](/faction/231) got worse (<span class='text-danger'>-100</span>)


Your faction standing with [Crimson Hands](/faction/233) got worse (<span class='text-danger'>-100</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_713.png" alt="" /> <a
                                href="/item/13551" data-url="13551" class="tooltip-link link">Dirt Soiled Robe*</a> (+20 exp)

 

elseif **Faction** >= Apprehensive and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_791.png" alt="" /> <a
                                href="/item/13068" data-url="13068" class="tooltip-link link">Bat Wing</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_791.png" alt="" /> <a
                                href="/item/13068" data-url="13068" class="tooltip-link link">Bat Wing</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_801.png" alt="" /> <a
                                href="/item/13067" data-url="13067" class="tooltip-link link">Snake Fang</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_801.png" alt="" /> <a
                                href="/item/13067" data-url="13067" class="tooltip-link link">Snake Fang</a>) then 


>**Coriante Verisue says:** Very good, young acolyte. Maintain your diligence in your duties and you will quickly learn the secrets of the Dark Truth.


Your faction standing with [Heretics](/faction/265) got better (<span class='text-success'>+2</span>)


Your faction standing with [Craftkeepers](/faction/231) got worse (<span class='text-danger'>-2</span>)


Your faction standing with [Crimson Hands](/faction/233) got worse (<span class='text-danger'>-2</span>)


Your faction standing with [Deepwater Knights](/faction/242) got worse (<span class='text-danger'>-2</span>)


Your faction standing with [Gate Callers](/faction/254) got worse (<span class='text-danger'>-2</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15338" data-url="15338" class="tooltip-link link">Spell: Cavorting Bones</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15342" data-url="15342" class="tooltip-link link">Spell: Locate Corpse</a>) (+5000 exp)

 

**This NPC *should* return incorrect items given.**
