# Srafen the Soaked



[Srafen the Soaked](/npc/98046) is a level 20 Human Warrior that spawns in [Erud's Crossing](/zone/98).

local counting;



## On NPC Spawn

**Set a timer** named *DillonSpawn* for 170 seconds

counting = 0;


## Dialog

**You say:** `hail`



>**Srafen the Soaked says:** Why hello there! Ahh, it's good to see a new face down [here]. So you've come to [wait] with [us] eh? That is splendid! It's been getting very boring lately.

**You say:** `here`



>**Srafen the Soaked says:** Oh! Well this is where [we wait]. It's not much for looks but if you're lucky, a pretty fish will swim by. Oh, and once Dillon said he saw one of those fish women, a mermaid, he called it! Although, I'm not so sure of his state of mind, hehehe. He's been waiting here much longer than I.

**You say:** `us`



>**Srafen the Soaked says:** Well, there's me, Srafen. I've been down here for, can't quite remember, a number of years, I guess. If my wife saw the condition my clothes are in, she'd whack me, I'm sure, heheh. Although I'd bet she's long since dead, probably. Then there's Dillon. He says he's been here since those people up top in Erud blew that big hole in the ground. Not sure what happened but I guess it was a long time ago. Hmmmm, who [else]?

**You say:** `wait`



>**Srafen the Soaked says:** We've been waiting quite some time, really. I have been here the least amount of time, but that doesn't help keep the boredom away, heheh. What are we waiting for, you ask? HehehHAahahah! What are we waiting for?? Heheheh, what a silly question! It's quite obvious if you take the time to think about it. Heh. Ummm.. I'm really not sure.

**You say:** `else`



>**Srafen the Soaked says:** Ahh, yes, there's also a really old guy I've only seen a couple times, name's Froham. Whew, he is really old, and not much of a talker. Mostly mumbles from time to time. Dillon says he's been here since Erud first took his people across the sea. Not sure who this Erud feller is but Froham isn't in the best of shape, so it must have been a LONG time ago. Froham did mention there's one other guy but we've never seen him. He apparently had something to do with the Combine Empire, no idea what that is though.

**You say:** `an illusion`



>**Srafen the Soaked says:** Awww, well that's too bad. Although illusions and real people don't seem to be much different at times, so, please stay and keep Dillon and me company. We could use it, right Dillon?


**Signaled to:**  [Dillon the Drowned](/npc/98051)
end



## Signals

if(e.signal == 0) then


>**Srafen the Soaked says:** Hey there, Dillon! Good to see you again, I think.

elseif(e.signal == 1) then


>*Srafen the Soaked looks around frantically a moment then laughs and says, 'Ohhh, them! Hehehe! This is a friend of mine come to wait with us. Isn't that exciting, Dillon? And it's not just an illusion, I don't think! Say, are you [an illusion], shaman?*
end



## Timer(s)

if (e.timer == "DillonSpawn") then


counting = counting + 1;

if(counting == 1) then


**Spawn NPC:**  [Dillon the Drowned](/npc/98051) at (**y:** -1562, **x:** 4186)

elseif(counting == 4) then


>**Srafen the Soaked says:** Hey Dillon, why don't you tell us again about what happened up top? You know, where they blew that big hole into the ground.


**Signaled to:**  [Dillon the Drowned](/npc/98051)

elseif(counting == 5) then


eq.start(33);


>**Srafen the Soaked says:** Okay, well, I've had enough. Yet again, we've waited for nothing. Sometimes I really wonder if the spirits are real after all. Well I for one am going to go find something fun to do - this is obviously a waste of time. Come with me, shaman, it'll be great fun! Fairwell Dillon.


**Signaled to:**  [Dillon the Drowned](/npc/98051)

elseif(counting == 7) then


**Spawn NPC:**  [Froham the Forgotten](/npc/98047) at (**y:** -1584, **x:** 4170)


**Stop timer** named *DillonSpawn*


**Srafen the Soaked despawns.**
end

