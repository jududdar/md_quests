# Hierophant Oxyn


## Dialog


**You say:** `hail`



>**Hierophant Oxyn says:** Greetings, and may the pain of the ancients guide you. You have come to us for guidance, have you not? We are the Hierophants of Cabilis and we guide the young Scale Mystics. All petitioners shall speak with me of [temple tasks].

**You say:** `temple tasks`



>**Hierophant Oxyn says:** The Temple of Terror requires all young Scaled Mystics to [perform daily tasks.]. The tasks are necessary to the upkeep of our order as well as that of our brothers, the Crusaders of Greenmist.

**You say:** `daily tasks`



if **Faction** >= Amiable then



>**Hierophant Oxyn says:** We require many components for various rituals. Take this Component mortar and fill it with the following items - foraged [mud crabs]. two small mosquito wings and one portion of bone chips. You must then use the pestle and combine all the components. When you have a full component mortar, you may return to me and I shall pay you your wages, but most importantly, you shall prove your devotion to the Scaled Mystics.



**You receive:**  [Component Mortar](/item/17020)










elseif **Faction** >= Indifferent then



>**Hierophant Oxyn says:** You will only obtain that which you seek by assisting the wills of the Scaled Mystics.


else



**Hierophant Oxyn says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.




**You say:** `mud crabs`








>**Hierophant Oxyn says:** Mud crabs are tiny crustaceans which live along the mudcaked shores of the Lake of Ill Omen. You can forage for them and find a handful of them at a time.



**You say:** `lost skulls`



if **Faction** >= Amiable then



>**Hierophant Oxyn says:** You must have heard of the Trilac Brotherhoods disappearance. They are the skulls of three soon to be ancients. They were taken from this temple by a silent intruder. Crusaders are always on duty. I do not know how they got into our vault. Every petitioner is ordered to search for the three skulls and return them to me along with their petitioner cudgel and then they shall become clairvoyants.


elseif **Faction** >= Indifferent then



>**Hierophant Oxyn says:** You will only obtain that which you seek by assisting the wills of the Scaled Mystics.


else



**Hierophant Oxyn says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.




**You say:** `iron cudgel`



>*Hierophant Oxyn shakes his head and waves a finger in your face. If you are looking to be handed the Iron Cudgel of the Clairvoyant then you are sadly mistaken. Perhaps if you were to gather a few [lost skulls] for the temple we may find you worthy to wield one.'*


e.self:DoAnim(170);



**You say:** `larger problem`



if **Faction** >= Amiable then



>**Hierophant Oxyn says:** Many of the ancient skulls have been cast out of our temple. A hierophant was supposed to cast a special spell which was to protect the skulls from dust and decay. He cast some unknown spell which has sent many of our skulls to their original point of death. It would be most helpful if you would [assist in collecting the ancient skulls].


elseif **Faction** >= Indifferent then



>**Hierophant Oxyn says:** You will only obtain that which you seek by assisting the wills of the Scaled Mystics.


else



**Hierophant Oxyn says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.




**You say:** `ancient skull`



if **Faction** >= Amiable then



>*Hierophant Oxyn seems unsure of your prowess. 'Hmmm. First you shall go after the two skulls of the Cleansers of the Outlands. If you find them, bring them back unbroken and then I shall trust you. Hand me both skulls and your iron cudgel of the clairvoyant and I will know you are prepared.'*


elseif **Faction** >= Indifferent then



>**Hierophant Oxyn says:** You will only obtain that which you seek by assisting the wills of the Scaled Mystics.


else



**Hierophant Oxyn says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.




**You say:** `liquid`









>**Hierophant Oxyn says:** The bottle contains deklium in a liquid solution. The metal of prophecy has been determined to rest in a mass of living earth. Our scholars have written of a mass of ore that fell from the heavens. This ore was used in the creation of a blade of our father, Rile. We have been filled with visions of this blade. I have seen it in the hands of our Crusaders as they march towards the new age of Greenmist! Seek out the corrupted earth that guards the interlopers. We have an alchemist near there. He will be able to use the deklium to determine which golem contains the metal. Take care to go in force. I sense that there will be a battle.
end

