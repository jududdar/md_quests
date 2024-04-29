# Cryssia Stardreamer


## Dialog

if **Faction** >= Indifferent then



**You say:** `hail`




>**Cryssia Stardreamer says:** Well met Soandso. I am Cryssia Stardreamer of the Temple of Solusek Ro, protector of a powerful armor that will aid any bard in their journey across Norrath.  Are you a bard that desires this armor?


**You say:** `no`




>**Cryssia Stardreamer says:** Very well then.


**You say:** `yes`




>**Cryssia Stardreamer says:** Very well. I can craft a special type of bardic armor called lambent.  I can craft for you a set of [bracers], a [breastplate], a [helm], and [vambraces]. I require a special kind of lambent stone for each of my armor pieces.  Find my friends Orstorm, Genni, Gardern, and Vilissia within the temple and they will help you create them.


**You say:** `bracers`




>**Cryssia Stardreamer says:** Alright, I will be needing some items. Return to me with them and I will craft your bracers. I will be needing a Dark Boned Bracelet, a Griffenne Charm, and a Lambent Fire Opal.


**You say:** `breastplate`




>**Cryssia Stardreamer says:** This is the most difficult piece to make. In order for me to craft it I will be needing a Basalt Carapace, a Consortium Lute, and a Lambent Ruby. Return to me with these and I will craft your breastplate.


**You say:** `helm`




>**Cryssia Stardreamer says:** In order to craft the helm, I will be needing a Mudwater Rune, an Opoline Helm, and a Lambent Star Ruby. Give these items to me and I will craft your helm


**You say:** `vambraces`




>**Cryssia Stardreamer says:** Very good, get me some Fiery Vambraces, the top portion of the Rune of the One Eye, and a Lambent Sapphire.


else


**Cryssia Stardreamer says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!
end

## Turn-Ins



local text = "Wait, Soandso, are you not forgetting something?";


if **Faction** >= Indifferent and  **You turn in:** [Dark Boned Bracelet](/item/10564), [Griffenne Charm](/item/10563), [Lambent Fire Opal](/item/10128)) then


>**Cryssia Stardreamer says:** Good show, Soandso, here is your lambent bracer


* __Faction:__ [Temple of Solusek Ro](/faction/415) (10)


* __Faction:__ [Shadowed Men](/faction/416) (-1)


 **You receive:**  [Lambent Bracers](/item/4156) (+1000 exp)

elseif **Faction** >= Indifferent and  **You turn in:** [Basalt Carapace](/item/4100), [Consortium Mandolin](/item/10565), [Lambent Ruby](/item/10118)) then


>**Cryssia Stardreamer says:** Exceptionally well done, Soandso, here is your lambent breastplate. Wear it with pride.


* __Faction:__ [Temple of Solusek Ro](/faction/415) (10)


* __Faction:__ [Shadowed Men](/faction/416) (-1)


 **You receive:**  [Lambent Breastplate](/item/4154) (+1000 exp)

elseif **Faction** >= Indifferent and  **You turn in:** [Mudwater Rune](/item/10559), [Opoline Helm](/item/4099), [Lambent Star Ruby](/item/10117)) then


>**Cryssia Stardreamer says:** Well done, Soandso, here is your lambent helm. Wear it with the praises of the League of Antonican Bards.


* __Faction:__ [Temple of Solusek Ro](/faction/415) (10)


* __Faction:__ [Shadowed Men](/faction/416) (-1)


 **You receive:**  [Lambent Helm](/item/4153) (+1000 exp)

elseif **Faction** >= Indifferent and  **You turn in:** [Fiery Vambraces](/item/4113), [Rune of the One Eye](/item/10560), [Lambent Sapphire](/item/10119)) then


>**Cryssia Stardreamer says:** Excellent, Soandso, you have proved yourself most resourceful. Here are your lambent vambraces.


* __Faction:__ [Temple of Solusek Ro](/faction/415) (10)


* __Faction:__ [Shadowed Men](/faction/416) (-1)


 **You receive:**  [Lambent Vambraces](/item/4155) (+1000 exp)

**This NPC *should* return incorrect items given.**





