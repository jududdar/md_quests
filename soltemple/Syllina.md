# Syllina


## Dialog

**You say:** `Hail`



>**Syllina says:** Hello, I am Syllina, follower of Solusek Ro and keeper of the [Shadow Lore].

**You say:** `lore`



>**Syllina says:** I hold the secrets to the Shadow Lore so highly prized by Necromancers. If you are interested, I can tell you about [ShadowBound Boots], [ShadowBound Gloves], the [Robe of Enshroudment] or the secrets to the making of [Shadow Silk].

**You say:** `shadowbound boots`



>**Syllina says:** ShadowBound Boots are boots woven from purest shadow. If you are interested, I will weave you a pair - but I will need [boot components].

**You say:** `boot components`



>**Syllina says:** I will need the following items to make you a pair of ShadowBound Boots: Shadow Silk, The Scepter of Sorrow from Castle Mistmoore, an Eye of Shadow from our mortal enemies the Shadowed Men and a Skeletal toe from a Rathe Giant Skeleton.

**You say:** `shadowbound gloves`



>**Syllina says:** ShadowBound Gloves are gloves woven from the purest shadow. If you are interested, I will weave you a pair - but I will need [glove components].

**You say:** `glove components`



>**Syllina says:** I will need the following items to make you a pair of ShadowBound Gloves: Inky Shadow Silk, The Scepter of Tears from the circle-stair-waterfall of Guk, a Hand of Shadow from our mortal enemies the Shadowed Men and a Skeletal finger from a Rathe Giant Skeleton.

**You say:** `robe of enshroudment`



>**Syllina says:** The Robe of Enshroudment is a robe woven from the purest of shadow. If you are interested, I will weave you a robe - but I will need the following [robe components].

**You say:** `robe components`



>**Syllina says:** I will need the following items to make you a Robe of Enshroudment: Large Shadow Silk, A Werebat Wing from the Estate of Unrest, A Mask of Shadow from our mortal enemies the Shadowed Men and a Globe of Shadow from a Nokta Shaman in Guk.

**You say:** `shadow silk`



>**Syllina says:** If you are interested, I will tell you the secrets of making Shadow Silk for a mere 50 pieces of gold.
end

## Turn-Ins



local text = "Solusek Ro does not believe in half measures.";





if( **You turn in:** gold = 50) then


>**Syllina says:** You will need to give the following components to a tailor: a Shadow Wolf Pelt, a Silk Swatch and a Scroll of Gather Shadows. Have the tailor weave them together and she will make you Shadow Silk. To make large shadow silk add an extra shadow wolf pelt. To make inky shadow silk, add an extra scroll.


* __Faction:__ [Temple of Solusek Ro](/faction/415) (1)


* __Faction:__ [Shadowed Men](/faction/416) (-1)



elseif( **You turn in:** [Large Shadow Silk](/item/16484), [A Werebat Wing](/item/13239), [Mask of Shadow](/item/2309), [Globe of Shadow](/item/10535)) then


>**Syllina says:** Silk, wing, mask, globe... all of the components necessary for the making of a robe of Enshroudment. Well done. Here is your reward.


* __Faction:__ [Temple of Solusek Ro](/faction/415) (5)


* __Faction:__ [Shadowed Men](/faction/416) (-1)


 **You receive:**  [Robe of Enshroudment](/item/1355) (+1000 exp)



elseif( **You turn in:** [A Scepter](/item/14363), [Hand of Shadow](/item/13234), [A skeletal finger](/item/10534), [Inky Shadow Silk](/item/16485)) then


>**Syllina says:** So you have gathered all of the components for me to weave Shadowbound Gloves... Well done. You will be wanting these.


* __Faction:__ [Temple of Solusek Ro](/faction/415) (5)


* __Faction:__ [Shadowed Men](/faction/416) (-1)


 **You receive:**  [ShadowBound Gloves](/item/3318) (+1000 exp)



elseif( **You turn in:** [A Scepter](/item/14364), [Eye of Shadow](/item/13180), [A skeletal toe](/item/10533), [Shadow Silk](/item/16483)) then


>**Syllina says:** I see that you have gathered all of the necessary components... Well done. Here are your Shadowbound Boots.


* __Faction:__ [Temple of Solusek Ro](/faction/415) (5)


* __Faction:__ [Shadowed Men](/faction/416) (-1)


 **You receive:**  [ShadowBound Boots](/item/3317) (+1000 exp)
end
