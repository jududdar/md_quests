# Fenn Kaedrick
## On NPC Spawn

**Set a timer** named *depop* for 1800 seconds
## Dialog

local qglobals = eq.get_qglobals(e.self,e.other);

**You say:** `hail`



>**Fenn Kaedrick says:** What brings you to the top of the castle? Me? I am just the Highkeep exterminator. We have had a nasty time with rats.

**You say:** `scout`



>**Fenn Kaedrick says:** I have no idea what you are speaking of!  Maybe you could show me some sort of token of appreciation for wasting my time with such questions.

**You say:** `xentil`



if **Faction** >= Amiable +100 then 




>**Fenn Kaedrick says:** Xentil Herkanon is related to one of the bigwigs of the Circle of Unseen Hands, the rogue guild in Qeynos. Killing him would greatly decrease your popularity with them, but who do they like, anyway? He travels with two bodyguards, Lartin and Grex, very tough customers. It's best to avoid them. Goodbye and good luck.



**Stop timer** named *depop*



**Fenn Kaedrick despawns.**




else



>**Fenn Kaedrick says:** The Scouts of Tunare have no quarrel with you, but perhaps a few less Crushbone Orcs would prove your worth. Then we shall speak.


end

## Turn-Ins



if **Faction** >= Amiable +100 and  **You turn in:** [Useless Token](/item/12185)




>**Fenn Kaedrick says:** So you are the one Laren sent. I myself was trained by Laren. Imagine that, a human trained by elven rogues. I share the concerns of the scouts. You were sent to assassinate [Xentil Herkanon]. He betrayed the scouts and Kelethin. He is somewhere in this keep. Return his head to Laren in Kelethin.






 **You receive:** 0 (+2000 exp)


**Spawn NPC:**  [Xentil Herkanon](/npc/6185) at (**y:** -102, **x:** -258)





**Spawn NPC:**  [Lartin](/npc/6186) at (**y:** -78, **x:** -259)





**Spawn NPC:**  [Grex](/npc/6187) at (**y:** -78, **x:** -240)









**This NPC *should* return incorrect items given.**

## Timer(s)

**Stop timer** named *depop*

**Fenn Kaedrick despawns.**