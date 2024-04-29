# Samatansyn Flamecaller
## Dialog

if(eq.get_current_expansion() >= 4.0) then


**You say:** `hail`




>**Samatansyn Flamecaller says:** It is a pleasure to meet you Soandso, I am Samatansyn Flamecaller, Warder of Tunare and Guildmaster of Faydarks Champions. I have studied here for many of my years until recently when I took up teaching. I have many pupils that undergo my vigorous [training exercises].


**You say:** `training exercises`




>**Samatansyn Flamecaller says:** I have a series of tests that all new rangers of Kelethin are suggested to participate in. These tests will help you develop many of your skills including hunting and gathering and will also provide you with a chance to fashion your own Trueshot Chainmail. If you are a [ranger of Tunare] and are willing to begin your training I will be happy to explain to you how the tests work.


**You say:** `ranger of tunare`




>**Samatansyn Flamecaller says:** Excellent Soandso, then lets get started! Here is your Trueshot Assembly Kit. You will collect various items from the Faydark and Clan Crushbone that will be necessary for creating your armor materials in your assembly kit. Once you have fashioned together a specific armor material you can then take it to a forge along with the applicable pattern to create your Trueshot Chainmail armor piece. Simply tell me what armor piece you [want] to craft and I can provide you with the material recipes and patterns for Trueshot Chainmail [Coifs], [Bracers], [Sleeves], [Boots], [Legplates], [Gauntlets] and [Tunics].



**You receive:**  [Trueshot Assembly Kit](/item/17367)


**You say:** `coif`




>**Samatansyn Flamecaller says:** To create your coif material you will need to combine 2 Bricks of Crude Bronze, 1 Royal Jelly, 1 Spiderling Eye and 1 Ration in your assembly kit. Once you have created the proper material take it to a forge along with this mold to fashion your very own Trueshot Coif.



**You receive:**  [An Enchanted Coif Pattern](/item/22671)


**You say:** `bracer`




>**Samatansyn Flamecaller says:** To create your bracer material you will need to combine 1 Brick of Crude Bronze, 1 Skeleton Tibia, 1 Pixie Wing and 1 Gypsy Wine in your assembly kit. Once you have created the proper material take it to a forge along with this mold to fashion your very own Trueshot Chainmail Bracer.



**You receive:**  [An Enchanted Bracer Pattern](/item/22672)


**You say:** `sleeve`




>**Samatansyn Flamecaller says:** To create your sleeves material you will need to combine 2 Bricks of Crude Bronze, 2 Giant Wasp Venom Sacs, 1 Large Widow Abdomen and 1 White Wine in your assembly kit. Once you have created the proper material take it to a forge along with this mold to fashion your very own Trueshot Chainmail Sleeves.



**You receive:**  [An Enchanted Sleeves Pattern](/item/22673)


**You say:** `boot`




>**Samatansyn Flamecaller says:** To create your boots material you will need to combine 3 Bricks of Crude Bronze, 1 Severed Orc Foot, 2 Spider Legs in your assembly kit. Once you have created the proper material take it to a forge along with this mold to fashion your very own Trueshot Chainmail Boots.



**You receive:**  [An Enchanted Boots Pattern](/item/22674)


**You say:** `legplates`




>**Samatansyn Flamecaller says:** To create your legplates material you will need to combine 4 Bricks of Crude Bronze, 1 Orc Fibula, 1 Orc Clavicle, and 1 Lightstone in your assembly kit. Once you have created the proper material take it to a forge along with this mold to fashion your very own Trueshot Chainmail Legplates.



**You receive:**  [An Enchanted Legplates Pattern](/item/22675)


**You say:** `gauntlet`




>**Samatansyn Flamecaller says:** To create your gauntlets material you will need to combine 3 Bricks of Crude Bronze, 1 Orc Ulna, 1 Orc Tibia, and 2 Orc Finger Bones in your assembly kit. Once you have created the proper material take it to a forge along with this mold to fashion your very own Trueshot Chainmail Gauntlets.



**You receive:**  [An Enchanted Gauntlets Pattern](/item/22676)


**You say:** `tunic`




>**Samatansyn Flamecaller says:** To create your tunic material you will need to combine 5 Bricks of Crude Bronze, 1 Orc Fibula, 1 Golden Bandit Tooth, 1 Pristine Forest Drakeling Scale, 1 Orc Ribcage and 1 Orc Eye in your assembly kit. Once you have created the proper material take it to a forge along with this mold to fashion your very own Trueshot Chainmail Tunic. Please return to me after you have completed your tunic, for I have one final [favor] to ask of you.



**You receive:**  [An Enchanted Tunic Pattern](/item/22677)


**You say:** `favor`




>**Samatansyn Flamecaller says:** I have received word that there are numerous elves being held hostage in the confines of Clan Crushbone, beaten and forced to perform slave work under horrible conditions. There is believed to be a specific Orc that patrols the jail cells that has a master key in his possession for all of the elven hostages. If you were to retrieve this master key for me I would possibly be able to make copies of it and distribute them to my task force so that we may attempt to rescue our helpless bretheren. Will you [retrieve the master key]?


**You say:** `retrieve the master key`




>**Samatansyn Flamecaller says:** Excellent news, I was afraid I would not be able to find someone willing to help. Please bring me the master key along with 2 Orc Eyes and I shall craft you a long sword worthy of your great deeds.

end

## Turn-Ins



local expansion_flag = eq.get_current_expansion();



if(expansion_flag >= 4.0 and  **You turn in:** [Master Crushbone Cell Key](/item/27539), [Orc Eye](/item/13266), [Orc Eye](/item/13266)) then 


>**Samatansyn Flamecaller says:** Well done, Soandso! Now we will be able to free more of our brothers and sisters from the orcs! Take this, as promised, a fine weapon with which to slay more orcs!!


 **You receive:**  [Faydark Champions Long Sword](/item/27532) (+7000 exp)

**This NPC *should* return incorrect items given.**

