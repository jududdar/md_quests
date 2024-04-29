# Ebon Strongbear
## Dialog

if(eq.get_current_expansion() >= 4.0) then


**You say:** `hail`




>**Ebon Strongbear says:** Welcome. I am the champion of the Steel Warriors. There are none who can challenge me. I guide this brotherhood of Steel Warriors. From Qeynos to the trade city of Freeport, the ways of the Steel Warriors are taught. I welcome all [young Steel Warriors].


**You say:** `young steel warrior`




>**Ebon Strongbear says:** Then listen well to the words of the trainers of this arena. Learn to aid our friends such as the Knights of Thunder, the Priests of Life, the rangers and druids of Surefall Glade, the monks of the Silent Fist Clan and always support the Qeynos Guards for many of our brothers have entered their ranks. Oh yes.. You can also trust the bards of this city, after all, they do perform at all of our major events. If you are a [new recruit] I have some tasks for you to complete.


**You say:** `I am a new recruit`




>**Ebon Strongbear says:** I am always pleased to see new blood ready to serve the Steel Warriors. All new recruits are asked to go through training that I personally oversee. These training exercises will test both your mind body and spirit because they are not easily completed. If you are [ready to begin] I will explain to you how the tests work and present you with your Steel Warriors Assembly Kit.


**You say:** `ready to begin`




**You receive:**  [Steel Warriors Assembly Kit](/item/17268)



>**Ebon Strongbear says:** Here is your Steel Warriors Assembly Kit. In this kit you will combine numerous [magical items] that can be infused in certain quantities to create an armor material. These armor materials can then be placed in a forge along with the correct mold to fashion a piece of Battlemasters Platemail Armor.


**You say:** `What magical items`




>**Ebon Strongbear says:** The items you will need for your armor materials will be collected throughout the Qeynos area. You will find items that you need by hunting and by talking to local merchants. Once you are ready to begin collecting the items for an armor material you must simply tell me what piece you [want] to craft. I can provide you with the recipes and armor molds for Battlemasters Platemail [Helm], [Bracers], [Armguards], [Boots], [Greaves], [Gauntlets] and [Breastplate].


**You say:** `helm`




**You receive:**  [An Enchanted Helm Mold](/item/22610)



>**Ebon Strongbear says:** To create your helm material you will need to combine 2 Bricks of Crude Iron, 1 Giant Whiskered Bat Eye, 1 Snake Scales and 1 Brandy in your assembly kit. Once you have created the proper material take it to a forge along with this mold to fashion your very own Helm of the Battlemaster.


**You say:** `bracer`




**You receive:**  [An Enchanted Bracer Mold](/item/22611)



>**Ebon Strongbear says:** To create your bracer material you will need to combine 1 Brick of Crude Iron, 1 King Snake Poison Sac, 1 Gray Wolf Fang and 1 Rat Eye in your assembly kit. Once you have created the proper material take it to a forge along with this mold to fashion your very own Bracer of the Battlemaster.


**You say:** `armguard`




**You receive:**  [An Enchanted Armguard Mold](/item/22613)



>**Ebon Strongbear says:** To create your armguards material you will need to combine 2 Bricks of Crude Iron, 2 Rabid Grizzly Skins, 1 Giant Bat Wing and 1 Mistletoe in your assembly kit. Once you have created the proper material take it to a forge along with this mold to fashion your very own Armguards of the Battlemaster.


**You say:** `boot`




**You receive:**  [An Enchanted Boot Mold](/item/22612)



>**Ebon Strongbear says:** To create your boot material you will need to combine 3 Bricks of Crude Iron, 1 Gnoll Backbone and 2 Ruined Blackburrow Gnoll Pelt in your assembly kit. Once you have created the proper material take it to a forge along with this mold to fashion your very own Boots of the Battlemaster.


**You say:** `greave`




**You receive:**  [An Enchanted Greaves Mold](/item/22614)



>**Ebon Strongbear says:** To create your greaves material you will need to combine 4 Bricks of Crude Iron, 1 Giant Fire Beetle Brain, 1 Lion Tail, 1 Bottle and 1 Young Plains Cat Scalp in your assembly kit. Once you have created the proper material take it to a forge along with this mold to fashion your very own Greaves of the Battlemaster.


**You say:** `gauntlet`




**You receive:**  [An Enchanted Gauntlet Mold](/item/22615)



>**Ebon Strongbear says:** To create your gauntlet material you will need to combine 3 Bricks of Crude Iron, 1 Spider Legs, 1 Brown Bear Paw, and 2 Mist Wolf Pelts in your assembly kit. Once you have created the proper material take it to a forge along with this mold to fashion your very own Gauntlets of the Battlemaster.


**You say:** `breastplate`




**You receive:**  [An Enchanted Breastplate Mold](/item/22616)



>**Ebon Strongbear says:** To create your breastplate material you will need to combine 5 Bricks of Crude Iron, 1 Thick Grizzly Bear Skin, 1 Woven Spider Silk, 1 Burned Out Lightstone, 1 Matted Lion Pelt and 1 Golden Bandit Tooth in your assembly kit. Once you have created the proper material take it to a forge along with this mold to fashion your very own Breastplate of the Battlemaster. Once you have completed your breastplate and finished your armor please return to me for I have an [important mission] that I can only trust one of my finest warriors such as yourself with.


**You say:** `important mission`




>**Ebon Strongbear says:** I have heard word that the corrupt guards are up to it again and this time one has gone too far. Guard Beris has stolen my sisters coinpurse by claiming it was due for city tax. This is not true because my family is held in high regard here and we always pay our taxes promptly. This was simply a ploy to steal money and I do not take kindly to that. I must ask that you retrieve my sisters coinpurse from Beris, he can usually be found in the hills fishing on his off-duty time. Bring me whatever you can from him along with 3 perfect gnoll skins and I will reward you with a finely refined blade for your trouble.

end

## Turn-Ins



local expansion_flag = eq.get_current_expansion();

if( **You turn in:** [Recruitment Flyer](/item/18707)) then 


>**Ebon Strongbear says:** Welcome to the Hall of Steel, our swords are strong, and our warriors stronger. Here is our guild tunic. Brin Stolunger is in charge of our new recruits. Go see him, and he'll teach the basics. You look like you'll make a fine addition to our guild.


* __Faction:__ [Steel Warriors](/faction/311) (100)


* __Faction:__ [Guards of Qeynos](/faction/262) (20)


* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (-15)


* __Faction:__ [The Freeport Militia](/faction/330) (-15)


* __Faction:__ [Knights of Truth](/faction/281) (20)


 **You receive:**  [Dirty Training Tunic*](/item/13572) (+20 exp)

elseif(expansion_flag >= 4.0 and  **You turn in:** [Perfect Gnoll Skin](/item/27421), [Perfect Gnoll Skin](/item/27421), [Perfect Gnoll Skin](/item/27421), [A Studded Coin Purse](/item/27422)) then


>**Ebon Strongbear says:** I knew he would still have it, such an unintelligent one Beris is. As I promised I have crafted you a blade for your trouble. I hope you will promptly stain it with the blood of the gnolls. You have done well Soandso, good luck to you.





* __Faction:__ [Steel Warriors](/faction/311) (10)


* __Faction:__ [Guards of Qeynos](/faction/262) (2)


* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (-1)


* __Faction:__ [The Freeport Militia](/faction/330) (-1)


* __Faction:__ [Knights of Truth](/faction/281) (2)


 **You receive:**  [Warsword of the Battlemaster](/item/27492) (+500 exp)

**This NPC *should* return incorrect items given.**


