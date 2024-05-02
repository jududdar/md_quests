# Lynuga
## Dialog

**You say:** `hail`



>**Lynuga says:** Hrrump?! Who you? Soandso? What you want with Lynuga? Me am out [collecting]. Leave me be!

**You say:** `collecting`



>**Lynuga says:** I collect all sorts of things. Gems be my favorite. Me really like rubies. If you have ruby, give to me! Why you want to know? You want to steal my collection?!? I squish you if you do!!
end

## Turn-Ins



local rewarditem = 0;



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_964.png" alt="" /> <a
                                href="/item/10035" data-url="10035" class="tooltip-link link">Ruby</a>) then 


>**Lynuga says:** Mmm. Ruby!! Me thank's you! Here take this, me got it off dead someone who try take my collection. Me think's this valuable thing..


if (math.random(100) < 6) then 



rewarditem = 10082; 


else



rewarditem = eq.ChooseRandom(10080, 10081); 



Your faction standing with [Broken Skull Clan](/faction/222) got better (<span class='text-success'>+5</span>)


Your faction standing with [Shadowknights of Night Keep](/faction/308) got worse (<span class='text-danger'>-5</span>)


Your faction standing with [Da Bashers](/faction/235) got worse (<span class='text-danger'>-5</span>)


 &#127873; **You receive:** None 

 

**This NPC *should* return incorrect items given.**

## On NPC Spawn

**Set a timer** named *depop* for 2700 seconds
## Combat

if  Lynuga enters combat  then


if ( not eq.is_paused_timer("depop") ) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end

## Timer(s)

if ( e.timer == "depop" ) then


**Lynuga despawns.**
end
