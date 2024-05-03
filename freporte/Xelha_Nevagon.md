# Xelha Nevagon


## Dialog

**You say:** `hail`



if **Faction** >= Apprehensive then



>**Xelha Nevagon says:** A new recruit to our cause.  Just what I have been waiting for! How would you like to serve the great Xelha Nevagon? I need an apprentice necromancer to [assist the great Xelha].


else



**Xelha Nevagon says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `assist the great xelha`




if **Faction** >= Amiable then



>**Xelha Nevagon says:** Fantastic. Stick with me and you shall ascend in our ranks quickly. I am in need of some components for new spells.  Will you collect them for me?  I shall need four each of the following - fire beetle eyes. bone chips and spiderling silk.  Fetch these items for me at once. Well..? Did not you hear the great Xelha? Begone!


elseif( **Faction is** == Indifferent) then



>**Xelha Nevagon says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Xelha Nevagon says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!

end



## Turn-Ins



local text1 = "Do not flame beetles have two eyes?!! This will do me no good. I will not reward you until I have two pairs!!";

local text2 = "Oh wonderful!! A few strands of spiderling web. Aren't you quite the hunter... Despite your obviously great skills, you managed to only kill one spiderling?! Get your cowardly hide out there and get me a few more spiderling silks!.";


if **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_782.png" alt="" /> <a
                                href="/item/13099" data-url="13099" class="tooltip-link link">Spiderling Silk</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_782.png" alt="" /> <a
                                href="/item/13099" data-url="13099" class="tooltip-link link">Spiderling Silk</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_782.png" alt="" /> <a
                                href="/item/13099" data-url="13099" class="tooltip-link link">Spiderling Silk</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_782.png" alt="" /> <a
                                href="/item/13099" data-url="13099" class="tooltip-link link">Spiderling Silk</a>) then 


>**Xelha Nevagon says:** Let's see here. One.. two.. three.. and.. four. Great!! Just enough for my needs. You are serving Xelha well. I give you Xelha's Sparkler. It is not much, but neither are you. You know what I really need is a cyclops eye. That would be worthy of a great reward.





Your faction standing with [Dismal Rage](/faction/271) got better (<span class='text-success'>+10</span>)


Your faction standing with [Knights of Truth](/faction/281) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Opal Darkbriar](/faction/296) got better (<span class='text-success'>+2</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_809.png" alt="" /> <a
                                href="/item/12247" data-url="12247" class="tooltip-link link">Xelha's Sparkler</a> (+2500 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-7 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-9 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_859.png" alt="" /> <a
                                href="/item/10307" data-url="10307" class="tooltip-link link">Fire Beetle Eye</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_859.png" alt="" /> <a
                                href="/item/10307" data-url="10307" class="tooltip-link link">Fire Beetle Eye</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_859.png" alt="" /> <a
                                href="/item/10307" data-url="10307" class="tooltip-link link">Fire Beetle Eye</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_859.png" alt="" /> <a
                                href="/item/10307" data-url="10307" class="tooltip-link link">Fire Beetle Eye</a>) then 


>**Xelha Nevagon says:** This is a good sight. I needed these to complete the current mixture. Bah!! I shall reward you for this small, very small, deed!! I pass on to you the knowledge of summoning. The more you serve, the more your faith in Innoruuk grows.





Your faction standing with [Dismal Rage](/faction/271) got better (<span class='text-success'>+10</span>)


Your faction standing with [Knights of Truth](/faction/281) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Opal Darkbriar](/faction/296) got better (<span class='text-success'>+2</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15338" data-url="15338" class="tooltip-link link">Spell: Cavorting Bones</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15331" data-url="15331" class="tooltip-link link">Spell: Reclaim Energy</a>) (+2500 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-7 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-9 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_804.png" alt="" /> <a
                                href="/item/13073" data-url="13073" class="tooltip-link link">Bone Chips</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_804.png" alt="" /> <a
                                href="/item/13073" data-url="13073" class="tooltip-link link">Bone Chips</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_804.png" alt="" /> <a
                                href="/item/13073" data-url="13073" class="tooltip-link link">Bone Chips</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_804.png" alt="" /> <a
                                href="/item/13073" data-url="13073" class="tooltip-link link">Bone Chips</a>) then 


>**Xelha Nevagon says:** Excellent work! You are quite the little helper. Here you go, then. A little something for your little work. Your service to me has caused Innoruuk to look upon you favorably. Your faith in our group has grown. Continue the work.





Your faction standing with [Dismal Rage](/faction/271) got better (<span class='text-success'>+5</span>)


Your faction standing with [Knights of Truth](/faction/281) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Opal Darkbriar](/faction/296) got better (<span class='text-success'>+1</span>)





 &#127873; **You receive:** 0 (+2500 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-9 <img src='/static/icons/item_647.png' width='14' height='14'/> 



elseif **Faction** >= Kindly and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_859.png" alt="" /> <a
                                href="/item/13927" data-url="13927" class="tooltip-link link">Cyclops Eye</a>) then 


>**Xelha Nevagon says:** A cyclops eye!! You are stronger than I believed. You will rise in the ranks of the Dismal Rage quickly with acts such as this!! I am most appreciative! Here, take this. It was lying around my shelves, just gettingg all dusty. I hope you can use it. And watch yourself in your journeys, the aura of your faith in Innoruuk surrounds you like a shroud. Our enemies will surely see you for what you are.





Your faction standing with [Dismal Rage](/faction/271) got better (<span class='text-success'>+25</span>)


Your faction standing with [Knights of Truth](/faction/281) got worse (<span class='text-danger'>-3</span>)


Your faction standing with [Opal Darkbriar](/faction/296) got better (<span class='text-success'>+5</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15036" data-url="15036" class="tooltip-link link">Spell: Gate</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15491" data-url="15491" class="tooltip-link link">Spell: Leering Corpse</a>) (+500 exp)

**You receive coin:** 1-7 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-9 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**




