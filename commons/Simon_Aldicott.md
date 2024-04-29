# Simon Aldicott


## Dialog

**You say:** `hail`



>**Simon Aldicott says:** Hail and well met. I am Simon Aldicott, a cleric in the service of Mithaniel Marr. I've been sent here to prepare a funeral service for one of our lost to join Marr in his kingdom.

**You say:** `funeral service`



>**Simon Aldicott says:** Are you the brave knight whom Valeron sent to meet me here? If so please place the remains in the coffin and seal it. Then hand me the coffin so that we may bless it in the waters of this lake.
end

## Turn-Ins




if( **You turn in:** [A Gem Encrusted Casket](/item/6708)) then


>*Simon Aldicott places the coffin in the water and begins to pray. 'Lord of Valor high above, take this knight, your loyal child, into thy kingdom and all that is holy! What is that thing!'*


**Spawn NPC:**  [a Tortured Revenant](/npc/21031) at (**y:** 259.7, **x:** 2901)

elseif( **You turn in:** [Revenant Ash](/item/6709)) then


>**Simon Aldicott says:** Thank you, Knight. With this task accomplished, I shall reward you with this scroll. It is an ancient spell that only the holiest of knights may cast. Remember your duty!


* __Faction:__ [Priests of Marr](/faction/362) (10)


* __Faction:__ [The Freeport Militia](/faction/330) (-1)


* __Faction:__ [Knights of Truth](/faction/281) (1)


 **You receive:**  [Spell: Divine Might](/item/15693) (+20000 exp)

**This NPC *should* return incorrect items given.**
;
## Signals

>**Simon Aldicott says:** Tis a sad thing. His soul was twisted to its current state somehow and he thought YOU were the foul Teir'Dal who destroyed him in the first place. But that is no matter..you have freed him to stand by Marrs side once more! Now, give me the ash so that I may finally put him to rest. In return for your valor I shall provide you with an ancient spell unknown to most Holy Knights of Marr.


