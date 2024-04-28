# Brona Frugrin


## Dialog

**You say:** `Hail`



>**Brona Frugrin says:** Well met, Soandso!  What brings you out this way?  Are you interested in becoming an observer?  No, you look like the adventuring type.  The wilds of the Steamfont Mountains is as far as my body goes.  But through my [duties] as an observer, my mind travels the cosmos.

**You say:** `duties`



if( **Faction is** >= Indifferent) then



>**Brona Frugrin says:** Well, I am quite an accomplished enchanter but most of my time now is spent crafting the magical lenses that enable us to see beyond the ceiling of Norrath and into other realms and dimensions.  Say, in your travels have you encountered any [evil eyes]?


else



**Brona Frugrin says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `evil eyes`



if( **Faction is** >= Indifferent) then



>**Brona Frugrin says:** Evil Eyes are dangerous creatures of great magical power. You will know one if you see one. There is a rumor that somewhere on Antonica there lives a powerful Evil Eye by the name of Borxx. I believe that with the Lens from her eye and some expert tinkering I could create a device that will enable me to observe the gods themselves in their native planes. If you were to bring me this lens the Eldrich Collective will reward you greatly.


else



**Brona Frugrin says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!

end

## Turn-Ins



if( **Faction is** >= Indifferent and  **You turn in:** [Evil Eye Lens](/item/10170)


>**Brona Frugrin says:** Not only did you find Borxx but you were able to slay her as well?! You are truly a champion of great skill. This lens of Borxx's will greatly aid our research of other planes of existence. I have been authorized by the Eldritch Collective to offer you this Staff of the Observers. Carry it with pride.


* __Faction:__ [Eldritch Collective](/faction/245) (15)


* __Faction:__ [Dark Reflection](/faction/238) (-2)


* __Faction:__ [The Dead](/faction/239) (-1)


* __Faction:__ [Gem Choppers](/faction/255) (2)


* __Faction:__ [King Ak`Anon](/faction/333) (2)





 **You receive:**  [Staff of the Observers](/item/10171) (+100 exp)

**This NPC *should* return incorrect items given.**







