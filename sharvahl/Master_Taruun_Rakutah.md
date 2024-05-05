# Master Taruun Rakutah



[Master Taruun Rakutah](/npc/155166) is a level 61 Vah Shir GM Rogue that spawns in [The City of Shar Vahl](/zone/155).



## Dialog

local qglobals = eq.get_qglobals(e.self,e.other);

**You say:** `hail`



>**Master Taruun Rakutah says:** Well met, friend. May I be of assistance?

**You say:** `application`



>**Master Taruun Rakutah says:** Luckily for you someone found it.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_869.png" alt="" /> <a
                                href="/item/2873" data-url="2873" class="tooltip-link link">Application for Citizenship</a>

**You say:** `cloak`



>**Master Taruun Rakutah says:** Someone found a rockhopper chewing on this in the pit. Try not to lose it this time.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_656.png" alt="" /> <a
                                href="/item/2878" data-url="2878" class="tooltip-link link">Initiate's Cloak of Shar Vahl</a>
end



## Turn-Ins



local text = "This item, by itself, means nothing to me.";



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18554" data-url="18554" class="tooltip-link link">A Taruun Guild Summons</a>) then 


>**Master Taruun Rakutah says:** Good Soandso, I am pleased to see you. You have come of age and it is time for you to register for citzenship. Your invitation indicates that the Taruun, hunters and providers of Shar Vahl, have noticed you and consider your potential to be worthy of our training. First, take this application to the Registrar Bindarah and return to me with proof of citzenship.


>**Master Taruun Rakutah says:** I know that you may be nervous right now... after all, this should be very exciting first step for you. If you happen to get lost while looking for the registrar, just ask one of the other citizens or guards for directions. They will most likely know where to find the place or person that you are looking for.


eq.set_global("Shar_Vahl_Cit","1",5,"F");


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_869.png" alt="" /> <a
                                href="/item/2873" data-url="2873" class="tooltip-link link">Application for Citizenship</a> (+20 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_844.png" alt="" /> <a
                                href="/item/29828" data-url="29828" class="tooltip-link link">Shadowscream Steel Boots</a>) then 


>**Master Taruun Rakutah says:** So you're Barkhem's newest student are you? I may not have taken your word for it, but craftsmanship this fine could only be from a student of our Master Smith. Take this and fill it with Shadowscream steel boots. I need 6 pairs to outfit some of my hunters. When you've finished, return the box to me.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1144.png" alt="" /> <a
                                href="/item/17499" data-url="17499" class="tooltip-link link">Boot Case</a> 

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1144.png" alt="" /> <a
                                href="/item/29825" data-url="29825" class="tooltip-link link">Shadowscream Boot Case</a>) then 


>*Master Taruun Rakutah inspects the boots for a moment and looks you square in the eyes. 'This is excellent work, Soandso, you do not disappoint! Would that you could outfit all of my hunters with these boots, but I must not keep your talents all to myself. Take some change for your troubles and this seal back to Barkhem - let him know that I am very impressed with his new protege.'*


Your faction standing with [Guardians of Shar Vahl](/faction/1513) got better (<span class='text-success'>+10</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_861.png" alt="" /> <a
                                href="/item/29826" data-url="29826" class="tooltip-link link">Rakutah's Seal</a> (+500 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_869.png" alt="" /> <a
                                href="/item/2897" data-url="2897" class="tooltip-link link">Notarized Application</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1036.png" alt="" /> <a
                                href="/item/2877" data-url="2877" class="tooltip-link link">Acrylia Slate of Shar Vahl</a>) then 


>**Master Taruun Rakutah says:** Allow me to be the first to welcome you. Accept this cloak, young initiate. It is a symbol of your loyalty to our noble people. May it serve you as you serve us all. Present your acrylia slate to Harbin Gernawl and he will give you instruction. May the spirits of the beasts guide you and keep you safe.


eq.set_global("Shar_Vahl_Cit","7",5,"F");


 &#127873; **You receive:** GiveAll( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1036.png" alt="" /> <a
                                href="/item/2877" data-url="2877" class="tooltip-link link">Acrylia Slate of Shar Vahl</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_656.png" alt="" /> <a
                                href="/item/2878" data-url="2878" class="tooltip-link link">Initiate's Cloak of Shar Vahl</a>) (+450 exp)

 

**This NPC *should* return incorrect items given.**





