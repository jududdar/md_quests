# Brona Frugrin



[Brona Frugrin](/npc/56114) is a level 35 Gnome Enchanter that spawns in [Steamfont Mountains](/zone/56).





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



if( **Faction is** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1129.png" alt="" /> <a
                                href="/item/10170" data-url="10170" class="tooltip-link link">Evil Eye Lens</a>) then


>**Brona Frugrin says:** Not only did you find Borxx but you were able to slay her as well?! You are truly a champion of great skill. This lens of Borxx's will greatly aid our research of other planes of existence. I have been authorized by the Eldritch Collective to offer you this Staff of the Observers. Carry it with pride.


Your faction standing with [Eldritch Collective](/faction/245) got better (<span class='text-success'>+15</span>)


Your faction standing with [Dark Reflection](/faction/238) got worse (<span class='text-danger'>-2</span>)


Your faction standing with [The Dead](/faction/239) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Gem Choppers](/faction/255) got better (<span class='text-success'>+2</span>)


Your faction standing with [King Ak`Anon](/faction/333) got better (<span class='text-success'>+2</span>)





 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_602.png" alt="" /> <a
                                href="/item/10171" data-url="10171" class="tooltip-link link">Staff of the Observers</a> (+100 exp)

 

**This NPC *should* return incorrect items given.**







