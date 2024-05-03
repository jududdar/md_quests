# Synthan


## Dialog

**You say:** `hail`



if **Faction** >= Indifferent then



>**Synthan says:** I am Mrysila, custodian of the [Concordance of Research].


else



**Synthan says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `concordance of research`



if **Faction** >= Indifferent then



>**Synthan says:** The 'Concordance of Research' is an aid to those who follow the path of academia. It, and its sister books, 'Runes and Research,' volumes I and II, help those who are [interested] in researching spells.


else



**Synthan says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `interested`



if **Faction** >= Indifferent then



>**Synthan says:** I have several copies of each book. If you want a copy of 'Runes and Research', volume I or II, bring me a lightstone and I will give you whichever book I have more of at the moment. Bring me a greater lightstone, and I will give you a copy of the 'Concordance of Research.


else



**Synthan says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!

end



## Turn-Ins



local gls =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_507.png" alt="" /> <a
                                href="/item/10400" data-url="10400" class="tooltip-link link">Greater Lightstone</a>}

local ls =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_507.png" alt="" /> <a
                                href="/item/10300" data-url="10300" class="tooltip-link link">Lightstone</a>}


if **Faction** >= Indifferent and (ls > 0)) then 


repeat



>**Synthan says:** A lightstone? Thank you very much. Here is a copy of 'Runes and Research'.



 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18175" data-url="18175" class="tooltip-link link">Runes and Research Volume I</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18176" data-url="18176" class="tooltip-link link">Runes and Research Volume II</a>) (+10000 exp)

 



ls = ls - 1;


until ls == 0



if **Faction** >= Indifferent and (gls > 0)) then 


repeat



>**Synthan says:** A greater lightstone? Thank you very much. Here is a 'Concordance of Research' for you.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_777.png" alt="" /> <a
                                href="/item/17504" data-url="17504" class="tooltip-link link">Concordance of Research</a> (+10000 exp)

 



gls = gls - 1;


until gls == 0

**This NPC *should* return incorrect items given.**


