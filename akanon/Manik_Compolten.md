# Manik Compolten
## Dialog

**You say:** `hail`



>**Manik Compolten says:** Greetings, young one. I am Manik Compolten, High Watchman. Are you a [new warrior] or an [experienced fighter]?

**You say:** `new warrior`



if **Faction** >= Amiable then



>**Manik Compolten says:** It is always good to see new blood amongst the Gemchoppers. I have a small task for you. Take this keycard. I will give you only one at a time. Use each to obtain blackboxes for the C series clockworks. I am sure you are familiar with the clockworks. When you are done, bring them all to me. Let me know if you need another keycard.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_648.png" alt="" /> <a
                                href="/item/13844" data-url="13844" class="tooltip-link link">Shiny Card</a>


elseif( **Faction is** == Indifferent) then



>**Manik Compolten says:** You must show a greater allegiance to the Gemchoppers before we can speak with you. Search the hills for rogue clockworks. Captain Compolten shall accept two of their blackboxes and you shall prove your loyalty to our hall.


else



>**Manik Compolten says:** You are lucky I do not cut you in half right where you stand. Your actions so far have proven you an enemy to the Gemchoppers. Leave while you still can!


**You say:** `another keycard`



if **Faction** >= Amiable then



>**Manik Compolten says:** Here. Remember, I will give you only one keycard at a time. These keycards only work for the C series clockworks.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_648.png" alt="" /> <a
                                href="/item/13844" data-url="13844" class="tooltip-link link">Shiny Card</a>


elseif( **Faction is** == Indifferent) then



>**Manik Compolten says:** You must show a greater allegiance to the Gemchoppers before we can speak with you. Search the hills for rogue clockworks. Captain Compolten shall accept two of their blackboxes and you shall prove your loyalty to our hall.


else



>**Manik Compolten says:** You are lucky I do not cut you in half right where you stand. Your actions so far have proven you an enemy to the Gemchoppers. Leave while you still can!


**You say:** `experienced fighter`



if **Faction** >= Amiable then



>**Manik Compolten says:** Good. I require your talents to destroy rogue clockworks. After we sent the clockworks to destroy the Asylum of the Mad we found some of the clockworks went haywire and never returned. We must destroy them, not for the safety of the people, but to keep our technology from falling into the hands of any other nation. Go to the Steamfont Mountains and return their rogue blackboxes to me.


elseif( **Faction is** == Indifferent) then



>**Manik Compolten says:** You must show a greater allegiance to the Gemchoppers before we can speak with you. Search the hills for rogue clockworks. Captain Compolten shall accept two of their blackboxes and you shall prove your loyalty to our hall.


else



>**Manik Compolten says:** You are lucky I do not cut you in half right where you stand. Your actions so far have proven you an enemy to the Gemchoppers. Leave while you still can!


**You say:** `clockwork`



>**Manik Compolten says:** The clockworks were developed by the Eldritch Collective. They are used as our policing force in Ak'Anon. They come in many series. The letter following their number is the series model.

**You say:** `blackbox`



>**Manik Compolten says:** All the clockworks contain blackboxes. These are not containers for items, but rather containers of data of all the clockwork's experiencees. The data can only be extracted by using a blackbox definer.

**You say:** `red 5`



>**Manik Compolten says:** Red 5 is the infernal clockwork once owned by the mad gnome, Meldrath. I hear he has survived the scrap heap and is active once more. I offer a reward to all gnome warriors for the return of Red 5's Blackbox. Perhaps even the reward of a [Bull Smasher].

**You say:** `bull smasher`



>**Manik Compolten says:** The war hammer, Bull Smasher was crafted by our great blacksmiths and tinkers. It is not magical, but it is weighted to perform for only the short of stature. Certainly an item like Bull Smasher could only be crafted by gnomes.

**You say:** `meldrath`



>**Manik Compolten says:** Meldrath is the mad gnome.  He used to be a member of the Eldritch Collective.  Some say he lost his mind while he was working on a formula he obtained from other worlds.  He used to lead the cult called the [Asylum of the Mad].

**You say:** `asylum`



>**Manik Compolten says:** The Asylum of the Mad was formed by the mad gnome, Meldrath. Under his direction, they were trying to build some giant mechanical titan.  We recently sent all of our clockworks into the Steamfont Mountains to destroy their evil cult.
end

## Turn-Ins



local text = "Only two blackboxes shall prove your worth to this hall.";

local text1 = "There are a total of four C series clockworks.";



if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1144.png" alt="" /> <a
                                href="/item/13208" data-url="13208" class="tooltip-link link">Rusted Blackbox</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1144.png" alt="" /> <a
                                href="/item/13208" data-url="13208" class="tooltip-link link">Rusted Blackbox</a>) then


>**Manik Compolten says:** Excellent work! You were born to be a warrior. Here is a little bonus for the good job.





Your faction standing with [Gem Choppers](/faction/255) got better (<span class='text-success'>+5</span>)



Your faction standing with [King Ak`Anon](/faction/333) got better (<span class='text-success'>+1</span>)



Your faction standing with [Merchants of Ak`Anon](/faction/288) got better (<span class='text-success'>+1</span>)



Your faction standing with [Clan Grikbar](/faction/1604) got worse (<span class='text-danger'>-1</span>)



Your faction standing with [Dark Reflection](/faction/238) got worse (<span class='text-danger'>-1</span>)



