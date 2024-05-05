# Gnasher Furgutt



[Gnasher Furgutt](/npc/4181) is a level 9 Gnoll Warrior that spawns in [Qeynos Hills](/zone/4).



## Dialog

**You say:** `hail`



>**Gnasher Furgutt says:** Who are you? Did McNeal send you? If not, you would do yourself good to leave Gnasher alone. I have friends in high places.

**You say:** `yes`



if **Faction** >= Indifferent then



>**Gnasher Furgutt says:** I don't believe you.  Now, leave!



else



>**Gnasher Furgutt says:** I know of you! You leave before Gnasher calls gnoll watchers. You are no friend of gnolls or Gnasher's human friends...


**You say:** `no`



>**Gnasher Furgutt says:** Wrong answer!


**Gnasher Furgutt attacks you.**
end



## Turn-Ins




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18800" data-url="18800" class="tooltip-link link">A tattered note</a>) then


>**Gnasher Furgutt says:** Ah. Good for you! Here you are. Take this to McNeal, but next time there will be no stout if there are no weapons.


Your faction standing with [Circle of Unseen Hands](/faction/223) got better (<span class='text-success'>+5</span>)


Your faction standing with [Merchants of Qeynos](/faction/291) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Corrupt Qeynos Guards](/faction/230) got better (<span class='text-success'>+1</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Kane Bayle](/faction/273) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_836.png" alt="" /> <a
                                href="/item/13131" data-url="13131" class="tooltip-link link">Case of Blackburrow Stout</a> (+200 exp)

 

**This NPC *should* return incorrect items given.**
