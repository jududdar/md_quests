# Vesteri Nomanoi



[Vesteri Nomanoi](/npc/3038) is a level 61 Human GM Druid that spawns in [Surefall Glade](/zone/3).



## Dialog

**You say:** `hail`



>**Vesteri Nomanoi says:** Hail, Soandso. I am Vesteri Namanoi. I provide training to the Jaggedpine Treefolk and their allies. If you are not busy, I would like to ask a small [favor] of you.

**You say:** `favor`



if **Faction** >= Amiable then 



>**Vesteri Nomanoi says:** I need you to take this claim check to Qeynos for me. Nesiff Talaherd is a woodcarver who owns a shop in South Qeynos. I am having him carve a small statue of Tunare for Te'Anara. With my training schedule, I can not make the journey to Qeynos. Please give this claim check to Nesiff and bring the statue to me. It is a surprise, so please do not say anything to Te'Anara about it.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18012" data-url="18012" class="tooltip-link link">Claim Check</a>


elseif **Faction** >= Indifferent then



>**Vesteri Nomanoi says:** We, the Jaggedpine Treefolk, appreciate the help you've given us in the past. But, we must trust you more before allowing you to handle such important matters.




else



>**Vesteri Nomanoi says:** You are an enemy of the Jaggedpine Treefolk, this forest, and the residents of it. Begone, before I am forced to take drastic measures!



end



## Turn-Ins




if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_894.png" alt="" /> <a
                                href="/item/13864" data-url="13864" class="tooltip-link link">Wooden Statue</a>) then


>**Vesteri Nomanoi says:** Oh thank you so much! Here. Take this reward for your time. I will also tell Te'Anara of you.


Your faction standing with [Jaggedpine Treefolk](/faction/272) got better (<span class='text-success'>+5</span>)


Your faction standing with [Protectors of Pine](/faction/302) got better (<span class='text-success'>+1</span>)


Your faction standing with [QRG Protected Animals](/faction/343) got better (<span class='text-success'>+1</span>)


Your faction standing with [Unkempt Druids](/faction/324) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:** 0 (+250 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-5 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**