**Experience:** Awards 15% experience at level 1.


 &#127873; **You receive:** None 

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0-5 <img src='/static/icons/item_645.png' width='14' height='14'/> 0-10 <img src='/static/icons/item_646.png' width='14' height='14'/> 0-10 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1144.png" alt="" /> <a
                                href="/item/13212" data-url="13212" class="tooltip-link link">Blackbox XIIC</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1144.png" alt="" /> <a
                                href="/item/13211" data-url="13211" class="tooltip-link link">Blackbox XXVIC</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1144.png" alt="" /> <a
                                href="/item/13213" data-url="13213" class="tooltip-link link">Blackbox XVIIC</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1144.png" alt="" /> <a
                                href="/item/13214" data-url="13214" class="tooltip-link link">Blackbox XXVIIC</a>) then


>**Manik Compolten says:** Ah!! I see you had no problem finding all of the C series clockworks. Good work. Here. Take this blackbox. We received it from Clockwork 27C. Take it to Jogl Doobraugh. He is the operator of the only blackbox definer in Ak'Anon. He is out at the windmills checking on their operation.





Your faction standing with [Gem Choppers](/faction/255) got better (<span class='text-success'>+1</span>)



Your faction standing with [King Ak`Anon](/faction/333) got better (<span class='text-success'>+1</span>)



Your faction standing with [Merchants of Ak`Anon](/faction/288) got better (<span class='text-success'>+1</span>)



Your faction standing with [Clan Grikbar](/faction/1604) got worse (<span class='text-danger'>-1</span>)



Your faction standing with [Dark Reflection](/faction/238) got worse (<span class='text-danger'>-1</span>)



**Experience:** Awards 12% experience at level 1.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1144.png" alt="" /> <a
                                href="/item/13209" data-url="13209" class="tooltip-link link">Blackbox XXVIIC</a> 

 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1144.png" alt="" /> <a
                                href="/item/13215" data-url="13215" class="tooltip-link link">Rusted Blackbox</a>) then


>**Manik Compolten says:** This is fabulous news!! You have done well, young one. Once you are ready for [further instruction] please let me know, I will guide you through your early most dangerous days. When you have become more experienced in our art, I wil be able to further instruct you on how to progress through your early ranks, as well as in some various [trades] you will have available to you.





Your faction standing with [Gem Choppers](/faction/255) got better (<span class='text-success'>+10</span>)



Your faction standing with [King Ak`Anon](/faction/333) got better (<span class='text-success'>+2</span>)



Your faction standing with [Merchants of Ak`Anon](/faction/288) got better (<span class='text-success'>+2</span>)



Your faction standing with [Clan Grikbar](/faction/1604) got worse (<span class='text-danger'>-2</span>)



Your faction standing with [Dark Reflection](/faction/238) got worse (<span class='text-danger'>-1</span>)



**Experience:** Awards 14% experience at level 1.


if(math.random(100) < 20) then



 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_567.png" alt="" /> <a
                                href="/item/13219" data-url="13219" class="tooltip-link link">Bull Smasher</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_507.png" alt="" /> <a
                                href="/item/13220" data-url="13220" class="tooltip-link link">Iony's Absorber</a>) 

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0-5 <img src='/static/icons/item_645.png' width='14' height='14'/> 0-10 <img src='/static/icons/item_646.png' width='14' height='14'/> 0-10 <img src='/static/icons/item_647.png' width='14' height='14'/> 


else



 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_639.png" alt="" /> <a
                                href="/item/1013" data-url="1013" class="tooltip-link link">Small Cloth Cap</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_656.png" alt="" /> <a
                                href="/item/1018" data-url="1018" class="tooltip-link link">Small Cloth Cape</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_500.png" alt="" /> <a
                                href="/item/1015" data-url="1015" class="tooltip-link link">Small Cloth Choker</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_572.png" alt="" /> <a
                                href="/item/1019" data-url="1019" class="tooltip-link link">Small Cloth Cord</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_517.png" alt="" /> <a
                                href="/item/1022" data-url="1022" class="tooltip-link link">Small Cloth Gloves</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_631.png" alt="" /> <a
                                href="/item/1023" data-url="1023" class="tooltip-link link">Small Cloth Pants</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_666.png" alt="" /> <a
                                href="/item/1024" data-url="1024" class="tooltip-link link">Small Cloth Sandals</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_665.png" alt="" /> <a
                                href="/item/1017" data-url="1017" class="tooltip-link link">Small Cloth Shawl</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_678.png" alt="" /> <a
                                href="/item/1016" data-url="1016" class="tooltip-link link">Small Cloth Shirt</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_670.png" alt="" /> <a
                                href="/item/1020" data-url="1020" class="tooltip-link link">Small Cloth Sleeves</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_677.png" alt="" /> <a
                                href="/item/1014" data-url="1014" class="tooltip-link link">Small Cloth Veil</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_638.png" alt="" /> <a
                                href="/item/1021" data-url="1021" class="tooltip-link link">Small Cloth Wristband</a>) 

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0-5 <img src='/static/icons/item_645.png' width='14' height='14'/> 0-10 <img src='/static/icons/item_646.png' width='14' height='14'/> 0-10 <img src='/static/icons/item_647.png' width='14' height='14'/> 




**This NPC *should* return incorrect items given.**
