# Renux Herkanor
## Dialog

**You say:** `hail`



>**Renux Herkanor says:** You need something, or are you just browsing?

**You say:** `knargon`



>**Renux Herkanor says:** Heh. Knargon is one of our expendables. And if he keeps up his trash, he'll find my dagger in his back...  whether Hanns likes it or not.

**You say:** `who.* carson`



>**Renux Herkanor says:** Hmm. Maybe you should ask someone else and quit annoying me.

**You say:** `about stanos`



>**Renux Herkanor says:** What? <she looks shaken> I see it is time to make my choices. Forget you mentioned that name, Soandso. Leave me.


e.self:DoAnim(12);

**You say:** `Lomarc`



if **Faction** >= Indifferent +50 then 



>**Renux Herkanor says:** Lomarc? He's a small time smuggler who runs from here to Odus. He got sloppy on his last run, and now the guards are on to him. We need to have someone [meet him behind the Mermaid's Lure] tonight to pick up a package.


elseif **Faction** >= Indifferent then



>**Renux Herkanor says:** The Circle has recognized your deeds and contributions, but I think you need to prove your worth to us a little more.


else



>**Renux Herkanor says:** Heh...  With all you've done, I'm surprised you're still alive.





**You say:** `him.* mermaid`



if **Faction** >= Indifferent +50 then



>**Renux Herkanor says:** Hmm, you think you can handle it? Eh, Lomarc is nothing but a two-bit smuggler anyway. Take this payment to him for the package, and don't let him give you any grief. Got it?



**You receive:**  [Lomarc's Payment](/item/18793)


elseif **Faction** >= Indifferent then



>**Renux Herkanor says:** The Circle has recognized your deeds and contributions, but I think you need to prove your worth to us a little more.


else



>**Renux Herkanor says:** Heh...  With all you've done, I'm surprised you're still alive.




end

## Turn-Ins



if **Faction** >= Indifferent +40 and  **You turn in:** [Kerran Doll](/item/13716)


>**Renux Herkanor says:** Yes, I see you aim to please. I hope you gave Lomarc the payment he deserved? Heh, that punk had no idea of the value of this shipment. The emerald inside this doll will fetch a pretty penny from those greedy merchants.





* __Faction:__ [Circle of Unseen Hands](/faction/223) (30)




* __Faction:__ [Merchants of Qeynos](/faction/291) (-4)



* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (4)




* __Faction:__ [Guards of Qeynos](/faction/262) (-4)



* __Faction:__ [Kane Bayle](/faction/273) (4)




 **You receive:** 0 (+1000 exp)

**This NPC *should* return incorrect items given.**

## Arrive at Waypoint Script

if(e.wp == 3) then


>**Renux Herkanor says:** When is Lomarc getting back from Odus? He was supposed to be back three nights ago. Have you heard anything?


**Signaled to:**  [Hanns Krieghor](/npc/2074)

elseif(e.wp == 4) then


>**Renux Herkanor says:** Hanns, you are not going to want to hear this, but one of our boys in Donovan's gang swears he saw Stanos in the Karanas a week ago. And we still haven't cornered Malka Rale.


**Signaled to:**  [Hanns Krieghor](/npc/2074)
end

## Signals

if(e.signal == 1) then


>**Renux Herkanor says:** Ok, I'll send someone out to meet [Lomarc] behind the [Mermaid's Lure] tonight.

elseif(e.signal == 2) then


>**Renux Herkanor says:** Very well, Father is as good as dead. Did I ever mention that I really hate family reunions? <chuckle>. I am gone!
end


