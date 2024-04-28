# Gargh
## Dialog

**You say:** `hail`



>**Gargh says:** You [friend of Gardunk]? Meez friend of Gardunk.

**You say:** `friend.* gardunk`



if **Faction** >= Amiable then



>**Gargh says:** Dat good. He tell meez you was comin'. Meez learn you to fight like alligator. Dominate through fear. Dat is what we do. Strike fear into heart of enemies. You [ready to start]?


else



>**Gargh says:** Meez don't trust you.


**You say:** `ready to start`



if **Faction** >= Amiable then



>**Gargh says:** Good. We start easy. Little froggies a good place. They our enemies. You go to da swamp and kill da tadpoles. Bring back to me four pieces of Froglok Tadpole Flesh. Strip da flesh from our enemies. Dat your first task.


else



>**Gargh says:** Meez don't trust you.


**You say:** `animals`



if **Faction** >= Amiable then



>**Gargh says:** 'We start with da rat. You go and kill rats. Tear da rat apart and bring me a Giant Rat Ear and a Giant Rat Pelt.


else



>**Gargh says:** Meez don't trust you.


**You say:** `alligator`



if **Faction** >= Amiable then






>**Gargh says:** Best way to do dat is to fight alligators. You go out and fight da alligators in da swamp. Bring back to meez an alligator tooth and meez believe you.


else



>**Gargh says:** Meez don't trust you.


**You say:** `training`



if **Faction** >= Amiable then






>**Gargh says:** For da next part of your training you go and strike fear into da hearts of da froggies again. Only not the little ones. You go and you drain da blood from one of da full grown ones. You bring meez back da Froglok Blood. Meez be waiting for you here if you make it back alive.


else



>**Gargh says:** Meez don't trust you.


**You say:** `one more task`



if **Faction** >= Amiable then






>**Gargh says:** You is getting stronger. It time for you to venture out some and spread fear to other parts of da world. You go over to da Feerrott. There you find lots of lizard men. You go and spread fear to them. Fight them. You cut off their tails. Bring me four Lizard Tail.


else



>**Gargh says:** Meez don't trust you.

end

## Turn-Ins





if  **Faction** >= Amiable and  **You turn in:** [Froglok Tadpole Flesh](/item/13187), [Froglok Tadpole Flesh](/item/13187), [Froglok Tadpole Flesh](/item/13187), [Froglok Tadpole Flesh](/item/13187)


>**Gargh says:** You done good. You begin to know fear by causing fear. You learning about da animals. You learn about da animals by fighting dem and tearing them apart. You ready to [learn about da animals]?


* __Faction:__ [Dark Ones](/faction/237) (1)


* __Faction:__ [Shadowknights of Night Keep](/faction/308) (1)


* __Faction:__ [Frogloks of Guk](/faction/251) (-1)


 **You receive:**  [Dark Ones Bracer](/item/7380) (+250 exp)

elseif  **Faction** >= Amiable and  **You turn in:** [Giant Rat Ear](/item/13050), [Giant Rat Pelt](/item/13054)


>**Gargh says:** So you know all about da rat now. Dat is good. Next step is important. You need to learn to [fight like da alligator].


* __Faction:__ [Dark Ones](/faction/237) (2)


* __Faction:__ [Shadowknights of Night Keep](/faction/308) (1)


* __Faction:__ [Frogloks of Guk](/faction/251) (-1)


 **You receive:**  [Dark Ones Cap](/item/7381) (+400 exp)

elseif  **Faction** >= Amiable and  **You turn in:** [An Alligator Tooth](/item/13725)


>**Gargh says:** Ok meez believe you. Here your reward. Meez think you just about ready for [next part of your training].


* __Faction:__ [Dark Ones](/faction/237) (6)


* __Faction:__ [Shadowknights of Night Keep](/faction/308) (1)


* __Faction:__ [Frogloks of Guk](/faction/251) (-1)


 **You receive:**  [Dark Ones Leggings](/item/7382) (+600 exp)

elseif  **Faction** >= Amiable and  **You turn in:** [Froglok Blood](/item/22524)


>**Gargh says:** You did it! You cause lots of fear for them. Dat good. Even da spirits are starting to tremble. Soon you will be able to make dem do what you want. But there is [one more task] meez want you to do.


* __Faction:__ [Dark Ones](/faction/237) (28)


* __Faction:__ [Shadowknights of Night Keep](/faction/308) (7)


* __Faction:__ [Frogloks of Guk](/faction/251) (-4)


 **You receive:**  [Dark Ones Claw](/item/7383) (+1000 exp)

elseif  **Faction** >= Amiable and  **You turn in:** [Lizard Tail](/item/13354), [Lizard Tail](/item/13354), [Lizard Tail](/item/13354), [Lizard Tail](/item/13354)


>**Gargh says:** Meez impressed. Da spirits, they tremble in terror before you. Meez can't teach you no more. Go and dominate through fear. Fight like da alligator and tear your enemies apart.


* __Faction:__ [Dark Ones](/faction/237) (10)


* __Faction:__ [Shadowknights of Night Keep](/faction/308) (2)


* __Faction:__ [Frogloks of Guk](/faction/251) (-1)


 **You receive:**  [Dark Ones Leather](/item/7384) (+1000 exp)

**This NPC *should* return incorrect items given.**
