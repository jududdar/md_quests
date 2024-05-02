# Lysbith McNaff
## Dialog

**You say:** `hail`



>**Lysbith McNaff says:** Hail! Ye've come to [serve Halas]. have ye not? We're the Wolves o' the North and it is our task to defend our city from harm.

**You say:** `serve halas`



if( **Faction is** > Indifferent) then 



**You say:** `serve halas`





>**Lysbith McNaff says:** Halas is surrounded by barren arctic tundra. We've many foes. Among them are the [orc troopers]. [ice goblins] and the ever-present polar bears.



**You say:** `orc troopers`





>**Lysbith McNaff says:** So. Ye think yerself strong enough to battle the snow orc troopers? I pray to the Tribunal that ye are. If ye can return to me four wrath orc wristbands from the troopers' bodies. I'll reward ye with the [Seax].



**You say:** `protect the pass`





>**Lysbith McNaff says:** Then travel to the Everfrost Peaks and take this pack with you.  I want you to return this pack to me when it is filled with the beaded ice necklaces of the Ice Goblins.  When it is filled, combine the items and return it to me and I shall decide if you deserve a reward for your deed.




 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_690.png" alt="" /> <a
                                href="/item/17944" data-url="17944" class="tooltip-link link">Empty Bag</a>










elseif( **Faction is** == Indifferent) then



>**Lysbith McNaff says:** The Wolves o' the North show ye no ill will, but there's much ye must do to earn our trust. Perhaps ye should inquire o' the [gnoll bounty].


elseif( **Faction is** < Indifferent) then



>**Lysbith McNaff says:** Run while ye still can!! The Wolves o' the North will not tolerate yer presence!





**You say:** `ice goblins`



>**Lysbith McNaff says:** The ice goblins have plagued our community fer some time now. At times. they even manage to get inside our walls. Fer the most part. they prey on travelers who pass through Everfrost Peaks. Since they're a weak race. we employ our youngest warriors to [protect the pass].

**You say:** `seax`



>**Lysbith McNaff says:** The Seax is a Northman warrior's piercing weapon. Dinnae confuse this with another [weapon] related to the Seax called the Langseax. The local rogues have also learned to master the Seax. I'll only offer it to those who battle the [orc troopers].

**You say:** `gnoll bounty`



>**Lysbith McNaff says:** I've placed a bounty on the gnolls o'Blackburrow. Their whelps have invaded our land and we must carry the fight into their dens. Join the fight and return three gnoll fangs as proof of yer victory in Blackburrow. Do so, and earn the respect o' the Wolves o' the North.

**You say:** `weapon`



>**Lysbith McNaff says:** The Langseax is a one-handed slashing weapon crafted fer a warrior. Tis the brother to the [Seax].


end

## Turn-Ins



if( **Faction is** > Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_637.png" alt="" /> <a
                                href="/item/12223" data-url="12223" class="tooltip-link link">Wrath Orc Wristbands</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_637.png" alt="" /> <a
                                href="/item/12223" data-url="12223" class="tooltip-link link">Wrath Orc Wristbands</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_637.png" alt="" /> <a
                                href="/item/12223" data-url="12223" class="tooltip-link link">Wrath Orc Wristbands</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_637.png" alt="" /> <a
                                href="/item/12223" data-url="12223" class="tooltip-link link">Wrath Orc Wristbands</a>) then 


>**Lysbith McNaff says:** Ye're becoming a fine champion o' Halas. Take th' Seax. May ye always defend Halas!





Your faction standing with [Wolves of the North](/faction/320) got better (<span class='text-success'>+20</span>)





Your faction standing with [Shamen of Justice](/faction/327) got better (<span class='text-success'>+4</span>)





Your faction standing with [Merchants of Halas](/faction/328) got better (<span class='text-success'>+5</span>)





Your faction standing with [Steel Warriors](/faction/311) got better (<span class='text-success'>+1</span>)





 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_592.png" alt="" /> <a
                                href="/item/7322" data-url="7322" class="tooltip-link link">Seax</a> (+3000 exp)

 

elseif( **Faction is** > Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_690.png" alt="" /> <a
                                href="/item/13898" data-url="13898" class="tooltip-link link">Bag of Ice Necklaces</a>) then 


>**Lysbith McNaff says:** Ye've done well, me young " .. e.other:Class() .. " .  We've gathered these to add to yer provisions.  While in the Everfrost Peaks, be on the watch fer any gnolls ye may find.  I declare there to be a [gnoll bounty].





Your faction standing with [Wolves of the North](/faction/320) got better (<span class='text-success'>+10</span>)





Your faction standing with [Shamen of Justice](/faction/327) got better (<span class='text-success'>+2</span>)





Your faction standing with [Merchants of Halas](/faction/328) got better (<span class='text-success'>+2</span>)





Your faction standing with [Steel Warriors](/faction/311) got better (<span class='text-success'>+1</span>)





 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_570.png" alt="" /> <a
                                href="/item/13005" data-url="13005" class="tooltip-link link">Iron Ration</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_570.png" alt="" /> <a
                                href="/item/13007" data-url="13007" class="tooltip-link link">Ration</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_584.png" alt="" /> <a
                                href="/item/13006" data-url="13006" class="tooltip-link link">Water Flask</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_547.png" alt="" /> <a
                                href="/item/13002" data-url="13002" class="tooltip-link link">Torch</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_684.png" alt="" /> <a
                                href="/item/13003" data-url="13003" class="tooltip-link link">Small Lantern</a>) (+3800 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0-5 <img src='/static/icons/item_645.png' width='14' height='14'/> 0-5 <img src='/static/icons/item_646.png' width='14' height='14'/> 0-5 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_800.png" alt="" /> <a
                                href="/item/13915" data-url="13915" class="tooltip-link link">Gnoll Fang</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_800.png" alt="" /> <a
                                href="/item/13915" data-url="13915" class="tooltip-link link">Gnoll Fang</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_800.png" alt="" /> <a
                                href="/item/13915" data-url="13915" class="tooltip-link link">Gnoll Fang</a>) then



>**Lysbith McNaff says:** Fine work, fine work!  The gnoll threat must be extinguished before it can ever fully grow.  Ye've done yer part to aid our cause.  Please allow me to repay ye with a few provisions and a wee bit o' coin.  Then, continue with yer good deeds.





Your faction standing with [Wolves of the North](/faction/320) got better (<span class='text-success'>+15</span>)




Your faction standing with [Shamen of Justice](/faction/327) got better (<span class='text-success'>+3</span>)




Your faction standing with [Merchants of Halas](/faction/328) got better (<span class='text-success'>+3</span>)




Your faction standing with [Steel Warriors](/faction/311) got better (<span class='text-success'>+1</span>)




 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_570.png" alt="" /> <a
                                href="/item/13005" data-url="13005" class="tooltip-link link">Iron Ration</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_570.png" alt="" /> <a
                                href="/item/13007" data-url="13007" class="tooltip-link link">Ration</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_584.png" alt="" /> <a
                                href="/item/13006" data-url="13006" class="tooltip-link link">Water Flask</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_547.png" alt="" /> <a
                                href="/item/13002" data-url="13002" class="tooltip-link link">Torch</a>) (+8000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0-5 <img src='/static/icons/item_645.png' width='14' height='14'/> 0-5 <img src='/static/icons/item_646.png' width='14' height='14'/> 0-5 <img src='/static/icons/item_647.png' width='14' height='14'/> 
**This NPC *should* return incorrect items given.**
