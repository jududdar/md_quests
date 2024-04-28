# Jarah Reskan


## Dialog

**You say:** `hail`



>**Jarah Reskan says:** Greetings, child. Welcome to Gemchopper Hall. I trust that you are a [warrior], or perhaps you are lost..?

**You say:** `lost`



>**Jarah Reskan says:** One can easily get lost in Ak'Anon. You must get your vision checked. If you are truly lost, I would advise speaking with a mechanical guide. There should be one close by on the main walkway.

**You say:** `warrior`



if **Faction** >= Amiable then 



>**Jarah Reskan says:** That is good news! We gnomes are not known for our love of battle so it is always good to bring new blood into our ranks. We shall prove our worth as warriors to all other races. For now. there is much to do in Ak'Anon. There are [rogue clockworks] and the [cargo clockwork].


elseif( **Faction is** == Indifferent) then



>**Jarah Reskan says:** You must show a greater allegiance to the Gemchoppers before we can speak with you.  Search the hills for rogue clockworks.  Captain Compolten shall accept two of their blackboxes and you shall prove your loyalty to our hall.


else



>**Jarah Reskan says:** You are lucky I do not cut you in half right where you stand. Your actions so far have proven you an enemy to the Gemchoppers. Leave while you still can!


**You say:** `rogue clockworks`



>**Jarah Reskan says:** The clockworks are the responsibility of Manik Compolten. Speak with him - I am sure he is here somewhere.

**You say:** `cargo clockwork`



>**Jarah Reskan says:** The cargo clockwork is located near the entrance to Ak'Anon in the Steamfont Mountains. It runs a delivery to the windmills every five days at eight in the morning. There have been attacks by a group of highwaymen. They are quite a formidable group. I have offered a reward for their heads. Be very careful if you plan on escorting the cargo clockwork. This trio of bandits is very strong.

**You say:** `blackbox`



>**Jarah Reskan says:** If you have a clockwork blackbox which is still intact, take it to [Manik Compolten].  All clockwork matters go through him.

**You say:** `manik compolten`



if **Faction** >= Indifferent then 



>**Jarah Reskan says:** Manik is a trainer within this guild. The clockworks are his responsibility. Speak with him - I am sure he is here somewhere.


else



>**Jarah Reskan says:** You are lucky I do not cut you in half right where you stand. Your actions so far have proven you an enemy to the Gemchoppers. Leave while you still can!


**You say:** `meldrath`



>**Jarah Reskan says:** Meldrath is the mad gnome.  He used to be a member of the Eldritch Collective.  Some say he lost his mind while he was working on a formula he obtained from other worlds.  He used to lead the cult called the [Asylum of the Mad].

**You say:** `asylum`



>**Jarah Reskan says:** The Asylum of the Mad was formed by the mad gnome, Meldrath. Under his direction, they were trying to build some giant mechanical titan.  We recently sent all of our clockworks into the Steamfont Mountains to destroy their evil cult.
end

## Turn-Ins



if **Faction** >= Amiable and  **You turn in:** [Hector's Severed Head](/item/1270), [Jerald's Severed Head](/item/1319), [Renaldo's Severed Head](/item/1323)


>**Jarah Reskan says:** I heard our shipment made it back safely. These heads will send a message to any other thief that plans on robbing our cargo shipments. Thank you Soandso, take this coin as your reward. I’m sorry to say we’re currently out of masks.


* __Faction:__ [Gem Choppers](/faction/255) (2)


* __Faction:__ [Merchants of Ak`Anon](/faction/288) (1)


* __Faction:__ [King Ak`Anon](/faction/333) (1)


* __Faction:__ [Dark Reflection](/faction/238) (-1)


* __Faction:__ [Clan Grikbar](/faction/1604) (-1)


 **You receive:** 0 (+1500 exp)


**This NPC *should* return incorrect items given.**
