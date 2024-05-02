# an angry goblin




## Dialog

if(**You possess item:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1045.png" alt="" /> <a
                                href="/item/5728" data-url="5728" class="tooltip-link link">Di'zok Signet of Service</a> x 1





**You say:** `hail`




>**an angry goblin says:** 'Go away, my life is miserable enough!' The angry goblin looks at you more closely, his rage fading for a moment. 'Are you here with the evidence I was promised? Give it to me if you have it.'

end

## Turn-Ins




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_861.png" alt="" /> <a
                                href="/item/6474" data-url="6474" class="tooltip-link link">Report to Skargus</a>) then 


eq.start(99);


>*an angry goblin howls in triumph! 'This is just what I needed! Skargus is mine now, wait until he finds out, just wait! His death is close at hand. Follow me and I'll take you to Skargus's chamber, you can wait there while I take this report to the chief!'*





 &#127873; **You receive:** 0 (+50000 exp)

 

**This NPC *should* return incorrect items given.**

## Arrive at Waypoint Script

if(e.wp == 11) then


**an angry goblin shouts:** <span class="text-danger">I have you now Skargus, you traitor! Even now I'm taking this report of slave-trading to the chief! Your days here are at an</span>


**Spawn NPC:**  [Warlord Skargus](/npc/81006) at this location.


**an angry goblin despawns.**
end
