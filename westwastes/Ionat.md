# Ionat
## Dialog

**You say:** `hail`



if **Faction** >= Kindly then



>**Ionat says:** Hello Soandso. It is good to see that you have traveled so far to be in my presence. I do believe that you are the one chosen to aid us in our fight against the giants. If you are then I am sure that you will need my rune for your research.


elseif **Faction** >= Indifferent then



>**Ionat says:** You seem like a decent sort for a snack food, but there is nothing you can do for me this day.  Come back when you have done more work for the Claws.


else



>**Ionat says:** We do have many living enemies.  Let me correct this oversight.


**You say:** `jualicn`



if **Faction** >= Kindly then



>**Ionat says:** You are the one that Jualicn speaks of?  Surely you must have something to symbolize your dediciation to our cause.



elseif **Faction** >= Indifferent then



>**Ionat says:** You seem like a decent sort for a snack food, but there is nothing you can do for me this day.  Come back when you have done more work for the Claws.


else



>**Ionat says:** We do have many living enemies.  Let me correct this oversight.


**You say:** `rune`




if **Faction** >= Kindly then



>**Ionat says:** I see. Many seek this rune that I keep for whatever magics they practice, however I can only release it to the one that aids Jualicn.


elseif **Faction** >= Indifferent then



>**Ionat says:** You seem like a decent sort for a snack food, but there is nothing you can do for me this day.  Come back when you have done more work for the Claws.


else



>**Ionat says:** We do have many living enemies.  Let me correct this oversight.

end

## Turn-Ins





if(**You possess item:**  [Rune of Revenge](/item/1894) x 1


>**Ionat says:** Take this Rune of Revenge, Soandso. You will need it to extract retribution in remembrance of our dear Hsagra. I thank you for your contributions to our cause. It is good to have you amongst our ranks.


* __Faction:__ [Claws of Veeshan](/faction/430) (5)


* __Faction:__ [Yelinak](/faction/436) (1)


* __Faction:__ [Kromzek](/faction/448) (-2)


 **You receive:** GiveAll( [Jualicns Token](/item/1908), [Rune of Revenge](/item/1894)) (+1000 exp)


**Ionat despawns.**

**This NPC *should* return incorrect items given.**
