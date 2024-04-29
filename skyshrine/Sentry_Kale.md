# Sentry Kale
## Dialog

**You say:** `hail`



>**Sentry Kale says:** Why come you to the home of the kin? Seek a home amongst the kin perhaps? Perhaps if you wish to prove yourself I may have a task for you.

**You say:** `prove`



>**Sentry Kale says:** Very well, it is a minor task, but I am sure you are quite capable. Lately the food supply in the guards' galley has been dwindling. I fear that there are spiders amongst us who are pilfering our food when we do not see. I would ask of you to please seek out and eliminate these vermin for us. Bring their legs back to me and I shall reward you for your effort.
end

## Turn-Ins





if( **You turn in:** [Velium Spider Leg](/item/29080), [Velium Spider Leg](/item/29080), [Velium Spider Leg](/item/29080), [Velium Spider Leg](/item/29080)) then


>**Sentry Kale says:** Excellent work, Soandso. Here is your payment. I will also reward you for any more you bring.


* __Faction:__ [Claws of Veeshan](/faction/430) (5)



* __Faction:__ [Yelinak](/faction/436) (1)



* __Faction:__ [Kromzek](/faction/448) (-2)



if(math.random(1,5) == 1) then



 **You receive:**  [Ring of the Chameleon](/item/29063) 



note = Item not always given.



 **You receive:** 0 (+5000 exp)

**This NPC *should* return incorrect items given.**
