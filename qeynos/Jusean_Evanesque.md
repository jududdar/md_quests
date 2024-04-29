# Jusean Evanesque
## Dialog

**You say:** `hail`



if **Faction** >= Dubious +300 then 



>**Jusean Evanesque says:** Why, hello there, Soandso! I am Jusean, loyal member of the League of Antonican Bards. You look like the reliable sort, maybe you could help me out for a bit, huh? It's about time for our field agents to turn in their [watch reports], and I need someone to go pick them up for me.


else



>**Jusean Evanesque says:** The League of Antonican Bards is very displeased with your recent actions.   And I don't particularly care for you, or your stench, either!



**You say:** `watch report`



if **Faction** >= Dubious +300 then



>**Jusean Evanesque says:** We always have someone stationed on watch duty at the two main entries to the city to keep an eye on what is happening around Qeynos. We have [Anehan and Behroe] down at the docks, and [Leanon and Quinon] working the North Gate.


else



>**Jusean Evanesque says:** The League of Antonican Bards is very displeased with your recent actions.   And I don't particularly care for you, or your stench, either!



**You say:** `anehan and behroe`



if **Faction** >= Dubious +300 then



>**Jusean Evanesque says:** Here, if you take this to Anehan or Behroe down at the docks, and then return their report to me as soon as you can, I will give you a small reward.



**You receive:**  [Jusean's Report Request](/item/18021)


else



>**Jusean Evanesque says:** The League of Antonican Bards is very displeased with your recent actions.   And I don't particularly care for you, or your stench, either!



**You say:** `leanon and quinon`



if **Faction** >= Dubious +300 then



>**Jusean Evanesque says:** Leanon is in charge of the day shift at the North Gates of Qeynos, and Quinon is stationed there during the night. Please take this to either of them, have them fill it out, and then return it to me as soon as you can.



**You receive:**  [Jusean's Report Request](/item/18020)


else



>**Jusean Evanesque says:** The League of Antonican Bards is very displeased with your recent actions.   And I don't particularly care for you, or your stench, either!



**You say:** `father`



if **Faction** >= Dubious +300 then






>**Jusean Evanesque says:** My father Heltin disappeared while on a voyage aboard the Sea King. A group of troll pirates attacked and boarded the ship. Ginleen Harltop and the steel warriors traveling with them managed to fight them off, but took many casualties. My father was one of the bodies that was not accounted for. They found his song book floating in the water near the boat. The red water soaked through it's pages told more of the story then I ever care to know.


else



>**Jusean Evanesque says:** The League of Antonican Bards is very displeased with your recent actions.   And I don't particularly care for you, or your stench, either!



**You say:** `flute`



if **Faction** >= Dubious +300 then






>**Jusean Evanesque says:** Sorry, I'm not in the flute-making business anymore.


else



>**Jusean Evanesque says:** The League of Antonican Bards is very displeased with your recent actions.   And I don't particularly care for you, or your stench, either!


end

## Arrive at Waypoint Script

if(e.wp == 3) then


>*Jusean Evanesque growls, revealing his fangs.*
end


## Turn-Ins



local item_check = 0;


if( **You turn in:** [Behroe's Report](/item/18023)) then


>**Jusean Evanesque says:** Good job. I hope Behroe wasn't sleeping on the job again when you talked to him. Hmm, the docks seem to be a hotbed of activity after the sun goes down. Thanks for your quick work, Soandso, here's a little cash for your efforts.


item_check = 1;

elseif( **You turn in:** [Leanon's Report](/item/18024)) then


>**Jusean Evanesque says:** Ah, very good. I'll make sure to note Leanon's report in our journals. Here's a little something for your troubles, Soandso.


item_check = 2;

elseif( **You turn in:** [Anehan's Report](/item/18022)) then


>**Jusean Evanesque says:** Ok, good work, Soandso. I'll make sure to note the day's activities in our journal. Here's a little something for your efforts.


item_check = 1;

elseif( **You turn in:** [Quinon's Report](/item/18025)) then


>**Jusean Evanesque says:** Hmm... interesting...  good work, Soandso, thank you for your help.


item_check = 2;





if(item_check == 1 or item_check == 2) then





if(item_check == 1) then



* __Faction:__ [League of Antonican Bards](/faction/284) (25)



* __Faction:__ [Knights of Truth](/faction/281) (3)



* __Faction:__ [Guards of Qeynos](/faction/262) (3)


elseif(item_check == 2) then



* __Faction:__ [League of Antonican Bards](/faction/284) (10)



* __Faction:__ [Knights of Truth](/faction/281) (1)



* __Faction:__ [Guards of Qeynos](/faction/262) (1)









* __Faction:__ [Ring of Scale](/faction/304) (-1)


* __Faction:__ [Mayong Mistmoore](/faction/285) (-1)


 **You receive:** 0 (+50 exp)

**This NPC *should* return incorrect items given.**
