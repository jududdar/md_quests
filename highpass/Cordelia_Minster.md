# Cordelia Minster


## Dialog



**You say:** `hail`



>**Cordelia Minster says:** Greetings!  I am Cordelia, a traveling piper. I am afraid I cannot play a tune for you, however, as my [flute] is gone.




**You say:** `flute`



>**Cordelia Minster says:** I traded my flute to a hermit in the southern plains of Karana. I had a spare flute, but that was taken from me by some bandits. If you could find this hermit and ask him for my flute back, I would be most appreciative.
end



## Turn-Ins




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_751.png" alt="" /> <a
                                href="/item/13310" data-url="13310" class="tooltip-link link">A Cracked Flute</a>) then 


>**Cordelia Minster says:** Why thank you, kind adventurer! Here is a little something to keep food in your belly. Now back to practice. La la la..


Your faction standing with [League of Antonican Bards](/faction/284) got better (<span class='text-success'>+5</span>)


Your faction standing with [Knights of Truth](/faction/281) got better (<span class='text-success'>+1</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+1</span>)


Your faction standing with [Ring of Scale](/faction/304) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Mayong Mistmoore](/faction/285) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/13119" data-url="13119" class="tooltip-link link">Winds of Karana sheet 2</a> (+1000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-5 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**



## On NPC Spawn

**Set a timer** named *timecheck* for 60 seconds


## Timer(s)

if ( e.timer == "timecheck" and not e.self:IsEngaged() ) then




local zoneTime = eq.get_zone_time()["zone_hour"];



if ( zoneTime < 19 and zoneTime > 6 ) then



**Cordelia Minster despawns.**

end



## On NPC Death

**Spawn NPC from spawn group:** [Cytodl Krish](/npc/336269) after 1200 second(s)