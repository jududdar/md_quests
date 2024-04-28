# Bungre Crawcrusher


## Dialog

**You say:** `hail`



>**Bungre Crawcrusher says:** What manner of creature are you, strange one? I can see that you are not native to any nearby territories. Your thin flesh and lack of hair would mean certain death when the ice queen breathes upon these seas.

**You say:** `elf`



>**Bungre Crawcrusher says:** I have heard not of your kind but you are welcome to take refuge on our beaches, we only ask that you help to defend them should the predators choose to attack.

**You say:** `human`



>**Bungre Crawcrusher says:** I have heard of others of your kind. The sirens have lured them to this bay from afar to feast upon and use as slaves. We Othmir are immune to the sirens' songs, but you must take care not to fall under their thrall. The remains of many of your kind's great wooden traveling beasts decay on the floor of our bay, abandoned by the victims of the sirens. You are welcome to take shelter on our beaches as long as you assist in defending them should predators decide to attack.

**You say:** `predators`



>**Bungre Crawcrusher says:** There are many dangerous predators that prowl the surrounding oceans and cliffs. It is my duty to train pups to become strong warriors in order to defend our villages. The wyverns on the cliffs prey primarily on the wounded and sick as well as many creatures that live in the brackish waters of our bay. The deadliest predators are the ones that roam all the coasts preying not only on my people but the Snowfangs and the Ulthork as well. Kelorek'Dar and Lodizal are the most feared of all.

**You say:** `lodizal`



>**Bungre Crawcrusher says:** Lodizal is a giant carnivorous sea turtle that roams the iceclad ocean preying primarily on the Snowfang gnolls. The Snowfang gnolls are not trusted by we Othmir as they survive on the skins and meat of walrus and otter but Lodizal is a threat to all coastal dwellers. Should Lodizal ever be slain I would be willing to craft a shield from his shell and adorn it with Othmir runes. I would charge ten thousand gold for the service.

**You say:** `kelorek`



>**Bungre Crawcrusher says:** Kelorek'Dar is a sea dragon that prowls the coasts preying on any manner of creature he can fit between his massive jaws.
end

## Turn-Ins





if **You turn in:** [Section of Lodizal's Shell](/item/22815),platinum = 1000


>*Bungre Crawcrusher skillfully crafts the section of Lodizal's shell into the shape of a shield. He then attaches sturdy cured walrus hide leather straps to the inner side of the shield and inscribes intricate glowing runes on the shield's face. When he is finished, he hands you the shield and claps loudly.*


* __Faction:__ [Othmir](/faction/432) (5)


* __Faction:__ [Ulthork](/faction/431) (-1)


 **You receive:**  [Lodizal Shell Shield](/item/22816) (+150000 exp)

local returned = item_lib.return_items(e.self, e.other, e.trade, false);

if (returned) then


>**Bungre Crawcrusher says:** Sorry stranger, but that is not enough to barter with.
end