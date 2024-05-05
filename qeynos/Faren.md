# Faren



[Faren](/npc/1159) is a level 3 Human Warrior that spawns in [South Qeynos](/zone/1).



## On NPC Spawn

**Set a timer** named *fishing* for 300 seconds


## Timer(s)

>**Faren says:** Whoo!!! I think I got a [bite]! Darn.. Seaweed.


## Dialog

**You say:** `hail`



>**Faren says:** Oh.. Hiya, I'm just out here fishing, since I can't find a job. I hope this [bait] I just bought catches me a big ol' fish.

**You say:** `bait`



>**Faren says:** I use Captain Rohand's Secret Recipe Super Magic Catch-A-Lot brand bait. I bought my pole from Sneed's up by the north pond.


**You say:** `tacklebox`



>**Faren says:** Oh. That mean [dwarf], Trumpy, just knocked my tacklebox into the water. Could you please get it for me? I can't swim.


**You say:** `dwarf`



>**Faren says:** His name is Trumpy. He is one of those [Irontoes] I think. I've seen him hanging out in the Fish's Ale. I don't know why he likes to torment me.

**You say:** `irontoe`



>**Faren says:** Ah! The Irontoes are a rough bunch of dwarves from Kaladim. The seem to get quite drunk on a frequent basis.

**You say:** `fishing`



>**Faren says:** Huh?  OH!  Sorry, I was dozing off!  It's been a slow day.  A few fish and an old shoe are all I have reeled in.  I did see a shark swim by, though!

**You say:** `kane`



>**Faren says:** Commander Kane Bayle is the commander of all the Qeynos Guard.  He is second only to his brother, Antonius Bayle.  His post is in the guard house at the city gates.  Mind you, do not bother him, he has a bit of a temper.



**You say:** `circle.* unseen hand`



>**Faren says:** The Circle of the Unseen Hand?  I have heard nothing of them.  Are they some sort of performing magic troupe?
end



## Signals

if(e.signal == 1) then


>**Faren says:** Oh, hi, Beren. Not too good so far. That [dwarf] keeps bothering me, too.


**Signaled to:**  [Guard Beren](/npc/1090)
end



## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_730.png" alt="" /> <a
                                href="/item/13702" data-url="13702" class="tooltip-link link">Wooden Fishing Tackle</a>) then


>**Faren says:** Thank you so much! If you want some free advice, steer clear of those [Irontoes]! They are nothing but trouble. Here, It's not much but I must thank you somehow.





Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+10</span>)


Your faction standing with [Antonius Bayle](/faction/219) got better (<span class='text-success'>+1</span>)


Your faction standing with [Corrupt Qeynos Guards](/faction/230) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Circle of Unseen Hands](/faction/223) got worse (<span class='text-danger'>-2</span>)


Your faction standing with [Merchants of Qeynos](/faction/291) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_712.png" alt="" /> <a
                                href="/item/13129" data-url="13129" class="tooltip-link link">Hurrieta's Tunic</a> (+200 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-20 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**
