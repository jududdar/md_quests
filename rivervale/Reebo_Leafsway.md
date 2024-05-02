# Reebo Leafsway
## Dialog

**You say:** `hail`



>**Reebo Leafsway says:** Greetings and salutations, Soandso! My name is Reebo Leafsway, loyal Druid of [Karana]. I am in charge of helping young druids who wish to get started down the [trail to Karana's wisdom]. I also do my share of tending the [crops].

**You say:** `shakey`



>**Reebo Leafsway says:** Shakey is our protector and friend.  He is just getting old.  Losing his [stuffing].  His [head] is getting very dry and cracked.

**You say:** `stuffing`



if **Faction** >= Indifferent then



>**Reebo Leafsway says:** The hay he requires is difficult to obtain. It must have been harvested from the Plains of Karana, then cursed by a high priest of the Faceless, [Cazic-Thule]. Finally, you must cast the hay and a flask of blessed Oil of Life into an armorer's forge. Only then will the hay be ready. We Stormreapers will reward you greatly if you could accomplish this task. Remember, you must give the scarecrow stuffing to Shakey only after it has been properly prepared.


else



**Reebo Leafsway says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

>Oh look, a talking lump of refuse.  How novel!



**You say:** `cazic`



if **Faction** >= Indifferent then



>**Reebo Leafsway says:** Cazic-Thule is the dark deity of fear. He is worshiped by many evil beings. There is believed to be a ruined temple dedicated to him deep in the [Feerrott]. That would be a good place to look for one of his high priests.


else



**Reebo Leafsway says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

>Oh look, a talking lump of refuse.  How novel!



**You say:** `feerrott`



>**Reebo Leafsway says:** The Feerrott is a vast rain forest in southwestern Antonica. It is home to many lizardman tribes.

**You say:** `trail.* wisdom`




if **Faction** >= Indifferent then



>**Reebo Leafsway says:** Good. First you should learn that Karana's work is just that.. work. Karana provides us with the tools but it is by the sweat of our brows that we prosper. Common sense and hard work are two things that are highly prized by our people. Time for you to sweat, young one. Take this crate of carrots over to Blinza Toepopal in the Fool's Gold. They need our finest carrots for Mayor Gubbin's stew. When you return I will teach you a lesson of the Rainkeeper.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_723.png" alt="" /> <a
                                href="/item/13971" data-url="13971" class="tooltip-link link">Crate of Rotten Carrots</a>


else



**Reebo Leafsway says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

>Oh look, a talking lump of refuse.  How novel!



**You say:** `karana`



>**Reebo Leafsway says:** Karana is known as the Rainkeeper. It is through His will that our [crops] and our children grow big and healthy. He watches over us and protects us. calling down the fury of a tempest on those who wish harm upon His followers.

**You say:** `crops`



>**Reebo Leafsway says:** The crops we grow here are mostly carrots, lettuce and squash. We also are the only place on all of Norrath where the soil can support the mystical Jumjum Stalk.

**You say:** `head`



>**Reebo Leafsway says:** The head of a scarecrow is difficult to replace. We do not know what is needed and all of our attempts have failed. Perhaps you could [research] this for us and bring back a new head for our old friend Shakey?

**You say:** `research`



>**Reebo Leafsway says:** We have heard of a great forbidden tome penned by an evil necromancer that holds the secrets of instilling life into scarecrows. We have recovered pages from that book. That is how we know about Shakey's hay. But the pages detailing the creation of a scarecrow's head are missing. We believe that the Erudites possess at least some of the pages and might know where the rest of them may be found. Start your search in their city of Erudin.

**You say:** `nillipuss`



>**Reebo Leafsway says:** Nillipuss?  Oh that dirty brownie keeps stealing our jumjum for his own greedy uses.  We certainly would not mind if someone taught him a painful [lesson].

**You say:** `lesson`



if **Faction** >= Indifferent then



>**Reebo Leafsway says:** He needs to be taught not to steal our jumjum!  If you find some jumjum on him, I would appreciate it if you would return it to me.


else



**Reebo Leafsway says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

>Oh look, a talking lump of refuse.  How novel!


end

## Turn-Ins



local text = "Oh good! I see you have taught that nasty Nillipuss a thing or two! Good. But it seems to me that he has stolen more jumjum than this. Perhaps he needs another lesson?";


if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_723.png" alt="" /> <a
                                href="/item/13971" data-url="13971" class="tooltip-link link">Crate of Rotten Carrots</a>) then


>**Reebo Leafsway says:** Very good. Very good indeed. Karana does not need the blind obedience that so many deities require. Trust your instincts, they are more often right than not. Here, take this to Blinza. Hurry, she is expecting them. You may keep the donation she gives you in return.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_723.png" alt="" /> <a
                                href="/item/13957" data-url="13957" class="tooltip-link link">Crate of Fine Carrots</a> (+5 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_723.png" alt="" /> <a
                                href="/item/13972" data-url="13972" class="tooltip-link link">Crate of Rotten Carrots</a>) then


