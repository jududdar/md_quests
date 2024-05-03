# Altunic Jartin


## Arrive at Waypoint Script

if(e.wp == 2) then


e.self:SetRunning(true);

elseif(e.wp == 3) then


e.self:SetRunning(false);
end



## Dialog

**You say:** `hail`



>**Altunic Jartin says:** Greetings, traveler! Have you need of provisions or perhaps other wares? I sell what I find upon the battlegrounds of the Commonlands.

**You say:** `Where is your house`



>**Altunic Jartin says:** Follow me.


eq.move_to(4791.06,-83.55,-51.47);


**Spawn NPC:**  [Squire Narl](/npc/22196) at (**y:** -105.49, **x:** 4707.63)
end



## Turn-Ins




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18896" data-url="18896" class="tooltip-link link">A note</a>) then


>**Altunic Jartin says:** You are the one they have sent? A squire?!! I hope you can help me. I gather items strewn upon the grounds of the Commonlands. I sell them at good prices. Lately, I have been terrorized by a human rogue named Narl. He will no doubt appear at my [house] soon. Bring his head to me.

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_982.png" alt="" /> <a
                                href="/item/13867" data-url="13867" class="tooltip-link link">A Human Head</a>) then


>**Altunic Jartin says:** You have performed a great service to me, but I fear others will attack me while I stroll the countryside. It would be very noble of you to fetch me a cloth shirt for protection from wicked creatures. It is not much, but it will help.


Your faction standing with [Knights of Truth](/faction/281) got better (<span class='text-success'>+5</span>)


Your faction standing with [Dismal Rage](/faction/271) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [The Freeport Militia](/faction/330) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Priests of Marr](/faction/362) got better (<span class='text-success'>+1</span>)


Your faction standing with [Steel Warriors](/faction/311) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:** 0 (+500 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_678.png" alt="" /> <a
                                href="/item/1004" data-url="1004" class="tooltip-link link">Cloth Shirt</a>) then


>**Altunic Jartin says:** Thank you. You are very noble for a squire. I can see you becoming a very valuable asset to the Hall of Truth. Take this token. Tell Merko that you have [earned the Token of Generosity].


Your faction standing with [Knights of Truth](/faction/281) got better (<span class='text-success'>+5</span>)


Your faction standing with [Dismal Rage](/faction/271) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [The Freeport Militia](/faction/330) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Priests of Marr](/faction/362) got better (<span class='text-success'>+1</span>)


Your faction standing with [Steel Warriors](/faction/311) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_646.png" alt="" /> <a
                                href="/item/13865" data-url="13865" class="tooltip-link link">Token of Generosity</a> (+500 exp)

 
end


