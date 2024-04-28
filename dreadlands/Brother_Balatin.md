# Brother Balatin

## Dialog

**You say:** `hail`



>*Brother Balatin turns toward you. A transparent human face materializes upon the skull. As he speaks the smells of rotted rat corpses rushes into your face. You must fight the urge to vomit. 'What discipline do you [follow]?'*

**You say:** `lost circle`



>**Brother Balatin says:** Then we are one. The rebirth of our circle shall start with you. I have waited decades for your arrival. You should seek the living brothers within Tunaria. When you have earned your garb then you will be ready for the [true drape].

**You say:** `true drape`



>**Brother Balatin says:** Seek the broken flute of our master. Taken from us by the Iksar twins of Vistrei. To me they will come and to me your robe and you will come the dawning of the new brotherhood.
end

## Turn-Ins



local text = "May you have the correct items or lost forever will be all.";




if **You turn in:** [A Metal Pipe](/item/12979), [A Metal Pipe](/item/12980), [Robe of the Lost Circle](/item/12256)


>*Brother Balatin holds his arms out and a fine robe materializes before your eyes. You grab it just in time to see the skeleton fade from existence.*


 **You receive:**  [Robe of the Whistling Fists](/item/12970) 


elseif **You turn in:** [Ancient Thin Flute](/item/12429)


>*Brother Balatin quickly stashes the flute inside of his ribcage, where it joins another. 'If you want the true Flute of Zan-Fi, you'll have to take it from me!'* 


**Spawn NPC:**  [\#Brother Balatin](/npc/86004) at this location.


**Brother Balatin despawns.**

**This NPC *should* return incorrect items given.**