## Turn-Ins



local text1 = "In my hand shall be placed three skulls of the Trilac Brotherhood and an iron cudgel of the petitioner.";



if **Faction** >= Indifferent and  **You turn in:** [A note to Oxyn](/item/3895)



>*Hierophant Oxyn takes the note and begins to howl into the air! 'The visions are true! The new prophecy begins today, Crusader,' the mystic growls with pleasure. He quickly turns and takes a bottle of murky liquid from one of his potion bags and hands it to you. 'Take this and keep it safe. Our visions have told of this day. We have been able to learn of the metal of prophecy. This [liquid] will help us to locate its true resting place!*


* __Faction:__ [Crusaders of Greenmist](/faction/442) (20)


* __Faction:__ [Legion of Cabilis](/faction/441) (10)


 **You receive:**  [Bottle of Liquid Deklium](/item/3892) (+5000 exp)

elseif **Faction** >= Indifferent and  **You turn in:** [Chunk of Tynnonium](/item/3886)


>*Hierophant Oxyn holds the ore in his hands and begins to chant. His eyes go white as he raises the chunk of ore above his head. He lowers his arms and shakes his head for a moment. His eyes return to their normal state as they focus on you. The shaman hands you the ore and says, 'Seek out the creator of Rile's blade. He is still on this plane. I have felt his torment. Take this note to Librarian Zimor. He learned a great deal from the tome and can instruct you further.'*


* __Faction:__ [Crusaders of Greenmist](/faction/442) (20)


* __Faction:__ [Legion of Cabilis](/faction/441) (10)


 **You receive:**  [Note to Librarian Zimor](/item/3893) (+5000 exp)



 **You receive:**  [Chunk of Tynnonium](/item/3886) 



elseif **Faction** >= Amiable and  **You turn in:** [Full Component Mortar](/item/12403)


>**Hierophant Oxyn says:** We appreciate your service. Take a few copper for your deed as well as some of our cursed waters. They will provide you with nourishment. As for future tasks, we are searching for a few [lost skulls] and i am sure you are searching for your [iron cudgel of the clairvoyant] And i also hear that the furscales are in need of some broodlings to do some manual labor. Tell them Oxyn sent you.


* __Faction:__ [Scaled Mystics](/faction/445) (2)






* __Faction:__ [Legion of Cabilis](/faction/441) (1)






 **You receive:**  [Cursed Wafers](/item/12406) (+50 exp)


 **You receive:**  [Cursed Wafers](/item/12406) 



elseif **Faction** >= Amiable and  **You turn in:** [Morgl Skull](/item/12721), [Logrin Skull](/item/12722), [Waz Skull](/item/12723), [Iron Cudgel of the Petitioner](/item/5140)


>**Hierophant Oxyn says:** Excellent! You have proved yourself worthy to wield the iron cudgel of the clairvoyant. As a clairvoyant I feel I can trust you, so I will tell you that the issue of the missing skulls is a [much larger problem] than last stated.


* __Faction:__ [Scaled Mystics](/faction/445) (10)






* __Faction:__ [Legion of Cabilis](/faction/441) (5)






 **You receive:**  [Iron Cudgel of the Clairvoyant](/item/5141) (+2000 exp)



elseif **Faction** >= Amiable and  **You turn in:** [Skull with I](/item/12724), [Skull with II](/item/12725), [Iron Cudgel of the Clairvoyant](/item/5141)


>**Hierophant Oxyn says:** We are in your debt,Soandso . You are truly one who shall collect all the lost ancient skulls. Take your weapon. Go to Hierophant Zand and he shall guide you further. Tell him you are [the chosen saviour].


* __Faction:__ [Scaled Mystics](/faction/445) (10)






* __Faction:__ [Legion of Cabilis](/faction/441) (5)






 **You receive:**  [Iron Cudgel of the Seer](/item/5142) (+60000 exp)

**This NPC *should* return incorrect items given.**
