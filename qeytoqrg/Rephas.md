# Rephas


## Dialog

**You say:** `hail`



if **Faction** >= Apprehensive then



>**Rephas says:** Aagggh..  Get away from here..  Go, run..  Far away..  Or I shall call [Karana's] wrath upon you!


else



**Rephas says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `karana`



if **Faction** >= Apprehensive then



>**Rephas says:** Heh!..  Ignorant one!  Begone, and take your stupidity with you!


else



**Rephas says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!

end



## Turn-Ins



local text = "Hey..  wow..  Now THESE are some good, meaty ears..  These will make one great rat ear pie..  Tell ya what, kid..  bring me a few more o' these beauties, and I'll give you my secret recipe for cooking 'em.";


if **Faction** >= Apprehensive and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_793.png" alt="" /> <a
                                href="/item/13072" data-url="13072" class="tooltip-link link">Rat Ears</a>) then


>**Rephas says:** Ahh yes..  These are a little small, but still some good eating, if you know how to cook 'em of course..   Here ya go, enjoy and may Karana keep your fields lush and green.





Your faction standing with [Arcane Scientists](/faction/220) got better (<span class='text-success'>+5</span>)


Your faction standing with [Knights of Truth](/faction/281) got better (<span class='text-success'>+1</span>)


Your faction standing with [Opal Darkbriar](/faction/296) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [The Freeport Militia](/faction/330) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_915.png" alt="" /> <a
                                href="/item/13719" data-url="13719" class="tooltip-link link">Grilled Rat Ears</a> (+10 exp)

 

elseif **Faction** >= Apprehensive and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_915.png" alt="" /> <a
                                href="/item/13719" data-url="13719" class="tooltip-link link">Grilled Rat Ears</a>) then


>**Rephas says:** Wha?..   Ah, I guess it's a bit of an acquired taste..  Oh well, your loss..  Here, take this..  They ain't no ears, but it's the least I could do..   And if ya find any more rat ears, good ol' Rephas here will be glad to take 'em off your hands for ya!





Your faction standing with [Arcane Scientists](/faction/220) got better (<span class='text-success'>+5</span>)


Your faction standing with [Knights of Truth](/faction/281) got better (<span class='text-success'>+1</span>)


Your faction standing with [Opal Darkbriar](/faction/296) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [The Freeport Militia](/faction/330) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_761.png" alt="" /> <a
                                href="/item/1038" data-url="1038" class="tooltip-link link">Tattered Cloth Sandal</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_799.png" alt="" /> <a
                                href="/item/13076" data-url="13076" class="tooltip-link link">Fish Scales</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15041" data-url="15041" class="tooltip-link link">Spell: Weaken</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15208" data-url="15208" class="tooltip-link link">Spell: Lull</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15205" data-url="15205" class="tooltip-link link">Spell: True North</a>) (+5 exp)

 

elseif **Faction** >= Apprehensive and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_793.png" alt="" /> <a
                                href="/item/13050" data-url="13050" class="tooltip-link link">Giant Rat Ear</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_793.png" alt="" /> <a
                                href="/item/13050" data-url="13050" class="tooltip-link link">Giant Rat Ear</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_793.png" alt="" /> <a
                                href="/item/13050" data-url="13050" class="tooltip-link link">Giant Rat Ear</a>) then


>**Rephas says:** Wow!..  How big was the dang varmint that these come off of?!  Bigger'n a ol' grizzly, I bet!  You've earned this, my friend!  It's my own secret recipe for rat ear pie..  sure is tasty, easy to make, and keeps your belly full while you're running about in the hills and such.  Take care, and may Karana keep your path clear and our lakes full.





Your faction standing with [Arcane Scientists](/faction/220) got better (<span class='text-success'>+5</span>)


Your faction standing with [Knights of Truth](/faction/281) got better (<span class='text-success'>+1</span>)


Your faction standing with [Opal Darkbriar](/faction/296) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [The Freeport Militia](/faction/330) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18103" data-url="18103" class="tooltip-link link">Rat Ear Pie</a> (+10 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_864.png" alt="" /> <a
                                href="/item/27428" data-url="27428" class="tooltip-link link">Assorted Research pg1</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_864.png" alt="" /> <a
                                href="/item/27429" data-url="27429" class="tooltip-link link">Assorted Research pg2</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_864.png" alt="" /> <a
                                href="/item/27430" data-url="27430" class="tooltip-link link">Assorted Research pg3</a>) then


>**Rephas says:** These were the exact pages I was missing. I have been compiling this research for Juegile. It is now finished so please bring this book to him. Thank you!





Your faction standing with [Arcane Scientists](/faction/220) got better (<span class='text-success'>+10</span>)


Your faction standing with [Knights of Truth](/faction/281) got better (<span class='text-success'>+2</span>)


Your faction standing with [Opal Darkbriar](/faction/296) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [The Freeport Militia](/faction/330) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_777.png" alt="" /> <a
                                href="/item/27431" data-url="27431" class="tooltip-link link">An Enchanted Book</a> (+500 exp)

 

**This NPC *should* return incorrect items given.**

