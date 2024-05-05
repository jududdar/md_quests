# Megan OReilly



[Megan OReilly](/npc/30097) is a level 2 Barbarian Warrior that spawns in [Everfrost Peaks](/zone/30).



## Dialog

**You say:** `hail`



>**Megan OReilly says:** Brrrr.. It.. Is sooo.. c-cold!! I never.. sh-should've j-joined.. the.. the W-wolves of the N-north!!

**You say:** `ivan's remains`



if( **Faction is** > Indifferent) then 



>**Megan OReilly says:** You were sent to retrieve the remains? I am sorry, I lost them. It was not my fault! There was no escort as I was told. I got lost returning to Halas and ended up on a frozen river. The ice broke and the remains were scattered into the freezing water. Will you [dive for the remains]?


elseif( **Faction is** == Indifferent) then



>**Megan OReilly says:** The Wolves o' the North show ye no ill will, but there's much ye must do t' earn our trust.  Perhaps ye should speak with Lysbith and inquire o' the [gnoll bounty].


elseif( **Faction is** < Indifferent) then



>**Megan OReilly says:** Run while ye still can!! The Wolves o' the North will not tolerate yer presence!



**You say:** `dive for the remains`



if( **Faction is** > Indifferent) then 



>**Megan OReilly says:** Thank the Tribunal!! I would have, but I cannot swim. Take this chest. Fill it with the four pieces which fell below the surface. I know not what else lies within. When you fill the box and combine the items, return it to Renth. Good luck, Soandso.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_608.png" alt="" /> <a
                                href="/item/17945" data-url="17945" class="tooltip-link link">Empty Box</a>


elseif( **Faction is** == Indifferent) then



>**Megan OReilly says:** The Wolves o' the North show ye no ill will, but there's much ye must do t' earn our trust.  Perhaps ye should speak with Lysbith and inquire o' the [gnoll bounty].


elseif( **Faction is** < Indifferent) then



>**Megan OReilly says:** Run while ye still can!! The Wolves o' the North will not tolerate yer presence!



end



## Turn-Ins




if( **Faction is** > Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_788.png" alt="" /> <a
                                href="/item/13244" data-url="13244" class="tooltip-link link">One Quarter of Elixir</a>) then 


>**Megan OReilly says:** Oh thank you. Sorry, but the bottle is empty now. I hope you did't need any. Take the empty bottle back to Dargon. He may refill it for you.





Your faction standing with [Wolves of the North](/faction/320) got better (<span class='text-success'>+5</span>)


Your faction standing with [Shamen of Justice](/faction/327) got better (<span class='text-success'>+1</span>)


Your faction standing with [Merchants of Halas](/faction/328) got better (<span class='text-success'>+1</span>)


Your faction standing with [Steel Warriors](/faction/311) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_788.png" alt="" /> <a
                                href="/item/13245" data-url="13245" class="tooltip-link link">Empty Bottle of Elixir</a> (+150 exp)

 

**This NPC *should* return incorrect items given.**
;


## Arrive at Waypoint Script

if(e.wp == 3) then


e.self:SetRunning(true);

elseif(e.wp == 6) then


e.self:SetRunning(false);
end


