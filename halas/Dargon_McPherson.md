# Dargon McPherson
## Dialog

**You say:** `Hail`



>**Dargon McPherson says:** Hail, mighty Soandso! I assume ye must be a [warrior o' the Wolves]. Why else would ye approach a trainer such as meself, then?

**You say:** `warrior o' the Wolves`



if( **Faction is** > Indifferent) then 



>**Dargon McPherson says:** Aye, 'tis as I thought. I'm glad t' see we've warriors such as yerself amongst the Wolves o' the North. Lately, Kylan's been allowing too many scrawny warriors in, methinks. Nor have they fared well in Everfrrost. Many frreeze to death, ye know... Will ye assist me and [deliver an elixir to young warriors] in Everfrost?


elseif( **Faction is** == Indifferent) then



>**Dargon McPherson says:** The Wolves o' the North show ye no ill will, but there's much ye must do t' earn our trust.  Perhaps ye should speak with Lysbith and inquire o' the [gnoll bounty].


elseif( **Faction is** < Indifferent) then



>**Dargon McPherson says:** Run while ye still can!! The Wolves o' the North will not tolerate yer presence!


**You say:** `deliver an elixir to young warriors`



if( **Faction is** > Indifferent) then 



>**Dargon McPherson says:** Ach, 'tis good o' ye! Take this bottle of elixir to Everfrost Peaks. Find Talin O'Donal. He'll take the first sip, and then instruct ye on who else ye need to find. Do that, and I'll give ye a fine reward when ye return the empty elixir bottle. Good luck, then. Don't die.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_788.png" alt="" /> <a
                                href="/item/13241" data-url="13241" class="tooltip-link link">Full Bottle of Elixir</a>


elseif( **Faction is** == Indifferent) then



>**Dargon McPherson says:** The Wolves o' the North show ye no ill will, but there's much ye must do t' earn our trust.  Perhaps ye should speak with Lysbith and inquire o' the [gnoll bounty].


elseif( **Faction is** < Indifferent) then



>**Dargon McPherson says:** Run while ye still can!! The Wolves o' the North will not tolerate yer presence!

end

## Turn-Ins



if( **Faction is** > Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_788.png" alt="" /> <a
                                href="/item/13245" data-url="13245" class="tooltip-link link">Empty Bottle of Elixir</a>) then 


>**Dargon McPherson says:** Ye've proven yerself to be a cut above the rest and aided yer fellow warriors, no matter how worthless they were. Ye may take this. It was found in the snow by one of our foraging parties. I hope it can be of use to a warrior like yerself.





Your faction standing with [Wolves of the North](/faction/320) got better (<span class='text-success'>+5</span>)


Your faction standing with [Shamen of Justice](/faction/327) got better (<span class='text-success'>+1</span>)


Your faction standing with [Merchants of Halas](/faction/328) got better (<span class='text-success'>+1</span>)


Your faction standing with [Steel Warriors](/faction/311) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_633.png" alt="" /> <a
                                href="/item/2012" data-url="2012" class="tooltip-link link">Leather Boots</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_667.png" alt="" /> <a
                                href="/item/17001" data-url="17001" class="tooltip-link link">Wrist Pouch</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_748.png" alt="" /> <a
                                href="/item/10004" data-url="10004" class="tooltip-link link">Copper Band</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_946.png" alt="" /> <a
                                href="/item/10017" data-url="10017" class="tooltip-link link">Turquoise</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_761.png" alt="" /> <a
                                href="/item/1038" data-url="1038" class="tooltip-link link">Tattered Cloth Sandal</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_945.png" alt="" /> <a
                                href="/item/10016" data-url="10016" class="tooltip-link link">Lapis Lazuli</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_759.png" alt="" /> <a
                                href="/item/13877" data-url="13877" class="tooltip-link link">Corroded Buckler</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_635.png" alt="" /> <a
                                href="/item/2135" data-url="2135" class="tooltip-link link">Large Patchwork Pants</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_592.png" alt="" /> <a
                                href="/item/7007" data-url="7007" class="tooltip-link link">Rusty Dagger</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_573.png" alt="" /> <a
                                href="/item/8008" data-url="8008" class="tooltip-link link">Throwing Axe</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_848.png" alt="" /> <a
                                href="/item/10009" data-url="10009" class="tooltip-link link">Bead Necklace</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_570.png" alt="" /> <a
                                href="/item/13007" data-url="13007" class="tooltip-link link">Ration</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_569.png" alt="" /> <a
                                href="/item/5014" data-url="5014" class="tooltip-link link">Rusty Axe</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_684.png" alt="" /> <a
                                href="/item/13003" data-url="13003" class="tooltip-link link">Small Lantern</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_827.png" alt="" /> <a
                                href="/item/13107" data-url="13107" class="tooltip-link link">Black Burrow Stout</a>) (+125 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-5 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**
