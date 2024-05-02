# Dirkog Steelhand
## On NPC Spawn

**Set a timer** named *depop* for 300 seconds
## Dialog

**You say:** `hail`



>**Dirkog Steelhand says:** Leave me be, ye orc kissin' son o' Innoruuk!

**You say:** `innoruuk`



>**Dirkog Steelhand says:** Eh? Ye say that ye ain't one o' the cursed dark elf dogs? Well then, laddie, are ye ready to get started or are ye here fer somethin' else??

**You say:** `holy swords`







>**Dirkog Steelhand says:** Eh, lad? What was that? Ye wish to hear o' holy swords? Well, lad, I ain't the one ye be needin' t' talk to!

**You say:** `who do I need to talk to`




>**Dirkog Steelhand says:** A follower o' the water god he be, an' one o' the most powerful holy knights e'er to walk Norrath. His name be Inte Akera, an' he kin tell ye what ye be wantin' t' know.

**You say:** `where is inte akera`





>**Dirkog Steelhand says:** Ah, I see ye wish t' speak with him! Why didn't ye say that earlier, laddie? It would've saved ye some trouble! If ye wish to speak with him, ye must donate some spare change t' me ale.. er, t' me holy crusade fund! Well, lad, what d' ye say?

**You say:** `donate`








>**Dirkog Steelhand says:** Eh? Oh, 500 platinum will be plenty, laddie!

**You say:** `ready.* started`





>**Dirkog Steelhand says:** That's the spirit, laddie!  I only have one test for ye.  Return to me a silvery girdle, a diaphanous globe, and an ivory sky diamond.  In return, I will give ye me girdle.
end

## Turn-Ins





if( **You turn in:** platinum = 500) then


>**Dirkog Steelhand says:** Thank ye, laddie! He's awaitin' ya up top!


**Spawn NPC:**  [Inte Akera](/npc/71091) at (**y:** 767, **x:** -586)


**Dirkog Steelhand despawns.**

if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_947.png" alt="" /> <a
                                href="/item/20943" data-url="20943" class="tooltip-link link">Diaphanous Globe</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/20869" data-url="20869" class="tooltip-link link">Ivory Sky Diamond</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_563.png" alt="" /> <a
                                href="/item/20868" data-url="20868" class="tooltip-link link">Silvery Girdle</a>) then 


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_560.png" alt="" /> <a
                                href="/item/2716" data-url="2716" class="tooltip-link link">Girdle of Faith</a> (+100000 exp)

 


>**Dirkog Steelhand says:** Ye surprised me, Soandso. Wear me girdle with pride!

**This NPC *should* return incorrect items given.**

## Timer(s)

**Stop timer** named *depop*

**Dirkog Steelhand despawns.**




