# Larkon Theardor
## Dialog

**You say:** `hail`



>**Larkon Theardor says:** Greetings! Welcome to the Library of Mechanimagica. You must be a [current member of the Library] or has my [mind begun to slip]?

**You say:** `slip`



if **Faction** >= Amiable then 



>**Larkon Theardor says:** What!!? That was but a joke. I try to make you feel comfortable with a little levity and you proclaim my mind has gone the way of Meldrath's. Well.. enough frivolity. You will do your part to help in the menial tasks of the Collective. Do you want the [clean tasks] or the [dirty tasks]?


elseif( **Faction is** == Indifferent) then



>**Larkon Theardor says:** There is much more you must do for the Library of Mechanimagica before such things can be revealed to you.  Perhaps fetching minotaur horns and returning them to Professor Theardor will earn you membership to the Library of Mechanimagica.


else



>**Larkon Theardor says:** You dare to speak to a member of the Eldritch Collective! You had best leave before you find your soul displaced from your body.


**You say:** `tasks`



if **Faction** >= Amiable then 



>**Larkon Theardor says:** Clean.. Dirty.. It matters not. You have upset me with your rude remarks. You will go to the Steamfont Mountains. There you will find Fodin and tell him I have sent you. He will have a nice tidy task for you. A bath!! Be on your way!


elseif( **Faction is** == Indifferent) then



>**Larkon Theardor says:** There is much more you must do for the Library of Mechanimagica before such things can be revealed to you.  Perhaps fetching minotaur horns and returning them to Professor Theardor will earn you membership to the Library of Mechanimagica.


else



>**Larkon Theardor says:** You dare to speak to a member of the Eldritch Collective! You had best leave before you find your soul displaced from your body.


**You say:** `current member of the library`



if **Faction** >= Amiable then 



>**Larkon Theardor says:** Good. The last thing a member of the Eldritch Collective needs is to lose his mind. Look what happened to Meldrath. Enough chitchat. I am Larkon and it is not my job to teach you. It is my job to direct you to service. We require items and such to complete our studies. We need someone of moderate skill to [gather minotaur horns] and [collect basilisk tongues].


elseif( **Faction is** == Indifferent) then



>**Larkon Theardor says:** There is much more you must do for the Library of Mechanimagica before such things can be revealed to you.  Perhaps fetching minotaur horns and returning them to Professor Theardor will earn you membership to the Library of Mechanimagica.


else



>**Larkon Theardor says:** You dare to speak to a member of the Eldritch Collective! You had best leave before you find your soul displaced from your body.


**You say:** `gather minotaur horns`



if **Faction** >= Amiable then 



>**Larkon Theardor says:** We magicians require the horns of minotaurs. We crush them down and use the powder in many of our tests. Go and fetch two minotaur horns. Do not return empty-handed. I await your return as does your reward.


elseif( **Faction is** == Indifferent) then



>**Larkon Theardor says:** There is much more you must do for the Library of Mechanimagica before such things can be revealed to you.  Perhaps fetching minotaur horns and returning them to Professor Theardor will earn you membership to the Library of Mechanimagica.


else



>**Larkon Theardor says:** You dare to speak to a member of the Eldritch Collective! You had best leave before you find your soul displaced from your body.


**You say:** `basilisk tongues`



if **Faction** >= Amiable then 



>**Larkon Theardor says:** Very good of you. Go beyond the land of the gnomes and seek out basilisks. Return four of their tongues to me and I shall share the knowledge of the magicians of the Eldritch Collective.


elseif( **Faction is** == Indifferent) then



>**Larkon Theardor says:** There is much more you must do for the Library of Mechanimagica before such things can be revealed to you.  Perhaps fetching minotaur horns and returning them to Professor Theardor will earn you membership to the Library of Mechanimagica.


else



>**Larkon Theardor says:** You dare to speak to a member of the Eldritch Collective! You had best leave before you find your soul displaced from your body.


**You say:** `kaladim`



if **Faction** >= Amiable then 



>**Larkon Theardor says:** We need someone to venture to the dwarven kingdom of Kaladim and speak with Myre of Miner's Guild 628. She has a delivery of special pestles made from bozinite. If you feel up to it, go to her and tell her you are from the Eldritch Collective and desire the bozinite pestles. Return them to me.


elseif( **Faction is** == Indifferent) then



>**Larkon Theardor says:** There is much more you must do for the Library of Mechanimagica before such things can be revealed to you.  Perhaps fetching minotaur horns and returning them to Professor Theardor will earn you membership to the Library of Mechanimagica.


else



>**Larkon Theardor says:** You dare to speak to a member of the Eldritch Collective! You had best leave before you find your soul displaced from your body.

end

## Turn-Ins



local text = "I will require two minotaur horns for further studies.";

