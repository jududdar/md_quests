# Kinlo Strongarm




## On NPC Spawn

eq.set_timer("chant",math.random(1800000,2700000));


## Timer(s)

>**Kinlo Strongarm says:** Mud, rock, crystals, gems, metal. Arrrrrr!


## Dialog

if( **Faction is** > Apprehensive) then


**You say:** `mud`




>**Kinlo Strongarm says:** Eh? Oh, the clay. Arrr. Lots o' that mud round 'ere. Mostly, a good dwarf not be needin' somethin' so soft 'n squishy but the womenfolk, you know, the elves come lookin' fer it. If ye be one o' those pansy elves wantin' some mud fer workin' into fairy statues, flashy trinkets, 'n pig sticker arrers then I can get it for ye. Course I'd be lowerin' meself, a good dwarf, ta be diggin' that kinda mush outta the ground, but I can do it fer ya.


**You say:** `do it for me`




>**Kinlo Strongarm says:** Arrr. Shaddap. I ain't doin' it til ya bring me somethin'. A fee, I guess ye'd call it, fer lowerin' meself ta elf woman work. Go get me a good strong axe and I'll do it fer ye. Mebbe somethin' with a good tinted polish on it. I got plenty o' axes but no tinted ones. Har har! Colored axe. Somethin' to go with the color left on the blade after I be crackin open a gobbo head.


**You say:** `ancient`




>**Kinlo Strongarm says:** The ancient smiths, for what I think yer askin' about, ain't been around fer a long time, laddy. Last anyone heard o' the ancients was 'fore my time even. There be more than a few tales about 'em.


**You say:** `tales`




>**Kinlo Strongarm says:** There be some who talk about how the ancient smiths went down to work fer the Duke o' Below, sayin' he be needin' some fine dwarven smiths fer makin' some castle or some such. There be tales that the ancients were so good at smithin' that the Duke took 'em down and made 'em head smiths over his minions. There's even tales that some o' the smiths' souls were trapped in their hammers, stuck there by some necromancer or somethin', as punishment or retribution.


**You say:** `hammer`




>**Kinlo Strongarm says:** Aye. Some says their souls were bound into their hammers by an Erudite necromancer and enchanter. They say they used the power of the hammers ta profit by makin' ships, boats, and houses better than any other merchants. Sad tale, if'n it be true.


**You say:** `necromancer`




>**Kinlo Strongarm says:** I'm not knowin' more about the story, lad. Everythin' I know is already in what I said. Aye, Erudites. I suppose if yer wantin' ta run after shortbeard tales ya can look over on that plague island they call Odus.


**You say:** `rock`




>**Kinlo Strongarm says:** Aye, good stuff ta be workin' with.


**You say:** `arr.*`




>**Kinlo Strongarm says:** Har, har!  Ooooo!  Arrrrrr!


else


>*Kinlo Strongarm will not speak to you.*
end



## Turn-Ins



if( **Faction is** > Dubious and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1164.png" alt="" /> <a
                                href="/item/5664" data-url="5664" class="tooltip-link link">Jade Reaver</a>) then


>**Kinlo Strongarm says:** Arrrrr. Ooooo. Arrrrrr... Yah, now that's what I be callin' a good lookin' axe. I be crackin' a few skulls with this one. Oh, here's yer block o' mud. Our priests o' Brell use the mud pit fer relievin' themselves after really hard ale blessin' ceremonies, so ya ain't got ta be enchantin' it in holy water or anythin' cause they already have. Har har!


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1135.png" alt="" /> <a
                                href="/item/20455" data-url="20455" class="tooltip-link link">Enchanted Clay</a> 

 

elseif( **Faction is** > Dubious and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_567.png" alt="" /> <a
                                href="/item/20478" data-url="20478" class="tooltip-link link">Soulbound Hammer</a>) then


>*Kinlo Strongarm examines the hammer respectfully, admiring its craftsmanship. He strikes it against his anvil and winces as a howl fills the air. 'This is one of the ancients' hammers? I can almost, well, almost hear it callin ta me. It's strong, that's fer sure, lad. I don't know how ye got it, but aye, a dwarf could make a mighty blade with this. It's lookin like this thing still has its owner inside it though. I'm not knowin how, and not wantin to know, but fer yer own good ye better find some way ta get 'im out.'*


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_567.png" alt="" /> <a
                                href="/item/20478" data-url="20478" class="tooltip-link link">Soulbound Hammer</a> 

 

elseif( **Faction is** > Dubious and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_567.png" alt="" /> <a
                                href="/item/20485" data-url="20485" class="tooltip-link link">Hammer of the Ancients</a>) then


>*Kinlo Strongarm looks at the hammer and nods once before slamming the head against his anvil, and shattering the head. In a cloud of dust, another dwarf appears from the cloud and tosses you a hunk of metal. Kinlo stares in awe.*


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1092.png" alt="" /> <a
                                href="/item/20482" data-url="20482" class="tooltip-link link">Small bit of Mithril Ore</a> 

 


**Spawn NPC:**  [Usbak the Old](/npc/67089) at (**y:** 346.8, **x:** -189.5)

elseif( **Faction is** > Dubious and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1092.png" alt="" /> <a
                                href="/item/20482" data-url="20482" class="tooltip-link link">Small bit of Mithril Ore</a>) then


>**Kinlo Strongarm says:** Erm. Well, I ain't never worked with this stuff but here's what I got for ya. It ain't bad, pretty much like the one ye got there. I suppose ye should take the one the ancient made and show it ta yer friend.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_590.png" alt="" /> <a
                                href="/item/20483" data-url="20483" class="tooltip-link link">Refined Mithril Blade</a> 

 

**This NPC *should* return incorrect items given.**
