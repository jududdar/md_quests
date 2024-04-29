# Centurion Peran
## Dialog

**You say:** `hail`



>**Centurion Peran says:** Hey there, come to take a swim?

**You say:** `mission`



>**Centurion Peran says:** Well, since you are so inquisitive I will tell you.  The orders say to go to Maiden's Eye and investigate reports of Vampyres in the area.  Vampyres!  Are they kidding?!  I am just a Centurion!  I know, I will continue to keep this area secure while you go investigate.  Bring me sufficient proof of their existence in the area.  Four piles of vampyre ashes should cover it.  Well, get going!  This mission isn't going to finish itself.
end

## Turn-Ins





if( **You turn in:** [Vampyre Ashes](/item/2692), [Vampyre Ashes](/item/2692), [Vampyre Ashes](/item/2692), [Vampyre Ashes](/item/2692)) then


>**Centurion Peran says:** Hah! I knew that we could do it! Oh, you can take my weapon for helping me out again. I will just tell the Hand it was lost in battle. I guess that I better take this evidence back to the Hand, right after one more lap!.





* __Faction:__ [Seru](/faction/1483) (5)


 **You receive:** eq.ChooseRandom( [Combine Long Sword](/item/5303), [Combine Two Handed Sword](/item/5304), [Combine Short Sword](/item/5305), [Combine Scimitar](/item/5313), [Combine Warhammer](/item/6303), [Combine Morning Star](/item/6311), [Combine Great Staff](/item/6312), [Combine Dagger](/item/7300), [Combine Spear](/item/7301), [Combine Rapier](/item/7311), [Combine Gladius](/item/7499)) (+5000 exp)

elseif( **You turn in:** [Perans Orders](/item/6514)) then


>**Centurion Peran says:** Bah, why do I always get stuck with the hard jobs. Here I am, out here patrolling the area in all this danger! They send me to even more threatening conditions? The life of a soldier is a hard one I tell ya! Oh well, off to do these orders I suppose. A shame no one will help me I am sure there is fame and fortune in the [mission]. More for me I suppose.

**This NPC *should* return incorrect items given.**
