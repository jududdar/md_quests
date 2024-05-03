# Arena Master Ferin


## Dialog

**You say:** `hail`



>**Arena Master Ferin says:** Hurry, hurry step right up and buy a ticket! Show your skills at battle! Amaze the crowds with your great skill! Buy a ticket from me, and when you think you are prepared for the fight give me the ticket!
end



## Turn-Ins





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_867.png" alt="" /> <a
                                href="/item/29866" data-url="29866" class="tooltip-link link">Arena Ticket</a>) then 


>**Arena Master Ferin says:** So you wish to show off your skills in the arena? Well come on let us see what you are made of! Be warned that this is a fight to the death, if a guard sees you fleeing like a coward they will assist in helping to finish you off!


eq.unique_spawn(eq.ChooseRandom(159108,159103,159109),0,0,-231,-1514,-68,128);

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1002.png" alt="" /> <a
                                href="/item/29867" data-url="29867" class="tooltip-link link">Arena Medal</a>) then 


>**Arena Master Ferin says:** Wonderful battle skills! You have pleased the audience. Here are a few coins for your valiant effort!


Your faction standing with [Citizens of Seru](/faction/1499) got better (<span class='text-success'>+10</span>)


Your faction standing with [Hand of Seru](/faction/1484) got better (<span class='text-success'>+1</span>)


Your faction standing with [Heart of Seru](/faction/1486) got better (<span class='text-success'>+1</span>)


Your faction standing with [Eye of Seru](/faction/1485) got better (<span class='text-success'>+1</span>)


Your faction standing with [Shoulders of Seru](/faction/1487) got better (<span class='text-success'>+1</span>)


Your faction standing with [Katta Castellum Citizens](/faction/1502) got worse (<span class='text-danger'>-5</span>)


 &#127873; **You receive:** 0 (+5000 exp)

**You receive coin:** 1-20 <img src='/static/icons/item_644.png' width='14' height='14'/> 0-10 <img src='/static/icons/item_645.png' width='14' height='14'/> 0-10 <img src='/static/icons/item_646.png' width='14' height='14'/> 0-10 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**
