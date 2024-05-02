# Lord Korzin


## Dialog

**You say:** `hail`



>**Lord Korzin says:** What is it you seek? [Eternal suffering]?

**You say:** `eternal suffering`



>**Lord Korzin says:** Then follow the words of Cazic-Thule and may his blessed curses rain upon your soul as they shall on all of his faithful servants. Were you [sent] to me by Gikzic?

**You say:** `sent`



if **Faction** >= Amiable then



>**Lord Korzin says:** Then you must be the squire who found the ancient tome, 'The Origins of Pain'. I can use a talented crusader such as yourself. In my dreams, Cazic-Thule has spoken to me. He instructed me to seek out the 'Skull of Torture' which was last reported to be within the torture tower of the ancient Lord of Pain, Kurn. Will you [accept the calling]?


elseif **Faction** >= Indifferent then



>**Lord Korzin says:** The Crusaders of Greenmist demand further devotion to our ways before the knowledge you seek shall be revealed.


else



>**Lord Korzin says:** Ignorant lout!  The Crusaders of Greenmist shall have nothing to do with you.  Go while I ponder your suffering to come.


**You say:** `accept the calling`



if **Faction** >= Amiable then



>**Lord Korzin says:** As if you had a choice. Seek out the tower of Kurn and find the Skull of Torture. You should be able to easily recognize this skull as it glows with the power of Cazic Thule. Return it to me with your squire's khukri and I shall reward you with the knight's khukri. Go at once.


elseif **Faction** >= Indifferent then



>**Lord Korzin says:** The Crusaders of Greenmist demand further devotion to our ways before the knowledge you seek shall be revealed.


else



>**Lord Korzin says:** Ignorant lout!  The Crusaders of Greenmist shall have nothing to do with you.  Go while I ponder your suffering to come.

end

## Turn-Ins



local text1 = "You will be rewarded with the knight's khukri when I have possession of your squire's khukri and the Skull of Torture.";




if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1070.png" alt="" /> <a
                                href="/item/12401" data-url="12401" class="tooltip-link link">A Glowing Skull</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1174.png" alt="" /> <a
                                href="/item/5122" data-url="5122" class="tooltip-link link">Squire's Khukri</a>) then



>**Lord Korzin says:** Excellent work! You are no squire. You are now a knight of the crusaders. Your next step shall be zealot. And every zealot wields a magical khukri.


Your faction standing with [Crusaders of Greenmist](/faction/442) got better (<span class='text-success'>+10</span>)


Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+2</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1174.png" alt="" /> <a
                                href="/item/5123" data-url="5123" class="tooltip-link link">Knight's Khukri</a> (+1500 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0-15 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**
