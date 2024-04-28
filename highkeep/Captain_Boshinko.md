# Captain Boshinko
## Dialog

local fac = e.other:GetFaction(e.self);


**You say:** `hail`



>**Captain Boshinko says:** Greetings, stranger! Are you the [bounty hunter I requested]?

**You say:** `bounty hunter you requested`



>**Captain Boshinko says:** It is about time.  I have been waiting for you for ages!  Your [reputation] precedes you.

**You say:** `reputation`



>**Captain Boshinko says:** You humor me, Soandso!  I would have guessed someone like yourself would have little time for humor.  Nevertheless, would you [like to hear about the job] I have for you?

**You say:** `about the job`



>**Captain Boshinko says:** Your name is as respected as the name of the Karana bandits.  Leave my presence while you still have legs to run with.

**You say:** `about the job`



>**Captain Boshinko says:** You must be new to Highhold. We will trust you when we hear your blade has cut down many Karana bandits or assisted our gatehouse guards with their tasks.

**You say:** `about the job`



>**Captain Boshinko says:** A prisoner named Bronin Higginsbot, a halfling, recently escaped.  He was a small time thief and I would care less if it were not for the fact that in the process of obtaining the cell key, he disemboweled my finest guard.  We found the bloodied shank still stuck in my guard's gutted corpse.  Would you [like to know more]?

**You say:** `like to know more`



>**Captain Boshinko says:** That little man has now made it to Rivervale.  He has ties with the halfling rogues, obviously. I want you to find him.  When you find him, take this shank he used to kill my guard and hand it to him.  I want him to know why he is about to die.  No one escapes my prison!!  Bring me his head and I shall pay the bounty.


**You receive:**  [Bloody Shank](/item/13110)
end

## Turn-Ins





if( **Faction is** > Indifferent and  **You turn in:** [Halfling Head](/item/13111)


>**Captain Boshinko says:** Good work, bounty hunter! You have served your legend well. I hope a few plat is good enough and, please, take this item we confiscated from one of our guests now serving time in our dungeon.


* __Faction:__ [Highpass Guards](/faction/332) (20)


* __Faction:__ [Carson McCabe](/faction/329) (3)


* __Faction:__ [Merchants of Highpass](/faction/331) (3)





* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (1)


* __Faction:__ [The Freeport Militia](/faction/330) (1)


 **You receive:** eq.ChooseRandom( [Bearskin Gloves](/item/2314), [Bronze Short Sword](/item/5026), [Bronze Long Sword](/item/5027), [Bronze Battle Axe](/item/5028), [Bronze Mace](/item/6019), [Ogre War Maul](/item/6302), [Scouts Blade](/item/7321), [Dwarven Axe](/item/5300)) (+250 exp)

**This NPC *should* return incorrect items given.**
