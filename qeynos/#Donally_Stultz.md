# Donally Stultz



[Donally Stultz](/npc/1197) is a level 25 Human Warrior that spawns in [South Qeynos](/zone/1).



## On NPC Spawn

**Set a timer** named *depop* for 1800 seconds


## Dialog

**You say:** `bloodsaber`



>**Donally Stultz says:** Of course I'm a Bloodsaber, you fool! I've just returned from the Plains of Karana where I was reveling in the glory of the Plaguebringer. Now then, since I see that this foolish investigator is with you, I suppose you want me to sign a confession document or something like that? Well, let's have it then!


**Set a timer** named *depop* for 90 seconds
end



## Turn-Ins
  
  
  if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_682.png" alt="" /> <a
                                href="/item/2344" data-url="2344" class="tooltip-link link">Confession Document</a>) then

>*Donally Stultz crumples the document into a ball, throws it to the ground and spits in your face, yelling, 'You are a fool if you really believe I would sign such a thing. Prepare to die!'*

**Donally Stultz attacks you.**

**Set a timer** named *depop* for 300 seconds
   **This NPC *should* return incorrect items given.**



## Timer(s)

if(e.timer == "depop") then


>**Donally Stultz says:** You aren't bringing me in alive and since I don't feel like dying today, I'm outta here!


**Donally Stultz despawns.**
end
