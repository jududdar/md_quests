# Guard F\`Lok



[Guard F\`Lok](/npc/40081) is a level 35 Dark Elf Warrior that spawns in [Neriak - Commons](/zone/41).



## Dialog

**You say:** `supplies`



>**Guard F-Lok says:** The local guild houses should sell a few items, but the best place to visit would be the Commons Quarter.  It is filled with shops.

**You say:** `wizard guild`



>**Guard F-Lok says:** Here in the Commons Quarter is the Tower of the Spurned.  It is the home of the Spurned, Teir'Dal who choose to study enchanting, wizardry and magic.

**You say:** `weapons`



>**Guard F-Lok says:** I recommend the Blue Flame forge near Adamant Armor or you might try the Cauldron of Hate.

**You say:** `bank`



>**Guard F-Lok says:** You are in the correct quarter.  You can find the Burnished Coin within Neriak Down Under.

**You say:** `inn`



>**Guard F-Lok says:** This is no place for outsiders.  That is why the Smuggler's Inn is located in the Foreign Quarter.

**You say:** `warrior guild`



>**Guard F-Lok says:** Within this area you will find the Cauldron of Hate which is home to the Teir'Dal warriors.

**You say:** `indigo brotherhood`



>**Guard F-Lok says:** In the Commons Quarter can be found the Indigo Brotherhood, Teir'Dal warriors.  They are the armies of King Naythox Thex and serve as the trainers of the Dreadguard and dragoons.  Why the masters chose to build the Cauldron of Hate in that area and not the Third Gate is an amazement to me.

**You say:** `king`



>**Guard F-Lok says:** The mighty empire of the Teir'Dal is ruled by King Naythox Thex.  All hail Thex!

**You say:** `queen`



>**Guard F-Lok says:** Queen Cristanos is the queen of Neriak, of course!  She was the one who formed the necromancers and shadowknights into the guild called the Dead.

**You say:** `rogue guild`



>**Guard F-Lok says:** The Ebon Mask are the rogues of Neriak.  Their Hall of the Ebon Mask lies within the Third Gate.

**You say:** `cleric guild`



>**Guard F-Lok says:** When you enter the Third Gate you shall see the Spires of Innoruuk.  This is the temple of the Priests of Innoruuk.

**You say:** `the dead`



>**Guard F-Lok says:** The Dead are the shadowknights and necromancers of Neriak.  They were formed by Queen Cristanos herself.  Even among the Teir'Dal they are feared and they keep to themselves within the Lodge of the Dead in the Third Gate.  I have heard they take orders only from the queen.

**You say:** `tavern`



>**Guard F-Lok says:** There are quite a few taverns in the Commons Quarter.  I recommend either Toadstool's or the Blind Fish.

**You say:** `bard guild`



>**Guard F-Lok says:** A class of people lost in their mythical art.  They are nothing more than dust under the feet of the empire of the Teir'Dal.

**You say:** `paladin guild`



>**Guard F-Lok says:** Speak not of those vile paladins within Neriak!
end



## Signals

if(e.signal == 1) then


eq.stop();


eq.move_to(-630,-71,-24,162,true);

elseif(e.signal == 2) then


eq.start(36);
end



## Arrive at Waypoint Script

if(e.wp == 7) then


eq.get_entity_list():GetDoorsByDoorID(1):ForceOpen(e.self);


eq.get_entity_list():GetDoorsByDoorID(2):ForceOpen(e.self);


eq.get_entity_list():GetDoorsByDoorID(49):ForceOpen(e.self);
end