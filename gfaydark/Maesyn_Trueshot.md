# Maesyn Trueshot
## Dialog

**You say:** `hail`



>**Maesyn Trueshot says:** Welcome to Kelethin, Soandso! I am Maesyn Trueshot, commander of Faydark's Champions. We are the finest marksmen in all of Norrath. With our trusty [Trueshot longbows] we can miss no target regardless of the distance or the conditions.

**You say:** `trueshot longbows`



>**Maesyn Trueshot says:** The Trueshot Longbow was created by my famed father. Eldin Trueshot. It is quite accurate and takes a ranger's skill to wield. We use our new recruits to [gather materials] needed by my father.  We shall soon begin to release the formula to good elves so all may fletch such a bow.

**You say:** `correct component`



>**Maesyn Trueshot says:** Now that I have crafted the Treant Bow Staff, you shall need one Planing Tool, one Treant Bow Staff, one Micro Servo and one spool of Dwarven Wire. These items will be used with your Fletching Kit as all other bows. Be forewarned, only a Master Fletcher can create such a bow and even a master fails from time to time. Good Luck.

**You say:** `next incarnation`



>**Maesyn Trueshot says:** The Trueshot Longbow was once enchanted by the Koada'Dal enchanters.  Once it was enchanted now it is no more.  I am sure if you were ask the Koada'Dal [where the enchanted bows] are you will get an answer.

**You say:** `gather material`



if **Faction** >= Amiable then 



>**Maesyn Trueshot says:** Take this pack. Go to Kaladim, find Trantor Everhot and ask for dwarven wire. Then go to Freeport to meet Jyle Windshot. Search the inns for him and ask him for treant wood. Then, collect some spiderling silk from spiderlings and finally, in Steamfont, we have the permission of the gnomes to use any micro servos we find while destroying rogue spiders. Combine them all and return the pack to me.



**You receive:**  [Material Pack](/item/17951)


elseif( **Faction is** == Indifferent) then



>**Maesyn Trueshot says:** Faydark's Champions cannot call you foe. but you have yet to earn our trust.


else



>**Maesyn Trueshot says:** Your ways are considered vile to Faydark's Champions. Leave before my rage overcomes my restraint.

end

## Turn-Ins





if **Faction** >= Amiable and  **You turn in:** [Pack of Materials](/item/12112)) then 


>**Maesyn Trueshot says:** I shall see that my father gets the materials. I hope this can be of use to you. It will serve as your starting point toward fletching a Trueshot longbow. It is unfortunate that we are unable to enchant the bow to its [next incarnation], but it is still a fine weapon. You do know the [correct components] needed for fletching such a bow, do you not?


* __Faction:__ [Faydarks Champions](/faction/246) (5)


* __Faction:__ [King Tearis Thex](/faction/279) (1)


* __Faction:__ [Clerics of Tunare](/faction/226) (1)


* __Faction:__ [Soldiers of Tunare](/faction/310) (1)


* __Faction:__ [Crushbone Orcs](/faction/234) (-1)


 **You receive:**  [Treant Bow Staff](/item/8091) (+500 exp)

elseif( **You turn in:** [A tattered note](/item/18785)) then 


>**Maesyn Trueshot says:** Hail, Soandso, and welcome.. I am Maesyn Trueshot, leader of Faydark's Champions. I will teach and train you, as I have done for many others. Let's get started.. Here, put this on.. it'll help protect you from the elements. You look pretty bright. Train hard, and I'm sure you'll do well.


* __Faction:__ [Faydarks Champions](/faction/246) (100)


* __Faction:__ [King Tearis Thex](/faction/279) (25)


* __Faction:__ [Clerics of Tunare](/faction/226) (25)


* __Faction:__ [Soldiers of Tunare](/faction/310) (25)


* __Faction:__ [Crushbone Orcs](/faction/234) (-25)


 **You receive:**  [Dirty Green Tunic*](/item/13536) (+20 exp)

**This NPC *should* return incorrect items given.**


