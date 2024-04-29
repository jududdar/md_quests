# Beek Guinders
## Dialog

**You say:** `hail`



>*Beek Guinders waves enthusiastically and says, Hay, ho, there, young " .. e.other:Race() .. "!  I'd love to yak it up with you but I'm a bit busy at the moment, trying to find some [help].*

**You say:** `help`



>**Beek Guinders says:** Well, we're experimenting with some tanning methods but we're running low on supplies. We need to find someone to go out and [gather some things]. Seems no one wants to do an honest day's work any more. I'd do it myself but, errrr, my, uhhh, foot hair has been hurting lately... yes, that's it.

**You say:** `heal`



>**Beek Guinders says:** Hey! That is not my responsibility! Go speak with Hendi Mrubble. She is the one who got stuck with that duty.

**You say:** `gather some thing`



>**Beek Guinders says:** Ahhh, excellent! Okay, first, we'll need a couple of wolf pelts. They don't have to be perfect, completely ruined would work just fine, hehe. I'll also need a black wolf skin and a handful of berries. The berries you should be able to find out in the Thicket. I hear they grow in a small canyon near the lone tower. Hurry, hurry!
end

## Turn-Ins



local text = "Whoooops! I'll need the two ruined wolf pelts along with the berries and black wolf skin before I can reward you, Soandso. Don't dawdle now.";


if( **You turn in:** [A tattered note](/item/18731)) then 


>**Beek Guinders says:** Aye. Welcome. my fur-footed friend. My name is Beek Guinders. and I am guildmaster here at the Chapel of Mischief. Here is our guild tunic. Wear it with pride, as it will set you apart from the crowd.


* __Faction:__ [Priests of Mischief](/faction/300) (100)


* __Faction:__ [Mayor Gubbin](/faction/286) (15)


* __Faction:__ [Guardians of the Vale](/faction/263) (15)


 **You receive:**  [Faded Gold Felt Tunic*](/item/13538) (+20 exp)

elseif( **You turn in:** [Berries](/item/13045), [Ruined Wolf Pelt](/item/13782), [Ruined Wolf Pelt](/item/13782), [Black Wolf Skin](/item/13758)) then 


>**Beek Guinders says:** Hey, great! You found the materials! We'll get to work right away. If you find any more, please come by again. Here's a little something for your troubles, friend.





* __Faction:__ [Priests of Mischief](/faction/300) (3)


* __Faction:__ [Mayor Gubbin](/faction/286) (1)


* __Faction:__ [Guardians of the Vale](/faction/263) (1)


 **You receive:** eq.ChooseRandom( [Spell: Strike](/item/15014), [Spell: Flash of Light](/item/15201), [Spell: Divine Aura](/item/15207), [Spell: Lull](/item/15208), [Spell: Gate](/item/16303)) (+5000 exp)

**This NPC *should* return incorrect items given.**


