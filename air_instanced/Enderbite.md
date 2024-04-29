# Enderbite
## On NPC Spawn

**Set a timer** named *depop* for 300 seconds
## Dialog

**You say:** `hail`



>**Enderbite says:** Great, let us waste no more time! I have three tests from which you can choose from. They are Disillusion, Memorization, and Incapacitation.

**You say:** `disillusion`



>**Enderbite says:** Disillusion it is.  Proceed upward through the sky and return to me a harpy statuette, a black nebulous sapphire, and an adamantium earring.  This will prove your abilities to me and I will reward you with an Earring of Displacement.

**You say:** `memorization`



>**Enderbite says:** Memorization it is.  Proceed upward through the sky and return to me a carmine spiroc feather, some ganoric poison, and a glowing necklace.  This will prove your abilities to me and I will reward you with a Necklace of Whispering Winds.

**You say:** `incapacitation`



>**Enderbite says:** Incapacitation it is.  Proceed upward through the sky and return to me an efreeti wind staff, some sweet nectar, a black sky diamond, and a large sky sapphire.  This will prove your abilities to me and I will reward you with the Rod of the Protecting Winds.
end

## Turn-Ins



if( **You turn in:** [Adamantium Earring](/item/20774), [Harpy Statuette](/item/20952), [Black Nebulous Sapphire](/item/20773)) then 


>**Enderbite says:** Good. Take this as your reward.


 **You receive:**  [Earring of Displacement](/item/14559) (+100000 exp)


**Enderbite despawns.**

elseif( **You turn in:** [Carmine Spiroc Feather](/item/20959), [Ganoric Poison](/item/20775), [Glowing Necklace](/item/20776)) then 


>**Enderbite says:** Good. Take this as your reward.


 **You receive:**  [Necklace of Whispering Winds](/item/14558) (+100000 exp)


**Enderbite despawns.**

elseif( **You turn in:** [Black Sky Diamond](/item/20777), [Efreeti Wind Staff](/item/20779), [Large Sky Sapphire](/item/20778), [Sweet Nectar](/item/20966)) then 


>**Enderbite says:** Good. Take this as your reward.


 **You receive:**  [Rod of the Protecting Winds](/item/27711) (+100000 exp)


**Enderbite despawns.**

**This NPC *should* return incorrect items given.**

## Timer(s)

**Stop timer** named *depop*

**Enderbite despawns.**



