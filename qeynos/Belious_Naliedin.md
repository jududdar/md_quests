# Belious Naliedin



[Belious Naliedin](/npc/1125) is a level 61 Human GM Bard that spawns in [South Qeynos](/zone/1).



## Signals

>**Belious Naliedin says:** Sure. Go Ahead and play it now, while the stage is clear.


## Dialog

**You say:** `hail`



>**Belious Naliedin says:** Welcome, my name is Belious Naliedin of the League of Antonican Bards. A few years ago, I had finally saved up the money, and I bought this place. I settled in, and have been [working] here ever since.

**You say:** `working`



>**Belious Naliedin says:** Ah, this is my shop. I am a musician, well known for my ability both in tuning, and [building instruments.]

**You say:** `building`



>**Belious Naliedin says:** Young bards are often not the wealthiest people in Norrath, and oftentimes, they have nothing to accompany their beautiful voices when they sing. If young bards are able to locate, and bring to me the [various parts] to assemble a lute with, I provide the labor for free.

**You say:** `parts`



>**Belious Naliedin says:** If you are able to find an unfinished lute body, an unfinished lute neck, a box of lute strings, and a set of fine lute tuners I will be able to craft for you one of the best sounding lutes that you have ever heard in your young life, and it will be yours, free of charge. It has long been my desire to help out any young men and women who wish to explore the bardic arts.

**You say:** `bard`



>**Belious Naliedin says:** A famous bard, you say? Why you must be seeking none other than the great Baenar Swiftsong! He is not here as you can see. Mayhap you seek an audience with him? He is a busy man and has not the time to speak with everyone who wishes to preoccupy his time with useless prattle! You are many and he is but one! Leave him be, I beg of you, to continue his songwriting in peace.

**You say:** `audience`



>*Belious Naliedin laughs briefly. 'Ah! In order to gain an audience with him, you must have a letter of introduction from me, otherwise he will not give you the time of day.'*

**You say:** `introduction`



>*Belious Naliedin looks around. 'Well, you want a letter of introduction, eh? I think that fifty shiny platinum pieces sounds like a good introduction to me, my friend.'*

**You say:** `carson`



if **Faction** >= Apprehensive then




>**Belious Naliedin says:** Well, we all know that Carson McCabe runs Highpass Hold, the main passage to Eastern Antonica. Rumor has it that he has some big internal power struggle going on right now.


else



>**Belious Naliedin says:** The League of Antonican Bards is very displeased with your recent actions.   And I don't particularly care for you, or your stench, either!

end



## Turn-Ins




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_864.png" alt="" /> <a
                                href="/item/18717" data-url="18717" class="tooltip-link link">A tattered note</a>) then 


>**Belious Naliedin says:** Good day friend, and welcome to the Wind Spirit's Song. Thank you for joining our cause. Go speak with Jusean Evanesque; I'm sure you'll fit in well.


Your faction standing with [League of Antonican Bards](/faction/284) got better (<span class='text-success'>+100</span>)


Your faction standing with [Knights of Truth](/faction/281) got better (<span class='text-success'>+15</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+15</span>)


Your faction standing with [Ring of Scale](/faction/304) got worse (<span class='text-danger'>-5</span>)


Your faction standing with [Mayong Mistmoore](/faction/285) got worse (<span class='text-danger'>-5</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_678.png" alt="" /> <a
                                href="/item/13502" data-url="13502" class="tooltip-link link">Brown Tunic*</a> (+100 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_864.png" alt="" /> <a
                                href="/item/20374" data-url="20374" class="tooltip-link link">Ripped Qeynos Bards Guild Flyer</a>) then


>**Belious Naliedin says:** A famous bard, you say? Why you must be seeking none other than the great Baenar Swiftsong! He is not here as you can see. Mayhap you seek an audience with him? He is a busy man and has not the time to speak with everyone who wishes to preoccupy his time with useless prattle! You are many and he is but one! Leave him be, I beg of you, to continue his songwriting in peace.


 &#127873; **You receive:** 0 (+100 exp)

 

elseif( **You turn in:** platinum = 50) then


>**Belious Naliedin says:** Ah! Here is that letter of introduction I was looking for! Baenar likes to frequent a serene fountain in the southern Karanas. He finds the peace there accommodating to his work. He may even sing a tale for you if the mood strikes him.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/20373" data-url="20373" class="tooltip-link link">Letter of Introduction</a> (+100 exp)

 

elseif( **Faction is** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_551.png" alt="" /> <a
                                href="/item/13775" data-url="13775" class="tooltip-link link">Unfinished Lute Body</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_551.png" alt="" /> <a
                                href="/item/13776" data-url="13776" class="tooltip-link link">Unfinished Lute Neck</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_609.png" alt="" /> <a
                                href="/item/13777" data-url="13777" class="tooltip-link link">Box of Lute Strings</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_551.png" alt="" /> <a
                                href="/item/13778" data-url="13778" class="tooltip-link link">Fine Lute Tuners</a>) then 


>**Belious Naliedin says:** Ok, great. See, assembling these isn't that hard. Add a few special touches, and there you go. Another beautiful Naliedin lute is born, and ears everywhere rejoice.







Your faction standing with [League of Antonican Bards](/faction/284) got better (<span class='text-success'>+250</span>)


Your faction standing with [Knights of Truth](/faction/281) got better (<span class='text-success'>+37</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+37</span>)


Your faction standing with [Ring of Scale](/faction/304) got worse (<span class='text-danger'>-12</span>)


Your faction standing with [Mayong Mistmoore](/faction/285) got worse (<span class='text-danger'>-12</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_551.png" alt="" /> <a
                                href="/item/13105" data-url="13105" class="tooltip-link link">Custom Naliedin Lute</a> (+20000 exp)

 

**This NPC *should* return incorrect items given.**


