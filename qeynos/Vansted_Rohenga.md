# Vansted Rohenga
## Dialog

if(eq.get_current_expansion() >= 4.0) then


**You say:** `hail`




>**Vansted Rohenga says:** Pleased to meet you Soandso. I am Vansted Rohenga High Priest of Karana. I have spent all of my years studying the ways of the Cleric in our wonderful Temple of Thunder. We receive many new recruits every day and it is my duty to place them in my [training program].


**You say:** `training program`




>**Vansted Rohenga says:** Well all young clerics of Karana are brought up from their first day of training to know and respect their practice. I have developed a number of exercises that will enable a young cleric to make a set of their own armor by means of collecting certain items and making [enchanted armor materials] out of them.


**You say:** `enchanted armor materials`




>**Vansted Rohenga says:** Recently we have discovered that combing certain items in certain quantities using a magical assembly kit can forge together an armor material. These armor materials are used with specific armor molds to create a piece of enchanted Stormhealer Armor. If you would like to [begin forging armor materials] I will present you with your Stormhealers Assembly Kit.


**You say:** `begin forging armor materials`




>**Vansted Rohenga says:** Excellent Soandso, please take this Stormhealers Assembly Kit. It is in this kit that you will combine certain items together into materials necessary for crafting your armor. I can present you with the material recipes and armor molds for Stormhealer [Helms], [Bracers], [Armguards], [Boots], [Greaves], [Gauntlets] and [Breastplates]. When you are ready to gather the items for an armor piece simply tell me what piece you [want] to craft. Once you have created a specific material take it to a forge along with the applicable mold to create your armor piece.



**You receive:**  [Stormhealers Assembly Kit](/item/17265)


**You say:** `helms`




>**Vansted Rohenga says:** Here is your Stormhealers Helm Mold. To create your helm material you will need to combine 2 Bricks of Crude Iron, 1 Field Rat Ribcage, 1 Rat Tooth and 1 Honey Mead in your assembly kit. Once you have created the proper material take it to a forge along with this mold to fashion your very own Helm of the Stormhealer.



**You receive:**  [An Enchanted Helm Mold](/item/22610)


**You say:** `bracers`




>**Vansted Rohenga says:** Here is your Stormhealers Bracer Mold. To create your bracer material you will need to combine 1 Brick of Crude Iron, 1 Field Rat Skull, 1 Coyote Skull and 1 Grapes in your assembly kit. Once you have created the proper material take it to a forge along with this mold to fashion your very own Bracer of the Stormhealer.



**You receive:**  [An Enchanted Bracer Mold](/item/22611)


**You say:** `armguard`




>**Vansted Rohenga says:** Here is your Stormhealers Armguard Mold. To create your armguards material you will need to combine 2 Bricks of Crude Iron, 2 Whiskered Bat Fangs, and 1 Torch in your assembly kit. Once you have created the proper material take it to a forge along with this mold to fashion your very own Armguards of the Stormhealer.



**You receive:**  [An Enchanted Armguard Mold](/item/22613)


**You say:** `boot`




>**Vansted Rohenga says:** Here is your Stormhealers Boot Mold. To create your boot material you will need to combine 3 Bricks of Crude Iron, 1 Ruined Blackburrow Gnoll Pelt, 2 Gnoll Fangs in your assembly kit. Once you have created the proper material take it to a forge along with this mold to fashion your very own Boot of the Stormhealer.



**You receive:**  [An Enchanted Boot Mold](/item/22612)


**You say:** `greave`




>**Vansted Rohenga says:** Here is your Stormhealers Greaves Mold. To create your greaves material you will need to combine 5 Bricks of Crude Iron, 1 Giant Fire Beetle Brain, 1 Shadow Wolf Paw, 1 Bottle and 1 Raw Bamboo in your assembly kit. Once you have created the proper material take it to a forge along with this mold to fashion your very own Greaves of the Stormhealer.



**You receive:**  [An Enchanted Greaves Mold](/item/22614)


**You say:** `gauntlet`




>**Vansted Rohenga says:** Here is your Stormhealers Gauntlet Mold. To create your gauntlet material you will need to combine 3 Bricks of Crude Iron, 1 Puma Skin, 1 Bear Meat, and 1 Bandit Sash in your assembly kit. Once you have created the proper material take it to a forge along with this mold to fashion your very own Gauntlets of the Stormhealer.



**You receive:**  [An Enchanted Gauntlet Mold](/item/22615)


**You say:** `breastplate`




>**Vansted Rohenga says:** Here is your Stormhealers Breastplate Mold. To create your breastplate material you will need to combine 5 Bricks of Crude Iron, 1 Young Plains Cat Scalp, 1 Low Quality Bear Skin, 1 Water Flask 1 Lock of Scarecrow Straw and 1 Giant Fire Beetle Carapace in your assembly kit. Once you have created the proper material take it to a forge along with this mold to fashion your very own Breastplate of the Stormhealer. Please come back to see me after you have completed your breastplate. I have a [final favor] to ask of you.



**You receive:**  [An Enchanted Breastplate Mold](/item/22616)


**You say:** `favor`




>**Vansted Rohenga says:** I thank you for returning to assist me in this very important task. It has come to my attention that the gnolls of Blackburrow are planning an attack on Qeynos sometime in the near future. Although I know that these hairballs posses no actual fighting skills, they can present a problem for the defenders of our city just due to sheer numbers. I need you to infiltrate Blackburrow and retrieve some [important documents] for me.


**You say:** `important document`




>**Vansted Rohenga says:** There is a believed to be a gnoll tactician somewhere in the gnoll camp of Blackburrow. I need you to bring whatever battle plans he may be in possession of so that I can position my troops accordingly. Return to me with whatever battle plans you can find along with 2 Gnoll Backbones and I will surely reward you for your dedication.



## Turn-Ins




local expansion_flag = eq.get_current_expansion();

if(expansion_flag >= 4.0 and  **You turn in:** [Blackburrow Battle Plans](/item/27416), [Gnoll Backbone](/item/27405), [Gnoll Backbone](/item/27405)) then


>**Vansted Rohenga says:** These are exactly what I was looking for Soandso! I am very proud to have one as noble as yourself amongst our ranks! Please take this mace as a token of my appreciation. I bid you farewell, and safe travels.





* __Faction:__ [Knights of Thunder](/faction/280) (10)


* __Faction:__ [Bloodsabers](/faction/221) (-10)


* __Faction:__ [Priests of Life](/faction/341) (7)


* __Faction:__ [Guards of Qeynos](/faction/262) (7)


 **You receive:**  [Stormhealers Mace](/item/27489) (+500 exp)

**This NPC *should* return incorrect items given.**


