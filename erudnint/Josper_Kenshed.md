# Josper Kenshed



[Josper Kenshed](/npc/23072) is a level 61 Erudite GM Wizard that spawns in [Erudin Palace](/zone/23).



## Dialog

**You say:** `hail`



>**Josper Kenshed says:** Come forward and speak.  What is it you seek within these walls?  Let it be the knowledge of wizardry. for that is what we are.  Only a [servant of wizardry] should be within these walls.

**You say:** `servant of wizardry`



>**Josper Kenshed says:** A servant. you say?  If you be a young apprentice. perhaps you might assist me? I could use you to [collect components].  If you believe yourself to be beyond such things. you may wish to assist me with a [special matter].

**You say:** `collect component`



if **Faction** >= Amiable then 



**You say:** `collect component`





>**Josper Kenshed says:** Of course you may assist me!! We have much need of a certain item which can only be found in the frigid peaks of Everfrost. There you shall find creatures called ice goblins. Take this bag and fill it with ice goblin beads and be sure to combine them before you return them. Well, then... Off with you!! And be quick about it and I shall give you a fine wizard's weapon. None of this rust-covered garbage offered by our associates!




 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_690.png" alt="" /> <a
                                href="/item/17944" data-url="17944" class="tooltip-link link">Empty Bag</a>



**You say:** `special matter`





>**Josper Kenshed says:** It seems my last apprentice was sent into Toxxulia to test a spell I call Ice Capade, well, everyone else calls it Column of Frost, how droll! Anyway... he never returned. I fear he is nothing more than BONES, though I hope I'm wrong. Could you find good old Ilanic and ask him, [where is the scroll]?! I do not wish it to fall into enemy hands. Return it and I shall let you keep the scroll. Oh yes, It is only half of a spell. I forgot to send him the full scroll. I imagine that is why he was not victorious.




elseif **Faction** >= Indifferent then



>**Josper Kenshed says:** The Crimson Hands have no quarrel with you, but we cannot truly trust you as yet.





else



>**Josper Kenshed says:** The Crimson Hands will have nothing to do with you. Perhaps only your death shall improve our relations.


end



## Turn-Ins




if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_690.png" alt="" /> <a
                                href="/item/13898" data-url="13898" class="tooltip-link link">Bag of Ice Necklaces</a>) then 


>**Josper Kenshed says:** Well done, my young apprentice. I call you apprentice for you are nothing but a spark to my fire. This is the final component for my greatest creation. AHA!! I call it - iced tea!! Never again shall I boil under the hot sun. As for you, take this. It should serve you well. Now go away. There is no iced tea for you.





Your faction standing with [Crimson Hands](/faction/233) got better (<span class='text-success'>+15</span>)


Your faction standing with [High Council of Erudin](/faction/266) got better (<span class='text-success'>+1</span>)


Your faction standing with [Heretics](/faction/265) got worse (<span class='text-danger'>-2</span>)


Your faction standing with [High Guard of Erudin](/faction/267) got better (<span class='text-success'>+2</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_601.png" alt="" /> <a
                                href="/item/12208" data-url="12208" class="tooltip-link link">Servants Staff</a> (+1000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 7 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_864.png" alt="" /> <a
                                href="/item/12207" data-url="12207" class="tooltip-link link">Half of a Spell</a>) then 


>**Josper Kenshed says:** I see you found Ilanic. How is he doing? I hope he is well. As for you, you may have the spell Ice Capa... err, I mean Column of Frost. Don't go and lose it now.





Your faction standing with [Crimson Hands](/faction/233) got better (<span class='text-success'>+5</span>)


Your faction standing with [High Council of Erudin](/faction/266) got better (<span class='text-success'>+1</span>)


Your faction standing with [Heretics](/faction/265) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [High Guard of Erudin](/faction/267) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15380" data-url="15380" class="tooltip-link link">Spell: Column of Frost</a> (+1000 exp)

 



**This NPC *should* return incorrect items given.**
;

