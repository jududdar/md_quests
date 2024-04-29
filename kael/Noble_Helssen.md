# Noble Helssen
## Dialog

**You say:** `hail`



if **Faction** >= Indifferent then



>**Noble Helssen says:** You obviously have no idea where you have trespassed so I will generously allow you to live. I suggest you leave immediately before my generosity runs out however......Unless, you're looking for work.


else



**Noble Helssen says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `looking for work`



if **Faction** >= Indifferent then



>**Noble Helssen says:** Well, you might do. Out in the deepest scar, known as the Wakening Land we have deployed several mercenaries to harass the local annoying population. They are in need of constant supplies so we hire those we can trust to deliver those supplies to the mercenaries wandering out in the field. Are you interested, " .. e.other:Race() .. "?


else



**Noble Helssen says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `interested`



if **Faction** >= Indifferent then



>**Noble Helssen says:** Very well. Take this pack of supplies to any of the Mercenaries you come across in the field. They will pay you upon delivery. Return here for more supplies to deliver when you are ready.



**You receive:**  [Field Supplies](/item/1724)


else



**Noble Helssen says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `plane of growth`



if **Faction** >= Indifferent then



>**Noble Helssen says:** Our soldiers fell victim to the denizens of that plane and unless we can find some way to stop this from happening, the land of Wakening will never be under our control. Many have suggested just destroying the Nexus but they are short-sighted fools. My vision is not only to control the resources that forest provides, but also to control the very force of Growth itself! You will help me to do this, mercenary.


else



**Noble Helssen says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `help you`



if **Faction** >= Indifferent then



>**Noble Helssen says:** The tablet I have given you is inscribed with runes of binding. I am owed a favor and it has come time to use it. There is a venerable sea turtle that lives along the warmer part of the coast, where the ice floes begin to break up. His name is Corudoth. Find him and speak with him. Remind him of his obligation to me and if he is not forthcoming in his answers, tell him he owes me. Then show him the tablet. He will tell you what to do. He will most likely be beneath the ocean.  The mask I gave you should help.



**You receive:**  [Enchanted Velium Mask](/item/1713)


else



**Noble Helssen says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

end

## Turn-Ins



local text = "I have much to do, Soandso. Do not waste my time unless you have the Arcanum AND the key to open it.";



if **Faction** >= Indifferent and  **You turn in:** [Report of Failure](/item/1709)) then 


>*Noble Helssen takes the report from you and places it in a pocket without even glancing at it. He says, 'Do not worry, Soandso. I know of the planar creatures who eliminated my troops. The fault is not yours but of that fool Drioc's. The Savage land is not just a simple forest as those idiots in the field believe. It is a cradle of life and the forces that drive it. Within that forest is a nexus, a gateway to another plane of existence, the Plane of Growth.'*





* __Faction:__ [Kromzek](/faction/448) (15)


* __Faction:__ [Kromrif](/faction/419) (3)


* __Faction:__ [King Tormax](/faction/429) (3)


* __Faction:__ [Claws of Veeshan](/faction/430) (-7)


 **You receive:**  [Inscribed Velium Tablet](/item/1710) (+1000 exp)

elseif **Faction** >= Indifferent and  **You turn in:** [Helssen's Voucher](/item/1722)) then 


>**Noble Helssen says:** Excellent choice, " .. e.other:Race() .. ". Competence and a sense of style. When we are ready to take the Wakening I will most definitely welcome your participation. Here is your reward.


 **You receive:**  [Noble's Seal](/item/1723) (+2000 exp)


 **You receive:**  [Helssen's Prismatic Trinket](/item/1720) 

elseif **Faction** >= Indifferent and  **You turn in:** [Arcanum of Rosh](/item/1712), [Ancient Rusted Key](/item/1714)) then 


>**Noble Helssen says:** Ahhh, you suprise me mercenary. You have found the book as well as the key to open it. I must begin my research as soon as possible. But first, your reward. With this voucher you can receive 1 of the 3 treasures I will offer you. If given to Kellek you will receive an item worthy of a hearty and rugged combatant. If given to Wenglawks you will aquire an item to be worn by only the most pious. And if given to me I will give you a sorcerous trinket of my own design.


* __Faction:__ [Kromzek](/faction/448) (11)


* __Faction:__ [Kromrif](/faction/419) (5)


* __Faction:__ [King Tormax](/faction/429) (5)


* __Faction:__ [Claws of Veeshan](/faction/430) (-5)


 **You receive:**  [Helssen's Voucher](/item/1722) (+2000 exp)

**This NPC *should* return incorrect items given.**
