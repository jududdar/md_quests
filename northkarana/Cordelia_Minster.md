# Cordelia Minster



## Arrive at Waypoint Script

if(e.wp == 1 or e.wp == 3 or e.wp == 8) then


e.self:SetRunning(true);

elseif(e.wp == 2 or e.wp == 6 or e.wp == 10) then


e.self:SetRunning(false);
end

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


