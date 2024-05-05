# Grahan Rothkar



[Grahan Rothkar](/npc/1064) is a level 61 Human GM Warrior that spawns in [South Qeynos](/zone/1).



## Dialog

**You say:** `hail`



>**Grahan Rothkar says:** Hail, Soandso! What business do you have in the pens of the Qeynos Arena? Have you a report of the [escaped catman]?

**You say:** `escaped catman`



>**Grahan Rothkar says:** We had a catman imprisoned here for use in future gladiator battles. He escaped. In the process, he bit off my assistant's hand which held the key to pen number seven. I now seek to hire a warrior to [retrieve key seven].

**You say:** `retrieve key seven`



if( **Faction is** >= Amiable) then 



**You say:** `retrieve key seven`





>**Grahan Rothkar says:** Hmmm. You seem a bit young, but I shall give you a chance. Seek out the catman named Nomala. He most likely returned to [Kerra Isle]. He is not very powerful, but his people are surely watching over him. Retrieve the key for me and be rewarded.



**You say:** `second escaped gladiator`





>**Grahan Rothkar says:** It appears our prize gladiator has escaped. He is a minotaur hero!! Trained by our best. He took down five of our greatest warriors during his escape. Rumor has it he fled to his homeland in the Steamfont Mountains. They say he is an outcast and does not live with his people. He appears during times of great need to champion the minotaurs. Return his shackles to me and glory is yours!!











elseif( **Faction is** == Indifferent) then



>**Grahan Rothkar says:** The Steel Warriors have no cause to dislike you, but you have yet to truly prove your worth to this guild.


else



>**Grahan Rothkar says:** Your head shall look grand mounted on the wall of the Steel Warriors Arena!!




**You say:** `kerra isle`



>**Grahan Rothkar says:** Kerra Isle is a dangerous place. The Kerra are not a friendly race. There is an island between Erudin and Qeynos which is inhabited by a more docile tribe of Kerra. I hear they took some of their Kerra beetles along with them to the island, too.
end



## Turn-Ins




if( **Faction is** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_620.png" alt="" /> <a
                                href="/item/12188" data-url="12188" class="tooltip-link link">Minotaur Hero Shackles</a>) then 


>**Grahan Rothkar says:** You are a true Steel Warrior!! Now you shall wear my hero bracers. I designed them for my greatest gladiators and you have shown yourself mighty enough to wear them.





Your faction standing with [Steel Warriors](/faction/311) got better (<span class='text-success'>+75</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+15</span>)


Your faction standing with [Corrupt Qeynos Guards](/faction/230) got worse (<span class='text-danger'>-11</span>)


Your faction standing with [The Freeport Militia](/faction/330) got worse (<span class='text-danger'>-11</span>)


Your faction standing with [Knights of Truth](/faction/281) got better (<span class='text-success'>+15</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_516.png" alt="" /> <a
                                href="/item/12189" data-url="12189" class="tooltip-link link">Hero Bracers</a> (+0 exp)

**You receive coin:** 2 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_834.png" alt="" /> <a
                                href="/item/13398" data-url="13398" class="tooltip-link link">Arena Lion Skin</a>) then


>**Grahan Rothkar says:** I salute you. You have done well and crossed into the brotherhood of the Steel Warriors. Welcome. Take this. It is the mark of a Steel Warrior. Live the way of the warrior.





Your faction standing with [Steel Warriors](/faction/311) got better (<span class='text-success'>+25</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+5</span>)


Your faction standing with [Corrupt Qeynos Guards](/faction/230) got worse (<span class='text-danger'>-3</span>)


Your faction standing with [The Freeport Militia](/faction/330) got worse (<span class='text-danger'>-3</span>)


Your faction standing with [Knights of Truth](/faction/281) got better (<span class='text-success'>+5</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_637.png" alt="" /> <a
                                href="/item/13229" data-url="13229" class="tooltip-link link">Steel Warrior Bracer</a> (+0 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/18894" data-url="18894" class="tooltip-link link">A Sealed Letter</a>) then


>**Grahan Rothkar says:** So you are ready to encounter your final test. I wish you well, young warrior. Take this key to the pen on the left along the wall with three doors. There you shall meet your final challenge. Return with proof of victory. Exit before it is at anand I shall not help you.


**Spawn NPC:**  [a young lion](/npc/1005) at (**y:** -120, **x:** -520)


**Set a timer** named *86* for 120 seconds





Your faction standing with [Steel Warriors](/faction/311) got better (<span class='text-success'>+5</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+1</span>)


Your faction standing with [Corrupt Qeynos Guards](/faction/230) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [The Freeport Militia](/faction/330) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Knights of Truth](/faction/281) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1078.png" alt="" /> <a
                                href="/item/20029" data-url="20029" class="tooltip-link link">Pen Key \# 5</a> (+0 exp)

 

**This NPC *should* return incorrect items given.**



## Timer(s)

if(e.timer == "86") then


**Signaled to:**  [a young lion](/npc/1005)


**Stop timer** named *86*
end


