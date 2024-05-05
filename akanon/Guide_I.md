# Guide I



[Guide I](/npc/55179) is a level 32 Clockwork Gnome Warrior that spawns in [Ak'Anon](/zone/55).



## Dialog

**You say:** `hail`



if( **Faction is** < Dubious) then



>**Guide I says:** Click... Warning. You are not an ally of the state of Ak'Anon. Further queries may result in death. Have a nice day.


else



>**Guide I says:** Greetings, lost soul. I am a guide, automaton, series G. I can assist you by leading you to all the important destinations in Ak'Anon. All you need to do is state a valid destination... Bzzz... Click!


**You say:** `exit`



>**Guide I says:** Click... The Steamfont Mountains may be accessed through the tunnel. Please come back.


eq.move_to(-34,4,4,0,false);

**You say:** `warrior`



>**Guide I says:** Gemchopper Hall is the headquarters of the Gemchoppers, the warriors of Ak'Anon. All clockworks and Watchmen operations are directed by the great Gemchopper guild masters. Have a grand visit!


eq.move_to(-469,958,-28,0,false);

**You say:** `cleric`



>**Guide I says:** 'The Abbey of Deep Musing serves as a shrine to both Brell Serilis and Fizzlethorpe Bristlebane. It is here that one can find healing, if desired. Enjoy your visit.


eq.move_to(-540,1401,-79,128,false);

**You say:** `wizard`



>**Guide I says:** The Library of Mechanimagica is the home of the Eldritch Collective, the practitioners of all positive circles of magic. The Eldritch Collective's members are the chief designers of all of Ak'Anon's wondrous machines. Enjoy your visit.


eq.move_to(-769,1212,-24,172,false);

**You say:** `king`



>**Guide I says:** Click! Whirr...  Ak'Anon Palace is home to the throne of his majesty, King Ak'Anon. All visitors to the palace must first report to Receptionist VI.  Click. The palace can be found to the right of the forward structure. Have a pleasant visit.


eq.move_to(-367,903,-6,64,false);

**You say:** `zoo`



>**Guide I says:** Click...  The Grand Zoo of Ak'Anon is home to some of the rarest creatures in Norrath. Inside you will find the likes of minotaurs, tigers and bears, among others. Please do not feed the animals. City Code, Section 3465.


eq.move_to(-844,1300,-30,172,false);

**You say:** `armor`



>**Guide I says:** Welcome to the Forge of Defiance. Within these walls, the finest armor in all of Norrath is shaped. Prices are reasonable and the smiths are friendly. Spend wisely!


eq.move_to(-740,1240,-26,172,false);

**You say:** `works`



>**Guide I says:** Click! The Works is the main supplier of all the essentials for venturing into the wilds of the Steamfont Mountains and beyond...  Spend wisely.


eq.move_to(152,717,-26,0,false);

**You say:** `weapon`



>**Guide I says:** Click... The Tools of Battle is the finest supplier of weapons on Faydwer. Spend wisely.


eq.move_to(-724,1300,-26,128,false);

**You say:** `scrapyard`



>**Guide I says:** The scrapyard is located down the path and through the tunnel on the right. It is here one can discard unwanted refuse, sometimes for a price. Watch your step.


eq.move_to(-541,1420,-6,0,false);

**You say:** `gatehouse`



>**Guide I says:** The Gatehouse serves as the repair shop for all automatons in Ak'Anon. It is also the last line of defense. Enjoy your visit.


eq.move_to(21,236,-26,64,false);
end



## Turn-Ins



**This NPC *should* return incorrect items given.**
