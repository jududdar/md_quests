# Narron Jenork




## Dialog

if(eq.get_current_expansion() >= 4.0) then


**You say:** `hail`




>**Narron Jenork says:** Pleased to meet you, Soandso! I am Narron Jenork, High Watchman of Ak'anon. I am one of the most skilled Watchmans in all of Ak'anon, and I pride myself on training the most promising young warriors that Ak'anon has to offer. Are you a young gnome warrior?


**You say:** `young gnome warrior`




>**Narron Jenork says:** Well, we can never get enough warriors around these parts, as far as I am concerned! Now if you are a new warrior, then you must go through the training to become a true watchman. I have a series of tests that will require you to test both your hunting and navigational skills. These tests will not leave you with nothing to show for your work, because upon completing them you will be outfitted with a full suit of Initiate Watchman's armor. Are you [ready to be tested]?


**You say:** `ready to be tested`




>**Narron Jenork says:** Well then, let's get you started! First, I will present you with this Watchman's Mail Assembly kit to gather assorted items from both your training grounds of the Steamfont Mountains and in our great town of Ak'anon. You will then combine the different recipes of components in your kit to create a material that will be used with a mold in a forge to create your Watchman armor. When you are ready to craft a specific piece, all you must do is tell me what armor piece you want to craft, and I will present you with the recipe for the material, along with the mold. I have the material recipes necessary to make Initiate Watchman [Helms], [Bracers], [Armguards], [Boots], [Greaves], [Gauntlets] and [Breastplates].



**You receive:**  [Watchmans Mail Assembly Kit](/item/17255)


**You say:** `helm`




>**Narron Jenork says:** No watchman can even think of going into battle without the proper helmet, and I think this one will do the job for you, Soandso. To create your helm material, you will need to combine 2 Bricks of Crude Bronze, 1 Piece of Scrap Metal, 1 Ruined Cat Pelt and 1 Raw Bamboo in your assembly kit. Once you have created the proper material, take it to a forge along with this mold to fashion your very own Initiate Watchman's Helm.



**You receive:**  [An Enchanted Helm Mold](/item/22610)


**You say:** `bracer`




>**Narron Jenork says:** Always a wise idea to keep your wrists well protected, because if you don't, you might have a difficult time swinging your weapons! To create your bracer material, you will need to combine 1 Brick of Crude Bronze, 1 Rusty Mace, 1 Kobold Tooth and 1 Bottle of Milk in your assembly kit. Once you have created the proper material, take it to a forge along with this mold to fashion your very own Initiate Watchman's Bracer.



**You receive:**  [An Enchanted Bracer Mold](/item/22611)


**You say:** `armguard`




>**Narron Jenork says:** One always has to be able to really pack a punch with their attacks, so preventing any injuries on your arms ahead of time is good planning! To create your armguards material, you will need to combine 2 Bricks of Crude Bronze, 2 Brownie Legs, and 1 Short Beer in your assembly kit. Once you have created the proper material, take it to a forge along with this mold to fashion your very own Initiate Watchman's Armguards.



**You receive:**  [An Enchanted Armguard Mold](/item/22613)


**You say:** `boots`




>**Narron Jenork says:** I certainly wouldn't advise any watchman to be on patrol without proper boots on. We aren't halflings, you know! Therefore our obsession should be with our tactical attacks, not our foothairs. To create your boot material, you will need to combine 3 Bricks of Crude Bronze, 1 Aviak Beak, 2 Wolf Meats and 1 Red Wine in your assembly kit. Once you have created the proper material, take it to a forge along with this mold to fashion your very own Initiate Watchman's Boots.



**You receive:**  [An Enchanted Boot Mold](/item/22612)


**You say:** `greaves`




>**Narron Jenork says:** Pants are a must, young Soandso. As a Watchman of Ak'anon, you should be known for your noble deeds and commitment to defending your home, not as a gnome that runs around with no pants on. To create your greaves material, you will need to combine 4 Bricks of Crude Bronze, 1 Coyote Pelt, 1 Rusted Blackbox and 1 Bottle in your assembly kit. Once you have created the proper material, take it to a forge along with this mold to fashion your very own Initiate Watchman's Greaves.



