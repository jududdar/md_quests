# Xiblin Fizzlebik



## On NPC Spawn

**Set a timer** named *sit* for 10 seconds


## Timer(s)

if(e.timer == "sit") then


e.self:SetAppearance(1);
end



## Dialog

**You say:** `hail`



>**Xiblin Fizzlebik says:** Hello, Soandso! I am Xiblin Fizzlebik, renowned archeologist and historian of Ak'Anon. I'm currently in search of artifacts and relics on the Iksar [Jarsath tribe]. If you stumble upon anything, please bring it to me.

**You say:** `Jarsath tribe`



>**Xiblin Fizzlebik says:** About two thousand years ago, there were five different tribes of Iksar who dwelled on the continent of Kunark. One of these tribes was the Jarsath. They were a very primitive sort, proud and tribal, but also cannibalistic. Often, they went to war with the other tribes that co-existed with them back then. The ruins found on this island were of structures created by the Jarsath. I've been excavating for quite some time now, but haven't been able to find anything of significance.

**You say:** `looking for`



>**Xiblin Fizzlebik says:** In my studies, I have learned that the Jarsath believed they could draw power from a holy symbol... specifically a medallion that represented their tribe. When Salthir became king of the Iksar empire Sebilis, he had the medallion broken into three pieces and hid them on the Kunark continent so that they would never be found. I'm searching for the pieces so that I can put it back together and learn more about this tribe. Perhaps you wish to help?

**You say:** `help`



>**Xiblin Fizzlebik says:** All I know is that the pieces were most likely hidden in water regions. If you manage to find them, bring them to me and I will be able to put the medallion of the Jarsath back together. I am sure there is much to be learned from it.
end



## Turn-Ins



local text = "Yes yes, now where is the rest of the medallion?";




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1002.png" alt="" /> <a
                                href="/item/19959" data-url="19959" class="tooltip-link link">Piece of a medallion</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1002.png" alt="" /> <a
                                href="/item/19960" data-url="19960" class="tooltip-link link">Piece of a medallion</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1002.png" alt="" /> <a
                                href="/item/19961" data-url="19961" class="tooltip-link link">Piece of a medallion</a>) then


>*Xiblin Fizzlebik tinkers with the three pieces and snaps the pieces together. 'Wow.. You've done it.. but I suddenly feel very.. strange.. This medallion is cursed! Here, you take it!'*


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1002.png" alt="" /> <a
                                href="/item/19954" data-url="19954" class="tooltip-link link">Medallion of the Jarsath</a> (+100 exp)

 

**This NPC *should* return incorrect items given.**



## Signals

if(e.signal == 1) then


>*Xiblin Fizzlebik sighs to himself in resignation and continues to dig with obvious annoyance.*

if(e.signal == 2) then


>*Xiblin Fizzlebik mutters to himself. 'Yeah, not because you're a goblin headed moron or anything.'*


**Signaled to:**  [Alrik Farsight](/npc/96032)

if(e.signal == 3) then


>**Xiblin Fizzlebik says:** I didn't say anything! Now get back on your side of the island, you're getting dirt and junk all over mine!
end






