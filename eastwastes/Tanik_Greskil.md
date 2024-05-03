# Tanik Greskil




## On NPC Spawn

**Set a timer** named *faint* for 1 seconds

**Set a timer** named *moveloc* for 120 seconds


## Dialog

**You say:** `hail`



>**Tanik Greskil says:** Outlander! Thank Brell you've found me! I am the last surviving member of my unit. Our mission was somehow compromised, the bloody Kromrif knew just where to find us... I can't imagine how they knew. I was barely able to escape with my life and wandered into a trap here. I am badly hurt and need your help.

**You say:** `help`



>**Tanik Greskil says:** Quickly, give me a vial of Velium Vapors so I can return home, I am in desperate need of some attention from our clerics.

**You say:** `velium vapor`



>**Tanik Greskil says:** Drat! Are you telling me you don't have one with you? Run back to Thurgadin at once and speak with Frundle, she can make you one. I will do what I can to stay alive. I may need to move about a bit to keep from being discovered. Hurry now outlander, you're my only hope.
end



## Turn-Ins





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1160.png" alt="" /> <a
                                href="/item/1553" data-url="1553" class="tooltip-link link">Vial of Velium Vapors</a>) then


>**Tanik Greskil says:** Thank you, Soandso. I shall be eternally grateful to you. Should you ever require my assistance I pledge to you my aid. Please deliver this to Borannin, it is imperative that he deliver this to the Dain at once. Farewell for now outlander....


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_868.png" alt="" /> <a
                                href="/item/1560" data-url="1560" class="tooltip-link link">Taniks note</a> 

 


**Stop timer** named *moveloc*


**Tanik Greskil despawns.**

**This NPC *should* return incorrect items given.**



## Timer(s)

if(e.timer == "faint") then


**Stop timer** named *faint*


e.self:SetAppearance(3);

elseif(e.timer == "moveloc") then


**Stop timer** named *moveloc*


**Tanik Greskil despawns.**
end



## On NPC Death

**Stop timer** named *moveloc*