>**Reebo Leafsway says:** These carrots are rotten. They were rotten when I gave them to you. Why would you waste time and energy on such a fool's errand? Because I asked you to? Many, even those you trust will ask you to do things which you should not. Use the common sense that Karana has blessed you with to know which tasks can benefit our people and which could harm them. Learn this lesson well. You will need it if you plan to adventure beyond the vale. Now take these fresh carrots to Blinza and apologize for your error. You may keep the donation she gives you as payment.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_723.png" alt="" /> <a
                                href="/item/13958" data-url="13958" class="tooltip-link link">Crate of Carrots</a> 

 

elseif **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1085.png" alt="" /> <a
                                href="/item/13974" data-url="13974" class="tooltip-link link">Jumjum Stalk</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1085.png" alt="" /> <a
                                href="/item/13974" data-url="13974" class="tooltip-link link">Jumjum Stalk</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1085.png" alt="" /> <a
                                href="/item/13974" data-url="13974" class="tooltip-link link">Jumjum Stalk</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1085.png" alt="" /> <a
                                href="/item/13974" data-url="13974" class="tooltip-link link">Jumjum Stalk</a>) then


>**Reebo Leafsway says:** Excellent!!  You must have taught ol' Nillipuss a great deal!  But he never seems to learn..  Oh well.  The Stormreapers and all of Rivervale owe you a debt of gratitude.  Please accept this token of our appreciation.


Your faction standing with [Storm Reapers](/faction/355) got better (<span class='text-success'>+10</span>)


Your faction standing with [Mayor Gubbin](/faction/286) got better (<span class='text-success'>+1</span>)


Your faction standing with [Merchants of Rivervale](/faction/292) got better (<span class='text-success'>+1</span>)


Your faction standing with [Unkempt Druids](/faction/324) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_566.png" alt="" /> <a
                                href="/item/10308" data-url="10308" class="tooltip-link link">Anti-Poison Amulet</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_598.png" alt="" /> <a
                                href="/item/8303" data-url="8303" class="tooltip-link link">Arrow of Contagion</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_598.png" alt="" /> <a
                                href="/item/8304" data-url="8304" class="tooltip-link link">Arrow of Frost</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1050.png" alt="" /> <a
                                href="/item/10302" data-url="10302" class="tooltip-link link">Earring of Disease Reflection</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1048.png" alt="" /> <a
                                href="/item/10303" data-url="10303" class="tooltip-link link">Earring of Fire Reflection</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1042.png" alt="" /> <a
                                href="/item/10304" data-url="10304" class="tooltip-link link">Earring of Frost Reflection</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_618.png" alt="" /> <a
                                href="/item/10305" data-url="10305" class="tooltip-link link">Earring of Magic Reflection</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_522.png" alt="" /> <a
                                href="/item/10306" data-url="10306" class="tooltip-link link">Earring of Poison Reflection</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_507.png" alt="" /> <a
                                href="/item/10309" data-url="10309" class="tooltip-link link">Eye of Disvan</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_884.png" alt="" /> <a
                                href="/item/17302" data-url="17302" class="tooltip-link link">Pierces Pouch of Storing</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_547.png" alt="" /> <a
                                href="/item/12001" data-url="12001" class="tooltip-link link">Rod of Identification</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_765.png" alt="" /> <a
                                href="/item/10301" data-url="10301" class="tooltip-link link">Runners Ring</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_884.png" alt="" /> <a
                                href="/item/17301" data-url="17301" class="tooltip-link link">Travelers Pack</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_884.png" alt="" /> <a
                                href="/item/17300" data-url="17300" class="tooltip-link link">Travelers Pouch</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_810.png" alt="" /> <a
                                href="/item/12002" data-url="12002" class="tooltip-link link">Wand of Frost Bolts</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_750.png" alt="" /> <a
                                href="/item/12000" data-url="12000" class="tooltip-link link">Compass</a>) (+27440 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0-10 <img src='/static/icons/item_645.png' width='14' height='14'/> 0-15 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**

## Arrive at Waypoint Script

if(e.wp == 12 or e.wp == 33 or e.wp == 51 or e.wp == 73 or e.wp == 96 or e.wp == 120) then


>*Reebo Leafsway whistles a happy hafling tune.*
end

## Signals

if ( e.signal == 0 ) then


>*Reebo Leafsway shakes his head sadly. 'Poor old [Shakey] just isn't what he used to be.'*

elseif ( e.signal == 1 ) then


local nillipuss = eq.get_entity_list():GetMobByNpcTypeID(19015); 


if ( e.self:CalculateDistance(nillipuss:GetX(), nillipuss:GetY(), nillipuss:GetZ()) < 150 ) then



>**Reebo Leafsway says:** Blast you, [Nillipuss]!  Leave our jumjum alone!

end

