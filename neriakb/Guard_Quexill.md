# Guard Quexill



[Guard Quexill](/npc/40047) is a level 35 Dark Elf Warrior that spawns in [Neriak - Commons](/zone/41).



## Dialog

**You say:** `supplies`



>**Guard Quexill says:** The local guild houses should sell a few items, but the best place to visit would be the Commons Quarter.  It is filled with shops.

**You say:** `wizard guild`



>**Guard Quexill says:** Here in the Commons Quarter is the Tower of the Spurned.  It is the home of the Spurned, Teir'Dal who choose to study enchanting, wizardry and magic.

**You say:** `weapons`



>**Guard Quexill says:** I recommend the Blue Flame forge near Adamant Armor or you might try the Cauldron of Hate.

**You say:** `bank`



>**Guard Quexill says:** You are in the correct quarter.  You can find the Burnished Coin within Neriak Down Under.

**You say:** `inn`



>**Guard Quexill says:** This is no place for outsiders.  That is why the Smuggler's Inn is located in the Foreign Quarter.

**You say:** `warrior guild`



>**Guard Quexill says:** Within this area you will find the Cauldron of Hate which is home to the Teir'Dal warriors.

**You say:** `indigo brotherhood`



>**Guard Quexill says:** In the Commons Quarter can be found the Indigo Brotherhood, Teir'Dal warriors.  They are the armies of King Naythox Thex and serve as the trainers of the Dreadguard and dragoons.  Why the masters chose to build the Cauldron of Hate in that area and not the Third Gate is an amazement to me.

**You say:** `king`



>**Guard Quexill says:** The mighty empire of the Teir'Dal is ruled by King Naythox Thex.  All hail Thex!

**You say:** `queen`



>**Guard Quexill says:** Queen Cristanos is the queen of Neriak, of course!  She was the one who formed the necromancers and shadowknights into the guild called the Dead.

**You say:** `rogue guild`



>**Guard Quexill says:** The Ebon Mask are the rogues of Neriak.  Their Hall of the Ebon Mask lies within the Third Gate.

**You say:** `cleric guild`



>**Guard Quexill says:** When you enter the Third Gate you shall see the Spires of Innoruuk.  This is the temple of the Priests of Innoruuk.

**You say:** `the dead`



>**Guard Quexill says:** The Dead are the shadowknights and necromancers of Neriak.  They were formed by Queen Cristanos herself.  Even among the Teir'Dal they are feared and they keep to themselves within the Lodge of the Dead in the Third Gate.  I have heard they take orders only from the queen.

**You say:** `tavern`



>**Guard Quexill says:** There are quite a few taverns in the Commons Quarter.  I recommend either Toadstool's or the Blind Fish.

**You say:** `bard guild`



>**Guard Quexill says:** A class of people lost in their mythical art.  They are nothing more than dust under the feet of the empire of the Teir'Dal.

**You say:** `paladin guild`



>**Guard Quexill says:** Speak not of those vile paladins within Neriak!
end



## Arrive at Waypoint Script

if(e.wp == 3 or e.wp == 6) then


eq.get_entity_list():GetDoorsByDoorID(1):ForceOpen(e.self);


eq.get_entity_list():GetDoorsByDoorID(2):ForceOpen(e.self);


eq.get_entity_list():GetDoorsByDoorID(49):ForceOpen(e.self);
end