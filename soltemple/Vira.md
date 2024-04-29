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


if **Faction** >= Indifferent and  **You turn in:** [A Broom](/item/16544), [Cyclops Toes](/item/16543), [Griffon Feathers](/item/16538), [Star Ruby](/item/10032)) then


>**Vira says:** All of the components to make the infamous broom of Trilon!  Well done, adventurer.  As you have proven yourself worthy, I grant you this broom.


* __Faction:__ [Temple of Solusek Ro](/faction/415) (5)


* __Faction:__ [Shadowed Men](/faction/416) (-1)


 **You receive:**  [Broom of Trilon](/item/6360) (+1000 exp)

elseif **Faction** >= Indifferent and  **You turn in:** [Ruby](/item/10035), [Gargoyle Eye](/item/10014), [A Shovel](/item/16545), [Hill Giant Toes](/item/16539)) then 


>**Vira says:** Each of the four items needed to construct the famed Shovel of Ponz!  Very well.  As you have displayed ingenuity, I grant you this shovel.


* __Faction:__ [Temple of Solusek Ro](/faction/415) (5)


* __Faction:__ [Shadowed Men](/faction/416) (-1)


 **You receive:**  [Shovel of Ponz](/item/6361) (+1000 exp)

elseif **Faction** >= Indifferent and  **You turn in:** [A Torch](/item/16546), [Fire Drake Scale](/item/16534), [Fire Emerald](/item/10033), [Fire Giant Toes](/item/16541)) then 


>**Vira says:** All of the pieces of the famous Torch of Alna!  I never thought you would find them all!  As you have displayed courage, I grant you this torch.


* __Faction:__ [Temple of Solusek Ro](/faction/415) (5)


* __Faction:__ [Shadowed Men](/faction/416) (-1)


 **You receive:**  [Torch of Alna](/item/6362) (+1000 exp)


elseif **Faction** >= Indifferent and  **You turn in:** [Ice Giant Toes](/item/16540), [Mermaid Scale](/item/16542), [Sapphire](/item/10034), [A Stein](/item/16547)) then 


>**Vira says:** The four components required for the stein of Ulissa?!  I am impressed!  As you have displayed valor, I grant you this stein.


* __Faction:__ [Temple of Solusek Ro](/faction/415) (5)


* __Faction:__ [Shadowed Men](/faction/416) (-1)


 **You receive:**  [Stein of Ulissa](/item/6363) (+1000 exp)


**This NPC *should* return incorrect items given.**
