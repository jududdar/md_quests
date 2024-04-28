# Arinna Trueblade
## Dialog

**You say:** `hail`



>**Arinna Trueblade says:** Well met, Soandso. I am Arianna Trueblade, Warlord of the Steel Warriors. I am personally in charge of all the training that our young warriors receive. I take pride in knowing that my teaching can help make the foundation of a Freeport Champion. If you are a [warrior] then we might just have something to talk about.

elseif(e.other:Class() == "Warrior" and eq.get_current_expansion() >= 4.0) then


**You say:** `warrior`




>**Arinna Trueblade says:** So you think you have what it takes to become one of Freeports finest? I will warn you now that we expect every single warrior that is brought into our ranks to go through a series of exercises. Rest assured you will be rewarded for your hard work with a set of armor that I will walk you though the process of making. Are you [ready to begin your testing]?


**You say:** `ready to begin`




>**Arinna Trueblade says:** Very well, Soandso. Here is your Steel Warriors Mail Kit. This kit will be your main tool in creating your own armor. You will gather various items from all areas of Freeport from monsters and stores alike. You will use specific item combinations in this kit to fashion together armor materials that you will combine in a forge with the appropriate mold to make an armor piece. Once you are ready to attempt a piece of armor simply tell me what piece you want to craft. I will then present you with the recipe and mold for Steel Warrior [Helms], [Bracers], [Armguards], [Boots], [Greaves], [Gauntlets] and [Breastplates].



**You receive:**  [Steel Warriors Mail Kit](/item/17262)


**You say:** `helm`




>**Arinna Trueblade says:** Any Steel Warrior that is caught not wearing a helm is usually placed on probation. We feel it is necessary sometimes to do this so that our younger ones in training will understand the importance of keeping your head well protected. To create your helm material you will need to combine two Bricks of Crude Iron Ore, one Rat Ear, one Meat Pie and one Barley in your assembly kit. Once you have created the proper material take it to a forge along with this mold to fashion your very own Steel Warriors Helm.



**You receive:**  [An Enchanted Helm Mold](/item/22610)


**You say:** `bracer`




>**Arinna Trueblade says:** As you progress further through your training you will find yourself in heavy battle more and more often. Bracers will ensure that you are able to fend off your opponents blows with minimum injury. To create your bracer material you will need to combine one Brick of Crude Iron Ore, one Rotting Zombie Skull, one Snake Bile and one Tiny Dagger in your assembly kit. Once you have created the proper material take it to a forge along with this mold to fashion your very own Steel Warriors Bracer.



**You receive:**  [An Enchanted Bracer Mold](/item/22611)


**You say:** `armguards`




>**Arinna Trueblade says:** A slash or gash to the arms can greatly hinder a warrior's combat abilities. Wearing these armguards will ensure that this does not happen. To create your armguard material you will need to combine two Bricks of Crude Iron Ore, two Young Kodiak Paws, one Young Plains Cat Scalp and one Freeport Stout in your assembly kit. Once you have created the proper material, take it to a forge along with this mold to fashion your very own Steel Warriors Armguards.



**You receive:**  [An Enchanted Armguard Mold](/item/22613)


**You say:** `boots`




>**Arinna Trueblade says:** Boots are very necessary for any warrior especially when you will usually be the one leading most combat units. Being on the front line and treading across terrains first make good boots a must. To create your boots material you will need to combine three Bricks of Crude Iron Ore, one Shadow Wolf Tibia and two Spiderling Eyes in your assembly kit. Once you have created the proper material take it to a forge along with this mold to fashion your very own Steel Warriors Boots.



**You receive:**  [An Enchanted Boot Mold](/item/22612)


**You say:** `greaves`




>**Arinna Trueblade says:** While most armor pieces are very vital to a young warriors survival, greaves are one of the most important armor pieces you will craft. To create your greaves material you will need to combine four Bricks of Crude Iron Ore, one Giant Fire Beetle Brain, one Lion Tail, one Bottle and one Young Puma Skin in your assembly kit. Once you have created the proper material take it to a forge along with this mold to fashion your very own Steel Warriors Greaves.



**You receive:**  [An Enchanted Greaves Mold](/item/22614)


**You say:** `gauntlets`




>**Arinna Trueblade says:** Keeping your hands well guarded is without question the most important thing a warrior will do. Suffering a blow to the hands that would prevent you from defending yourself would most certainly mean death. To create your gauntlet material you will need to combine three Bricks of Crude Iron Ore, one Armadillo Tail, one Severed Orc Foot, and two Spider Legs in your assembly kit. Once you have created the proper material take it to a forge along with this mold to fashion your very own Steel Warriors Gauntlets.



**You receive:**  [An Enchanted Gauntlet Mold](/item/22615)


**You say:** `breastplate`




>**Arinna Trueblade says:** Your dedication to learning everything about your class is impressive, Soandso. I have no doubt that you are ready to collect the pieces for your Steel Warriors Breastplate. To create your breastplate material you will need to combine five Bricks of Crude Iron Ore, one Deathfist Orc Skull, one Woven Spider Silk, one Armadillo Carapace, one Matted Lion Pelt and one Rusty Short Sword in your assembly kit. Once you have created the proper material take it to a forge along with this mold to fashion your very own Steel Warriors Breastplate. Please come back to see me after you are finished with your breastplate for your [final task].



**You receive:**  [An Enchanted Breastplate Mold](/item/22616)


**You say:** `final task`




>**Arinna Trueblade says:** I am in need of some assistance to craft a special sword that I would like to present all graduates of my training like yourself with. However. I don't have all the pieces I need to make one. If you could retrieve a Pristine Giant Scarab Leg, one Lion Paw and one Vial of Smoke I will have all I need to create this weapon. I would have no problem presenting you with the first if I was able to create it. See you soon.

end

## Turn-Ins



local expansion_flag = eq.get_current_expansion();


if(expansion_flag >= 4.0 and  **You turn in:** [Pristine Giant Scarab Leg](/item/9919), [Lion Paw](/item/9918), [Vial of Smoke](/item/9923)


>**Arinna Trueblade says:** Your determination to further your training and knowledge never ceases to amaze me. I knew I could count on you to retrieve these items for me. Luck was also on my side because I was able to craft the blade we spoke of before. May it protect you in all of your battles that await you. Excellent work Soandso.


* __Faction:__ [Steel Warriors](/faction/311) (25)


* __Faction:__ [Guards of Qeynos](/faction/262) (5)


* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (-3)


* __Faction:__ [The Freeport Militia](/faction/330) (-3)


* __Faction:__ [Knights of Truth](/faction/281) (5)


 **You receive:**  [Jagged Blade of the Steel Warrior](/item/9940) (+100 exp)

**This NPC *should* return incorrect items given.**
;

