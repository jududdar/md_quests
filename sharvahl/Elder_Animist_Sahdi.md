# Elder Animist Sahdi



[Elder Animist Sahdi](/npc/155165) is a level 61 Vah Shir GM Beastlord that spawns in [The City of Shar Vahl](/zone/155).



## Dialog

local qglobals = eq.get_qglobals(e.self,e.other);

**You say:** `hail`



>**Elder Animist Sahdi says:** Greetings Soandso. Are you one of our new recruits?

**You say:** `yes`



>**Elder Animist Sahdi says:** In that case, it's very nice to meet you! When you aren't working on your requirements for citizenship, you may want to make your way out to the pit to practice some basic combat skills.  There is a training camp for new recruits, just outside of the western city wall.  It's just on the other side of the royal palace.  If you walk along the ledge, you won't be able to miss it.

**You say:** `no`



>**Elder Animist Sahdi says:** Well, then how may I help you?

**You say:** `application`



>**Elder Animist Sahdi says:** Luckily for you someone found it.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_869.png" alt="" /> <a
                                href="/item/2873" data-url="2873" class="tooltip-link link">Application for Citizenship</a>

**You say:** `cloak`



>**Elder Animist Sahdi says:** Someone found a rockhopper chewing on this in the pit. Try not to lose it this time.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_656.png" alt="" /> <a
                                href="/item/2878" data-url="2878" class="tooltip-link link">Initiate's Cloak of Shar Vahl</a>
end



## Turn-Ins



local text = "This item, by itself, means nothing to me.";



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18849" data-url="18849" class="tooltip-link link">A Khati Sha Guild Summons</a>) then 


>**Elder Animist Sahdi says:** Soandso, welcome to the Animist's guild. You have grown strong in the safety of our city and it is now time for you to register for official citizenship of Shar Vahl. The Khati Sha, explorers of this hostile land, have granted your request of inclusion and deem you to be worthy of our training. Take this application to Registrar Bindarah and return to me with proof of your citizenship.


>**Elder Animist Sahdi says:** I know that you may be nervous right now... after all, this should be a very exciting first step for you.  If you happen to get lost while looking for the registrar, just ask one of the other citizens or guards for directions.  They will most likely know where to find the place or person that you are looking for.


eq.set_global("Shar_Vahl_Cit","1",5,"F");


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_869.png" alt="" /> <a
                                href="/item/2873" data-url="2873" class="tooltip-link link">Application for Citizenship</a> (+20 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_869.png" alt="" /> <a
                                href="/item/2897" data-url="2897" class="tooltip-link link">Notarized Application</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1036.png" alt="" /> <a
                                href="/item/2877" data-url="2877" class="tooltip-link link">Acrylia Slate of Shar Vahl</a>) then


>**Elder Animist Sahdi says:** Allow me to be the first to welcome you to the Khati Sha, lords of the beasts. Accept this cloak, young initiate. It is a symbol of your loyalty to our noble people. May it serve you as you serve us all. Present your acrylia slate to Animist Poren and he will give you instruction. May the spirits of the beasts guide you and keep you safe.


eq.set_global("Shar_Vahl_Cit","7",5,"F");


 &#127873; **You receive:** GiveAll( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1036.png" alt="" /> <a
                                href="/item/2877" data-url="2877" class="tooltip-link link">Acrylia Slate of Shar Vahl</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_656.png" alt="" /> <a
                                href="/item/2878" data-url="2878" class="tooltip-link link">Initiate's Cloak of Shar Vahl</a>) (+450 exp)

 

**This NPC *should* return incorrect items given.**
