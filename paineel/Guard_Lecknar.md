# Guard Lecknar



[Guard Lecknar](/npc/75040) is a level 15 Skeleton Warrior that spawns in [Paineel](/zone/75).



## Dialog

if **Faction** >= Amiable then


**You say:** `hail`




>**Guard Lecknar says:** Uggg. You needz [keyz]? Rrrrrrr.


**You say:** `key`




>**Guard Lecknar says:** Uggggg. Take dis keyz.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1078.png" alt="" /> <a
                                href="/item/6378" data-url="6378" class="tooltip-link link">Bone Crafted Key</a>


elseif **Faction** >= Indifferent then


>**Guard Lecknar says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else


**Guard Lecknar says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!
end