# Tarker Blazetoss
## Dialog

**You say:** `hail`



if **Faction** >= Indifferent then




>**Tarker Blazetoss says:** Hail and well met, Soandso!  Have you come to study, or can you [perform a task] for me this day?


else



**Tarker Blazetoss says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `perform a task`



if **Faction** >= Indifferent then




>**Tarker Blazetoss says:** That is the spirit.  There are many black wolves wandering Faydark these days.  One of my brethren needs a black wolf skin as a component for his magic.  Bring me a black wolf skin, and I shall reward you for your efforts.


else



**Tarker Blazetoss says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!

end

## Turn-Ins




if **You turn in:** [An Enrollment Letter](/item/18779)


>**Tarker Blazetoss says:** Welcome to the wizards' guild of the Keepers of the Art. My name's Tarker, and I run this guild. You've got a lot of training ahead of you, so let's get started. Here, take this - it's our guild tunic. Wear it with honor, friend.


* __Faction:__ [Keepers of the Art](/faction/275) (100)


* __Faction:__ [King Tearis Thex](/faction/279) (25)


* __Faction:__ [Faydarks Champions](/faction/246) (15)


* __Faction:__ [The Dead](/faction/239) (-25)


 **You receive:**  [Singed Training Robe*](/item/13594) (+20 exp)

elseif **Faction** >= Indifferent and  **You turn in:** [Black Wolf Skin](/item/13758)


>**Tarker Blazetoss says:** This is just what I needed.. and with hardly a mark on it! You have my thanks. Here is a something that you might find useful.


* __Faction:__ [Keepers of the Art](/faction/275) (1)


* __Faction:__ [King Tearis Thex](/faction/279) (1)


* __Faction:__ [Faydarks Champions](/faction/246) (1)


* __Faction:__ [The Dead](/faction/239) (-1)


 **You receive:** eq.ChooseRandom( [Rusty Dagger](/item/7007), [Bandages](/item/13009), [Worn Great Staff](/item/6012), [Spell: Numbing Cold](/item/15374), [Copper Band](/item/10004), [Cracked Staff](/item/6018), [Gold Ring](/item/10008)) (+350 exp)

**This NPC *should* return incorrect items given.**
;

