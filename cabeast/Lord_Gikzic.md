# Lord Gikzic


## Dialog

**You say:** `hail`



>**Lord Gikzic says:** You dare to intrude upon the presence of a Lord of Pain?!  Such foolish acts can only be those of a knight in training.  Are you a [knight in training]?

**You say:** `knight in training`



>**Lord Gikzic says:** If you are a pawn, then let us begin with a simple test.  Complete the test and you shall be rewarded with a new khukri.  Do you [wish to perform the test of a pawn]?

**You say:** `test of a pawn`



if **Faction** >= Amiable then



>**Lord Gikzic says:** You shall carry this pack.  Within it you shall combine 4 sarnak hatchling heads. When you have the full sarnak head pack then you shall return it to me along with your pawn's khukri and I shall reward you with the khukri of a knave. Beware, for the sarnak are our most hated foes and even their whelps are quite formidable fighters. Be sure to seek out Klok Mugruk. He may have some curscale armor available.



**You receive:**  [Sarnak Head Pack](/item/17017)


elseif **Faction** >= Indifferent then



>**Lord Gikzic says:** The Crusaders of Greenmist demand further devotion to our ways before the knowledge you seek shall be revealed.


else



>**Lord Gikzic says:** Ignorant lout!  The Crusaders of Greenmist shall have nothing to do with you.  Go while I ponder your suffering to come.


**You say:** `greater concern`



if **Faction** >= Amiable then




>**Lord Gikzic says:** A tome has been taken from us. An expeditionary unit was returning to Cabilis when they were overtaken by a band of froglok raiders. The odds were greatly in their favor, but our forces would soon cut them down. Then, as abruptly as the battle began, it came to an The frogs retreated. The only item they took was an ancient tome entitled 'The Origins of Pain'. What the frogs want with it is unknown to us. Will you [retrieve the tome]?


elseif **Faction** >= Indifferent then



>**Lord Gikzic says:** The Crusaders of Greenmist demand further devotion to our ways before the knowledge you seek shall be revealed.


else



>**Lord Gikzic says:** Ignorant lout!  The Crusaders of Greenmist shall have nothing to do with you.  Go while I ponder your suffering to come.


**You say:** `retrieve the tome`



if **Faction** >= Amiable then



>**Lord Gikzic says:** The tome ripped open in battle. There were but ten pages. This is one of those pages. You must find the remainder and the tome binder. Place the pages within the binder and once you combine them, the binder shall magically lock. Do not look upon the pages, for the words would bring a great madness upon you. Your task is simply to seek out the froglok raiders and return the magically locked tome to me. Return it with a knave's khukri and I shall give you a more powerful weapon.



**You receive:**  [A Page of A Tome](/item/18229)


elseif **Faction** >= Indifferent then



>**Lord Gikzic says:** The Crusaders of Greenmist demand further devotion to our ways before the knowledge you seek shall be revealed.


else



>**Lord Gikzic says:** Ignorant lout!  The Crusaders of Greenmist shall have nothing to do with you.  Go while I ponder your suffering to come.

end

## Turn-Ins



local text1 = "I instructed you to return the full sarnak head pack and also your pawn's khukri.";


local text2 = "I shall keep this and you shall get no reward, unless you wield a knave's khukri. If so, then hand me that also and I shall give you a squire's khukri. A finer weapon to deal out pain.";



if **Faction** >= Amiable and  **You turn in:** [Full Pack of Sarnak Heads](/item/12381), [Pawn's Khukri](/item/5120)


>**Lord Gikzic says:** You have learned to behead your opponents with great precision. Take the khukri of the knave. It shall prove most formidable in combat when wielded by a young crusader. You may now assist us with a [greater concern] than your training.


* __Faction:__ [Crusaders of Greenmist](/faction/442) (10)


* __Faction:__ [Legion of Cabilis](/faction/441) (2)


 **You receive:**  [Knave's Khukri](/item/5121) (+100 exp)

elseif **Faction** >= Amiable and  **You turn in:** [Magically Locked Tome](/item/12382), [Knave's Khukri](/item/5121)


>**Lord Gikzic says:** You have done as instructed. You are wise to hand this tome to me. It could bring you nothing more than insanity. As your reward, you shall have the squire's khukri. Soon you shall wield the knight's khukri, but that is for another Lord of Pain to decide.


* __Faction:__ [Crusaders of Greenmist](/faction/442) (10)


* __Faction:__ [Legion of Cabilis](/faction/441) (2)


 **You receive:**  [Squire's Khukri](/item/5122) (+300 exp)

**This NPC *should* return incorrect items given.**






