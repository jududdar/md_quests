# Rathmana Allin


## Dialog

**You say:** `hail`



>**Rathmana Allin says:** Company?! Way out here in the desert of Ro? This is a pleasant surprise! Won't you stay for a while? I am sure the desert has dried your throat. I have supplies if necessary. At a price, of course. Are you [traveling] or are you here on [business]?

**You say:** `business`



>**Rathmana Allin says:** Of course. You do not look like a traveling merchant or a lost adventurer. Someone has sent you to Rathmana. Well then, let's not waste time. Give me the item, or items, and my fee of twenty gold coins. It must be gold. I have no use for any other metals.

**You say:** `traveling`



>**Rathmana Allin says:** Oh, wonderful! Then you must need water and rations for your long journey. Be sure to approach any camp you may find in Ro with caution. There are many bandits in the desert. If it were not for Ortallius, they would have gutted me and thieved all my merchandise by now. If you have any use of magic then I believe I may have an [offer] for you.

**You say:** `offer`



>**Rathmana Allin says:** My offer to you is this, you give me thirty gold and I allow you to reach into my scroll bag and retrieve one scroll and only one. It may be the spell of a wizard or maybe not. The school of magic will not be known beforehand. The only knowledge you will have is that Rathmana will not exchange the spell for another. You get what you take. Do you wish to reach into my bag? Then give Rathmana his thirty gold coins.

**You say:** `solusek`



>**Rathmana Allin says:** Solusek Ro is the Burning Prince.  It is He who watches over this desert and chooses who lives and who dies.  It was He who saved Rathmana from the heretics and it was He who saved Ortallius from the sands.

**You say:** `heretic`



>**Rathmana Allin says:** As you can see, I am an Erudite, and I was raised in the great schools of magic in Erud.  In my youth, I learned of a forbidden art. That art was necromancy. I secretly studied this art and eventually happened upon others who practiced the art of darkness.  These magic users, or rather, necromancers,  are called heretics.  I learned their ways, but before I completely converted to their dark ways, I attempted to flee their circle.  They caught me and through arcane means transported me to this desert.  I would have died if it were not for a vision of Solusek Ro.  He appeared to me and created a hole in Norrath. It was from this hole I drank and lived. Since then I call the desert of Ro home, and live my humble life in the name of the Burning Prince, Solusek Ro.

**You say:** `ortallius`



>**Rathmana Allin says:** Pay no mind to him.  He is my friend.  I found him as a child, dying under the blazing sun of Ro.  He was curled up next to his dead mother's body.  I raised him since then.  He is quite the opposite of what you would expect of an orc.  He is a good person.  To me, anyway.
end

## Turn-Ins



local text = "I believe there is more yet.";



if **You turn in:** gold = 30


>**Rathmana Allin says:** Good luck, my friend. May Solusek Ro guide your hand.


* __Faction:__ [Temple of Solusek Ro](/faction/415) (5)


* __Faction:__ [Shadowed Men](/faction/416) (-1)


 **You receive:** None 






elseif  **You turn in:** [Bayle List I](/item/18808), [Bayle List II](/item/18809), [Bayle List III](/item/18810), gold = 20


>**Rathmana Allin says:** A simple code. Why do you even bother Rathmana with such child's play? Here is your translation. That was the easiest twenty gold coins I ever earned.


* __Faction:__ [Temple of Solusek Ro](/faction/415) (5)


* __Faction:__ [Shadowed Men](/faction/416) (-1)




 **You receive:**  [Bayle List](/item/18825) 

**This NPC *should* return incorrect items given.**
