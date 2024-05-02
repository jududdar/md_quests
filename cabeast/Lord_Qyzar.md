# Lord Qyzar


## Dialog

**You say:** `hail`



>*Lord Qyzar looks upon you with a sneer. 'What is the year of our birth and who was our Father?'*

**You say:** `371 AG.* Rile`



>**Lord Qyzar says:** You are a student of our ways? I would hope so. I seek a knight in search of a way to prove his allegiance and a way to earn his [zealot khukri].

**You say:** `zealot khukri`



if **Faction** >= Amiable then



>**Lord Qyzar says:** In search of a zealot khukri? I have heard much of your deeds to aid us. I offer it to you in exchange for your service. I have dispatched a knight named Grizzle to seek out the Kromdul fortress called Chalp. He was to secretly map Chalp and return with a [Chalp diagram]. He has yet to return. Perhaps you can [rescue Grizzle].


elseif **Faction** >= Indifferent then



>**Lord Qyzar says:** The Crusaders of Greenmist demand further devotion to our ways before the knowledge you seek shall be revealed.


else



>**Lord Qyzar says:** Ignorant lout!  The Crusaders of Greenmist shall have nothing to do with you.  Go while I ponder your suffering to come.


**You say:** `chalp diagram`



if **Faction** >= Amiable then



>*Lord Qyzar grimaces in pure disgust. 'I have been awaiting the Chalp diagram from a knight named Grizzle, but alas, he has proven himself weak. He has been taken prisoner by one of the Kromdul of Chalp. If only there were another knight I could send to [rescue Grizzle] and return the Chalp diagram...'*


elseif **Faction** >= Indifferent then



>**Lord Qyzar says:** The Crusaders of Greenmist demand further devotion to our ways before the knowledge you seek shall be revealed.


else



>**Lord Qyzar says:** Ignorant lout!  The Crusaders of Greenmist shall have nothing to do with you.  Go while I ponder your suffering to come.


**You say:** `rescue grizzle`



>**Lord Qyzar says:** If you can find the knight in Chalp and have him hand you the Chalp diagram, you shall become a zealot and wield a zealot khukri. All I need are the Chalp diagram and your knight khukri.

**You say:** `matter of betrayal`



if **Faction** >= Amiable then



>**Lord Qyzar says:** One of our agents, a hero by the name of Goxnok, has found evidence that the book entitled 'Charasis' has been taken from this temple and is to be delivered to an unknown foe in the Outlands. Go at once to the lower levels of the temple and greet Goxnok. Hurry, before he departs!



**Spawn NPC:**  [an Iksar crusader](/npc/106301) at (**y:** 1000, **x:** -113)


elseif **Faction** >= Indifferent then



>**Lord Qyzar says:** The Crusaders of Greenmist demand further devotion to our ways before the knowledge you seek shall be revealed.


else



>**Lord Qyzar says:** Ignorant lout!  The Crusaders of Greenmist shall have nothing to do with you.  Go while I ponder your suffering to come.


**You say:** `visceral dagger`



if **Faction** >= Amiable then



>**Lord Qyzar says:** The visceral dagger was an ancient torturing weapon. I do not know much of it other than that it was forged by a member of the Brood of Kotiz, but that was ages ago. He is surely dust by now.


elseif **Faction** >= Indifferent then



>**Lord Qyzar says:** The Crusaders of Greenmist demand further devotion to our ways before the knowledge you seek shall be revealed.


else



>**Lord Qyzar says:** Ignorant lout!  The Crusaders of Greenmist shall have nothing to do with you.  Go while I ponder your suffering to come.


**You say:** `greenmist`



if **Faction** >= Amiable then



>*Lord Qyzar shudders at the mention of Greenmist.  'What?!  Have you stumbled upon the ancient weapon of the Father?  Do not fill my ears with such knowledge.  It can only be delivered to the ears of the Arch Duke.  Go at once and speak with him!*


elseif **Faction** >= Indifferent then



>**Lord Qyzar says:** The Crusaders of Greenmist demand further devotion to our ways before the knowledge you seek shall be revealed.


else



>**Lord Qyzar says:** Ignorant lout!  The Crusaders of Greenmist shall have nothing to do with you.  Go while I ponder your suffering to come.

end

## Turn-Ins



local text1 = "There shall be no zealot khukri until I have the Chalp diagram and your knight khukri.";



local text2 = "You disappoint me. I must have the Charasis Tome and its copy along with your zealot khukri.";


local text3 = "I am saddened by your failure to procure the visceral dagger and your crusader khukri. You are no hero!!";



if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/12496" data-url="12496" class="tooltip-link link">Chalp Diagram</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1174.png" alt="" /> <a
                                href="/item/5123" data-url="5123" class="tooltip-link link">Knight's Khukri</a>) then 


>**Lord Qyzar says:** At last!! The Chalp diagram. I shall see that the emperor gets this at once. You have proven yourself more than just a mere knight, you are a zealot. Being new to the temple we have need of you in a [matter of betrayal].


Your faction standing with [Crusaders of Greenmist](/faction/442) got better (<span class='text-success'>+10</span>)


Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+2</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1174.png" alt="" /> <a
                                href="/item/5124" data-url="5124" class="tooltip-link link">Zealot's Khukri</a> (+1600 exp)

**You receive coin:** 0-2 <img src='/static/icons/item_644.png' width='14' height='14'/> 0-10 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/1730" data-url="1730" class="tooltip-link link">Charasis Tome Copy</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1174.png" alt="" /> <a
                                href="/item/5124" data-url="5124" class="tooltip-link link">Zealot's Khukri</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/1729" data-url="1729" class="tooltip-link link">Charasis Tome</a>) then 


>**Lord Qyzar says:** Congratulations! You are now a true crusader, but there is no time for celebration. We have lost two of our operatives. Crusaders Golin and Fodcod were dispatched to seek out an ancient artifact, the [visceral dagger]. Where they have gone, I do not know. They have been gone far too long. Find them and return the dagger to me with your crusader khukri and you shall be a hero.


Your faction standing with [Crusaders of Greenmist](/faction/442) got better (<span class='text-success'>+20</span>)


Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+5</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1174.png" alt="" /> <a
                                href="/item/5125" data-url="5125" class="tooltip-link link">Crusader's Khukri</a> (+2000 exp)

**You receive coin:** 0-2 <img src='/static/icons/item_644.png' width='14' height='14'/> 0-10 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1186.png" alt="" /> <a
                                href="/item/7324" data-url="7324" class="tooltip-link link">The Visceral Dagger</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1174.png" alt="" /> <a
                                href="/item/5125" data-url="5125" class="tooltip-link link">Crusader's Khukri</a>) then 


>*Lord Qyzar gazes in astonishment at the dagger. 'Ahhh!! You have brought the sacred visceral dagger back to the Temple of Terror. Let all be aware that the great Soandso has returned to Cabilis a hero!! You now wield the weapon of a hero. Hail, Soandso, hero of the Crusaders of Greenmist.*


Your faction standing with [Crusaders of Greenmist](/faction/442) got better (<span class='text-success'>+20</span>)


Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+5</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1184.png" alt="" /> <a
                                href="/item/5126" data-url="5126" class="tooltip-link link">Hero's Khukri</a> (+3000 exp)

**You receive coin:** 0-3 <img src='/static/icons/item_644.png' width='14' height='14'/> 0-10 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**
