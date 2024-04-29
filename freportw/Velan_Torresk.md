# Velan Torresk
## Dialog

local fac = e.other:GetFaction(e.self);


**You say:** `white training sash`



if **Faction** >= Amiable +50 then



>**Velan Torresk says:** The white training sash of the Ashen Order is awarded to our new members for completing a few simple tasks to prove their devotion to our clan. As you know, Freeport is a very hostile place, under constant attack from [orcs], wild beasts, and even the undead. To help keep this city and its citizens relatively safe, we must help the Militia protect the main gates. Bring me two Deathfist pawn scalps from those vile [Deathfist orcs], a snake fang, and some bone chips from a skeleton. Good luck, Soandso, represent us well!


elseif( **Faction is** == Indifferent) then



>**Velan Torresk says:** I have been watching you, and appreciate the help you've given to the brothers and sisters of the Ashen Order, but I feel that such a vital matter should be left to one of our more trusted members.


else



**Velan Torresk says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `yellow sash of order`



if **Faction** >= Amiable +75 then



>**Velan Torresk says:** To earn the yellow sash, you must prove yourself to be very skilled in the art of fighting. The lands to the west and south of Freeport are filled with dangerous beasts that often prey upon innocent travelers. Help protect our merchant caravans and traveling citizens, while at the same time practicing your defensive skills, and eliminating these deadly creatures from the surrounding landscape. Bring me a giant snake rattle, a Deathfist slashed belt, the chitin of a desert tarantula, and turn in your white training sash, and I shall reward your noble work with our yellow Sash of Order. Good luck, Soandso!


elseif( **Faction is** == Indifferent) then



>**Velan Torresk says:** I have been watching you, and appreciate the help you've given to the brothers and sisters of the Ashen Order, but I feel that such a vital matter should be left to one of our more trusted members.


else



**Velan Torresk says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `hail`



if **Faction** >= Apprehensive then



>**Velan Torresk says:** Greetings. Soandso!  I am Velan Torresk of the Ashen Order.  I am in charge of training the newest members of our clan. and helping them advance their skills and rank.  When members perform certain tasks on behalf of the Order. they advance to a higher rank in our clan. and are awarded a special [sash].


else



**Velan Torresk says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `sash`



>**Velan Torresk says:** The Sashes of Order are given out by the various trainers of our clan.  I give out the [white training sash] and the [yellow Sash of Order]. and [Reyia] is in charge of the [orange and red sashes].

**You say:** `orcs`



>**Velan Torresk says:** The Deathfist Orcs are a large tribe of Orcs who live out in the desert. They are constantly sending small raiding parties and scouts to attack Freeport and its citizens.

**You say:** `reyia`



>**Velan Torresk says:** Reyia Beslin is one of our head trainers. She helps our members to improve their skills, and is also in charge of the orange and red Sashes of Order.

**You say:** `purple`



>**Velan Torresk says:** Brother Klom is the Ashen Order's second master.  He is in charge whenever Master Puab is absent or falls ill.

**You say:** `puab`



>**Velan Torresk says:** Master Puab is the head master of the Ashen Order.  His grandfather, Khenur Closk, was the founder of the Ashen Order many years ago.  Khenur led the Order around the Desert of Ro nomadically for almost a decade, helping the lost and protecting trade caravans from bandits.  He then decided to settle here in Freeport, and the rest is history.
end

## Turn-Ins



local text1 = "Ah, very good. You are well on your way to earning the white sash."

local text2 = "Ah, very good. You are well on your way to earning the yellow Sash of Order."




if **Faction** >= Amiable +50 then


if( **You turn in:** [Deathfist Pawn Scalp](/item/13794), [Deathfist Pawn Scalp](/item/13794), [Snake Fang](/item/13067), [Bone Chips](/item/13073)) then



>**Velan Torresk says:** Good work, Soandso, you've worked hard and proven yourself a valuable addition to the Ashen Order. Here's your white sash, wear it with pride.



* __Faction:__ [Ashen Order](/faction/361) (25)



* __Faction:__ [Knights of Truth](/faction/281) (3)



* __Faction:__ [Silent Fist Clan](/faction/309) (1)



 **You receive:**  [White Training Sash](/item/10130) (+500 exp)






if **Faction** >= Amiable +75 and  **You turn in:** [White Training Sash](/item/10130), [Giant Snake Rattle](/item/13058), [Deathfist Slashed Belt](/item/13916), [Desert Tarantula Chitin](/item/20901)) then


>**Velan Torresk says:** Ah, well done, Soandso. You have proven that you are a very skillful fighter and it is an honor to have you as a member of the Ashen Order. On behalf of Master Closk, and under the watchful eyes of Quellious, I present you, Soandso, with this, the yellow Sash of Order. Go out and make us proud.


* __Faction:__ [Ashen Order](/faction/361) (50)


* __Faction:__ [Knights of Truth](/faction/281) (7)


* __Faction:__ [Silent Fist Clan](/faction/309) (2)


 **You receive:**  [Yellow Sash of Order](/item/10131) (+750 exp)

**This NPC *should* return incorrect items given.**
;


