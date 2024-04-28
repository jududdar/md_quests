# Draazak
## Dialog

**You say:** `hail`



if **Faction** >= Kindly then



>**Draazak says:** Greetings, Soandso. It cannot be that you would present yourself before me without reason. What brings you to these lands on this day? Please be quick for I have many ancient runes I must study.


elseif **Faction** >= Indifferent then



>**Draazak says:** I thank you for your inquiry, however you have not earned my trust yet.


else



>**Draazak says:** We do have many living enemies.  Let me correct this oversight.


**You say:** `rune`




if **Faction** >= Kindly then



>**Draazak says:** There are many that wish to gain our power through knowledge of the magic that we practice. I am afraid that I cannot simply give this treasure to just anyone. I must wait for the chosen that Jualicn speaks of only then can I release the rune I still carry from the great Relinar.


elseif **Faction** >= Indifferent then



>**Draazak says:** I thank you for your inquiry, however you have not earned my trust yet.


else



>**Draazak says:** We do have many living enemies.  Let me correct this oversight.


**You say:** `jualicn`



if **Faction** >= Kindly then



>**Draazak says:** If you are truly sent from Jualicn then he must have surely given you something to present me.



elseif **Faction** >= Indifferent then



>**Draazak says:** I thank you for your inquiry, however you have not earned my trust yet.


else



>**Draazak says:** We do have many living enemies.  Let me correct this oversight.

end

## Turn-Ins





if(**You possess item:**  [Rune of Concentration](/item/1896) x 1


>**Draazak says:** Soandso, whom Relinar found to be necessary for the success of the magic against those foul giants. I present this Rune of Concentration to you with faith that you are trusted amongst us or you would not have been sent to me. Make haste so that no time is wasted in extracting revenge for their past transgressions.


* __Faction:__ [Claws of Veeshan](/faction/430) (5)


* __Faction:__ [Yelinak](/faction/436) (1)


* __Faction:__ [Kromzek](/faction/448) (-2)


 **You receive:** None 


**Draazak despawns.**

**This NPC *should* return incorrect items given.**
