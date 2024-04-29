# Gardern



## Dialog

if **Faction** >= Indifferent then



**You say:** `Hail`




>**Gardern says:** I am Gardern, listed among the chosen of Solusek Ro.  I hold the lore to the [Staff of Temperate Flux] and the [Weeping Wand] - items coveted by my Wizardly brethren.


**You say:** `staff of temperate flux`




>**Gardern says:** The Staff of Temperate Flux is a boon to those who dabble in the elemental arts, for it can increase the susceptibility of a creature to both fire and cold.  Are you [interested in the staff]?


**You say:** `interested.* staff`




>**Gardern says:** I will craft you a Staff of Temperate Flux, but you must bring me the components which I require to make it.  I will need a Heart of Fire from an Inferno Goblin Wizard in the Caverns of Solusek, a Heart of Frost from a Goblin Wizard in the Caverns of Permafrost, a Rod of Bone from a Stone Skeleton by the shores of Lake Rathe and a Staff of Ro.  Bring me these items, and I will make you your staff.


**You say:** `weeping wand`




>**Gardern says:** The Weeping Wand is a fine item for a Wizard - it can aid as a focus for concentration, and, if needed, be used to parry as well.  Are you [interested in the wand]?


**You say:** `interested.* wand`




>**Gardern says:** I can make you a Weeping Wand, but you will need to bring me certain components.  I will need a Silver Wand from a Silvered Guard in the Temple Cazic Thule, A Bloodblack Wand from the Mountains of Rathe, Twice-Woven Silk from a Faerie Guard in Faydark and a Scepter of Sorrow from the Tomb in Castle Mistmoore.  Bring me these items and I will make for you a Weeping Wand.


else


**Gardern says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!
end

## Turn-Ins



local text = "Solusek Ro does not believe in half measures.";



if **Faction** >= Indifferent and  **You turn in:** [Heart of Fire](/item/10548), [Heart of Frost](/item/10549), [Rod of Bone](/item/10550), [Darkwood Staff](/item/6048)) then


>**Gardern says:** Well done, Soandso - here is the staff of Temperate Flux. Use it with the blessings of the Temple of Solusek Ro.


* __Faction:__ [Temple of Solusek Ro](/faction/415) (10)


* __Faction:__ [Shadowed Men](/faction/416) (-1)


 **You receive:**  [Staff of Temperate Flux](/item/6342) (+1000 exp)

elseif **Faction** >= Indifferent and  **You turn in:** [Bloodblack Wand](/item/10551), [Silver Wand](/item/6338), [Twice-Woven Silk](/item/10557), [A Scepter](/item/14364)) then


>**Gardern says:** Well done, Soandso. Now I will craft your Weeping Wand, as promised.


* __Faction:__ [Temple of Solusek Ro](/faction/415) (10)


* __Faction:__ [Shadowed Men](/faction/416) (-1)


 **You receive:**  [Weeping Wand](/item/6341) (+1000 exp)

elseif **Faction** >= Indifferent and  **You turn in:** [Sapphire](/item/10034), [Sapphire](/item/10034), [Lambent Stone](/item/10000)) then


>**Gardern says:** Here is your prize - a lambent sapphire.


* __Faction:__ [Temple of Solusek Ro](/faction/415) (1)


* __Faction:__ [Shadowed Men](/faction/416) (-1)


 **You receive:**  [Lambent Sapphire](/item/10119) (+1000 exp)
end






