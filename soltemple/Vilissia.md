# Vilissia
## Dialog

if **Faction** >= Indifferent then



**You say:** `hail`




>**Vilissia says:** I am Vilissia, chosen of Solusek Ro.  I am a practitioner in the wizardly arts, and keeper of lore for the [runescale cloak], [Tishan's kilt] and the [acumen mask].


**You say:** `runescale cloak`




>**Vilissia says:** The Runescale cloak is a wonderful item of defense for any wizard.  Are you [interested] in the [cloak]?


**You say:** `interested.* cloak`




>**Vilissia says:** I can assemble for you a runescale cloak, but I will need you to bring me the necessary components.  I will need a lizardscale cloak from the temple of Cazic-Thule and the three Runes of Scale.  All three can be found on crocodiles - saltwater crocodiles in the caverns of Guk, deepwater crocodiles in the Oasis of Marr and firescale crocodiles in the mountains of Lavastorm.  Bring me these items, and I will make you a runescale cloak.


**You say:** `acumen mask`




>**Vilissia says:** The acumen mask, as its name suggests, confers to its wearer certain powers of insight and knowledge.  Are you [interested] in obtaining a [mask]?


**You say:** `interested.* mask`




>**Vilissia says:** I can make an acumen mask for you, but you will need to bring me the proper components.  I will need a glowing mask from a skeletal monk in the caverns of Guk, a patch of Shadow from our mortal enemies, the shadowed men, a darkbone Skull from a darkbone skeleton in the Estate of Unrest, and a bonechipped mask from a goblin headmaster in the Ocean of Tears.  Bring me these four items, and I will make for you an acumen mask.


**You say:** `tishan.* kilt`




>**Vilissia says:** Tishan was once counted among the mightiest of wizards, and his items are items of power.  If you are interested in acquiring Tishan's kilt, you must take a shadowed ball from our mortal enemies, the shadowed men, and bring it to Trankia in the Everfrost Mountains.


else


**Vilissia says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!
end

## Turn-Ins



local text = "Solusek Ro does not believe in half measures.";


if **Faction** >= Indifferent and  **You turn in:** [Glowing Mask](/item/2352), [Bonechipped Mask](/item/2367), [Patch of Shadow](/item/2368), [Darkbone Skull](/item/10558)


>**Vilissia says:** Mask, patch, skull and mask. All of the items necessary for me to make an acumen mask.  Excellent.  All praise Solusek Ro!


* __Faction:__ [Temple of Solusek Ro](/faction/415) (10)


* __Faction:__ [Shadowed Men](/faction/416) (-1)


 **You receive:**  [Acumen Mask](/item/2366) (+1000 exp)

elseif **Faction** >= Indifferent and  **You turn in:** [Lambent Stone](/item/10000), [Ruby](/item/10035), [Ruby](/item/10035)


e.other:Say("Here is your prize - a lambent ruby.");


* __Faction:__ [Temple of Solusek Ro](/faction/415) (1)


* __Faction:__ [Shadowed Men](/faction/416) (-1)


 **You receive:**  [Lambent Ruby](/item/10118) (+1000 exp)

elseif **Faction** >= Indifferent and  **You turn in:** [Lizardscale Cloak](/item/2332), [Rune of Scale](/item/10553), [Rune of Scale](/item/10554), [Rune of Scale](/item/10555)


e.other:Say("You impress me, adventurer! I had not expected you to return with all of the runes. Very well, I shall keep my half of the bargain. Here is your Runescale Cloak.");


* __Faction:__ [Temple of Solusek Ro](/faction/415) (10)


* __Faction:__ [Shadowed Men](/faction/416) (-1)


 **You receive:**  [Runescale Cloak](/item/2364) (+1000 exp)

elseif **Faction** >= Indifferent and  **You turn in:** [Enchanted Platinum Bar](/item/16507)


e.other:Say("I see that Gavel has sent you to me.  Very well, I have vulcanized your platinum bar - take it.");


 **You receive:**  [Vulcanized Platinum Bar](/item/19048) (+1000 exp)


**This NPC *should* return incorrect items given.**
