# Tilania Shadowwalker
## Dialog

if(eq.get_current_expansion() >= 4.0) then


**You say:** `hail`




>**Tilania Shadowwalker says:** Greetings to you Soandso. I welcome you to the Scouts of Tunare training halls. I have seen many scouts pass through my halls with unimaginable abilities and daggers guided by Tunare herself. I cannot say for certain what the future has in store for you. But I can say that wherever your adventures may take you it is always wise to have the proper [training].


**You say:** `training`




>**Tilania Shadowwalker says:** The training that I speak of is only intended for rogues of Tunare that wish to develop skills that will mold them into the most deadly assassins in all of the lands. If you are a [rogue of Tunare] then I will be happy to explain the training exercises to you. However. if you are not a rogue I suggest you seek training from another house.


**You say:** `i am a rogue of tunare`




>**Tilania Shadowwalker says:** Excellent Soandso. let us get started then. Your training will test your fighting and gathering skills respectively. because of the items you will be required to gather all over the Faydark for [magical armor materials].


**You say:** `magical armor materials`




>**Tilania Shadowwalker says:** First things first. here is your Assassins Mail Assembly Kit. Inside this kit you will combine different magical items. which in certain quantities in your mail kit can create armor materials for specific pieces of Tunarean Scouts Armor. Once you have completed a specific armor material you can then place it in a forge with the applicable pattern to create your piece of armor.[continue]



**You receive:**  [Assassins Mail Assembly Kit](/item/17365)


**You say:** `continue`




>**Tilania Shadowwalker says:** Simply tell me what armor piece you [want] to craft and I can provide you with the material recipes and armor patterns for [Coifs][Bracers][Sleeves][Boots][Legplates][Gauntlets] and [Tunics].


**You say:** `coif`




>**Tilania Shadowwalker says:** To create your coif material you will need to combine 2 Bricks of Crude Bronze. 1 Pixie Wing . 1 Ruined Wolf Pelt and 1 Bottle in your assembly kit. Once you have created the proper material take it to a forge along with this mold to fashion your very own Coif of the Tunarean Scout.



**You receive:**  [An Enchanted Coif Pattern](/item/22671)


**You say:** `bracer`




>**Tilania Shadowwalker says:** To create your bracer material you will need to combine 1 Brick of Crude Bronze. 2 Wasp Wings. 1 Faerie Wing and 1 Cask in your assembly kit. Once you have created the proper material take it to a forge along with this mold to fashion your very own Bracer of the Tunarean Scout.



**You receive:**  [An Enchanted Bracer Pattern](/item/22672)


**You say:** `sleeve`




>**Tilania Shadowwalker says:** To create your sleeves material you will need to combine 2 Bricks of Crude Bronze. 1 Fairy Dust and 1 Royal Jelly and 1 Elven Wine in your assembly kit. Once you have created the proper material take it to a forge along with this mold to fashion your very own Sleeves of the Tunarean Scout.



**You receive:**  [An Enchanted Sleeves Pattern](/item/22673)


**You say:** `boot`




>**Tilania Shadowwalker says:** To create your boots material you will need to combine 3 Bricks of Crude Bronze. 1 Basilisk Hatchling Hide. 1 Orc Hatchet and 1 Bottle of Milk in your assembly kit. Once you have created the proper material take it to a forge along with this mold to fashion your very own Boots of the Tunarean Scout.



**You receive:**  [An Enchanted Boots Pattern](/item/22674)


**You say:** `legplate`




>**Tilania Shadowwalker says:** To create your legplates material you will need to combine 4 Bricks of Crude Bronze. 2 Orc Eyes. 1 Orc Scalp and 1 Raw Bamboo in your assembly kit. Once you have created the proper material take it to a forge along with this mold to fashion your very own Legplates of the Tunarean Scout.



**You receive:**  [An Enchanted Legplates Pattern](/item/22675)


**You say:** `gauntlet`




>**Tilania Shadowwalker says:** To create your gauntlets material you will need to combine 3 Bricks of Crude Bronze. 1 Orc Head. 1 Orc Skull . and 2 Bat Wings in your assembly kit. Once you have created the proper material take it to a forge along with this mold to fashion your very own Gauntlets of the Tunarean Scout.



**You receive:**  [An Enchanted Gauntlets Pattern](/item/22676)


**You say:** `tunic`




>**Tilania Shadowwalker says:** To create your tunic material you will need to combine 5 Bricks of Crude Bronze. 1 Coyote Skull. 1 Orc Ribcage. 1 Pristine Forest Drakeling Scale. 1 Crushbone Shoulderpads and 1 Golden Bandit Tooth in your assembly kit. Once you have created the proper material take it to a forge along with this mold to fashion your very own Tunic of the Tunarean Scout. Please return to me after you have completed your tunic. for I have one final [favor] to ask of you.



**You receive:**  [An Enchanted Tunic Pattern](/item/22677)


**You say:** `favor`




>**Tilania Shadowwalker says:** I have recently been trying my hand at weaponcrafting and I can say that it is going quite well. Before I can practice my skills however I need some [specific items] that will enable me to begin crafting daggers for our young scouts like yourself that have completed the training exercises.


**You say:** `specific item`




>**Tilania Shadowwalker says:** In order to craft some more daggers I am in need of 1 Preserved Orc Hide and 2 Rotting Orc Teeth. You can most likely find these items on the vile orcs that inhabit the Faydark and Clan Crushbone of course. Bring me these items and I will reward you with a training dagger of the finest quality.

end

## Turn-Ins



local expansion_flag = eq.get_current_expansion();



if(expansion_flag >= 4.0 and  **You turn in:** [Preserved Orc Hide](/item/27535), [Rotting Orc Tooth](/item/27536), [Rotting Orc Tooth](/item/27536)


>**Tilania Shadowwalker says:** Excllent!  Here's your reward.


 **You receive:**  [Tunarean Scouts Training Dagger](/item/27530) (+500 exp)


**This NPC *should* return incorrect items given.**

