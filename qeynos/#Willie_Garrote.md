# Willie Garrote
## On NPC Spawn

**Set a timer** named *depop* for 1800 seconds
## Dialog
  **You say:** `bloodsaber`


>**Willie Garrote says:** A Bloodsaber? Of course I'm not, don't be ridiculous!

**Signaled to:**  [an investigator](/npc/1031)
 end

## Turn-Ins



if( **You turn in:** [Confession Document](/item/2344)) then


>**Willie Garrote says:** Here's your confession.  I hope you choke on it!


 **You receive:**  [Willies Confession](/item/2394) 


eq.set_global("invest_badge","third_suspect",3,"F");


**Spawn NPC:**  [\#Donally Stultz](/npc/1197) at (**y:** -341, **x:** 55)


**Set a timer** named *depop* for 300 seconds

item_lib.return_items(e.self, e.other, e.trade, e.text)
## Timer(s)
  if(e.timer == "depop") then

>**Willie Garrote says:** I'm outta here!

**Stop timer** named *depop*

**Willie Garrote despawns.**
 end

## Signals

if(e.signal == 1) then


>*Willie Garrote begins to perspire and says, 'Umm... Well, I don't know. It just started following me around.  You know, like a puppy. I didn't actually RAISE it. Really. Come on!'*


**Signaled to:**  [an investigator](/npc/1031)

elseif(e.signal == 2) then


>**Willie Garrote says:** You really believe that I would do that sort of thing? Undead scare me to death! Really, they do! You folks can not be serious about this, can you? Give me a break already!


**Signaled to:**  [an investigator](/npc/1031)

elseif(e.signal == 3) then


>**Willie Garrote says:** All right! Fine! I admit I've raised a few servants in my time. I hold no love for Antonius Bayle and frankly, I tire of keeping to the shadows and crawling through the blasted sewers as a second class citizen in my home town! I'll sign your blasted document but know that this is only the tip of the shark's fin you see sticking out of the water. The next and last thing you'll see are its teeth before you are consumed!


**Set a timer** named *depop* for 90 seconds

elseif(e.signal == 4) then


eq.start(67);
end