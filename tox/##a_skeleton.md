# a skeleton


## On NPC Spawn

eq.set_timer("rant",math.random(180000,450000));


## Dialog

**You say:** `hail`



>**a skeleton says:** Can't you see we're busy here?!
end



## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_639.png" alt="" /> <a
                                href="/item/13894" data-url="13894" class="tooltip-link link">Useless Cloth Cap</a>) then


>**a skeleton says:** Aye.. You cut out the middleman..  I shall reward you.. hmm..  I have not found anything. how about..  <CRACK!! SNAP!! RIPP!!>  How about something off meself?


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_974.png" alt="" /> <a
                                href="/item/9304" data-url="9304" class="tooltip-link link">Bone Shield</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_905.png" alt="" /> <a
                                href="/item/12195" data-url="12195" class="tooltip-link link">Fractured Femur</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_804.png" alt="" /> <a
                                href="/item/13073" data-url="13073" class="tooltip-link link">Bone Chips</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_823.png" alt="" /> <a
                                href="/item/13074" data-url="13074" class="tooltip-link link">Zombie Skin</a>) (+500 exp)

 

**This NPC *should* return incorrect items given.**



## Timer(s)

if(e.timer == "rant") then


>**a skeleton says:** Yo ho. No sun!


eq.set_timer("rant",math.random(180000,450000));
end
