# a drunkard



[a drunkard](/npc/54261) is a level 8 High Elf Warrior that spawns in [Greater Faydark](/zone/54).



## Dialog

**You say:** `tandan nybright`



>**a drunkard says:** How did you know my name? You must be from Felwithe. Hic.. Excuse my condition. I am not the man I was. I have had a [shocking experience].

**You say:** `shocking`



>**a drunkard says:** My daughters have become blood thirsty bandits. They went off to visit Antonica and when they returned they became bandits. They now attack every poor traveler who happens upon them. They have disgraced the name of Nybright. Will you [hunt the Nybright Sisters] or is this not to your liking?

**You say:** `hunt`



>**a drunkard says:** I am most thankful. Many adventurers would not help me with this matter. Go and seek out the Nybright sisters. I gave all four of them a Personalized Necklace. Return them all to me when the deed is done. May the Tribunal watch over you.

**You say:** `hail`



>**a drunkard says:** Can you -hic- . . . spare some copper or -hic- . . . silver? I just . . . -Hic- . . . need some change to buy something to drin . . Er . . Eat . -Hic-
end



## Turn-Ins





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_825.png" alt="" /> <a
                                href="/item/13035" data-url="13035" class="tooltip-link link">Elven Wine</a>) then


>**a drunkard says:** Thank you kind sir <hic>, I am most grateful for your generosity.


 &#127873; **You receive:** 0 (+150 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_851.png" alt="" /> <a
                                href="/item/13347" data-url="13347" class="tooltip-link link">Dull Pearl Necklace</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_851.png" alt="" /> <a
                                href="/item/13349" data-url="13349" class="tooltip-link link">Dull Pearl Necklace</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_851.png" alt="" /> <a
                                href="/item/13348" data-url="13348" class="tooltip-link link">Dull Pearl Necklace</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_851.png" alt="" /> <a
                                href="/item/13350" data-url="13350" class="tooltip-link link">Dull Pearl Necklace</a>) then


>**a drunkard says:** This is a sad day, but it was the just thing to do. The Nybright name will no longer be tarnished. Here you are my friend. This is a bit uncared for, but it is yours. My warrior days are over. Now go. I must be alone.


Your faction standing with [Clerics of Tunare](/faction/226) got better (<span class='text-success'>+10</span>)


Your faction standing with [King Tearis Thex](/faction/279) got better (<span class='text-success'>+10</span>)


Your faction standing with [Anti-mage](/faction/5002) got better (<span class='text-success'>+7</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_636.png" alt="" /> <a
                                href="/item/2314" data-url="2314" class="tooltip-link link">Bearskin Gloves</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_564.png" alt="" /> <a
                                href="/item/2007" data-url="2007" class="tooltip-link link">Leather Belt</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_668.png" alt="" /> <a
                                href="/item/2005" data-url="2005" class="tooltip-link link">Leather Shoulderpads</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_676.png" alt="" /> <a
                                href="/item/9003" data-url="9003" class="tooltip-link link">Targ Shield</a>) (+1000 exp)

 




**This NPC *should* return incorrect items given.**



## Arrive at Waypoint Script

if(e.wp == 3 or e.wp == 9 or e.wp == 15 or e.wp == 24 or e.wp == 26 or e.wp == 33) then


>**a drunkard says:** Please.. Can anyone spare some coppers? <Hic>.. Anyone?
end


