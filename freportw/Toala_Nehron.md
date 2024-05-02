# Toala Nehron
## Dialog

**You say:** `hail`



>**Toala Nehron says:** I am Toala Nehron. You must be another young warrior aspiring to join the ranks of the Steel Warriors. We welcome all who would try. When you [have time] there is a friend of mine I would like you to check on.

**You say:** `opal`



>**Toala Nehron says:** Opal Darkbriar is a little plague rat.  She has used her knowledge of arcane arts to charm [Cain Darkmoore].  I know that is what happened.  Why else would he be in love with her?  He is a mighty warrior and she is nothing more than a sickly little librarian for the Academy of Arcane Science.  He must truly yearn for a bold hearted female warrior such as myself.  Not that I care, of course.

**You say:** `cain darkmoore`



>**Toala Nehron says:** Cain Darkmoore is only the most handsome of warriors!  He is also the strongest and most bold.  He has slain the mightiest of fiends.  He is truly the manliest man around.  It is no wonder he is the guildmaster of the Steel Warriors.

elseif( **Faction is** > Indifferent) then


**You say:** `have time`




>**Toala Nehron says:** I have A friend by the name of [Lenka Stoutheart]. She reported to me that her ship was broken into and someone stole a pouch of hers. Could you go look into it for me? Just tell her Toala sent you. Oh, and pay no mind to the walking mountain by her. That will only be Bronto, her navigator. Thanks friend.


**You say:** `lenka stoutheart`




>**Toala Nehron says:** Lenka Stoutheart is an old friend of mine. I met her in my younger days when the Steel Warriors sent me to train in the ways of the Wolves of the North, the barbarian warriors of Halas. She is now an adventurer of great renown. She travels from continent to continent aboard her ship,the Blue Beast, her ship.


elseif( **Faction is** == Indifferent) then


**You say:** `have time`




>**Toala Nehron says:** The Steel Warriors have no cause to dislike you, but you have yet to prove your worth to this guild.



elseif( **Faction is** < Indifferent) then


**You say:** `have time`




>**Toala Nehron says:** Your head shall look grand mounted on the wall of the Steel Warriors Arena!!


end

## Turn-Ins



if( **Faction is** > Indifferent) then


if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/18814" data-url="18814" class="tooltip-link link">A Sealed Letter</a>) then 



>**Toala Nehron says:** Why, that little trollop! What is she up to? Cain will never believe this! She must be in league with some faction of the dark elves, but why? Neither the Academy of Arcane Science nor Cain will believe this note. I will see what I can do. As for you, I command you to kill this Shintl and her dark elf courier Hollish!! Put their heads into this box and combine them. We shall cut the link. Bring me thier heads.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_608.png" alt="" /> <a
                                href="/item/17971" data-url="17971" class="tooltip-link link">Toalas Box for heads</a> (+500 exp)

 


elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_608.png" alt="" /> <a
                                href="/item/12246" data-url="12246" class="tooltip-link link">Box with Two Heads</a>) then 



>**Toala Nehron says:** Good work!! We will soon catch Opal. I have started to formulate a plan to stop her. When I complete it, I shall notify you. Here. Take this small reward. I am sure killing Shintl was no trouble. She was just a halfling.



Your faction standing with [Steel Warriors](/faction/311) got better (<span class='text-success'>+10</span>)



Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+2</span>)



Your faction standing with [Knights of Truth](/faction/281) got better (<span class='text-success'>+2</span>)



Your faction standing with [Corrupt Qeynos Guards](/faction/230) got worse (<span class='text-danger'>-1</span>)



Your faction standing with [The Freeport Militia](/faction/330) got worse (<span class='text-danger'>-1</span>)



 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_640.png" alt="" /> <a
                                href="/item/2001" data-url="2001" class="tooltip-link link">Leather Skullcap</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_771.png" alt="" /> <a
                                href="/item/2002" data-url="2002" class="tooltip-link link">Leather Mask</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_643.png" alt="" /> <a
                                href="/item/2003" data-url="2003" class="tooltip-link link">Leather Gorget</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_632.png" alt="" /> <a
                                href="/item/2004" data-url="2004" class="tooltip-link link">Leather Tunic</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_668.png" alt="" /> <a
                                href="/item/2005" data-url="2005" class="tooltip-link link">Leather Shoulderpads</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_660.png" alt="" /> <a
                                href="/item/2006" data-url="2006" class="tooltip-link link">Leather Cloak</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_564.png" alt="" /> <a
                                href="/item/2007" data-url="2007" class="tooltip-link link">Leather Belt</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_634.png" alt="" /> <a
                                href="/item/2008" data-url="2008" class="tooltip-link link">Leather Sleeves</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_637.png" alt="" /> <a
                                href="/item/2009" data-url="2009" class="tooltip-link link">Leather Wristbands</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_636.png" alt="" /> <a
                                href="/item/2010" data-url="2010" class="tooltip-link link">Leather Gloves</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_635.png" alt="" /> <a
                                href="/item/2011" data-url="2011" class="tooltip-link link">Leather Leggings</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_633.png" alt="" /> <a
                                href="/item/2012" data-url="2012" class="tooltip-link link">Leather Boots</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_542.png" alt="" /> <a
                                href="/item/9002" data-url="9002" class="tooltip-link link">Round Shield</a>) (+2000 exp)

**You receive coin:** 0-1 <img src='/static/icons/item_644.png' width='14' height='14'/> 0-5 <img src='/static/icons/item_645.png' width='14' height='14'/> 0-10 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 


elseif( **Faction is** == Indifferent) then


if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/18814" data-url="18814" class="tooltip-link link">A Sealed Letter</a>) then 



>**Toala Nehron says:** The Steel Warriors have no cause to dislike you, but you have yet to truly prove your worth to this guild.


elseif( **Faction is** < Indifferent) then


if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/18814" data-url="18814" class="tooltip-link link">A Sealed Letter</a>) then 



>**Toala Nehron says:** Your head shall look grand mounted on the wall of the Steel Warriors Arena!!


**This NPC *should* return incorrect items given.**
;

