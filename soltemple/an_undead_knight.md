# an undead knight


## Dialog

**You say:** `Hail`



>**an undead knight says:** Away from this place of torment!  Make haste and flee before you, too, share my [gruesome fate]!!

**You say:** `gruesome fate`



>**an undead knight says:** I was once a proud shadowknight, but failed I did in my master's quest.  I was sent into a lizard fortress deep in the swamplands.  I was to seek out an ancient item for my master.  I failed and was captured. The lizards stripped me of my [darkforge armor] and planned to boil me alive.  Before they could do so, I escaped.  Upon my return to my master's lair I found myself in a [worse predicament].

**You say:** `worse predicament`



>**an undead knight says:** I was torn apart by my master and my bones were given as toys to my master's associates!!  I am now only half Grandyf the Vile.  My hands, feet and legs were sent here and assembled with spare bones of other unfortunates.  Since this is the case, I can only [create darkforge armor] in the form of boots, greaves and gauntlets.

**You say:** `create darkforge armor`



>**an undead knight says:** I and I alone have the power to create darkforge armor!!  It was crafted for me so naturally it is to be worn by shadowknights only.  My armor was taken by the lizardman crusaders.  Unfortunately for them, it lost all power and cannot be worn.  I would be glad to see it put to good use. Do you [seek the darkforge armor]?

**You say:** `seek the darkforge armor`



>**an undead knight says:** Darkforge gauntlets require both of my decayed gauntlets and one enchanted platinum bar.  For the darkforge greaves, I will need both decayed legplates and two pieces of melatite from the Solusek Mining Company.  For the boots, I need both my decayed boots and two parts of fairy dust.
end

## Turn-Ins



local text1 = "Two portions of fairy dust and the right and left decayed boots!!";




if( **You turn in:** [Decayed Left Gauntlet](/item/12292), [Decayed Right Gauntlet](/item/12291), [Enchanted Platinum Bar](/item/16507)) then


>**an undead knight says:** Well done, Soandso, here is your reward.


 **You receive:**  [Darkforge Gauntlets](/item/3144) (+5000 exp)

if( **You turn in:** [Decayed Left Legplate](/item/12294), [Decayed Right Legplate](/item/12293), [Melatite](/item/12297), [Melatite](/item/12297)) then


>**an undead knight says:** You have been granted the darkforge greaves!!


 **You receive:**  [Darkforge Greaves](/item/3145) (+5000 exp)

if( **You turn in:** [Decayed Left Boot](/item/12296), [Decayed Right Boot](/item/12295), [Fairy Dust](/item/12106), [Fairy Dust](/item/12106)) then


>**an undead knight says:** You may now wear the darkforge boots!!


 **You receive:**  [Darkforge Boots](/item/3146) (+5000 exp)

**This NPC *should* return incorrect items given.**






