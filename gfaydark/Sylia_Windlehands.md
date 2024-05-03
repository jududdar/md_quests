# Sylia Windlehands


## Dialog

**You say:** `hail`



>**Sylia Windlehands says:** Salutations! The Song Weavers are always glad to add a new voice to the choir.  In addition to your voice. will you also [fetch spiderling silk]?  We need some to replace our worn lute strings.  Carry out this task in high tempo and we will show our gratitude.

**You say:** `spiderling silk`



if **Faction** >= Amiable then



>**Sylia Windlehands says:** Very spirited of you!!  Gather four spiderling silk and return them to me.  Good hunting. my friend!!


elseif **Faction** >= Indifferent then



>**Sylia Windlehands says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Sylia Windlehands says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!

end



## Turn-Ins





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18783" data-url="18783" class="tooltip-link link">A tattered note</a>) then 


>**Sylia Windlehands says:** Greetings. friend. I am Sylia.  I see that you wish to join our humble guild.  Good.  Here is a gift for you - your guild tunic.  Let's get started with your training, shall we?


Your faction standing with [Song Weavers](/faction/401) got better (<span class='text-success'>+100</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_678.png" alt="" /> <a
                                href="/item/13534" data-url="13534" class="tooltip-link link">Faded Brown Tunic*</a> (+20 exp)

 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_782.png" alt="" /> <a
                                href="/item/13099" data-url="13099" class="tooltip-link link">Spiderling Silk</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_782.png" alt="" /> <a
                                href="/item/13099" data-url="13099" class="tooltip-link link">Spiderling Silk</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_782.png" alt="" /> <a
                                href="/item/13099" data-url="13099" class="tooltip-link link">Spiderling Silk</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_782.png" alt="" /> <a
                                href="/item/13099" data-url="13099" class="tooltip-link link">Spiderling Silk</a>) then


>**Sylia Windlehands says:** Splendid job! Now if you can just keep a tune, you'll be a fine bard.


Your faction standing with [Song Weavers](/faction/401) got better (<span class='text-success'>+5</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1152.png" alt="" /> <a
                                href="/item/13000" data-url="13000" class="tooltip-link link">Hand Drum</a> (+1000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-5 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**


