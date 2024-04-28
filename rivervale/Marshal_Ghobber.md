# Marshal Ghobber
## Dialog


**You say:** `hail`



>**Marshal Ghobber says:** Greetings!  Allow me to introduce myself.  I am Marshal Ghobber Truppack.  Marshal of the Great Wall Patrol.  Are you [new to the squad]?

**You say:** `new to the squad`



if **Faction** >= Amiable then 



>**Marshal Ghobber says:** Great!!! We require more deputies in this squad. We are suffering great losses to the [new threat]. Welcome to the Great Wall Patrol where our motto is, 'United we shall defend.' It will be some time before you can earn your squad ring - first you must prove your strength in battle. Report to the squad leader. He is Deputy Budo. You can find him at the Great Wall of Serilis in the Misty Thicket. Go to him at once and tell him you are reporting for duty.


elseif **Faction** >= Indifferent then 



>**Marshal Ghobber says:** You are in good standing with the Guardians of the Vale. Continue with your good work and then we may speak.




else



>**Marshal Ghobber says:** How can you expect to just waltz into Guardian Stronghold and expect to gather information?! Consider yourself lucky I don't command the Guardian of the Vale deputies to show you the sharpness of their blades!


**You say:** `one with the wall`



if **Faction** >= Ally +100 then



* __Faction:__ [Guardians of the Vale](/faction/263) (-1000)



>**Marshal Ghobber says:** Yes!! Welcome, Deputy Soandso! You are now an elite member of the Great Wall Division. Wear this ring with pride. You may take it to Hendi Mrubble of the Clerics of Mischief for healing at any time. Wear it with pride.



**You receive:**  [Squad Ring](/item/13936)


elseif **Faction** >= Indifferent then 



>**Marshal Ghobber says:** You are in good standing with the Guardians of the Vale. Continue with your good work and then we may speak.




else



>**Marshal Ghobber says:** How can you expect to just waltz into Guardian Stronghold and expect to gather information?! Consider yourself lucky I don't command the Guardian of the Vale deputies to show you the sharpness of their blades!


**You say:** `new threat`



>**Marshal Ghobber says:** The new threat I refer to is the community of goblins which was found beyond the Great Wall of Serilis. They are called Clan Runnyeye. They have begun to sneak over the wall. The deputies have reported seeing them launch themselves up the wall in a matter of seconds using ornate grappling hooks. We have attempted to obtain one of these devices for further inspection, but we have yet to find one on any of the dead goblins. If you should ever find one, be sure to bring it to me immediately.

**You say:** `freeport`



>**Marshal Ghobber says:** You can find Freeport beyond Kithicor Forest on the other side of the Commonlands.
end

## Turn-Ins



**This NPC *should* return incorrect items given.**


