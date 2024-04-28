# Seloxia Punox
## Dialog

**You say:** `hail`



>*Seloxia Punox 's eyes flare with fury as her beautiful features twist into a snarl of hatred that echoes her hissing voice, 'How dare you address me in such a fashion?!  I am the leader of the Indigo Brotherhood!!  You are lucky I do not strike you down where you stand!  You shall address me as 'Mistress.'  Many warriors have died so that I might gain this title.'*

**You say:** `mistress`



e.self:Emote("maintains her imposing posture as she indifferently eyes Soandso, 'You stand now in the Cauldron of Hate 

**You say:** `little test`



if **Faction** >= Amiable then



>**Seloxia Punox says:** My little test is this. I desire a report from Ambassador K'Rynn in the Ogre city of Oggok. You shall run to him. I will not wait until you raise your fighting skills. Combat is not your test. Overcoming the odds is. Fast agile warriors are we. We desire nothing less. Will you [venture to Oggok]?


elseif **Faction** >= Indifferent then



>**Seloxia Punox says:** Go! Return when you have done more to serve the Indigo Brotherhood of Neriak. Fewer Leatherfoot Raiders in Nektulos and a few Leatherfoot skullcaps in the palms of Master Narex shall prove your true warrior nature and loyalty to our house.


else



>**Seloxia Punox says:** Your head will make a fine trophy in the halls of the Indigo Brotherhood.




**You say:** `venture to oggok`



if **Faction** >= Amiable then



>**Seloxia Punox says:** Then you will go at once. Find your own way. Deliver this note to Ambassador K'Rynn and he shall give you the note to return to me. Do not stop to practice your skills. I offer this test to only the young warriors. If you die, then so be it. We need not inferior warriors. Now go!!



**You receive:**  [A Sealed Letter](/item/18842)


elseif **Faction** >= Indifferent then



>**Seloxia Punox says:** Go! Return when you have done more to serve the Indigo Brotherhood of Neriak. Fewer Leatherfoot Raiders in Nektulos and a few Leatherfoot skullcaps in the palms of Master Narex shall prove your true warrior nature and loyalty to our house.


else



>**Seloxia Punox says:** Your head will make a fine trophy in the halls of the Indigo Brotherhood.



end

## Turn-Ins





if **You turn in:** [A tattered note](/item/18751)


>**Seloxia Punox says:** I shall reserve any official welcoming until you have proven yourself a suitable member for the Indigo Brotherhood. That proof shall be obtained by your progression in your training. See Yegek B'Larin, one of my most trusted trainers in the Brotherhood and obey his command carefully if you wish to succeed as a member of the Brotherhood.


* __Faction:__ [Indigo Brotherhood](/faction/270) (100)


* __Faction:__ [Emerald Warriors](/faction/326) (-15)


* __Faction:__ [Steel Warriors](/faction/311) (-5)


* __Faction:__ [Primordial Malice](/faction/1522) (-200)


 **You receive:**  [Old Training Tunic*](/item/13580) (+20 exp)

elseif **Faction** >= Amiable and  **You turn in:** [a sealed letter](/item/18843)


>**Seloxia Punox says:** Very fine work my young warrior. You may soon be ready to become a Teir'Dal courier. For now we shall reward you. This will assist you in further service to the Indigo Brotherhood and King Naythox Thex.


* __Faction:__ [Indigo Brotherhood](/faction/270) (10)


* __Faction:__ [Emerald Warriors](/faction/326) (-1)


* __Faction:__ [Steel Warriors](/faction/311) (-1)


* __Faction:__ [Primordial Malice](/faction/1522) (-20)


 **You receive:** eq.ChooseRandom( [Bronze Short Sword](/item/5026), [Cloth Cap](/item/1001), [Cloth Veil](/item/1002), [Cloth Choker](/item/1003), [Cloth Shirt](/item/1004), [Cloth Shawl](/item/1005), [Rusty Axe](/item/5014), [Rusty Scythe](/item/5015), [Rusty Scimitar](/item/5021), [Bronze Long Sword](/item/5027)) (+250 exp)

**This NPC *should* return incorrect items given.**






