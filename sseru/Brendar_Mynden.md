# Brendar Mynden




## Dialog

**You say:** `hail`



>**Brendar Mynden says:** Yeah, what do you want?

**You say:** `compromise`



>**Brendar Mynden says:** A compromise? Zabaltin has fought me in every request asking for help protecting the delivery caravans! I will never work with him. Say what is that in your hand? The label looks like it is a bottle of my favorite ale. It's from Zabaltin you say? Maybe he really is trying to work things out. Well then let's open the bottle and have a drink!
end



## Turn-Ins





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_826.png" alt="" /> <a
                                href="/item/29862" data-url="29862" class="tooltip-link link">Poisoned Wine</a>) then
 

>*Brendar Mynden opens the bottle and takes a large drink right from it. Immediately his eyes roll back into their sockets and he falls to the ground. You look around to make sure no one has seen and then take the ring from his finger.*


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_875.png" alt="" /> <a
                                href="/item/29863" data-url="29863" class="tooltip-link link">Unadorned Ring</a> 

 


e.self:DoAnim(15);


e.self:SetAppearance(3);


**Set a timer** named *depop* for 5 seconds

**This NPC *should* return incorrect items given.**



## Timer(s)

if(e.timer == "depop") then


**Brendar Mynden despawns.**
end
