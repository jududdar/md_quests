# Grudash the Baker
## Dialog

**You say:** `hail`



>**Grudash the Baker says:** Ah, welcome stranger. Perhaps I could interest you in one of my famous Boysenberry pies, the delight of Sky Shrine.


if(**spawned NPC:**  [Ruru the Cook](/npc/114496)) then



eq.get_entity_list():GetMobByNpcTypeID( [Ruru the Cook](/npc/114496)):Say("Hah! Whatever Grudash. You know that my Roasted Walrus in Plum Sauce is better. You just don't want to admit it.");



>**Grudash the Baker says:** Why would I admit to such a lie? Everyone loves my pies. I rarely see anyone come in here asking for your Roasted Walrus.



eq.get_entity_list():GetMobByNpcTypeID( [Ruru the Cook](/npc/114496)):Say("Just you wait, just you wait! One of these days Grudash, you'll see.");



>**Grudash the Baker says:** Please ignore my friend Ruru here. He is a bit delusional.



eq.get_entity_list():GetMobByNpcTypeID( [Ruru the Cook](/npc/114496)):Say("Bah!");




**You say:** `boysenberry`



>*Grudash the Baker chuckles, 'I thought you might, what say you now Ruru? Who is the better cook between us now?'*


if(**spawned NPC:**  [Ruru the Cook](/npc/114496)) then



eq.get_entity_list():GetMobByNpcTypeID( [Ruru the Cook](/npc/114496)):Emote("grumbles, 'Bah, this still doesn't settle anything Grudash. This stranger obviously has no taste for fine cuisine.'");



end
