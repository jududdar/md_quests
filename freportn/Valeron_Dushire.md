# Valeron Dushire
## Dialog

**You say:** `hail`



>**Valeron Dushire says:** I am Sir Valeron Dushire, leader of the order of the Knights of Truth. If your soul shines with purity and strength, I urge you to join our order. The might of Mithaniel Marr stands behind all who join. Soon that might will help us free this city from the tyranny of the [Freeport Militia].

**You say:** `freeport militia`



>**Valeron Dushire says:** The Freeport Militia took control of this city long ago. They are nothing more than a group of thugs not worthy of respect. They follow the words of [Sir Lucan] D'Lere. He has been a thorn in this city's side for too long. If you wish to aid us in the fight against tyranny, go speak with Jemoz or Sir Theron. May the Truthbringer shine upon your soul.

**You say:** `stop.* lucan`



if **Faction** >= Amiable then



>**Valeron Dushire says:** That would be good, but I doubt you can. We have been trying for years and are unable to get him apart from the militia. If you do the impossible and destroy Sir Lucan, bring me his testimony. Every knight of the Hall of Truth carries a signed testimony. Sir Lucan still holds his.


elseif **Faction** >= Indifferent then




>**Valeron Dushire says:** Work on the ways of valor before we discuss such things. You are on the righteous path of the Truthbringer, but there is more work to do.


else



>**Valeron Dushire says:** Leave my presence at once. Your ways of life are not acceptable to one who follows the Truthbringer.


**You say:** `sir lucan`



>**Valeron Dushire says:** Lucan is a bad seed. You see, I trained Sir Lucan. He was nothing more than a street rat who was taken in by the Temple of Marr. The priests taught him and found him to be very agile and strong. They requested either the Priests of Marr or the Knights of Truth take him on as a squire. Gygus could not spare the trainers at the time and so we took the boy. The boy became a man, and a very formidable knight. Then something [went awry].

**You say:** `went awry`



>**Valeron Dushire says:** During one of our crusades into the lands of Norrath, we left Sir Lucan in charge of the remaining knights. He did much good and the people respected him. He was overtaken by power. He soon began to hire mercenaries to guard the city, calling them the Freeport Militia. His true downfall began when he killed Sentry Dillius, a paladin of the Priests of Marr. His divine powers were stripped from his soul. He was a paladin no longer. He and his militia now control the city. They treat it as their playground and bully the populace. Someone must [stop Sir Lucan].

**You say:** `hero`



>**Valeron Dushire says:** His name has been long lost but his legend lives on in every young knight who aspires to continue his fight. He attempted to quell an evil that resided within Kithicor, perverting nature itself. Much to his relief, it was an earthly foe he fought against and not a denizen summoned from the planes of evil. Then, suddenly, he was surrounded by dozens of dark elves. He was captured and taken to the Dead to be experimented upon and had his soul twisted by vile necromantic magics. Then the Tier'Dal cast his remains to the winds. Where they landed, no one knew, until now. You have found one of his bones. I hereby charge you with a Holy Quest to bring this Hero's bones back for a burial with honors. Do you [accept], knight?

**You say:** `accept`



>**Valeron Dushire says:** Good! I knew you would. It is one of the highest honors one can receive. Your quest will not be easy for I know not where his other bones lay. A spy of ours within Neriak was able to surmise that six of his bones along with his sword and shield were scattered throughout Norrath. You must search far and wide to find the remaining pieces, as you already have one.. Do not give up. It is now your sacred duty. Once you have retrieved all eight pieces, come back to me and inform me that you [have all the bones].

**You say:** `have all the bones`



>**Valeron Dushire says:** Excellent! You are indeed worthy to bear the title of Holy Knight! Now, about the coffin. I have spoken with Ping Fuzzlecutter, outside the western gates. Ask him about the coffin and once it is made, bring it to Simon Aldicott of Marr. I shall have Simon meet you by the lake in the Commonlands after Ping gives you the coffin.

**You say:** `who is`



>**Valeron Dushire says:** According to this crest on the tunic, you have recovered one of the bones of a lost Paladin [Hero].

**You say:** `honored member`



if **Faction** >= Indifferent +50 then



>**Valeron Dushire says:** Yes.  The light of righteousness shines from within you.


elseif **Faction** >= Indifferent then



>**Valeron Dushire says:** Work on the ways of valor before we discuss such things. You are on the righteous path of the Truthbringer, but there is more work to do.


else



>**Valeron Dushire says:** Leave my presence at once. Your ways of life are not acceptable to one who follows the Truthbringer.


**You say:** `heal`



>**Valeron Dushire says:** If you require the binding of wounds you should speak with Palious Jartan in the temple. He will be glad to help you.
end

## Turn-Ins




if( **You turn in:** [A tattered note](/item/18737)) then 


>**Valeron Dushire says:** Welcome to the Guild, here's your guild tunic. Now, let's get to work.


* __Faction:__ [Knights of Truth](/faction/281) (100)


* __Faction:__ [Dismal Rage](/faction/271) (-15)


* __Faction:__ [The Freeport Militia](/faction/330) (-15)


* __Faction:__ [Priests of Marr](/faction/362) (20)


* __Faction:__ [Steel Warriors](/faction/311) (10)


 **You receive:**  [Faded Purple Tunic*](/item/13554) (+20 exp)

elseif( **You turn in:** [A Dusty Old Leg Bone](/item/6701)) then 


>**Valeron Dushire says:** Hail, adventurer! I... what's this? Where did you get this? Never mind.. I.. I never thought we would find [him]!


 **You receive:**  [A Dusty Old Leg Bone](/item/6701) (+1 exp)

elseif **Faction** >= Amiable and  **You turn in:** [A Testimony of Truth](/item/18827)) then 


>**Valeron Dushire says:** Praise be to Marr!! You have done the impossible!! Sir Lucan is finally sent to the higher courts of the Tribunal. The city now has a chance to prosper. The Hall of Truth has been redeemed and gives you thanks. Take this, it is the Sword of Faith. May you wield it with righteousness. Beware of the remainder of the militia. They will be hunting for your head.


* __Faction:__ [Knights of Truth](/faction/281) (100)


* __Faction:__ [Dismal Rage](/faction/271) (-15)


* __Faction:__ [The Freeport Militia](/faction/330) (-15)


* __Faction:__ [Priests of Marr](/faction/362) (20)


* __Faction:__ [Steel Warriors](/faction/311) (10)


 **You receive:**  [Brilliant Sword of Faith](/item/13947) (+5000 exp)

**This NPC *should* return incorrect items given.**
;

