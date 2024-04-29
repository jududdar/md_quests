# Rephas
## Dialog

**You say:** `hail`



if **Faction** >= Apprehensive then



>**Rephas says:** Aagggh..  Get away from here..  Go, run..  Far away..  Or I shall call [Karana's] wrath upon you!


else



**Rephas says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `karana`



if **Faction** >= Apprehensive then



>**Rephas says:** Heh!..  Ignorant one!  Begone, and take your stupidity with you!


else



**Rephas says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!

end

## Turn-Ins



local text = "Hey..  wow..  Now THESE are some good, meaty ears..  These will make one great rat ear pie..  Tell ya what, kid..  bring me a few more o' these beauties, and I'll give you my secret recipe for cooking 'em.";


if **Faction** >= Apprehensive and  **You turn in:** [Rat Ears](/item/13072)) then


>**Rephas says:** Ahh yes..  These are a little small, but still some good eating, if you know how to cook 'em of course..   Here ya go, enjoy and may Karana keep your fields lush and green.





* __Faction:__ [Arcane Scientists](/faction/220) (5)


* __Faction:__ [Knights of Truth](/faction/281) (1)


* __Faction:__ [Opal Darkbriar](/faction/296) (-1)


* __Faction:__ [The Freeport Militia](/faction/330) (-1)


 **You receive:**  [Grilled Rat Ears](/item/13719) (+10 exp)

elseif **Faction** >= Apprehensive and  **You turn in:** [Grilled Rat Ears](/item/13719)) then


>**Rephas says:** Wha?..   Ah, I guess it's a bit of an acquired taste..  Oh well, your loss..  Here, take this..  They ain't no ears, but it's the least I could do..   And if ya find any more rat ears, good ol' Rephas here will be glad to take 'em off your hands for ya!





* __Faction:__ [Arcane Scientists](/faction/220) (5)


* __Faction:__ [Knights of Truth](/faction/281) (1)


* __Faction:__ [Opal Darkbriar](/faction/296) (-1)


* __Faction:__ [The Freeport Militia](/faction/330) (-1)


 **You receive:** eq.ChooseRandom( [Tattered Cloth Sandal](/item/1038), [Fish Scales](/item/13076), [Spell: Weaken](/item/15041), [Spell: Lull](/item/15208), [Spell: True North](/item/15205)) (+5 exp)

elseif **Faction** >= Apprehensive and  **You turn in:** [Giant Rat Ear](/item/13050), [Giant Rat Ear](/item/13050), [Giant Rat Ear](/item/13050)) then


>**Rephas says:** Wow!..  How big was the dang varmint that these come off of?!  Bigger'n a ol' grizzly, I bet!  You've earned this, my friend!  It's my own secret recipe for rat ear pie..  sure is tasty, easy to make, and keeps your belly full while you're running about in the hills and such.  Take care, and may Karana keep your path clear and our lakes full.





* __Faction:__ [Arcane Scientists](/faction/220) (5)


* __Faction:__ [Knights of Truth](/faction/281) (1)


* __Faction:__ [Opal Darkbriar](/faction/296) (-1)


* __Faction:__ [The Freeport Militia](/faction/330) (-1)


 **You receive:**  [Rat Ear Pie](/item/18103) (+10 exp)

elseif( **You turn in:** [Assorted Research pg1](/item/27428), [Assorted Research pg2](/item/27429), [Assorted Research pg3](/item/27430)) then


>**Rephas says:** These were the exact pages I was missing. I have been compiling this research for Juegile. It is now finished so please bring this book to him. Thank you!





* __Faction:__ [Arcane Scientists](/faction/220) (10)


* __Faction:__ [Knights of Truth](/faction/281) (2)


* __Faction:__ [Opal Darkbriar](/faction/296) (-1)


* __Faction:__ [The Freeport Militia](/faction/330) (-1)


 **You receive:**  [An Enchanted Book](/item/27431) (+500 exp)

**This NPC *should* return incorrect items given.**

