# Caleah Herblender
## Dialog

**You say:** `hail`



>**Caleah Herblender says:** Greetings, and welcome to my humble little shop. I sell and trade various goods for my fellow wizards of the Order of Three. My assistants, Hanlore and Drawna, specialize in magicians' and enchanters' goods and would be glad to help you, too.

**You say:** `bat fur`



if **Faction** >= Indifferent +50 then 



**You say:** `bat fur`





>**Caleah Herblender says:** You can probably find some outside the city gates... in the hills and plains.



**You say:** `experiment`





>**Caleah Herblender says:** I need someone to gather up the three ingredients for a new spell I'm working on. I need some [rat whiskers], a [fire beetle eye], and a patch of [bat fur]. Thanks for helping me, young Soandso.


  



elseif **Faction** >= Indifferent then



>**Caleah Herblender says:** Though the Order of Three appreciates your past efforts and deeds greatly, we do not feel we can trust you with such an important assignment just yet.


else



>**Caleah Herblender says:** The Order of Three has been monitoring your recent activities, and we are appalled by you and your actions! Now, begone!

end

## Turn-Ins



local text = "All right. Remember, I need all three ingredients to test this spell out. Keep up the good work, Soandso.";
  

if **Faction** >= Indifferent +50 and  **You turn in:** [Rat Whiskers](/item/13071), [Bat Fur](/item/13069), [Fire Beetle Eye](/item/10307)


>**Caleah Herblender says:** Hmm. Good job, Soandso, let's give this a try. Flame and fire. Heat and spark. Touch of Ro, light this dark! Ahh. It stills needs a little work, I guess. Thanks for your help, here's a little something for your effort.





* __Faction:__ [Order of Three](/faction/342) (5)


* __Faction:__ [Guards of Qeynos](/faction/262) (1)


* __Faction:__ [Bloodsabers](/faction/221) (-1)


* __Faction:__ [Opal Darkbriar](/faction/296) (-1)





 **You receive:** None 

local returned = item_lib.return_items(e.self, e.other, e.trade, false)

if ( returned ) then


>**Caleah Herblender says:** Though the Order of Three appreciates your past efforts and deeds greatly, we do not feel we can trust you with such an important assignment just yet.
end

## On NPC Spawn

**Set a timer** named *repeat* for 350 seconds

## Timer(s)

>**Caleah Herblender says:** Drawna.. Are we all out of bat fur again?

**Signaled to:**  [Drawna Opimsor](/npc/1051)
## Signals

>**Caleah Herblender says:** Hmmm.. Let's see if we can find someone to help replenish our stock of [rat whiskers] and [bat fur]. I need these items for a new little [experiment] I'm working on.
