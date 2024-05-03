# Chef Dooga


## Dialog

**You say:** `hail`



>**Chef Dooga says:** Welcome you. You look all skin 'n bones. Eat you must do. Chef Dooga can fix up goodies for you. Try [HEHE meat].

**You say:** `hehe meat`



>**Chef Dooga says:** It is a secret ground meat made with high elf, human, and Erudite Flesh. Mmmm. It good stuff. Dooga make it and [the Gobbler] make it. If you find any of those meats in the swamps bring to me and I pay you.

**You say:** `gobbler`



>**Chef Dooga says:** You no hear of the Gobbler!! Him great butcher. Have all kinds of meat. Him am low on froglok legs. Dooga supply him. Dooga need someone to [deliver froglok legs].

**You say:** `recipe`



>**Chef Dooga says:** Recipe, recipe, recipe!  All want Chef Dooga's recipes.  Me no give out secrets.  Only HEHE meat recipe me share.  Me share that only wit [the Gobbler].

**You say:** `apron`



>**Chef Dooga says:** Apron?! Me gots aprons, but dey no grow on trees. You bring Dooga proof you a butcher first. You makes me three portions of pickled froglok then me allow you to also pay me ten gold for apron.

**You say:** `froglok legs`



if **Faction** >= Indifferent then




>**Chef Dooga says:** You think so!! That be good thing. Make the Gobbler happy. Maybe he give you something good. Maybe not. You take this. Deliver meat.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1068.png" alt="" /> <a
                                href="/item/13384" data-url="13384" class="tooltip-link link">Preserved Leg</a>


else



>**Chef Dooga says:** Come closer. Bouncer smash your head!

end



## Turn-Ins



local text = "Chef Dooga asks for three pickled frogloks and ten gold pieces for da ogre butcher apron.";




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_817.png" alt="" /> <a
                                href="/item/13364" data-url="13364" class="tooltip-link link">Human Flesh</a>) then 


>**Chef Dooga says:** MmmmMmm. Human make good meat pies. Here. A little coins for you.





Your faction standing with [Clurg](/faction/228) got better (<span class='text-success'>+2</span>)



Your faction standing with [Kazon Stormhammer](/faction/274) got worse (<span class='text-danger'>-2</span>)



Your faction standing with [Craknek Warriors](/faction/232) got better (<span class='text-success'>+2</span>)



Your faction standing with [Green Blood Knights](/faction/261) got better (<span class='text-success'>+2</span>)



Your faction standing with [Oggok Guards](/faction/337) got better (<span class='text-success'>+2</span>)






 &#127873; **You receive:** 0 (+10000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_817.png" alt="" /> <a
                                href="/item/13365" data-url="13365" class="tooltip-link link">High Elf Flesh</a>) then 


>**Chef Dooga says:** High elf!! Now that is a good meat.  Goes good with Ogre Swill.





Your faction standing with [Clurg](/faction/228) got better (<span class='text-success'>+2</span>)



Your faction standing with [Kazon Stormhammer](/faction/274) got worse (<span class='text-danger'>-2</span>)



Your faction standing with [Craknek Warriors](/faction/232) got better (<span class='text-success'>+2</span>)



Your faction standing with [Green Blood Knights](/faction/261) got better (<span class='text-success'>+2</span>)



Your faction standing with [Oggok Guards](/faction/337) got better (<span class='text-success'>+2</span>)





 &#127873; **You receive:** 0 (+10000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1018.png" alt="" /> <a
                                href="/item/13452" data-url="13452" class="tooltip-link link">Pickled Froglok</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1018.png" alt="" /> <a
                                href="/item/13452" data-url="13452" class="tooltip-link link">Pickled Froglok</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1018.png" alt="" /> <a
                                href="/item/13452" data-url="13452" class="tooltip-link link">Pickled Froglok</a>, platinum = 1) then


>**Chef Dooga says:** Here is da ogre butcher apron. Gos and cook.





Your faction standing with [Clurg](/faction/228) got better (<span class='text-success'>+5</span>)



Your faction standing with [Kazon Stormhammer](/faction/274) got worse (<span class='text-danger'>-5</span>)



Your faction standing with [Craknek Warriors](/faction/232) got better (<span class='text-success'>+5</span>)



Your faction standing with [Green Blood Knights](/faction/261) got better (<span class='text-success'>+5</span>)



Your faction standing with [Oggok Guards](/faction/337) got better (<span class='text-success'>+5</span>)





 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_632.png" alt="" /> <a
                                href="/item/12217" data-url="12217" class="tooltip-link link">Ogre Butcher Apron</a> (+10000 exp)

 

**This NPC *should* return incorrect items given.**





