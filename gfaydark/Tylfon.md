# Tylfon
## Dialog

**You say:** `hail`



>**Tylfon says:** So, you think you have what it takes to be a Scout of Tunare? Come back with two gold and two rusty daggers and I'll make it worth your while.

**You say:** `silvermesh legging`



>**Tylfon says:** Scout silvermesh leggings are part of the garb of the Scouts of Tunare. Besides greater protection in battle, they offer a protection against magic and their unique powers boost the wearer's agility. They are meant for the scouts only and, as such, are not just given away. Are you [willing to earn the leggings]?

**You say:** `earn the legging`



if **Faction** >= Amiable then 



>**Tylfon says:** A former scout named Faldor Hendrys has stolen our [Gem of Tunare]. He has fled Faydwer and we have been unable to track him down. Perhaps if you go and speak with his brother, [Elmion Hendrys], and ask him of Faldor, we might learn something of value?


elseif( **Faction is** == Indifferent) then



>**Tylfon says:** The Scouts of Tunare have no quarrel with you, but perhaps a few less Crushbone Orcs would prove your worth. Then we shall speak.


else



>**Tylfon says:** You dare to speak with a loyal member of the Scouts of Tunare?!  You are truly foolish!  Run away, while you still can.


**You say:** `gem of tunare`



>**Tylfon says:** The bright green Gem of Tunare was discovered by the Scouts of Tunare in the trunk of a great tree. The lightning streaked down to split the tree in twain and there, inside, was the gem, Tunare's gift to the people of Kelethin. It has no magical properties, but it represents the glory of Tunare. It appears as a small emerald shard. Alas, now it has been stolen by Faldor Hendrys and only his brother [Elmion Hendrys] could know of his whereabouts.

**You say:** `elmion hendrys`



>**Tylfon says:** Seek out the Fier'Dal, Elmion. He was last heard telling the local bar patrons that he was off to do some adventuring at the lake near the estate. What that is, I do not know.
end

## Turn-Ins





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18784" data-url="18784" class="tooltip-link link">A tattered note</a>) then 
 

>**Tylfon says:** Hmm.. I hope you can prove yourself a lot more valuable than you look. Here, throw this on.. it'll help protect you a little. Let's get started on improving your skills.


Your faction standing with [Scouts of Tunare](/faction/316) got better (<span class='text-success'>+100</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_678.png" alt="" /> <a
                                href="/item/13535" data-url="13535" class="tooltip-link link">Old Worn Gray Tunic*</a> (+20 exp)

 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_592.png" alt="" /> <a
                                href="/item/7007" data-url="7007" class="tooltip-link link">Rusty Dagger</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_592.png" alt="" /> <a
                                href="/item/7007" data-url="7007" class="tooltip-link link">Rusty Dagger</a>,gold = 2) then
 

>**Tylfon says:** Well, well. I didn't think you could do it. Here's your cut and don't be surprised that it's not much because it's your first lesson. Remember. the smaller the operation. the bigger the share, and the richest rogues have the tightest lips.
 




Your faction standing with [Scouts of Tunare](/faction/316) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_592.png" alt="" /> <a
                                href="/item/7021" data-url="7021" class="tooltip-link link">Tarnished Dagger</a> (+500 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-5 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_592.png" alt="" /> <a
                                href="/item/13346" data-url="13346" class="tooltip-link link">Rusty Dagger</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_592.png" alt="" /> <a
                                href="/item/13346" data-url="13346" class="tooltip-link link">Rusty Dagger</a>,gold = 2) then
 

>**Tylfon says:** Well, well. I didn't think you could do it. Here's your cut and don't be surprised that it's not much because it's your first lesson. Remember. the smaller the operation. the bigger the share, and the richest rogues have the tightest lips.
 




Your faction standing with [Scouts of Tunare](/faction/316) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_592.png" alt="" /> <a
                                href="/item/7021" data-url="7021" class="tooltip-link link">Tarnished Dagger</a> (+500 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-5 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_592.png" alt="" /> <a
                                href="/item/7007" data-url="7007" class="tooltip-link link">Rusty Dagger</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_592.png" alt="" /> <a
                                href="/item/13346" data-url="13346" class="tooltip-link link">Rusty Dagger</a>,gold = 2) then
 

>**Tylfon says:** Well, well. I didn't think you could do it. Here's your cut and don't be surprised that it's not much because it's your first lesson. Remember. the smaller the operation. the bigger the share, and the richest rogues have the tightest lips.







Your faction standing with [Scouts of Tunare](/faction/316) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_592.png" alt="" /> <a
                                href="/item/7021" data-url="7021" class="tooltip-link link">Tarnished Dagger</a> (+500 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-5 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_958.png" alt="" /> <a
                                href="/item/13322" data-url="13322" class="tooltip-link link">Emerald Shard</a>) then
 

>**Tylfon says:** Excellent job, Soandso, we will turn you into a rogue of Tunare yet.  Here this is for your trouble.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_540.png" alt="" /> <a
                                href="/item/3315" data-url="3315" class="tooltip-link link">Silvermesh Leggings</a> (+100 exp)

 

**This NPC *should* return incorrect items given.**


