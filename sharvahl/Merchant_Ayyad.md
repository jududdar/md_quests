# Merchant Ayyad



[Merchant Ayyad](/npc/155069) is a level 10 Vah Shir Shopkeeper that spawns in [The City of Shar Vahl](/zone/155).




## Dialog

**You say:** `hail`



>**Merchant Ayyad says:** Hello Soandso, sorry but I have no time to chitchat. I'm looking for the help of a citizen.

**You say:** `citizen`



>*Merchant Ayyad looks at you excitedly, 'Show me your acrylia slate and I'll explain my situation.'*

**You say:** `additional instruction`



>**Merchant Ayyad says:** Mastered those runes already, Soandso? You're learning very fast indeed. Your next lesson will be in the molding of a new type of item. You'll need to gather some gray mud from below the city and mix it with some Rockhopper blood to make a block of reddish clay. Take this block of reddish clay and combine it with a Vah Shir model sketch to create an unfired Vah Shir figurines. Fire the model in a kiln with a firing sheet to create a Finished Vah Shir figurine. Finally, use the Runequill Set to etch grimling blood into runes on the figurine.
end



## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1036.png" alt="" /> <a
                                href="/item/2877" data-url="2877" class="tooltip-link link">Acrylia Slate of Shar Vahl</a>) then


>**Merchant Ayyad says:** Some of my wares are spoiling and I must place them in a container to preserve them. I cannot afford to take the loss that would result if they were to rot. Please Soandso, take this bowl and combine two lumps of gray mud with a flask of water and xakra bile. Take the resulting clay and this sketch with another water flask to fashion an unfired gray jar. Fire it in a kiln with a firing sheet and return to me with the product as soon as you can.


 &#127873; **You receive:** GiveAll( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1036.png" alt="" /> <a
                                href="/item/2877" data-url="2877" class="tooltip-link link">Acrylia Slate of Shar Vahl</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_861.png" alt="" /> <a
                                href="/item/3497" data-url="3497" class="tooltip-link link">Reusable Gray Jar Sketch</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_858.png" alt="" /> <a
                                href="/item/17233" data-url="17233" class="tooltip-link link">Ayyads Clay Bowl</a>) 

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_688.png" alt="" /> <a
                                href="/item/3498" data-url="3498" class="tooltip-link link">Gray Jar</a>) then


>**Merchant Ayyad says:** Excellent! Please accept this knapsack as payment for your trouble. Here is my seal as well. I can always use more jars and if you give me four of my seals I will share with you a family secret.


 &#127873; **You receive:** GiveAll( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_691.png" alt="" /> <a
                                href="/item/17234" data-url="17234" class="tooltip-link link">Ayyads Knapsack</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_644.png" alt="" /> <a
                                href="/item/3499" data-url="3499" class="tooltip-link link">Ayyad's seal</a>) 

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_644.png" alt="" /> <a
                                href="/item/3499" data-url="3499" class="tooltip-link link">Ayyad's seal</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_644.png" alt="" /> <a
                                href="/item/3499" data-url="3499" class="tooltip-link link">Ayyad's seal</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_644.png" alt="" /> <a
                                href="/item/3499" data-url="3499" class="tooltip-link link">Ayyad's seal</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_644.png" alt="" /> <a
                                href="/item/3499" data-url="3499" class="tooltip-link link">Ayyad's seal</a>) then


>**Merchant Ayyad says:** Excellent, Soandso, few of our kind show a true interest in the more refined arts of pottery these days. It is very good to see the young people taking interest in the old arts. Here is a Basic Runequill Set. Take the instruments in the set and practice marking runes on the gray jars that you previously brought to me. To etch the runes, simply cover a gray jar with some Xakra bile and use the Runequill Set to etch the runes on to the jar. You'll want to fire them in a kiln when you're finished. When those jars become trivial come back and give me those basic tools and we'll see about upgrading them.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_716.png" alt="" /> <a
                                href="/item/3631" data-url="3631" class="tooltip-link link">Basic Runequill Set</a> 

 

elseif(e.other:GetRawSkill(69) >= 100 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_716.png" alt="" /> <a
                                href="/item/3631" data-url="3631" class="tooltip-link link">Basic Runequill Set</a>)  then


>**Merchant Ayyad says:** You're progressing nicely, Soandso. Take this sculpting tool and add it to the set you already have. This new quill set will be able to make some very nice urns that should help ease the burden of moving all that heavy clay around. Take a gray jar and use the new set of tools I've given you to etch Xakra blood into runes on the side of the jars. These should prove to be very useful in your labors in the future. Once you have mastered those runes, bring back your runequill set to me for another addition.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_716.png" alt="" /> <a
                                href="/item/3632" data-url="3632" class="tooltip-link link">Novice's Runequill Set</a> 

 

elseif(e.other:GetRawSkill(69) > 100 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_716.png" alt="" /> <a
                                href="/item/3632" data-url="3632" class="tooltip-link link">Novice's Runequill Set</a>)  then


>**Merchant Ayyad says:** You're progressing nicely, Soandso. Take this sculpting tool and add it to the set you already have. This new quill set will be able to make some very nice urns that should help ease the burden of moving all that heavy clay around. Take a gray jar and use the new set of tools I've given you to etch Xakra blood into runes on the side of the jars. These should prove to be very useful in your labors in the future. Once you have mastered those runes, bring back your runequill set to me for another addition.


 &#127873; **You receive:** GiveAll( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_716.png" alt="" /> <a
                                href="/item/3641" data-url="3641" class="tooltip-link link">Finely Crafted Runequill Set</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/3647" data-url="3647" class="tooltip-link link">Ayyad's Note to Fareed</a>) 

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/3643" data-url="3643" class="tooltip-link link">Fareed's Note to Ayyad</a>) then


>**Merchant Ayyad says:** Welcome back Soandso, I trust you behaved well in the presence of the king's servants. It seems Fareed was very impressed with your work, as he has instructed me to give you a very nice reward. Here, take this Urn, it will surely prove very useful to you as you continue your study of the molding of the earth. Oh, I almost forgot to tell you, Grilo the mason was here earlier looking for you, he has heard of your talents and believes that you might do well in the school of masonry as well. Seek him out.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_688.png" alt="" /> <a
                                href="/item/17107" data-url="17107" class="tooltip-link link">Ayyad's Runed Urn</a> 

 

**This NPC *should* return incorrect items given.**
