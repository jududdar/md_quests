# Priestess Caulria
## Dialog

local fac = e.other:GetFaction(e.self);



**You say:** `hail`



>**Priestess Caulria says:** Welcome to the holy Temple of Life. Your presence shows an interest in our ways. We are the followers of the [Prime Healer] and would gladly open our arms to any who [serve Rodcet Nife]. Do we not all owe our lives to the sustaining force of the Prime Healer?

**You say:** `serve the prime healer`



if **Faction** >= Apprehensive then



>**Priestess Caulria says:** Then you are commanded by the Prime Healer to go into the surrounding terrirories of Qeynos and destroy any rabid creatures you may encounter. There will not be an outbreak of disease within reach of the Temple of Life, see to it! Bring me pelts of any rabid beast as proof of your good deed.


else



>**Priestess Caulria says:** Your mere presence disgusts me. Please remove yourself from my sight. Until you change yourself and your ways, you are unwelcome in the Temple of Life.


**You say:** `fleshy orb`



>**Priestess Caulria says:** I do not know what you are talking about.  Let me see it.

**You say:** `prime healer`



>**Priestess Caulria says:** The Prime Healer is Rodcet Nife. The one whose power flows through your body. He is the air that you breathe. To serve Him is to serve every living creature. Do you wish to [serve the Prime Healer] or do you [need more time for contemplation]?

**You say:** `bertoxxulous`



>**Priestess Caulria says:** You speak the name of the Lord of Disease.  The Plaguebringer.  Dinithn'al.  [Bertoxxulous], the evil one.  It is he who has brought disease unto this world and it is he whom we oppose.  We will not allow him or his followers to taint the beauty of life.

**You say:** `heal`



>**Priestess Caulria says:** I cannot help you with your request.   You must speak with Brother Tonmerk Plorsin.

**You say:** `contemplation`



>**Priestess Caulria says:** I understand. Sometimes a person can be filled with the lies of so many other false deities that he cannot see the truth when it lies in front of him.
end

## Turn-Ins




if **Faction** >= Apprehensive and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_553.png" alt="" /> <a
                                href="/item/13949" data-url="13949" class="tooltip-link link">Diseased Wolf Pelt</a>) then


>**Priestess Caulria says:** I see you have rid our land of a beast tainted with the blood of Bertoxxulous. The Prime Healer shall look favorably upon your soul. Here is our thanks and just in case the beast may have bitten you...


**Priestess Caulria casts:** [Counteract Disease](/spell/96) on target.





Your faction standing with [Priests of Life](/faction/341) got better (<span class='text-success'>+5</span>)


Your faction standing with [Knights of Thunder](/faction/280) got better (<span class='text-success'>+1</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+2</span>)


Your faction standing with [Bloodsabers](/faction/221) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Antonius Bayle](/faction/219) got better (<span class='text-success'>+1</span>)



 &#127873; **You receive:** 0 (+7250 exp)

 

elseif **Faction** >= Apprehensive and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_554.png" alt="" /> <a
                                href="/item/13298" data-url="13298" class="tooltip-link link">Putrid Bear Hide</a>) then


>**Priestess Caulria says:** Oh dear. The disease has spread to the realm of the Treefolk. It must have been difficult to kill such a large and rabid beast. Here. Take one of my personal scrolls as thanks for such a brave act of devotion. I pray you can use it. If not, then perhaps one of your fellow adventurers can.


**Priestess Caulria casts:** [Counteract Disease](/spell/96) on target.





Your faction standing with [Priests of Life](/faction/341) got better (<span class='text-success'>+20</span>)


Your faction standing with [Knights of Thunder](/faction/280) got better (<span class='text-success'>+6</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+10</span>)


Your faction standing with [Bloodsabers](/faction/221) got worse (<span class='text-danger'>-5</span>)


Your faction standing with [Antonius Bayle](/faction/219) got better (<span class='text-success'>+3</span>)



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15226" data-url="15226" class="tooltip-link link">Spell: Endure Disease</a> (+35350 exp)

**You receive coin:** 1 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif **Faction** >= Apprehensive and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_767.png" alt="" /> <a
                                href="/item/13950" data-url="13950" class="tooltip-link link">Fleshy Orb</a>) then


>**Priestess Caulria says:** This is odd. This could explain the increase in the number of beasts within the lands surrounding Qeynos. You must take this to Freeport. Here. You must speak with Lorme Tredore. Show him this pellet. You had best gear up for the trip. Freeport is very far away. Here is some gold. Outfit yourself at our expense.





Your faction standing with [Priests of Life](/faction/341) got better (<span class='text-success'>+10</span>)


Your faction standing with [Knights of Thunder](/faction/280) got better (<span class='text-success'>+3</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+5</span>)


Your faction standing with [Bloodsabers](/faction/221) got worse (<span class='text-danger'>-2</span>)


Your faction standing with [Antonius Bayle](/faction/219) got better (<span class='text-success'>+1</span>)



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_767.png" alt="" /> <a
                                href="/item/13951" data-url="13951" class="tooltip-link link">Fleshy Orb</a> (+9350 exp)

**You receive coin:** 1 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-20 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**
