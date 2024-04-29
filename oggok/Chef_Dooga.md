# Chef Dooga
## Dialog

**You say:** `hail`



>**Chef Dooga says:** Welcome you. You look all skin 'n bones. Eat you must do. Chef Dooga can fix up goodies for you. Try [HEHE meat].

**You say:** `hehe meat`



>**Chef Dooga says:** It is a secret ground meat made with high elf, human, and Erudite Flesh. Mmmm. It good stuff. Dooga make it and [the Gobbler] make it. If you find any of those meats in the swamps bring to me and I pay you.

**You say:** `gobbler`



>**Chef Dooga says:** You no hear of the Gobbler!! Him great butcher. Have all kinds of meat. Him am low on froglok legs. Dooga supply him. Dooga need someone to [deliver froglok legs].

**You say:** `recipe`



>**Chef Dooga says:** Recipe, recipe, recipe!  All want Chef Dooga's recipes.  Me no give out secrets.  Only HEHE meat recipe me share.  Me share that only wit [the Gobbler].

**You say:** `apron`



>**Chef Dooga says:** Apron?! Me gots aprons, but dey no grow on trees. You bring Dooga proof you a butcher first. You makes me three portions of pickled froglok then me allow you to also pay me ten gold for apron.

**You say:** `froglok legs`



if **Faction** >= Indifferent then




>**Chef Dooga says:** You think so!! That be good thing. Make the Gobbler happy. Maybe he give you something good. Maybe not. You take this. Deliver meat.



**You receive:**  [Preserved Leg](/item/13384)


else



>**Chef Dooga says:** Come closer. Bouncer smash your head!

end

## Turn-Ins



local text = "Chef Dooga asks for three pickled frogloks and ten gold pieces for da ogre butcher apron.";




if( **You turn in:** [Human Flesh](/item/13364)) then 


>**Chef Dooga says:** MmmmMmm. Human make good meat pies. Here. A little coins for you.





* __Faction:__ [Clurg](/faction/228) (2)



* __Faction:__ [Kazon Stormhammer](/faction/274) (-2)



* __Faction:__ [Craknek Warriors](/faction/232) (2)



* __Faction:__ [Green Blood Knights](/faction/261) (2)



* __Faction:__ [Oggok Guards](/faction/337) (2)






 **You receive:** 0 (+10000 exp)

elseif( **You turn in:** [High Elf Flesh](/item/13365)) then 


>**Chef Dooga says:** High elf!! Now that is a good meat.  Goes good with Ogre Swill.





* __Faction:__ [Clurg](/faction/228) (2)



* __Faction:__ [Kazon Stormhammer](/faction/274) (-2)



* __Faction:__ [Craknek Warriors](/faction/232) (2)



* __Faction:__ [Green Blood Knights](/faction/261) (2)



* __Faction:__ [Oggok Guards](/faction/337) (2)





 **You receive:** 0 (+10000 exp)

elseif( **You turn in:** [Pickled Froglok](/item/13452), [Pickled Froglok](/item/13452), [Pickled Froglok](/item/13452), platinum = 1) then


>**Chef Dooga says:** Here is da ogre butcher apron. Gos and cook.





* __Faction:__ [Clurg](/faction/228) (5)



* __Faction:__ [Kazon Stormhammer](/faction/274) (-5)



* __Faction:__ [Craknek Warriors](/faction/232) (5)



* __Faction:__ [Green Blood Knights](/faction/261) (5)



* __Faction:__ [Oggok Guards](/faction/337) (5)





 **You receive:**  [Ogre Butcher Apron](/item/12217) (+10000 exp)

**This NPC *should* return incorrect items given.**





