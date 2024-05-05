# Alrik Farsight



[Alrik Farsight](/npc/96032) is a level 50 High Elf Wizard that spawns in [Timorous Deep](/zone/96).




## Dialog

if( **Faction is** > Indifferent) then 


**You say:** `hail`




>**Alrik Farsight says:** Ah. Hello there, adventurer. Come to search for ancient artifacts with Fizzlebik and myself?


**You say:** `ancient artifacts`




>**Alrik Farsight says:** Oh. All types of things. This area is great. So many artifacts and remains of things all over. It's starting to fall into the pattern of things.


**You say:** `ancient bowl`




>*Alrik Farsight rummages through his tattered bag and throws aside a towel. 'Too many towels. Oh well, someone told me they were good to have once. Here it is, a bowl pattern. Interesting bowl. Looks almost like a magical bowl but I'm no potter. You need it, you say? Well, it is interesting. Part of my research here is for the wizard guild in Felwithe. I'm sure they'd put a high price on this one, the enchanters guild being so interested in trading for magical paraphernalia and all. Of course if you helped me out on a chore I have, I'd be happy to give it to you. I need to deliver an artifact to the guild and I'd much rather stay here exploring. If you wish, you can take the artifact and return with the receipt and I'll give you the pattern.'*


**You say:** `take the artifact`




>**Alrik Farsight says:** Hah! Okay, then. Here take this to Farios Elianos in Felwithe. He will give you the receipt.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1031.png" alt="" /> <a
                                href="/item/20457" data-url="20457" class="tooltip-link link">Crushed Pot</a>


elseif( **Faction is** < Amiable) then


local random = math.random(3);


if(random == 1) then



>**Alrik Farsight says:** I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.


elseif(random == 2) then



>**Alrik Farsight says:** Is that your BREATH, or did something die in here?  Now go away!


elseif(random == 3) then



>**Alrik Farsight says:** I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

end



## Turn-Ins



if( **Faction is** > Indifferent) then 


if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_867.png" alt="" /> <a
                                href="/item/20474" data-url="20474" class="tooltip-link link">Receipt</a>) then



>*Alrik Farsight grins happily. 'Excellent! Was he pleased with the artifact? Oh, that's not even worth answering. I'm sure he was. He's always happy with the things I send him. That's why he honored me with this position of esteem, searching for useful and powerful items in this newly discovered land.'*



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18960" data-url="18960" class="tooltip-link link">Ancient Pattern</a> 

 



if(e.wp >= 3 and e.wp <= 10) then




**Signaled to:**  [Xiblin Fizzlebik](/npc/96035)




**This NPC *should* return incorrect items given.**



## Arrive at Waypoint Script

if(e.wp == 8) then


>**Alrik Farsight says:** Hey there again, Xib!  Still a great day, isn't it?


**Signaled to:**  [Xiblin Fizzlebik](/npc/96035)

if(e.wp == 14) then


>*Alrik Farsight grins a little and mumbles. 'This place is great.  Feels like I'm at theof the universe.'*
end



## Signals

>**Alrik Farsight says:** What was that, Xib?

**Signaled to:**  [Xiblin Fizzlebik](/npc/96035)




