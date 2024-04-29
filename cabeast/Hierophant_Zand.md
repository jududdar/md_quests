# Hierophant Zand


## Dialog

**You say:** `chosen savior`



if **Faction** >= Amiable then



>**Hierophant Zand says:** I am honored to meet the one who shall pledge his life to the return of the Skulls of the Ancients. However, I must see proof of our prowess as of yet. Go to the outlands and retrieve one Froglok Hexdoll, and no, they are not found on Frogloks. They are shaman dolls made by the goblin tribe.


elseif **Faction** >= Indifferent then



>**Hierophant Zand says:** You will only obtain that which you seek by assisting the wills of the Scaled Mystics.


else



**Hierophant Zand says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.




**You say:** `hail`



>*Hierophant Zand raises his hand and looks up.  'May the wisdom of the ancients lead your soul to suffering and everlasting pain.  Such is the will of Cazic-Thule.  I see something in your eyes, Hatz.  Have you lost something... your cudgel perhaps?*

**You say:** `no`



>**Hierophant Zand says:** That is good to hear.  Continue to follow the path of pain.  Suffering awaits.

**You say:** `yes`





>**Hierophant Zand says:** That is most unfortunate for you.  Your suffering will be extended on this plane, until you find your way back to us. Take this and read it on your way to speak with the Toilmaster.  He will guide you.  Yesssss...' You feel as if something is peering at you from behind the speaker's soulless eyes as the last letter he speaks transforms into a sigh.


**You receive:**  [A Ragged Book](/item/18271)





**You say:** `skulls of di nozok`



>**Hierophant Zand says:** What?! I have read of them, but that is all I know of the legendary mystic, err, mystics... whatever! Where their remains rest is a mystery, but those filthy goblins always seem to get ahold of things that are lost, all that infernal digging you see.


e.self:DoAnim(65);
end

## Turn-Ins



local text1 = "seems to black out, and then recover. He speaks with the voice of an ancient. 'We are Dai and Die and we await our skulls and your iron cudgel of the prophet. Become a channeler.";




if( **You turn in:** [Rites of Exoneration](/item/18272), [Filled Penance Bag](/item/24770)) then 


>*Hierophant Zand takes the bag and tome from you and in return gives you the item that you have been thinking of all of this time. 'Lucky you. You have earned a second chance. Praise Cazic-Thule!'*


 **You receive:**  [Iron Cudgel of the Petitioner](/item/5140) 







if **Faction** >= Amiable and  **You turn in:** [A Froglok Hex Doll](/item/12734)) then


>**Hierophant Zand says:** Fine work! I hope for your sake, you did not purchase it from a brave adventurer. Take this note to the one for whom it is written. This lizard has knowledge of a large number of skulls.


* __Faction:__ [Scaled Mystics](/faction/445) (10)






* __Faction:__ [Legion of Cabilis](/faction/441) (10)






 **You receive:**  [The Bone Garrison](/item/18054) (+80000 exp)




elseif **Faction** >= Amiable and  **You turn in:** [Iksar Skull Helm](/item/12741), [Iron Cudgel of the Prophet](/item/5144), [Iksar Skull](/item/12740)) then


>*Hierophant Zand closes his eyes and reopens them. They have no pupils. He speaks and you hear his voice echo. 'We are Di Nozok. You have earned the weapon of a channeler. We hope to fill your thoughts with ours some day. Go and seek out Dexl. We send you to him. Farewell , Channeler of Cabilis.*


* __Faction:__ [Scaled Mystics](/faction/445) (20)






* __Faction:__ [Legion of Cabilis](/faction/441) (5)






 **You receive:**  [Iron Cudgel of the Channeler](/item/5145) (+120000 exp)


**This NPC *should* return incorrect items given.**






