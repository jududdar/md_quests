# Ghil Starn
## Dialog

**You say:** `hail`



>**Ghil Starn says:** I'm Ghil...  I used to run a small business before I hooked up with [Hanns]. Together, we muscled our competition out of Qeynos. But I'm getting too old for the rough stuff anymore, so I just lay low down here and peddle my goods. Anyway, I gotta get back to work and pack up this shipment for ol' [Denny-boy].

**You say:** `den`



if( **Faction is** >= Indifferent) then 



>**Ghil Starn says:** Den Magason works for ol' [Captain Rohand] down at the Qeynos docks. I need to find someone to take a [package] to him, so it can be shipped to Erudin.


else



**Ghil Starn says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `Hanns`



if( **Faction is** >= Indifferent) then 



>**Ghil Starn says:** Hanns is one of the most ruthless cutthroats I've ever met...  Glad that I work for him, and not on the other side of his blade.


else



**Ghil Starn says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `captain rohand`



>**Ghil Starn says:** Captain Rohand runs the Mermaid's Lure and trades goods with the sea merchants from Odus.

**You say:** `package`



if( **Faction is** >= Indifferent) then 



>**Ghil Starn says:** I need someone to take this package to Den. He'll make sure it goes out on the next ship to Odus. I owe him a small favor, too.. So when you meet up with him, I need you to do whatever you can to help him out. Do a good job.



**You receive:**  [Package for Den](/item/13784)


else



**Ghil Starn says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!

end

## Turn-Ins



if( **Faction is** >= Indifferent and  **You turn in:** [Note for Ghil](/item/18796)) then


>**Ghil Starn says:** Ah, good job, Soandso. It's good to know that I can trust you to get the job done. Here, take this for your efforts. This is a pair of gloves that we hand out to some of our more trusted members. Keep up the good work.





* __Faction:__ [Circle of Unseen Hands](/faction/223) (100)




* __Faction:__ [Merchants of Qeynos](/faction/291) (-15)



* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (15)




* __Faction:__ [Guards of Qeynos](/faction/262) (-15)



* __Faction:__ [Kane Bayle](/faction/273) (10)




 **You receive:**  [Brown Leather Gloves](/item/1049) (+50000 exp)

**This NPC *should* return incorrect items given.**


