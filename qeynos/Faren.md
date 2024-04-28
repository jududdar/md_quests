# Faren
## On NPC Spawn

**Set a timer** named *fishing* for 300 seconds
## Timer(s)

>**Faren says:** Whoo!!! I think I got a [bite]! Darn.. Seaweed.
## Dialog

**You say:** `hail`



>**Faren says:** Oh.. Hiya, I'm just out here fishing, since I can't find a job. I hope this [bait] I just bought catches me a big ol' fish.

**You say:** `bait`



>**Faren says:** I use Captain Rohand's Secret Recipe Super Magic Catch-A-Lot brand bait. I bought my pole from Sneed's up by the north pond.


**You say:** `tacklebox`



>**Faren says:** Oh. That mean [dwarf], Trumpy, just knocked my tacklebox into the water. Could you please get it for me? I can't swim.


**You say:** `dwarf`



>**Faren says:** His name is Trumpy. He is one of those [Irontoes] I think. I've seen him hanging out in the Fish's Ale. I don't know why he likes to torment me.

**You say:** `irontoe`



>**Faren says:** Ah! The Irontoes are a rough bunch of dwarves from Kaladim. The seem to get quite drunk on a frequent basis.

**You say:** `fishing`



>**Faren says:** Huh?  OH!  Sorry, I was dozing off!  It's been a slow day.  A few fish and an old shoe are all I have reeled in.  I did see a shark swim by, though!

**You say:** `kane`



>**Faren says:** Commander Kane Bayle is the commander of all the Qeynos Guard.  He is second only to his brother, Antonius Bayle.  His post is in the guard house at the city gates.  Mind you, do not bother him, he has a bit of a temper.



**You say:** `circle.* unseen hand`



>**Faren says:** The Circle of the Unseen Hand?  I have heard nothing of them.  Are they some sort of performing magic troupe?
end

## Signals

if(e.signal == 1) then


>**Faren says:** Oh, hi, Beren. Not too good so far. That [dwarf] keeps bothering me, too.


**Signaled to:**  [Guard Beren](/npc/1090)
end

## Turn-Ins



if **You turn in:** [Wooden Fishing Tackle](/item/13702)


>**Faren says:** Thank you so much! If you want some free advice, steer clear of those [Irontoes]! They are nothing but trouble. Here, It's not much but I must thank you somehow.





* __Faction:__ [Guards of Qeynos](/faction/262) (10)


* __Faction:__ [Antonius Bayle](/faction/219) (1)


* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (-1)


* __Faction:__ [Circle of Unseen Hands](/faction/223) (-2)


* __Faction:__ [Merchants of Qeynos](/faction/291) (1)


 **You receive:** None 

**This NPC *should* return incorrect items given.**
