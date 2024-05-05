# Ennixy Frennor



[Ennixy Frennor](/npc/56131) is a level 50 Gnome Shopkeeper that spawns in [Steamfont Mountains](/zone/56).



local wait = 0;



## Dialog

**You say:** `hail`



>**Ennixy Frennor says:** Unless you have something to tell me about yourself that I could possibly be interested in, be gone!

**You say:** `hate be my guide`



>**Ennixy Frennor says:** So you work for Szorn eh? It's about time he sent someone to check up on me! The Koada'Dal in possession of the crate is on his way here right now to cut a deal with me. I have been trying to send word to Szorn for several days to send support as I do not plan on allowing the elf to leave these mountains alive. You have arrived just in time. Kill the elf and the crate is yours!


if( wait == 0) then



eq.set_timer("Swiftmoon", math.random(30000, 600000));



wait = 1;


**You say:** `wormwood`



>**Ennixy Frennor says:** Wormwood? Why do you want that? OH nevermind. Here! Take it and leave me alone! You're wasting my valuable time!


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_583.png" alt="" /> <a
                                href="/item/10265" data-url="10265" class="tooltip-link link">Sprig of Wormwood</a>
end



## Timer(s)

if(e.timer == "Swiftmoon") then


**Stop timer** named *Swiftmoon*


**Spawn NPC:**  [Crusader Swiftmoon](/npc/56150) at (**y:** 1385, **x:** -836)


wait = 0;
end



## Turn-Ins



**This NPC *should* return incorrect items given.**
