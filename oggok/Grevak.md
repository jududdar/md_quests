# Grevak
## Dialog

**You say:** `Hail`



>**Grevak says:** Need new members we do not. Powerful enough are we with Grevak. Still. peons needed. Are you a [new peon] or are you an [outsider]? Speak up!! Fool!! No time Grevak has!!

**You say:** `new peon`



if **Faction** >= Indifferent then




>**Grevak says:** So you think you can be greater than Grevak!! Touch you not and still I can smash you. I am a Greenblood shadowknight!! Peon are you. Peons go to swamps and slay lizardmen. You return with four lizardmen tails and a reward is yours. You return with two lizardman shaman dolls and a great reward is yours.


else



>**Grevak says:** Foe of Greenbloods you are. In two I will rip you. Best if run.


**You say:** `i am an outsider`



>**Grevak says:** Go away or soon your pain will find you.
end

## Turn-Ins



local text = "This enough is not! Two is what Grevak spoke!";




if   **You turn in:** [Lizard Tail](/item/13354), [Lizard Tail](/item/13354), [Lizard Tail](/item/13354), [Lizard Tail](/item/13354)


>**Grevak says:** Now I shall take the lizard tails to shamans I will.  Healing spells will help create. You continue to slay. Continue to be the peon. Continue to live


* __Faction:__ [Green Blood Knights](/faction/261) (10)



* __Faction:__ [Clurg](/faction/228) (5)




* __Faction:__ [Storm Guard](/faction/312) (-1)



* __Faction:__ [Shadowknights of Night Keep](/faction/308) (-1)



 **You receive:** eq.ChooseRandom( [Large Tattered Skullcap](/item/2125), [Large Tattered Mask](/item/2126), [Large Tattered Gorget](/item/2127), [Large Tattered Shoulderpads](/item/2129), [Large Tattered Wristbands](/item/2133), [Large Tattered Gloves](/item/2134), [Large Buckler](/item/9016)) (+500 exp)

elseif **Faction** >= Amiable and  **You turn in:** [Mystic Doll](/item/13367), [Mystic Doll](/item/13367)


>**Grevak says:** A shaman doll! A great knight you some day become. A gift I give to help you on your way. The fight will continue. All hail the Greenbloods!


* __Faction:__ [Green Blood Knights](/faction/261) (10)



* __Faction:__ [Clurg](/faction/228) (5)




* __Faction:__ [Storm Guard](/faction/312) (-1)



* __Faction:__ [Shadowknights of Night Keep](/faction/308) (-1)



 **You receive:** eq.ChooseRandom( [Pickled Lizard](/item/13453), [Rusty Short Sword](/item/5013), [Rusty Axe](/item/5014), [Rusty Two Handed Battle Axe](/item/5025), [Rusty Broad Sword](/item/5016), [Rusty Long Sword](/item/5019), [Rusty Battle Axe](/item/5020), [Rusty Two Handed Sword](/item/5023), [Spell: Siphon Strength](/item/15343), [Spell: Invisibility vs Undead](/item/15235)) (+500 exp)

**This NPC *should* return incorrect items given.**






