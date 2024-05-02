# Zamel
## On NPC Spawn

**Set a timer** named *help* for 300 seconds
## Timer(s)

local endicRandom = 0;

if(e.timer == "help") then


endicRandom = math.random(100);


if(endicRandom < 16) then



>**Zamel says:** Clean the [aqueducts] they tell me. Peh, they don't pay me enough to climb into that filth!



end

## Dialog

**You say:** `hail`



>**Zamel says:** Greetings, good Soandso.  My name is Zamel and I have the much coveted duty of pulling sludge up out of the pools and [aqueducts] of Qeynos..

**You say:** `aqueducts`



>**Zamel says:** Aye, the aqueducts are a horrible place. I have heard rumors of horrible [beasts] who live under the city in the water and just the other day, a child playing in the water just up and disappeared!

**You say:** `beasts`



>**Zamel says:** I know nothing of what or where they may be, just rumors, friend.  However, should you foolishly choose to enter the waters to brave the possibilities and return with some evidence of the [child's] fate, I would be most appreciative.

**You say:** `child`



>**Zamel says:** The daughter of one of our own guardsmen is missing. He has offered me a reward for any information about her disappearance. So, if you find out anything, let me know and I will cut you in on the reward.
end

## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1149.png" alt="" /> <a
                                href="/item/13713" data-url="13713" class="tooltip-link link">A Small Tattered Dress</a>) then


>**Zamel says:** Yes,  I do believe this was the child's dress. Here, take this as your share of the reward. Her father will be heartbroken..





Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+2</span>)


Your faction standing with [Antonius Bayle](/faction/219) got better (<span class='text-success'>+1</span>)


Your faction standing with [Corrupt Qeynos Guards](/faction/230) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Circle of Unseen Hands](/faction/223) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Merchants of Qeynos](/faction/291) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_767.png" alt="" /> <a
                                href="/item/10018" data-url="10018" class="tooltip-link link">Hematite</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_767.png" alt="" /> <a
                                href="/item/10018" data-url="10018" class="tooltip-link link">Hematite</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1042.png" alt="" /> <a
                                href="/item/10320" data-url="10320" class="tooltip-link link">Golden Ear Stud</a>) (+5000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**
