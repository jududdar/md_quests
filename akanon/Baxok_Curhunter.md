# Baxok Curhunter


## Dialog

**You say:** `hail`



>**Baxok Curhunter says:** Hail, Soandso. I invite you to serve the mighty state of Ak'Anon by becoming a Gemchopper. We gnomes are not known for our warrior skills, but those few who endure and survive to become elite amongst our warriors soon find that the technology of the gnomes has found its way into our halls. You must be a [new recruit] or [an outsider], perhaps?

**You say:** `new recruit`



if **Faction** >= Amiable then



>**Baxok Curhunter says:** Well, good to make your acquaintance, Soandso. Maybe someday you shall be a great Watchman. Until then, I have a task for you. Will you [serve the Crown] or has a yellow streak appeared upon your back?


elseif( **Faction is** == Indifferent) then



>**Baxok Curhunter says:** You must show a greater allegiance to the Gemchoppers before we can speak with you. Search the hills for rogue clockworks. Captain Compolten shall accept two of their blackboxes and you shall prove your loyalty to our hall.


else



>**Baxok Curhunter says:** You are lucky I do not cut you in half right where you stand. Your actions so far have proven you an enemy to the Gemchoppers. Leave while you still can!


**You say:** `an outsider`



>**Baxok Curhunter says:** I should have guessed as much. You look the part.

**You say:** `serve the crown`



if(**Your level** <=5 ) then



>**Baxok Curhunter says:** You are too inexperienced. Leave that business to someone more worldly.


else



>**Baxok Curhunter says:** Go to the Lesser Faydarks. There you will seek out a fairy city. It seems the little pests have stolen one of our fabulous clockworks. Destroy the clockwork and bring me proof. Be very careful. The fairy folk may be small, but they pack a punch.


**You say:** `meldrath`



>**Baxok Curhunter says:** Meldrath is the mad gnome.  He used to be a member of the Eldritch Collective.  Some say he lost his mind while he was working on a formula he obtained from other worlds.  He used to lead the cult called the [Asylum of the Mad].

**You say:** `asylum`



>**Baxok Curhunter says:** The Asylum of the Mad was formed by the mad gnome, Meldrath. Under his direction, they were trying to build some giant mechanical titan.  We recently sent all of our clockworks into the Steamfont Mountains to destroy their evil cult.
end

## Turn-Ins



if **You turn in:** [Recruitment Summons](/item/18770)


>**Baxok Curhunter says:** I, Baxok, guildmaster, welcome you to Gemchopper Hall, young warrior! You are expected to serve his majesty, King Ak'Anon, with pride. You have much to learn. You may report to any of the trainers for further guidance. Go forth and serve!


* __Faction:__ [Gem Choppers](/faction/255) (100)


* __Faction:__ [Merchants of Ak`Anon](/faction/288) (25)


* __Faction:__ [King Ak`Anon](/faction/333) (25)


* __Faction:__ [Dark Reflection](/faction/238) (-25)


* __Faction:__ [Clan Grikbar](/faction/1604) (-5)


 **You receive:**  [Torn and Ripped Tunic*](/item/13520) (+20 exp)

elseif **You turn in:** [Blackbox XIVD](/item/13344)


>**Baxok Curhunter says:** I can hardly believe you destroyed the clockwork. The last ten men I sent became fairy fodder. Thank you. Here is a token of my appreciation. Serve Ak'Anon well and we shall treat you well.





* __Faction:__ [Gem Choppers](/faction/255) (20)


* __Faction:__ [Merchants of Ak`Anon](/faction/288) (5)


* __Faction:__ [King Ak`Anon](/faction/333) (5)


* __Faction:__ [Dark Reflection](/faction/238) (-5)


* __Faction:__ [Clan Grikbar](/faction/1604) (-1)


 **You receive:** eq.ChooseRandom( [Round Shield](/item/9002), [Cloth Cap](/item/1001), [Cloth Veil](/item/1002), [Cloth Choker](/item/1003), [Cloth Shirt](/item/1004), [Cloth Shawl](/item/1005), [Cloth Cape](/item/1006), [Cloth Cord](/item/1007), [Cloth Sleeves](/item/1008), [Cloth Wristband](/item/1009), [Cloth Gloves](/item/1010), [Cloth Gloves](/item/1010), [Cloth Pants](/item/1011)) (+5000 exp)

**This NPC *should* return incorrect items given.**
