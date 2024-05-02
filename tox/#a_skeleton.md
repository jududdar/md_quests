# a skeleton
## On NPC Spawn

eq.set_timer("rant",math.random(180000,450000));
## Dialog

**You say:** `hail`



>**a skeleton says:** Grab a pick. Give us a hand!
end

## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_639.png" alt="" /> <a
                                href="/item/13894" data-url="13894" class="tooltip-link link">Useless Cloth Cap</a>) then


>**a skeleton says:** Good work, you should be running this operation instead of that Talrigar fellow. Have a small reward. A little bit of the gems I found while tunneling through this rock.


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_944.png" alt="" /> <a
                                href="/item/10015" data-url="10015" class="tooltip-link link">Malachite</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_945.png" alt="" /> <a
                                href="/item/10016" data-url="10016" class="tooltip-link link">Lapis Lazuli</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_946.png" alt="" /> <a
                                href="/item/10017" data-url="10017" class="tooltip-link link">Turquoise</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_767.png" alt="" /> <a
                                href="/item/10018" data-url="10018" class="tooltip-link link">Hematite</a>) (+500 exp)

 

**This NPC *should* return incorrect items given.**

## Timer(s)

if(e.timer == "rant") then


>**a skeleton says:** A skeleton's day is never done.


eq.set_timer("rant",math.random(180000,450000));
end
