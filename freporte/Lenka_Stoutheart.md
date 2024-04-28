# Lenka Stoutheart
## Dialog

local fac = e.other:GetFaction(e.self);


**You say:** `hail`



>**Lenka Stoutheart says:** Hi, kid! You seem to be a stranger in these parts. Heed my words, this city is dangerous to new blood!


**Signaled to:**  [Bronto Thudfoot](/npc/10135)

**You say:** `hail`



>**Lenka Stoutheart says:** Run while ye still can!!  The Wolves o' the North will not tolerate yer presence!

**You say:** `toala sent me`



>**Lenka Stoutheart says:** She does not even have the courtesy to come herself. Some old friend!! Listen, some rogue in this city broke into the [Beast] and stole a pouch containing a voucher ticket for a part I need to repair the Beast. I can't get the part back without the ticket. I did not see the rogue. I did not sleep on the Beast that night. Bronto was there. Ask him if he saw the rogue.

**You say:** `beast`



>**Lenka Stoutheart says:** You're joking, right? You have never heard of the Blue Beast?!! She is the fastest ship in Norrath. She made the [Kunark run] in under three weeks. She was designed by [Bronto].

**You say:** `kunark run`



>**Lenka Stoutheart says:** The Kunark run is the most dangerous run between Freeport and [Firiona Vie], in Kunark. If the seas don't rip your hull to splinters and the pirates and sea wyrms don't kill you, you can make a quick run back and forth, avoiding any unwanted inspections.

**You say:** `Firiona Vie`



>**Lenka Stoutheart says:** Firiona Vie is an elven outpost on the continent of Kunark. Every so often I run supplies to and from there. Do not even think about asking me to take you there. It will be months before I can make improvements on the Blue Beast to make it impervious to aerial attacks.

**You say:** `journal strongbox`



>**Lenka Stoutheart says:** You must be from the Academy of Arcane Science.  Well, kid, bad news.  I was docked at the isle in the Ocean of Tears when I was boarded by the Freeport Militia.  To say the least, I panicked and dropped all my cargo.  It is still there.  Mostly illegal alcohol, but the strongbox is still out there, too.  Directly out from the dock.


eq.set_global("strongbox","1",7,"H1");

**You say:** `Bronto`



>**Lenka Stoutheart says:** My trusted friend. Together we travel the world aboard the [Beast]. He is quite skilled at boat making and other mechanical skills. He has a heart and brain far superior to any ogre I have ever met, as well as most other races.
end

## Turn-Ins




if **You turn in:** [Boat Beacon](/item/13818)


>**Lenka Stoutheart says:** Oh!! You must work for that Erudite named Palatos. I guess he won't have to spend anymore money drinking in Freeport. Here. Here is the portrait I kept until he could get me a new boat beacon.





* __Faction:__ [Wolves of the North](/faction/320) (5)


* __Faction:__ [Shamen of Justice](/faction/327) (1)


* __Faction:__ [Heretics](/faction/265) (1)


* __Faction:__ [High Guard of Erudin](/faction/267) (1)


 **You receive:**  [AkAnons Portrait](/item/12146) (+20000 exp)

elseif **You turn in:** [L.S. Pouch](/item/13814)


>**Lenka Stoutheart says:** You found my pouch! Thanks kid. Let me buy you A drink and this is for the good work. Hmmmm. It looks as though they took my voucher. Darn it! Hey... It looks like they were using my bag to hold items they were stealing. Here you go. You can have it. It looks like junk.





* __Faction:__ [Wolves of the North](/faction/320) (5)


* __Faction:__ [Shamen of Justice](/faction/327) (1)


* __Faction:__ [Merchants of Halas](/faction/328) (1)


* __Faction:__ [Steel Warriors](/faction/311) (1)


 **You receive:** None 

**This NPC *should* return incorrect items given.**
