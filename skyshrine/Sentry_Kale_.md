# Sentry Kale 
## Dialog

**You say:** `hail`



>**Sentry Kale  says:** Ah, the strangers, I have heard word of you. Why come you to the Skyshrine? Do you wish to be of assistance to the kin? If so, I may have a task, if you are willing.

**You say:** `willing`



>**Sentry Kale  says:** Very well, should you complete this task you will be doing a great service to the kin. As of late our supplies of velium ore have been growing short. We need to restock this supply but our normal source has run dry for the most part.  Word has come to us that the Coldain are sitting on a large source of this ore and while we have no love for these Coldain, we have arranged a deal with one of their velium miners. Deliver this note along with a payment of 50 platinum to Ungdin, in the Coldain mines. Bring the velium shipment back to me and I will see about a reward.


**You receive:**  [Velium Delivery Note](/item/1725)
end

## Turn-Ins



local hammerrew = 0;



if( **You turn in:** [A shipment of Velium Ore](/item/29064)) then


>**Sentry Kale  says:** You have shown us yet again your loyalty to our people. Please accept this token of our gratitude. This velium is badly needed, thank you, Soandso.


* __Faction:__ [Claws of Veeshan](/faction/430) (5)



* __Faction:__ [Yelinak](/faction/436) (1)



* __Faction:__ [Kromzek](/faction/448) (-2)



if(math.random(1,3) == 1) then



 **You receive:**  [Bracer of Hammerfal](/item/1727) 



note = Items not always given



 **You receive:** 0 (+5000 exp)

**This NPC *should* return incorrect items given.**
