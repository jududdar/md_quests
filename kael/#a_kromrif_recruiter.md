# a kromrif recruiter




## Dialog

if( **Faction is** > Apprehensive) then


**You say:** `hail`




>**a kromrif recruiter says:** Greetings, little thing.  You have entered into the great city of Kael Drakkel, home of the Kromzek as well as a few of my kind, the Kromrif.  If you are to walk among my people as a peer you must prove yourself as a friend, not a foe.


**You say:** `prove`




>**a kromrif recruiter says:** Leave this place then and return when you have waged war upon the Coldain.  Remove their heads from their bodies and return them to me.  I will spread the word of your deeds amongst my people if you do so, " .. e.other:Race() .. ".


**You say:** `coldain`




>**a kromrif recruiter says:** The Coldain are the ice dwarves who dwell in the city of Thurgadin.  They are a blight upon the land known as Velious, speaking the word of their god, Brell.


else


>**a kromrif recruiter says:** I will do nothing to help beings like you!
end



## Turn-Ins



local head = 0;



if( **Faction is** > Apprehensive and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_990.png" alt="" /> <a
                                href="/item/30081" data-url="30081" class="tooltip-link link">Coldain Head</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_990.png" alt="" /> <a
                                href="/item/30081" data-url="30081" class="tooltip-link link">Coldain Head</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_990.png" alt="" /> <a
                                href="/item/30081" data-url="30081" class="tooltip-link link">Coldain Head</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_990.png" alt="" /> <a
                                href="/item/30081" data-url="30081" class="tooltip-link link">Coldain Head</a>) then


head = 4;

elseif( **Faction is** > Apprehensive and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_990.png" alt="" /> <a
                                href="/item/30081" data-url="30081" class="tooltip-link link">Coldain Head</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_990.png" alt="" /> <a
                                href="/item/30081" data-url="30081" class="tooltip-link link">Coldain Head</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_990.png" alt="" /> <a
                                href="/item/30081" data-url="30081" class="tooltip-link link">Coldain Head</a>) then


head = 3;

elseif( **Faction is** > Apprehensive and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_990.png" alt="" /> <a
                                href="/item/30081" data-url="30081" class="tooltip-link link">Coldain Head</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_990.png" alt="" /> <a
                                href="/item/30081" data-url="30081" class="tooltip-link link">Coldain Head</a>) then


head = 2;

elseif( **Faction is** > Apprehensive and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_990.png" alt="" /> <a
                                href="/item/30081" data-url="30081" class="tooltip-link link">Coldain Head</a>) then


head = 1;


if(head > 0) then



for i = 1, head do



>**a kromrif recruiter says:** Very good, " .. e.other:Race() .. ".  Slay more of the beasts and your name will be known by all of the Kromrif!



Your faction standing with [Kromrif](/faction/419) got better (<span class='text-success'>+35</span>)



Your faction standing with [Kromzek](/faction/448) got better (<span class='text-success'>+8</span>)



Your faction standing with [Coldain](/faction/406) got worse (<span class='text-danger'>-17</span>)



Your faction standing with [Claws of Veeshan](/faction/430) got worse (<span class='text-danger'>-3</span>)



 &#127873; **You receive:** 0 (+5000 exp)

 


**This NPC *should* return incorrect items given.**

