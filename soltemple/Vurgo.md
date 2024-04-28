# Vurgo
## Dialog

if **Faction** >= Indifferent then


**You say:** `hail`




>**Vurgo says:** Welcome! I am Vurgo, follower of Solusek Ro and holder of the [harvester] and the [Words of Darkness].


**You say:** `harvester`




>**Vurgo says:** I can forge you one, but you will need to bring me the correct [scythe components].


**You say:** `scythe components`




>**Vurgo says:** The first thing I need is a shadowed scythe from our mortal enemies, the shadowed men.


**You say:** `words of darkness`




>**Vurgo says:** I can scribe for you the Words of Darkness, but you will need to bring me the correct [word components].


**You say:** `word components`




>**Vurgo says:** The first thing that I need is a shadowed book from our mortal enemies, the shadowed men.


else


**Vurgo says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!
end

## Turn-Ins



local text = "Solusek Ro does not believe in half measures.";


if **Faction** >= Indifferent and  **You turn in:** [Shadowed Scythe](/item/5103)


>**Vurgo says:** A shadowed scythe! Well done! The only good shadowed man is a banished one. As the weapons of the shadowed men have a tendency to disappear, I have given you a note to remind me that you have indeed supplied me with a scythe. Give me the note with the following items and I will forge you a harvester: a fungus eye from a mortuary fungus in the Estate of Unrest, a shadowed knife from an island goblin headmaster in the Ocean of Tears and a fire opal. Give me these items, and I will forge for you a harvester.


* __Faction:__ [Temple of Solusek Ro](/faction/415) (1)


* __Faction:__ [Shadowed Men](/faction/416) (-1)


 **You receive:**  [A note](/item/18944) (+500 exp)

elseif **Faction** >= Indifferent and  **You turn in:** [Shadowed Book](/item/10529)


>**Vurgo says:** A shadowed book! Well done! The more banished shadowed men the better. As the items of the shadowed men tend to disappear, I have given you a note to remind me that you have indeed supplied me with a book. Give me the note with the following items, and I will scribe for you Words of Darkness: a book of darkness from the Erudites in the tower by Lake Rathe, a book of frost from the icy goblin in Permafrost Keep and 300 golden coins. Bring me these items, and I will scribe for you the Words of Darkness.


* __Faction:__ [Temple of Solusek Ro](/faction/415) (1)


* __Faction:__ [Shadowed Men](/faction/416) (-1)


 **You receive:**  [A note](/item/18945) (+500 exp)

elseif **Faction** >= Indifferent and  **You turn in:** [A fungus eye](/item/10538), [Fire Opal](/item/10031), [A shadowed knife](/item/7331), [A note](/item/18944)


>**Vurgo says:** My note, a fungus eye, a shadowed knife and gold! All of the necessary components to make a harvester. Well done, adventurer!


* __Faction:__ [Temple of Solusek Ro](/faction/415) (1)


* __Faction:__ [Shadowed Men](/faction/416) (-1)


 **You receive:**  [Harvester](/item/5316) (+1000 exp)

elseif **Faction** >= Indifferent and  **You turn in:** [Book of Darkness](/item/10536), [Book of Frost](/item/10537), [A note](/item/18945),gold = 300


>**Vurgo says:** All of the necessary components for me to scribe the Words of Darkness! Very good, adventurer. Take your tome, you have earned it.


* __Faction:__ [Temple of Solusek Ro](/faction/415) (1)


* __Faction:__ [Shadowed Men](/faction/416) (-1)


 **You receive:**  [Words of Darkness](/item/10527) (+1000 exp)

**This NPC *should* return incorrect items given.**
