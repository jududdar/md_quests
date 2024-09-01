# Thadres Thyme

[Thadres Thyme](/npc/29013) is a level 5 Human Rogue that spawns in [Halas](/zone/29).

Their primary faction is [Circle of Unseen Hands](/faction/223).



## Dialog

**You say:** `hail`


>**Thadres Thyme says:** Hello. Soandso!  It's hard to believe just how cold it gets here!  It really has been wearing me down. Especially after the [journey] from Qeynos.

**You say:** `what journey`


>**Thadres Thyme says:** I have been traveling the face of Norrath to unravel the mystery of why my beloved [brother] attacked a group of traveling bards.  He didn't survive the fight.  It's been so long. I can't really remember what he looked like!  I miss him so much...  Now all I have are his [diary] and some brewing recipes he sold before his death.

**You say:** `brother`


>**Thadres Thyme says:** My brother was Delius Thyme. I think he was a great man. Soandso, have you ever lost someone close? I don't know if I can ever forgive myself for letting him travel on his own after his sanity began to fade. Oh, Delius, please forgive me!

**You say:** `what diary`


>**Thadres Thyme says:** The diary?  It's one of the two connections I still have to my brother.  Sadly. [pages] are missing from it.  I've been looking for them.

**You say:** `what pages`


>**Thadres Thyme says:** I believe the pages contain the events that drove my brother to insanity.  I have been searching for the remaining three missing pages.  There is some hope; I found a couple of pages over in Everfrost Mountains.









## Turn-Ins



local text = "Thank you very much. Now, please help me find all three missing pages.";



if( **You turn in:**   <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18136" data-url="18136" class="tooltip-link link">Delius Thymes Diary Pg. 74</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18137" data-url="18137" class="tooltip-link link">Delius Thymes Diary Pg. 75</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18138" data-url="18138" class="tooltip-link link">Delius Thymes Diary Pg. 76</a> ) then

>**Thadres Thyme says:** Thank you, thank you. Let me read them. Oh! How could I want these brewing recipes after they made my brother insane? Where are they? I think this is all of them. Take them away from me! Delius can smile upon me now.

 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18139" data-url="18139" class="tooltip-link link">Garsen's Brewing List</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18140" data-url="18140" class="tooltip-link link">Garsen's Notes</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18141" data-url="18141" class="tooltip-link link">Garsen's Secret Brews</a>) (+200 exp)

 



**This NPC *should* return incorrect items given.**


