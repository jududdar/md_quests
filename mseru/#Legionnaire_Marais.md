# Legionnaire Marais


## On NPC Spawn

**Set a timer** named *depop* for 600 seconds


## Timer(s)

if(e.timer == "depop") then


**Legionnaire Marais despawns.**

elseif(e.timer == "die") then


**Legionnaire Marais despawns.**
end



## Dialog

**You say:** `hail`



>*Legionnaire Marais looks up at you wearily, 'Corporal Donfeld?'*
end



## Turn-Ins





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1005.png" alt="" /> <a
                                href="/item/18332" data-url="18332" class="tooltip-link link">torn half of a note</a>) then 


>*Legionnaire Marais shows relief in his eyes, 'I knew someone would come if I... just held out... long enough... Take these... be careful... ' And with that, Marais allows himself to finally die.*


 &#127873; **You receive:** GiveAll( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_869.png" alt="" /> <a
                                href="/item/18334" data-url="18334" class="tooltip-link link">Marais' Notes</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_869.png" alt="" /> <a
                                href="/item/18333" data-url="18333" class="tooltip-link link">Marais' Notes</a>) 

 


**Set a timer** named *die* for 10 seconds

**This NPC *should* return incorrect items given.**
