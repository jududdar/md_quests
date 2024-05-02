# Arnis McLish
## Dialog

**You say:** `hail`



>**Arnis McLish says:** My word!! I cannot believe how cold it is out here. I must keep running around just to keep warm.

**You say:** `megan`



if( **Faction is** > Indifferent) then



>**Arnis McLish says:** I heard she got lost on the plains. You should go ask her dog, Snowflake, where she is. I hear she is somewhere around the pass to Halas.


elseif( **Faction is** == Indifferent) then



>**Arnis McLish says:** The Wolves o' the North show ye no ill will, but there's much ye must do t' earn our trust.  Perhaps ye should speak with Lysbith and inquire o' the [gnoll bounty].


else



>**Arnis McLish says:** Run while ye still can!! The Wolves o' the North will not tolerate yer presence!

end

## Turn-Ins




if( **Faction is** > Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_788.png" alt="" /> <a
                                href="/item/13243" data-url="13243" class="tooltip-link link">One Half of Elixir</a>) then 


>**Arnis McLish says:** Mmmm.. Thank you stranger. I feel a lot warmer now. You should now go and find [Megan] O'Reilly.





Your faction standing with [Wolves of the North](/faction/320) got better (<span class='text-success'>+5</span>)


Your faction standing with [Shamen of Justice](/faction/327) got better (<span class='text-success'>+1</span>)


Your faction standing with [Merchants of Halas](/faction/328) got better (<span class='text-success'>+1</span>)


Your faction standing with [Steel Warriors](/faction/311) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_788.png" alt="" /> <a
                                href="/item/13244" data-url="13244" class="tooltip-link link">One Quarter of Elixir</a> (+150 exp)

 

**This NPC *should* return incorrect items given.**
;
## On NPC Spawn

e.self:SetRunning(true);

