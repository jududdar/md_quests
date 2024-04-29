# Derasinal
## Dialog

**You say:** `hail`



if **Faction** >= Kindly then



>**Derasinal says:** It is not often that I see strangers in these dangerous lands. Perhaps you are the chosen that Jualicn speaks of that will aid us in our battle against the foul giants. I do not believe you would be here if you were not in need of my sacred rune.


elseif **Faction** >= Indifferent then



>**Derasinal says:** You seem like a decent sort for a snack food, but there is nothing you can do for me this day.  Come back when you have done more work for the Claws.


else



>**Derasinal says:** We do have many living enemies.  Let me correct this oversight.


**You say:** `rune`




if **Faction** >= Kindly then



>**Derasinal says:** Although I can see that you would surely put the rune to use in some way, I can only release it to the one that Jualicn speaks of. I am sorry, but I am quite protective to what ties I still have to the great Relinar.


elseif **Faction** >= Indifferent then



>**Derasinal says:** You seem like a decent sort for a snack food, but there is nothing you can do for me this day.  Come back when you have done more work for the Claws.


else



>**Derasinal says:** We do have many living enemies.  Let me correct this oversight.


**You say:** `jualicn`



if **Faction** >= Kindly then



>**Derasinal says:** I understand that you may know of Jualicn, but I can only deal with those that he would trust with something dear to him.



elseif **Faction** >= Indifferent then



>**Derasinal says:** You seem like a decent sort for a snack food, but there is nothing you can do for me this day.  Come back when you have done more work for the Claws.


else



>**Derasinal says:** We do have many living enemies.  Let me correct this oversight.

end

## Turn-Ins



local token = 0;



if(**You possess item:**  [Rune of Bleve](/item/1895) x 1


>**Derasinal says:** I have given you the Rune of Bleve, to assist you in your research for the once lost magic against the Kromzek. I hope that you can make good use of it, for it is very sacred to me. May Veeshan guide your path!


* __Faction:__ [Claws of Veeshan](/faction/430) (5)


* __Faction:__ [Yelinak](/faction/436) (1)


* __Faction:__ [Kromzek](/faction/448) (-2)


 **You receive:** GiveAll( [Jualicns Token](/item/1908), [Rune of Bleve](/item/1895)) (+1000 exp)


**Derasinal despawns.**

**This NPC *should* return incorrect items given.**
