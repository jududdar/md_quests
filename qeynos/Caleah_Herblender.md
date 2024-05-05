# Caleah Herblender



[Caleah Herblender](/npc/1118) is a level 28 Human Shopkeeper that spawns in [South Qeynos](/zone/1).



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
  

if **Faction** >= Indifferent +50 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_794.png" alt="" /> <a
                                href="/item/13071" data-url="13071" class="tooltip-link link">Rat Whiskers</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_792.png" alt="" /> <a
                                href="/item/13069" data-url="13069" class="tooltip-link link">Bat Fur</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_859.png" alt="" /> <a
                                href="/item/10307" data-url="10307" class="tooltip-link link">Fire Beetle Eye</a>) then 


>**Caleah Herblender says:** Hmm. Good job, Soandso, let's give this a try. Flame and fire. Heat and spark. Touch of Ro, light this dark! Ahh. It stills needs a little work, I guess. Thanks for your help, here's a little something for your effort.





Your faction standing with [Order of Three](/faction/342) got better (<span class='text-success'>+5</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+1</span>)


Your faction standing with [Bloodsabers](/faction/221) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Opal Darkbriar](/faction/296) got worse (<span class='text-danger'>-1</span>)





 &#127873; **You receive:** 0 (+300 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_647.png' width='14' height='14'/> 

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
