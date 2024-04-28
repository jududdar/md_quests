# Garret Zethkog


## Dialog

if(eq.get_current_expansion() >= 4.0) then


**You say:** `hail`




>**Garret Zethkog says:** Hail Soandso! I am Garret Zethkog, first Shadowknight of the Dark Reflection. Long ago I made the journey far to the west to the human city of Qeynos. In the catacombs of the Bloodsabres, human disciples of the Plague Lord, Bertoxxulous. I studied the ways of the Shadowknight. I have returned to Ak'Anon with this knowledge and now tutor young gnomes that have [heard the calling] of the Dark Reflection in the ways of a Dark Knight of Bertoxxulous.


**You say:** `heard the calling`




>**Garret Zethkog says:** Bertoxxulous has gifted his faithful with the sight of the Dark Reflection, the ability to recognize the power of disease and decay and its importance as a catalyst of change and progress. We Shadowknights of the Dark Reflection are the champions of the Plague Bringer. It is our duty to embrace our gifts and use them to act as the agents of Bertoxxulous, doing his bidding unquestioningly. There are many however who oppose the Plague Lord and his servants. They do not understand the importance of our existence and we must [defend ourselves] against these foes lest they would have us destroyed.


**You say:** `defend ourselves`




>**Garret Zethkog says:** Every young Knight of the Dark Reflection must first learn the basics of combat and acquire a suit of armor to help turn aside the weapons of our enemies. Take this parchment to my sister Mimtia Zethkog and she will assist you in acquiring a set of suitable armor for a young shadowknight. Once you have been suitably outfitted return to me and I will instruct you on your [next task].



**You receive:**  [Parchment to Mimtia](/item/10987)


**You say:** `next task`




>**Garret Zethkog says:** There are many through out Norrath who oppose the Dark Reflection. Even here in our home, Ak'Anon, the Eldrich Collective and the Deep Muses oppose us and wish to see us exiled or eradicated. A Paladin of the Deep Muses, Donlix Bonkle, has been leading a group of zealots that is hunting young members of the Dark Reflection in the Steamfont Mountains. Seek Donlix Bonkle and eliminate him. When you have accomplished this task return to me with Donlix's Short Sword.


else



**You say:** `hail`





>**Garret Zethkog says:** Hail Soandso! I am Garret Zethkog, first Shadowknight of the Dark Reflection. Long ago I made the journey far to the west to the human city of Qeynos. In the catacombs of the Bloodsabres, human disciples of the Plague Lord, Bertoxxulous. I studied the ways of the Shadowknight.


end

## Turn-Ins



local expansion_flag = eq.get_current_expansion();



if (expansion_flag >= 4.0 and  **You turn in:** [Donlixs Short Sword](/item/10991)


>**Garret Zethkog says:** Ah! Donlix's sword! You have done well to bring this to me... but oh! Look at your corruption seep into it. I think now this sword belongs to you. Use it well.


 **You receive:**  [Plague Knight Short Sword](/item/11078) 

elseif  **You turn in:** [Gnome Shadowknight Note](/item/18434)


>**Garret Zethkog says:** Welcome to the Dark Reflection, Soandso ! Take this tunic as a gift for your desire to serve the will of Bertoxxulous, The Plague Lord. Beware of the followers of Brell Serilis, they would see us members of the Dark Reflection exiled from Ak'Anon.


* __Faction:__ [Dark Reflection](/faction/238) (100)



* __Faction:__ [Eldritch Collective](/faction/245) (-10)



* __Faction:__ [Gem Choppers](/faction/255) (-10)


* __Faction:__ [Deepmuses](/faction/240) (-10)



 **You receive:**  [Tin Patched Tunic*](/item/13518) (+20 exp)


**This NPC *should* return incorrect items given.**
