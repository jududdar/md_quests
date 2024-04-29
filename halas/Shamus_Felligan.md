# Shamus Felligan

## Dialog

**You say:** `Hail`



>**Shamus Felligan says:** Greetin's! Justice speaks through us. We're the followers o' the Tribunal. We act as judge. jury and executioner fer all misled Northmen. Sometimes we must also execute our swift justice upon evil races. such as th' [ice goblins].

**You say:** `ice goblins`



>**Shamus Felligan says:** The ice goblins are a weak race. They pose no threat to our community. but lately we've heard rumors of ice goblins that can cast spells. They're said to be as weak as the goblin warriors. so I seek to employ the talents of our young shamans to [hunt the goblin casters].

**You say:** `hunt the goblin casters`



if( **Faction is** > Indifferent) then 



>**Shamus Felligan says:** Aye. ye'll serve justice. I must find the source o' their recent spellcasting ability. I hear reports o' glowing necklaces upon these wicked beasts' necks. Get me one o' these casters' necklaces. Return them in any condition at all. Go! Justice awaits yer return.


elseif( **Faction is** == Indifferent) then



>**Shamus Felligan says:** Ye're no criminal to the Shamans o' Justice, but ye've yet to prrove yer devotion to justice.


elseif( **Faction is** < Indifferent) then





>**Shamus Felligan says:** The scales o' the Shamans o' Justice dinnae tip in yer favor. Ye'd best flee while ye still have the chance.

end

## Turn-Ins



if( **Faction is** > Indifferent and  **You turn in:** [Shattered Caster Beads](/item/13968)) then 


>**Shamus Felligan says:** Shattered! This has happened frequently! These beads are very delicate. They're useless to me now, however, I'll reward ye fer the execution of yet more goblin casters. Continue yer work. The Tribunal watches ye!





* __Faction:__ [Shamen of Justice](/faction/327) (10)

















* __Faction:__ [Merchants of Halas](/faction/328) (1)

















* __Faction:__ [Circle of Unseen Hands](/faction/223) (-1)

















* __Faction:__ [Coalition of Tradefolk Underground](/faction/336) (-1)

















* __Faction:__ [Ebon Mask](/faction/244) (-2)



















 **You receive:** eq.ChooseRandom( [Spell: Drowsy](/item/15270), [Spell: Frost Rift](/item/15275), [Spell: Sicken](/item/15075), [Spell: Fleeting Fury](/item/15271), [Spell: Spirit of Bear](/item/15279), [Spell: Cure Blindness](/item/15212), [Spell: Spirit Sight](/item/15079), [Spell: Summon Food](/item/15050), [Spell: Endure Fire](/item/15224), [Spell: Gate](/item/15036)) (+1600 exp)

elseif( **Faction is** > Indifferent and   **You turn in:** [Caster Beads](/item/13969)) then



>**Shamus Felligan says:** Finally! Intact! This IS good news! I can continue me investigation now. As fer yer loyal deed, I'll offer ye this, the Gavel of Justice. May ye employ it well in the service o' justice.





* __Faction:__ [Shamen of Justice](/faction/327) (25)

















* __Faction:__ [Merchants of Halas](/faction/328) (3)

















* __Faction:__ [Circle of Unseen Hands](/faction/223) (-3)

















* __Faction:__ [Coalition of Tradefolk Underground](/faction/336) (-3)

















* __Faction:__ [Ebon Mask](/faction/244) (-5)



















 **You receive:**  [Gavel of Justice](/item/6028) (+6400 exp)


**This NPC *should* return incorrect items given.**
