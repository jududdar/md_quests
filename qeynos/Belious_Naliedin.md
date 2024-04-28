# Belious Naliedin
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




if **You turn in:** [A tattered note](/item/18717)


>**Belious Naliedin says:** Good day friend, and welcome to the Wind Spirit's Song. Thank you for joining our cause. Go speak with Jusean Evanesque; I'm sure you'll fit in well.


* __Faction:__ [League of Antonican Bards](/faction/284) (100)


* __Faction:__ [Knights of Truth](/faction/281) (15)


* __Faction:__ [Guards of Qeynos](/faction/262) (15)


* __Faction:__ [Ring of Scale](/faction/304) (-5)


* __Faction:__ [Mayong Mistmoore](/faction/285) (-5)


 **You receive:**  [Brown Tunic*](/item/13502) (+100 exp)

elseif **You turn in:** [Ripped Qeynos Bards Guild Flyer](/item/20374)


>**Belious Naliedin says:** A famous bard, you say? Why you must be seeking none other than the great Baenar Swiftsong! He is not here as you can see. Mayhap you seek an audience with him? He is a busy man and has not the time to speak with everyone who wishes to preoccupy his time with useless prattle! You are many and he is but one! Leave him be, I beg of you, to continue his songwriting in peace.


 **You receive:** 0 (+100 exp)

elseif **You turn in:** platinum = 50


>**Belious Naliedin says:** Ah! Here is that letter of introduction I was looking for! Baenar likes to frequent a serene fountain in the southern Karanas. He finds the peace there accommodating to his work. He may even sing a tale for you if the mood strikes him.


 **You receive:**  [Letter of Introduction](/item/20373) (+100 exp)

elseif( **Faction is** >= Amiable and  **You turn in:** [Unfinished Lute Body](/item/13775), [Unfinished Lute Neck](/item/13776), [Box of Lute Strings](/item/13777), [Fine Lute Tuners](/item/13778)


>**Belious Naliedin says:** Ok, great. See, assembling these isn't that hard. Add a few special touches, and there you go. Another beautiful Naliedin lute is born, and ears everywhere rejoice.







* __Faction:__ [League of Antonican Bards](/faction/284) (250)


* __Faction:__ [Knights of Truth](/faction/281) (37)


* __Faction:__ [Guards of Qeynos](/faction/262) (37)


* __Faction:__ [Ring of Scale](/faction/304) (-12)


* __Faction:__ [Mayong Mistmoore](/faction/285) (-12)


 **You receive:**  [Custom Naliedin Lute](/item/13105) (+20000 exp)

**This NPC *should* return incorrect items given.**


