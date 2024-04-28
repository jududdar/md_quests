# Shazda Asad
## Dialog

if **Faction** >= Dubious then


**You say:** `hail`




>**Shazda Asad says:** Rrrr..I am  Asad. Shazda of the Kerran [Sejah]. It is my duty to ensure the safety of what lands have not been taken from us by the Erudites. and to train my soldiers in the fighting styles of our heritage.


**You say:** `sejah`




>**Shazda Asad says:** The soldiers of our sejah are all trained from the time they are weaned from their matriarchs. If you wish to be honored by the sejah you must prove to us your loyalty and devotion to the defense of our lands. In Toxxulia Forest there are Erudite emissaries who constantly attempt to encroach upon our territory. Bring me the head of one such emissary.


else


**Shazda Asad says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!
end

## Turn-Ins



if **Faction** >= Dubious and  **You turn in:** [Emissary Head](/item/12319)


>**Shazda Asad says:** Excellent work, young ayyar! You have proven your willingness to dispose of the enemies of our tribe, now you must face one of their most murderous sentries! Bring me the head of Sentinel Creot and I shall induct you into our sejah!


* __Faction:__ [Kerra Isle](/faction/382) (20)



 **You receive:**  [Kejaar Totem](/item/10343) (+5000 exp)

elseif **Faction** >= Dubious and  **You turn in:** [Sentinel Creot's Head](/item/12438)


>**Shazda Asad says:** You have proven your devotion to our cause and defeated one of the greatest threats to our people. I welcome you into the Kerran Sejah. Wear this bracer as a symbol of your station in the Kerran tribes.


* __Faction:__ [Kerra Isle](/faction/382) (55)


 **You receive:**  [Sejah Ghulam Bracer](/item/3147) (+6500 exp)

**This NPC *should* return incorrect items given.**






