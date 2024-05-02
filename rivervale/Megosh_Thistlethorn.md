# Megosh Thistlethorn
## Dialog

if(eq.get_current_expansion() >= 4.0) then


**You say:** `hail`




>**Megosh Thistlethorn says:** Greetings Soandso! I am Megosh Thistlethorn first Ranger of the Storm Reapers of Rivervale. I journeyed many years ago to the Surefall Glade far to the west of our lovely shire. It was there I trained with the human and half-elven rangers that like the Storm Reapers are faithful disciples of Karana. I have returned now to Rivervale to teach our interested young people the ways of a ranger of the Storm Lord, so that we may defend our shire and the wilds of Norrath from the [evil forces] that would see it destroyed.


**You say:** `evil forces`




>**Megosh Thistlethorn says:** Currently the Death Fist Clan of Orcs, a race of bloodthirsty humanoids concerned only with expanding their territory and slaughtering all who stand in their path, threatens our homeland. The Orcs have long had a minor presence in the Misty Thicket but lately they have been amassing in greater numbers. The Death Fist has been chopping down our trees and quarrying rock from the nearby mountains. We know only that they have been shipping the materials to the commonlands and stockpiling it for what purpose we do not know. As rangers of the Storm Reapers it is our duty to [stop the desecration] of the thicket.


**You say:** `stop the desecration`




>**Megosh Thistlethorn says:** First you must outfit yourself for battle with the Death Fists. Seek Bipdo Hargin here in Rivervale and give him this letter. He will instruct you further on getting yourself outfitted for the tasks ahead. Once you have been outfitted in a suit of Thorn Mail Armor return to me and I will instruct you for your [next task].



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_868.png" alt="" /> <a
                                href="/item/19627" data-url="19627" class="tooltip-link link">Letter to Bipdo Hargin</a>


**You say:** `next task`




>**Megosh Thistlethorn says:** If you feel you are ready to face the Orcs of Clan Death Fist then journey to the Misty Thicket beyond the protection of the Wall of Cetelt. Hunt the Orcs that are cutting down the trees of the thicket and bring me two of the Orc Lumberjack Axes and two of the Orc Lumberjack Machetes.


**You say:** `forge`




>**Megosh Thistlethorn says:** What forge?  Didn't you see it on the way in, young Soandso?  Oh, and check with Smithy Bodbin about the sharpening stones, he usually has a good supply of them.

end

## Turn-Ins



local expansion_flag = eq.get_current_expansion();

if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_683.png" alt="" /> <a
                                href="/item/18432" data-url="18432" class="tooltip-link link">Halfling Ranger Note</a>) then 


>**Megosh Thistlethorn says:** Welcome to the Storm Reapers Soandso! Here is a tunic to keep you warm in your travels. Rivervale, our lovely home is facing dangerous times. From both the east and west forces devoted to the evil Gods Bertoxxulous and Innoruuk are corrupting and destroying the wilds of Norrath. Also, the Orcs of Clan Deathfist are waging war on this entire region and gathering lumber and stone for some unknown purpose. We must do our best to preserve the lands and way of life of all Karanas people.


Your faction standing with [Storm Reapers](/faction/355) got better (<span class='text-success'>+100</span>)


Your faction standing with [Mayor Gubbin](/faction/286) got better (<span class='text-success'>+10</span>)


Your faction standing with [Merchants of Rivervale](/faction/292) got better (<span class='text-success'>+15</span>)


Your faction standing with [Unkempt Druids](/faction/324) got worse (<span class='text-danger'>-15</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_678.png" alt="" /> <a
                                href="/item/13541" data-url="13541" class="tooltip-link link">Jumjum Sack Tunic*</a> (+100 exp)

 

elseif(expansion_flag >= 4.0 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_569.png" alt="" /> <a
                                href="/item/19622" data-url="19622" class="tooltip-link link">Orc Lumberjack Axe</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_569.png" alt="" /> <a
                                href="/item/19622" data-url="19622" class="tooltip-link link">Orc Lumberjack Axe</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_590.png" alt="" /> <a
                                href="/item/19623" data-url="19623" class="tooltip-link link">Orc Lumberjack Machete</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_590.png" alt="" /> <a
                                href="/item/19623" data-url="19623" class="tooltip-link link">Orc Lumberjack Machete</a>) then 


>**Megosh Thistlethorn says:** Excellent work young Storm Reaper Soandso. Now take this Dull Storm Reaper Machete to a [forge] and sharpen it with a sharpening stone. It may take several attempts to get the blade to an adequate sharpness if you are unfamiliar with the process. Once it is sharpened give it to Bodbin Gimple with a ruined thorn drakeling scales and he will put the finishing touches on what will be a fine weapon!


Your faction standing with [Storm Reapers](/faction/355) got better (<span class='text-success'>+5</span>)


Your faction standing with [Mayor Gubbin](/faction/286) got better (<span class='text-success'>+1</span>)


Your faction standing with [Merchants of Rivervale](/faction/292) got better (<span class='text-success'>+1</span>)


Your faction standing with [Unkempt Druids](/faction/324) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_590.png" alt="" /> <a
                                href="/item/19624" data-url="19624" class="tooltip-link link">Dull Storm Reaper Machete</a> (+10 exp)

 

**This NPC *should* return incorrect items given.**


