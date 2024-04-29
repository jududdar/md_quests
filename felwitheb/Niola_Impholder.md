# Niola Impholder
## Dialog

**You say:** `hail`



if **Faction** >= Indifferent then




>**Niola Impholder says:** Greetings, Soandso. Welcome to the home of the Keepers of the Art. I am in need of spell components. Would you be willing to [fetch] some for me?


else



**Niola Impholder says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `fetch`



if **Faction** >= Indifferent then




>**Niola Impholder says:** What I need are some bat wings for a spell I am researching. If you bring me back four bat wings, I would be willing to reward you with a scroll.


else



**Niola Impholder says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!

end

## Turn-Ins




if **Faction** >= Indifferent and  **You turn in:**  { [Bat Wing](/item/13068)}, 4) > 0


>**Niola Impholder says:** Ah yes.  These are exactly what I need.  Thank you very much.


* __Faction:__ [Keepers of the Art](/faction/275) (2)


* __Faction:__ [King Tearis Thex](/faction/279) (1)


* __Faction:__ [Faydarks Champions](/faction/246) (1)


* __Faction:__ [The Dead](/faction/239) (-1)





 **You receive:** eq.ChooseRandom( [Spell: Flare](/item/15310), [Spell: Flare](/item/15310), [Spell: Flare](/item/15310), [Spell: Flare](/item/15310), [Spell: Flare](/item/15310), [Spell: Flare](/item/15310), [Spell: Flare](/item/15310), [Spell: Flare](/item/15310), [Spell: Flare](/item/15310), [Spell: Shield of Fire](/item/15332)) (+10 exp)

elseif( **You turn in:** [An Enrollment Letter](/item/18777)) then 


>**Niola Impholder says:** Welcome. I am Niola Impholder. Master Magician of the Keepers of the Art. Here is our guild tunic. You have much to learn, so let's get started.


* __Faction:__ [Keepers of the Art](/faction/275) (100)


* __Faction:__ [King Tearis Thex](/faction/279) (25)


* __Faction:__ [Faydarks Champions](/faction/246) (15)


* __Faction:__ [The Dead](/faction/239) (-25)


 **You receive:**  [Faded Training Robe*](/item/13592) (+20 exp)

elseif( **You turn in:** [A Torn Drawing](/item/18902)) then


>**Niola Impholder says:** What? Not as supposed? What can he... Well, that's all well and good. You, I assume, wish a reward for your 'valiant work'? Well, here you go, adventurer.


 **You receive:**  [Gossamer Robe](/item/1307) (+500 exp)

**This NPC *should* return incorrect items given.**
;

