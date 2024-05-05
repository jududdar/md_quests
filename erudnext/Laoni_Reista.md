# Laoni Reista



[Laoni Reista](/npc/24054) is a level 61 Erudite GM Paladin that spawns in [Erudin](/zone/24).



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




if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_645.png" alt="" /> <a
                                href="/item/13881" data-url="13881" class="tooltip-link link">A Nicked Coin</a>) then 


>**Laoni Reista says:** Good work. You have shown these rogues who are the better swimmers. Now we have proof of their involvement. You are a fine addition to the temple. Take this small reward. Go, and serve Prexus.





Your faction standing with [Deepwater Knights](/faction/242) got better (<span class='text-success'>+10</span>)


Your faction standing with [High Council of Erudin](/faction/266) got better (<span class='text-success'>+1</span>)


Your faction standing with [Heretics](/faction/265) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:** 0 (+2000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**
;

