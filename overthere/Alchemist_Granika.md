# Alchemist Granika



[Alchemist Granika](/npc/93075) is a level 25 Iksar Shaman that spawns in [The Overthere](/zone/93).




## On NPC Spawn

**Set a timer** named *sit* for 10 seconds


## Dialog

**You say:** `hail`



>**Alchemist Granika says:** If you were sent to me, show proof or be gone from my sight!
end



## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_694.png" alt="" /> <a
                                href="/item/3892" data-url="3892" class="tooltip-link link">Bottle of Liquid Deklium</a>) then


>**Alchemist Granika says:** If Heirophant Oxyn has sent this with you, I can assume that our visions were corect. The new age is calling us from the heavens. Prepare for battle. I will take this solution to the Outlander's gates and use it to reveal the location of the metal of prophecy. Should I not return, you will only need to find the creature that glows without the use of a torch. Deklium glows when it gets near the smallest trace of tynnomium. Prepare for battle, Crusader... I am off!


**Stop timer** named *sit*


eq.start(4);


**Set a timer** named *Depop* for 8 seconds


**Spawn NPC:**  [a glowing cliff golem](/npc/93002) at (**y:** 2764, **x:** 2240)


**Spawn NPC:**  [Watch Sergeant Grolj](/npc/93005) at (**y:** 2698, **x:** 2240)


**Spawn NPC:**  [\#an undead marine](/npc/93004) at (**y:** 2794, **x:** 2260)


**Spawn NPC:**  [\#an undead marine](/npc/93004) at (**y:** 2698, **x:** 2260)


**Spawn NPC:**  [\#an undead marine](/npc/93004) at (**y:** 2794, **x:** 2280)


**Spawn NPC:**  [\#an undead marine](/npc/93004) at (**y:** 2698, **x:** 2280)


**Signaled to:**  [a cliff golem](/npc/93077)

**This NPC *should* return incorrect items given.**



## Timer(s)

if(e.timer == "Depop") then


**Stop timer** named *Depop*


**Alchemist Granika despawns.**

elseif(e.timer == "sit") then


e.self:SetAppearance(1);


**Stop timer** named *sit*
end






