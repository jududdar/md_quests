# Grudash the Baker
## Dialog

**You say:** `hail`



>**Grudash the Baker says:** Hello stranger, what was your name? Ahh good to meet you, Soandso, I am Grudash the Baker. We do not get many strangers to these parts. Some of those that we have had here turned out to be more trouble than they were worth, so you may encounter a few negative reactions. Not from me though, you look like honest folk and perhaps paying customers, so I will give you a chance. Watch your step around Halcix there, he seems a might hungry today.  He already finished off at least a dozen of my Boysenberry pies. He has what you would call, a very voracious appetite.


if(**spawned NPC:**  [Sentry Halcix](/npc/114536)) then



eq.get_entity_list():GetMobByNpcTypeID( [Sentry Halcix](/npc/114536)):Say("I like pie.");



eq.get_entity_list():GetMobByNpcTypeID( [Ruru the Cook](/npc/114496)):Say("Yes Halcix, we know you like pie. But you have had enough, we need to feed the others as well you know.");



eq.get_entity_list():GetMobByNpcTypeID( [Sentry Halcix](/npc/114536)):Say("I'm hungry.");




**You say:** `boysenberry`



>*Grudash the Baker chuckles, 'I thought you might, what say you now Ruru? Who is the better cook between us now?'*


if(**spawned NPC:**  [Ruru the Cook](/npc/114496)) then



eq.get_entity_list():GetMobByNpcTypeID( [Ruru the Cook](/npc/114496)):Emote("grumbles, 'Bah, this still doesn't settle anything Grudash. This stranger obviously has no taste for fine cuisine.'");



end