local text1 = "I believe I called for FOUR basilisk tongues.";



if **Faction** >= Apprehensive and  **You turn in:** [Minotaur Horn](/item/13077), [Minotaur Horn](/item/13077)) then 


>**Larkon Theardor says:** Fine work. You have earned the respect of the Library. Here is a small token of our appreciation. We shall have this ground down as soon as we find someone to go to Kaladim.


* __Faction:__ [Eldritch Collective](/faction/245) (20)



* __Faction:__ [Dark Reflection](/faction/238) (-3)



* __Faction:__ [The Dead](/faction/239) (-1)


* __Faction:__ [Gem Choppers](/faction/255) (3)



* __Faction:__ [King Ak`Anon](/faction/333) (1)



 **You receive:** 0 (+100 exp)

elseif **Faction** >= Amiable and  **You turn in:** [Air Tight Box](/item/13271)) then 


>**Larkon Theardor says:** Whew! What smells of rotting disease? Oh... It's you. I see you've gathered all the diseased livers. I shall have them incinerated in the scrapyard. The only reason we do this is to keep the Dark Reflection from using these components in their black arts. Take this. I hope you use it wisely. Oh, and... take a bath. You stink!


* __Faction:__ [Eldritch Collective](/faction/245) (10)



* __Faction:__ [Dark Reflection](/faction/238) (-1)



* __Faction:__ [The Dead](/faction/239) (-1)


* __Faction:__ [Gem Choppers](/faction/255) (1)



* __Faction:__ [King Ak`Anon](/faction/333) (1)



 **You receive:**  [Turquoise](/item/10017) (+100 exp)

elseif **Faction** >= Amiable and  **You turn in:** [Basilisk Tongue](/item/12160), [Basilisk Tongue](/item/12160), [Basilisk Tongue](/item/12160), [Basilisk Tongue](/item/12160)) then 


>**Larkon Theardor says:** Very very good! I can use these in some of our experiments. These tongues are hard to come by and more than a few of our scouts have been turned to stone because of these creatures, but I'm sure you found that out by now, eh?


* __Faction:__ [Eldritch Collective](/faction/245) (10)



* __Faction:__ [Dark Reflection](/faction/238) (-1)



* __Faction:__ [The Dead](/faction/239) (-1)


* __Faction:__ [Gem Choppers](/faction/255) (1)



* __Faction:__ [King Ak`Anon](/faction/333) (1)



 **You receive:** eq.ChooseRandom( [Spell: True North](/item/15205), [Spell: Summon Drink](/item/15211), [Spell: Minor Shielding](/item/15288), [Spell: Flare](/item/15310), [Spell: Summon Dagger](/item/15311), [Spell: Fire Flux](/item/15313), [Spell: Reclaim Energy](/item/15331), [Spell: Summon Food](/item/15050), [Spell: Burst of Flame](/item/15093), [Spell: Elementalkin: Water](/item/15315), [Spell: Elementalkin: Fire](/item/15316), [Spell: Elementalkin: Earth](/item/15058), [Spell: Elementalkin: Air](/item/15317), [Spell: Summon Bandages](/item/15318), [Spell: Gate](/item/15036), [Spell: Burn](/item/15094), [Spell: Lesser Shielding](/item/15246), [Spell: Flame Bolt](/item/15322), [Spell: Eye of Zomm](/item/15323), [Spell: Dimensional Pocket](/item/15325), [Spell: Renew Elements](/item/15851), [Spell: Shock of Blades](/item/15324), [Spell: Shield of Fire](/item/15332), [Spell: Elementaling: Air](/item/15400), [Spell: Elementaling: Fire](/item/15399), [Spell: Elementaling: Water](/item/15398), [Spell: Invisibility](/item/15042), [Spell: Staff of Tracing](/item/15613)) (+100 exp)

elseif **Faction** >= Amiable and  **You turn in:** [Bozinite Pestle](/item/13272)) then 


>**Larkon Theardor says:** The Eldritch Collective thanks you. You have done a great service. We need these special bozinite pestles for use with our eldritch mortars. Here is a scroll from our library. Study it and use it wisely.


* __Faction:__ [Eldritch Collective](/faction/245) (10)



* __Faction:__ [Dark Reflection](/faction/238) (-1)



* __Faction:__ [The Dead](/faction/239) (-1)


* __Faction:__ [Gem Choppers](/faction/255) (1)



* __Faction:__ [King Ak`Anon](/faction/333) (1)



 **You receive:** eq.ChooseRandom( [Spell: Elementaling: Air](/item/15400), [Spell: Elementaling: Fire](/item/15399), [Spell: Elementaling: Water](/item/15398), [Spell: Elementaling: Earth](/item/15397)) (+100 exp)

**This NPC *should* return incorrect items given.**
