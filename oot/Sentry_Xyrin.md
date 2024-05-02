# Sentry Xyrin
## On NPC Spawn

**Set a timer** named *depop* for 3600 seconds


## On NPC Spawn

**Set a timer** named *overwhelming* for 1200 seconds
## Timer(s)

>**Sentry Xyrin says:** Heeelp!  The evil undead on this isle are overwhelming!
## Dialog

**You say:** `hail`



>**Sentry Xyrin says:** Shhhh!! Keep quiet! Can you not tell this island is inhabited by undead? I wish to take the fight to them, but I am weak from the [boat disaster].

**You say:** `boat disaster`



>**Sentry Xyrin says:** I was returning to my temple in Freeport in a small boat when the storm hit. I soon found myself shipwrecked on this evil island of undead. The words of Marr tell me to destroy these beings, but I am far too weak. If I only had a sip of the [Potion of Marr].

**You say:** `potion of marr`



if **Faction** >= Indifferent then



>**Sentry Xyrin says:** The Potion of Marr was created for the Sentries of Passion. It makes us alert and energetic. It will work only on sentries such as myself. It is distributed by Serna Tasknon of the Temple of Marr in Freeport.


else



>**Sentry Xyrin says:** The passion of the Queen of Love does not favor you. Begone from my sight!

end

## Turn-Ins




if **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_788.png" alt="" /> <a
                                href="/item/12134" data-url="12134" class="tooltip-link link">Last of Potion of Marr</a>) then


>**Sentry Xyrin says:** Ahhhh! I am energized! Come! Let us show these undead the greatness of Erollisi Marr!


eq.start(62);


e.self:SetRunning(true);


Your faction standing with [Priests of Marr](/faction/362) got better (<span class='text-success'>+20</span>)


Your faction standing with [The Freeport Militia](/faction/330) got worse (<span class='text-danger'>-3</span>)


Your faction standing with [Knights of Truth](/faction/281) got better (<span class='text-success'>+3</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_788.png" alt="" /> <a
                                href="/item/12135" data-url="12135" class="tooltip-link link">Empty Potion of Marr</a> 

 

**This NPC *should* return incorrect items given.**

## Arrive at Waypoint Script

if(e.wp == 4) then


>**Sentry Xyrin says:** Let the fury of passion smite thee!

elseif(e.wp == 5) then


>**Sentry Xyrin says:** Many thanks to all who aided in this battle. I offer you this, a weapon I found on a slain Erudite paladin. May Marr watch over his soul and may Marr guide yours. Now I must go.


**Spawns on ground:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_736.png" alt="" /> <a
                                href="/item/5414" data-url="5414" class="tooltip-link link">Deepwater Harpoon</a> at (**y:** -886, **x:** - <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_975.png" alt="" /> <a
                                href="/item/6963" data-url="6963" class="tooltip-link link">Giang Yins Claws</a>)


**Sentry Xyrin despawns.**
end

## Timer(s)

if(e.timer == "depop") then


**Sentry Xyrin despawns.**
end
