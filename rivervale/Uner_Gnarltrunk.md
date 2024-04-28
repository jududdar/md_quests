# Uner Gnarltrunk
## Dialog

**You say:** `hail`



>**Uner Gnarltrunk says:** Hello there, Soandso. Please watch where you are stepping when you're out in the field.  Nothing is more frustrating than having some fine jumjum ruined by our own careless feet. That reminds me, [Deputy Tagil] still owes us for that jumjum he stomped on the other day!

**You say:** `deputy tagil`



if **Faction** >= Amiable then 



>**Uner Gnarltrunk says:** Deputy Tagil is a fine young halfling who serves the vale well. But the other day, chasing that dirty Nillipuss, he trampled some fresh Jumjum.  He promised to make amends but it must have slipped his mind.  Please take this note to him as a friendly reminder.



**You receive:**  [A Note](/item/18013)


elseif **Faction** >= Indifferent then



>**Uner Gnarltrunk says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Uner Gnarltrunk says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

>Oh look, a talking lump of refuse.  How novel!



end

## Turn-Ins




if **Faction** >= Amiable and  **You turn in:** [Deputy Tagils Payment](/item/13240)


>**Uner Gnarltrunk says:** I knew that Deputy Tagil had simply forgotten. He really is a good young halfling. Here, take this as a small payment for your time.





* __Faction:__ [Storm Reapers](/faction/355) (5)


* __Faction:__ [Mayor Gubbin](/faction/286) (1)


* __Faction:__ [Merchants of Rivervale](/faction/292) (1)


* __Faction:__ [Unkempt Druids](/faction/324) (-1)


 **You receive:** eq.ChooseRandom( [Carrot](/item/13977), [Fishing Pole](/item/13100), [Pine Needles](/item/13083)) (+10 exp)

**This NPC *should* return incorrect items given.**


