# Laoni Reista
## Dialog

**You say:** `hail`



>**Laoni Reista says:** Very good to make your acquaintance. Soandso. If you are a [new knight]. then let it be known. for I am seeking young knights of Deepwater.


**You say:** `new knight`



if **Faction** >= Amiable then 



>**Laoni Reista says:** You do seem a bit young. We shall have to test your mettle. Within this temple. you shall learn to swim as fast as the swordfish and attack with the bravery and skill of the shark. Are you willing to [assist with the cleansing of the ocean]?


elseif **Faction** >= Indifferent then



>**Laoni Reista says:** There is no reason to dislike you, but we of the Deepwater Knights must see more done for our cause before we truly accept you.


else



>**Laoni Reista says:** We, the Deepwater Knights, know of your vile ways. You had best leave while you can.


**You say:** `assist.* cleansing.* ocean`



if **Faction** >= Amiable then 



>**Laoni Reista says:** Go to the waters near the harbor. We have heard of Qeynos' rogue guild attempting to smuggle our valuable Vasty Deep water from Odus by way of swimmers. We require proof of their involvement. It is said they often carry special coins. Return one of these coins to me.


elseif **Faction** >= Indifferent then



>**Laoni Reista says:** There is no reason to dislike you, but we of the Deepwater Knights must see more done for our cause before we truly accept you.


else



>**Laoni Reista says:** We, the Deepwater Knights, know of your vile ways. You had best leave while you can.

end

## Turn-Ins




if **Faction** >= Amiable and  **You turn in:** [A Nicked Coin](/item/13881)


>**Laoni Reista says:** Good work. You have shown these rogues who are the better swimmers. Now we have proof of their involvement. You are a fine addition to the temple. Take this small reward. Go, and serve Prexus.





* __Faction:__ [Deepwater Knights](/faction/242) (10)


* __Faction:__ [High Council of Erudin](/faction/266) (1)


* __Faction:__ [Heretics](/faction/265) (-1)


 **You receive:** None 

**This NPC *should* return incorrect items given.**
;