**You receive:**  [An Enchanted Greaves Mold](/item/22614)


**You say:** `gauntlets`




>**Narron Jenork says:** Having the necessary protection on your hands and wrists will prevent any serious injuries that would make you unable to defend yourself. To create your gauntlet material, you will need to combine 3 Bricks of Crude Bronze, 1 Runaway Clockwork Gearbox, 1 Young Ebon Drakewing, and 1 Minotaur Scalp in your assembly kit. Once you have created the proper material, take it to a forge along with this mold to fashion your very own Initiate Watchman's Gauntlets.



**You receive:**  [An Enchanted Gauntlet Mold](/item/22615)


**You say:** `breastplate`




>**Narron Jenork says:** I am very pleased to see that you have progressed so quickly in your training, Soandso! I do also agree that you are ready to gather the items necessary for crafting your Initiate Watchman's Breastplate. To create your breastplate material, you will need to combine 5 Bricks of Crude Bronze, 1 Runaway Clockwork Motor, 1 Brownie Brain, 1 Rusty Long Sword, 1 Grikbar Kobold Scalp and the evil Diloperia\`s Bracer in your assembly kit. Once you have created the proper material, take it to a forge along with this mold to fashion your very own Initiate Watchman's Breastplate. When you are finished with your breastplate, please come back to see me. I have a [final task] for you to complete.



**You receive:**  [An Enchanted Breastplate Mold](/item/22616)


**You say:** `final task`




>**Narron Jenork says:** Much like most of the other guildmasters in our great city, we have decided to begin presenting all new worthy recruits with weapons that symbolize their devotion to Ak'anon. I am in need of a [few items] from the mountains to make this weapon. If you will collect these items for me, I will be happy to reward you with one of these fine weapons.


**You say:** `few items`




>**Narron Jenork says:** I will need for you to bring me 1 Clockwork Oil Extract, 1 Minotaur Tibia, 1 Young Ebon Drake Ribcage and 1 Renegade Clockwork Scrapmetal. Return to me after you have gathered this items and I will reward you with your weapon.


else


**You say:** `hail`




>**Narron Jenork says:** Pleased to meet you, Soandso! I am Narron Jenork, High Watchman of Ak'anon. I am one of the most skilled Watchmans in all of Ak'anon, and I pride myself on training the most promising young warriors that Ak'anon has to offer.



end

## Turn-Ins



local expansion_flag = eq.get_current_expansion();



if(expansion_flag >= 4.0 and  **You turn in:** [Clockwork Oil Extract](/item/9111), [Minotaur Tibia](/item/9112), [Young Ebon Drake Ribcage](/item/9113), [Renegade Clockwork Scrapmetal](/item/9114)) then


>**Narron Jenork says:** Well done, young Soandso! Since you have brought me the necessary items, I now present you with this Initiate Watchman's Long Sword. Use it worthily.


* __Faction:__ [Gem Choppers](/faction/255) (25)



* __Faction:__ [Merchants of Ak`Anon](/faction/288) (6)



* __Faction:__ [King Ak`Anon](/faction/333) (6)



* __Faction:__ [Dark Reflection](/faction/238) (-6)



* __Faction:__ [Clan Grikbar](/faction/1604) (-1)


 **You receive:**  [Initiate Watchmans Long Sword](/item/9115) 

elseif( **You turn in:** [Box of Undead Brownie Bones](/item/12378)) then 


>**Narron Jenork says:** Wonderful!! Watchman Dexlin sent word that you would be returning these specimens. I shall see that the Eldritch Collective gets them.  For you there is a reward. Manik has donated a pair of Watchman Boots!!


* __Faction:__ [Gem Choppers](/faction/255) (20)



* __Faction:__ [Merchants of Ak`Anon](/faction/288) (5)



* __Faction:__ [King Ak`Anon](/faction/333) (5)



* __Faction:__ [Dark Reflection](/faction/238) (-5)



* __Faction:__ [Clan Grikbar](/faction/1604) (-1)


 **You receive:**  [Watchman Boots](/item/12379) (+10000 exp)


**This NPC *should* return incorrect items given.**
