# Lord Gikzic



[Lord Gikzic](/npc/106108) is a level 61 Iksar GM Shadow Knight that spawns in [Cabilis East](/zone/106).





## Dialog

**You say:** `hail`



>**Lord Gikzic says:** You dare to intrude upon the presence of a Lord of Pain?!  Such foolish acts can only be those of a knight in training.  Are you a [knight in training]?

**You say:** `knight in training`



>**Lord Gikzic says:** If you are a pawn, then let us begin with a simple test.  Complete the test and you shall be rewarded with a new khukri.  Do you [wish to perform the test of a pawn]?

**You say:** `test of a pawn`



if **Faction** >= Amiable then



>**Lord Gikzic says:** You shall carry this pack.  Within it you shall combine 4 sarnak hatchling heads. When you have the full sarnak head pack then you shall return it to me along with your pawn's khukri and I shall reward you with the khukri of a knave. Beware, for the sarnak are our most hated foes and even their whelps are quite formidable fighters. Be sure to seek out Klok Mugruk. He may have some curscale armor available.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_565.png" alt="" /> <a
                                href="/item/17017" data-url="17017" class="tooltip-link link">Sarnak Head Pack</a>


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



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18229" data-url="18229" class="tooltip-link link">A Page of A Tome</a>


elseif **Faction** >= Indifferent then



>**Lord Gikzic says:** The Crusaders of Greenmist demand further devotion to our ways before the knowledge you seek shall be revealed.


else



>**Lord Gikzic says:** Ignorant lout!  The Crusaders of Greenmist shall have nothing to do with you.  Go while I ponder your suffering to come.

end



## Turn-Ins



local text1 = "I instructed you to return the full sarnak head pack and also your pawn's khukri.";


local text2 = "I shall keep this and you shall get no reward, unless you wield a knave's khukri. If so, then hand me that also and I shall give you a squire's khukri. A finer weapon to deal out pain.";



if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_565.png" alt="" /> <a
                                href="/item/12381" data-url="12381" class="tooltip-link link">Full Pack of Sarnak Heads</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1174.png" alt="" /> <a
                                href="/item/5120" data-url="5120" class="tooltip-link link">Pawn's Khukri</a>) then 


>**Lord Gikzic says:** You have learned to behead your opponents with great precision. Take the khukri of the knave. It shall prove most formidable in combat when wielded by a young crusader. You may now assist us with a [greater concern] than your training.


Your faction standing with [Crusaders of Greenmist](/faction/442) got better (<span class='text-success'>+10</span>)


Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+2</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1174.png" alt="" /> <a
                                href="/item/5121" data-url="5121" class="tooltip-link link">Knave's Khukri</a> (+100 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 1 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_865.png" alt="" /> <a
                                href="/item/12382" data-url="12382" class="tooltip-link link">Magically Locked Tome</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1174.png" alt="" /> <a
                                href="/item/5121" data-url="5121" class="tooltip-link link">Knave's Khukri</a>) then 


>**Lord Gikzic says:** You have done as instructed. You are wise to hand this tome to me. It could bring you nothing more than insanity. As your reward, you shall have the squire's khukri. Soon you shall wield the knight's khukri, but that is for another Lord of Pain to decide.


Your faction standing with [Crusaders of Greenmist](/faction/442) got better (<span class='text-success'>+10</span>)


Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+2</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1174.png" alt="" /> <a
                                href="/item/5122" data-url="5122" class="tooltip-link link">Squire's Khukri</a> (+300 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 3 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**






