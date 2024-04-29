# Trooper Inkin
## Dialog

**You say:** `hail`



>**Trooper Inkin says:** Many frogloks in here. Beware! They can be a sneaky bunch. I hear tales of a froglok village nearby.

**You say:** `sign the restraining order`



>**Trooper Inkin says:** I have been expecting this. Oh, well... Can't argue with the Baron or he will have both our heads. Keeping that in mind, I will make you a deal. I will sign the order if you bring me one of those grand skipping stones these Frogloks are said to have. Bring me the stone and the order and I shall sign.
end

## Turn-Ins



local text = "No deal! You bring me the legion order and the froglok skipping stone.";



if( **You turn in:** [Legion Order](/item/18243), [Skipping Stone](/item/12425)) then 


>**Trooper Inkin says:** So smooth. I shall be the skipping stone champion! Here. You may have my autograph.


 **You receive:**  [Legion Order](/item/18244) (+500 exp)

**This NPC *should* return incorrect items given.**
