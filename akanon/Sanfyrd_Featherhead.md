# Sanfyrd Featherhead




## Dialog

**You say:** `hail`



>**Sanfyrd Featherhead says:** Greetings! I am the operator of this scrapyard. If you have any scrap metal, I would be glad to purchase it from you in loads of four. The Gemchoppers no longer allow me to accept blackbox fragments and micro servos.

**You say:** `fairy wing`



>**Sanfyrd Featherhead says:** No!! You cannot have my magic Fairie Wing!! I need it. I read somewhere within the great library that the magic wing from a fairie princess will restore my full head of hair. Look at me!! I am bald!! I have no [friends] at all.

**You say:** `friend`



>**Sanfyrd Featherhead says:** Oh. You are just saying that so you can get my fairie wing. I will make you a deal. I cannot rely on this wing forever. I will trade it with you if you could get me a case of hair tonic. If you are a true friend you [will fetch the hair tonic] for me.

**You say:** `hair tonic`



>**Sanfyrd Featherhead says:** Great!! Here you go, my friend. Take this crate and within you shall fill each slot with hair tonic. When all are combined within the crate, return it to me for your wing. I am not sure what the tonic was or where I got it. There is some writing on the crate, but I could not identify it.


**You receive:**  [Crate for Tonics](/item/17979)
end

## Turn-Ins



local text1 = "I hear there is one more on the loose. Find him and then I shall pay you.";

local text2 = "I now require all deliveries of Scrap Metal to be in loads of four.";



if **You turn in:** [Scrap Metal](/item/13198), [Scrap Metal](/item/13198), [Scrap Metal](/item/13198), [Scrap Metal](/item/13198)


>**Sanfyrd Featherhead says:** Grand! We always need more scraps to melt down. Here you are, then... Some coins for supporting Ak'Anon and a salvaged item from the scrapyard.


* __Faction:__ [Gem Choppers](/faction/255) (5)


* __Faction:__ [Merchants of Ak`Anon](/faction/288) (1)


* __Faction:__ [King Ak`Anon](/faction/333) (1)


* __Faction:__ [Dark Reflection](/faction/238) (-1)


* __Faction:__ [Clan Grikbar](/faction/1604) (-1)


 **You receive:** None 

elseif **You turn in:** [Bundle of Super Conductive Wires](/item/9426), [Gold tipped boar horn](/item/28618), [Shard of Pure Energy](/item/29906), [Silicorrosive Grease](/item/28165)


>**Sanfyrd Featherhead says:** Wow! I see my nephew finally read my list of items. I also see he is not delivering them himself, he is too young to bind himself to the library like that. These items should help me in my research to upgrade the scrapyard. Here let me pen a note to him so you can take it back to him.


 **You receive:**  [Note to Fimli](/item/15980) (+1000 exp)

elseif **You turn in:** [A Crate of Tonic](/item/12336)


>**Sanfyrd Featherhead says:** Huzzah!! You are my friend. Now you can take my old toupee and get it repaired. Just go to Freeport and ask Ping to [repair the toupee]. Hey!! You know what? He is the guy who sells the hair tonic!! I remember now. Well,.. Get my toupee repaired and I will give you the fairie wing.


 **You receive:**  [A Tattered Toupee](/item/12337) 

elseif **You turn in:** [Mane Attraction](/item/12254)


>**Sanfyrd Featherhead says:** Double Huzzah!! You are a good friend Soandso. Now mayhaps I shall find myself a wife. Here pal, the fairy wing. I hope it can give you a great head of hair. You need it.


 **You receive:**  [A Glimmering Fairie Wing](/item/12339) 

elseif **You turn in:** [Scrap Metal](/item/13216), [Scrap Metal](/item/13217)


>**Sanfyrd Featherhead says:** Good. The citizens of Ak'Anon are safe from those little critters. They may have injured someone; that is why they are deactivated. Here is something I found in the scrapyard. I hope you can find a purpose for it.


* __Faction:__ [Gem Choppers](/faction/255) (10)


* __Faction:__ [King Ak`Anon](/faction/333) (2)


* __Faction:__ [Merchants of Ak`Anon](/faction/288) (2)


* __Faction:__ [Dark Reflection](/faction/238) (-2)


* __Faction:__ [Clan Grikbar](/faction/1604) (-1)


 **You receive:** None 

**This NPC *should* return incorrect items given.**
