# Vira
## Dialog

if **Faction** >= Indifferent then



**You say:** `hail`




>**Vira says:** I am Vira, elementalist of Solusek Ro.  I guard the secrets of the tools of [elemental summoning].  If you are a magician, you might be interested.


**You say:** `elemental summoning`




>**Vira says:** I hold the secets to the construction of four tools which assist magicians with the summoning of elementals.  I know about the [broom of Trilon], the [shovel of Ponz], the [torch of Alna] and the [stein of Ulissa].


**You say:** `shovel of ponz`




>**Vira says:** The shovel of Ponz was crafted by the earthen master of the same name.  Are you [interested] in the [shovel]?


**You say:** `interested.* shovel`




>**Vira says:** I will create a replica of the shovel of Ponz for you, but I will need the following components to make it: a ruby, the eyes of a gargoyle, a shovel from a magician in Najena and the toes of a hill giant.  Bring me these four components, and I will construct for you an object of elemental power.


**You say:** `broom of trilon`




>**Vira says:** The broom of Trilon was held by the infamous Mistress of Air of the same name.  Are you [interested] in the [broom]?


**You say:** `interested.* broom`




>**Vira says:** I will construct a replica of the broom of Trilon for you, but I will need the following components to make it: a star ruby; a feather from a griffon, a broom from a magician in Najena and the toes of a cyclops.  Bring me these four components, and I will fashion for you an object of elemental power.


**You say:** `torch of alna`




>**Vira says:** The torch of Alna was constructed and held by the fire mistress of the same name.  Are you [interested] in the [torch]?


**You say:** `interested.* torch`




>**Vira says:** I will make a replica of the torch of Alna for you, but I will need the following items to make it: a fire emerald, a scale from a fire drake, a torch from a magician in Najena and the toes of a fire giant.  Bring me these four components, and I will build for you an object of elemental power.


**You say:** `stein of ulissa`




>**Vira says:** The stein of Ulissa was found and used by the mistress of water of the same name.  Are you [interested] in the [stein]?


**You say:** `interested.* stein`




>**Vira says:** I will devise a replica of the stein of Ulissa for you, but I will need the following items to make it: a sapphire, a scale from a mermaid, a stein from a magician in Najena and the toes of an ice giant.  Bring me these four components, and I will make for you an object of elemental power.


else


**Vira says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!
end

## Turn-Ins



local text = "Solusek Ro does not believe in half measures.";


if **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_889.png" alt="" /> <a
                                href="/item/16544" data-url="16544" class="tooltip-link link">A Broom</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1094.png" alt="" /> <a
                                href="/item/16543" data-url="16543" class="tooltip-link link">Cyclops Toes</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_909.png" alt="" /> <a
                                href="/item/16538" data-url="16538" class="tooltip-link link">Griffon Feathers</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_961.png" alt="" /> <a
                                href="/item/10032" data-url="10032" class="tooltip-link link">Star Ruby</a>) then


>**Vira says:** All of the components to make the infamous broom of Trilon!  Well done, adventurer.  As you have proven yourself worthy, I grant you this broom.


Your faction standing with [Temple of Solusek Ro](/faction/415) got better (<span class='text-success'>+5</span>)


Your faction standing with [Shadowed Men](/faction/416) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_889.png" alt="" /> <a
                                href="/item/6360" data-url="6360" class="tooltip-link link">Broom of Trilon</a> (+1000 exp)

 

elseif **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_964.png" alt="" /> <a
                                href="/item/10035" data-url="10035" class="tooltip-link link">Ruby</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_943.png" alt="" /> <a
                                href="/item/10014" data-url="10014" class="tooltip-link link">Gargoyle Eye</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_891.png" alt="" /> <a
                                href="/item/16545" data-url="16545" class="tooltip-link link">A Shovel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1094.png" alt="" /> <a
                                href="/item/16539" data-url="16539" class="tooltip-link link">Hill Giant Toes</a>) then 


>**Vira says:** Each of the four items needed to construct the famed Shovel of Ponz!  Very well.  As you have displayed ingenuity, I grant you this shovel.


Your faction standing with [Temple of Solusek Ro](/faction/415) got better (<span class='text-success'>+5</span>)


Your faction standing with [Shadowed Men](/faction/416) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_891.png" alt="" /> <a
                                href="/item/6361" data-url="6361" class="tooltip-link link">Shovel of Ponz</a> (+1000 exp)

 

elseif **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_559.png" alt="" /> <a
                                href="/item/16546" data-url="16546" class="tooltip-link link">A Torch</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1088.png" alt="" /> <a
                                href="/item/16534" data-url="16534" class="tooltip-link link">Fire Drake Scale</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_962.png" alt="" /> <a
                                href="/item/10033" data-url="10033" class="tooltip-link link">Fire Emerald</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1094.png" alt="" /> <a
                                href="/item/16541" data-url="16541" class="tooltip-link link">Fire Giant Toes</a>) then 


>**Vira says:** All of the pieces of the famous Torch of Alna!  I never thought you would find them all!  As you have displayed courage, I grant you this torch.


Your faction standing with [Temple of Solusek Ro](/faction/415) got better (<span class='text-success'>+5</span>)


Your faction standing with [Shadowed Men](/faction/416) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_559.png" alt="" /> <a
                                href="/item/6362" data-url="6362" class="tooltip-link link">Torch of Alna</a> (+1000 exp)

 


elseif **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1094.png" alt="" /> <a
                                href="/item/16540" data-url="16540" class="tooltip-link link">Ice Giant Toes</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_998.png" alt="" /> <a
                                href="/item/16542" data-url="16542" class="tooltip-link link">Mermaid Scale</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_963.png" alt="" /> <a
                                href="/item/10034" data-url="10034" class="tooltip-link link">Sapphire</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_708.png" alt="" /> <a
                                href="/item/16547" data-url="16547" class="tooltip-link link">A Stein</a>) then 


>**Vira says:** The four components required for the stein of Ulissa?!  I am impressed!  As you have displayed valor, I grant you this stein.


Your faction standing with [Temple of Solusek Ro](/faction/415) got better (<span class='text-success'>+5</span>)


Your faction standing with [Shadowed Men](/faction/416) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_708.png" alt="" /> <a
                                href="/item/6363" data-url="6363" class="tooltip-link link">Stein of Ulissa</a> (+1000 exp)

 


**This NPC *should* return incorrect items given.**
