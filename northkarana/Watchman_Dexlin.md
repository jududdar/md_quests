# Watchman Dexlin

## Dialog

**You say:** `hail`



if **Faction** >= Amiable then



>**Watchman Dexlin says:** It is about time I met up with someone who I can tolerate.  Most of the residents within these plains shun gnomes.  I will happy to leave if I could just find those [pesky skeletons].


elseif **Faction** >= Indifferent then



>**Watchman Dexlin says:** I do not trust you.  I have yet to hear of the great deeds you have done in the name of the Gemchoppers of Ak'Anon.




else



>**Watchman Dexlin says:** You are quite bold to approach a noble servant of Ak'Anon. The knowledge of your allegiance leaves you with no friend in Ak'Anon. Begone, whelp!


**You say:** `pesky skeletons`



if **Faction** >= Amiable then



>**Watchman Dexlin says:** I was sent here by the Gemchoppers to seek out a pocketful of skeletons.  They are a creation of a one of Ak'Anon's exiled citizens.  He practiced the dark circle of magic and came to find the necromancers of Antonica.  He created and imported undead brownies to this realm.  We must find them to study them.  I can't seem to find them!!  If only I could find a [brave fighter] to assist me.


elseif **Faction** >= Indifferent then



>**Watchman Dexlin says:** I do not trust you.  I have yet to hear of the great deeds you have done in the name of the Gemchoppers of Ak'Anon.




else



>**Watchman Dexlin says:** You are quite bold to approach a noble servant of Ak'Anon. The knowledge of your allegiance leaves you with no friend in Ak'Anon. Begone, whelp!


**You say:** `brave fighter`



if **Faction** >= Amiable then



>**Watchman Dexlin says:** Very good. Take this tin box.  Fill each slot with the remains of the tiny undead, should you find them here.  I know not how many there exists, but I am sure that if I return this full tin box shall suffice.  Be quick, I have other matters to to tend to.  I shall depart when next my sun dial points to eight.



**You receive:**  [empty Tin Box](/item/17986)



* __Faction:__ [Gem Choppers](/faction/255) (-10)



**Set a timer** named *spawns* for 10 seconds


elseif **Faction** >= Indifferent then



>**Watchman Dexlin says:** I do not trust you.  I have yet to hear of the great deeds you have done in the name of the Gemchoppers of Ak'Anon.




else



>**Watchman Dexlin says:** You are quite bold to approach a noble servant of Ak'Anon. The knowledge of your allegiance leaves you with no friend in Ak'Anon. Begone, whelp!

end

## Turn-Ins




if **Faction** >= Amiable and  **You turn in:** [Box Full of Tiny Bones](/item/12376)) then 


>**Watchman Dexlin says:** Good Work. Unfortunately, I must investigate other matters in the name of Ak'anon.  Here.  You deliver the tin box to Lord Jenork of the Gem Choppers.  He shall reward you. Be safe my friend.  I must go now. Farewell.


* __Faction:__ [Gem Choppers](/faction/255) (10)


* __Faction:__ [Merchants of Ak`Anon](/faction/288) (2)


* __Faction:__ [King Ak`Anon](/faction/333) (2)


* __Faction:__ [Dark Reflection](/faction/238) (-2)


* __Faction:__ [Clan Grikbar](/faction/1604) (-1)


 **You receive:**  [Box of Undead Brownie Bones](/item/12378) (+10000 exp)


**Watchman Dexlin despawns.**

**This NPC *should* return incorrect items given.**

## Timer(s)

if(e.timer == "spawns") then


**Spawn NPC:**  [a tiny skeleton](/npc/13120) at (**y:** 829, **x:** -1839)


**Spawn NPC:**  [a tiny skeleton](/npc/13120) at (**y:** 10351, **x:** -2149)


**Spawn NPC:**  [a tiny skeleton](/npc/13120) at (**y:** 1075, **x:** -1713)


**Spawn NPC:**  [a tiny skeleton](/npc/13120) at (**y:** 363, **x:** -1690)


**Spawn NPC:**  [a tiny skeleton](/npc/13120) at (**y:** 222, **x:** -2604)


**Stop timer** named *spawns*
end
