# Trooper Roklon
## Dialog

**You say:** `hail`



>**Trooper Roklon says:** Hail! Beware the giants of the woods. They have a dwelling somewhere out there. Should you stumble upon it, run! Leave the fighting to us.

**You say:** `sign the restraining order`



>**Trooper Roklon says:** I've been ratted out! Very well. I shall sign the order, but first I shall force you to fetch me a set of goblin scout beads. I hear they make fine counters. Bring me the beads and that despicable order and I shall do as instructed.
end

## Turn-Ins



local text = "No, NO! I want the goblin scout beads and the legion order.";



if( **You turn in:** [Legion Order](/item/18247), [Goblin Scout Beads](/item/12672)) then 


>**Trooper Roklon says:** No, NO! I want the goblin scout beads and the legion order.


 **You receive:**  [Legion Order](/item/18248) (+500 exp)

**This NPC *should* return incorrect items given.**
