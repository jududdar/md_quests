# Elder Spiritist Grawleh


## Dialog

local qglobals = eq.get_qglobals(e.self,e.other);

**You say:** `application`



>**Elder Spiritist Grawleh says:** Luckily for you someone found it.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_869.png" alt="" /> <a
                                href="/item/2873" data-url="2873" class="tooltip-link link">Application for Citizenship</a>

**You say:** `cloak`



>**Elder Spiritist Grawleh says:** Someone found a grimling wearing this in the pit. Try not to lose it this time.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_656.png" alt="" /> <a
                                href="/item/2878" data-url="2878" class="tooltip-link link">Initiate's Cloak of Shar Vahl</a>

**You say:** `love potion`



>**Elder Spiritist Grawleh says:** Love potion? Sounds intriguing but not familiar, I am afraid I cannot help you. However, if I were looking for information about potions and the alchemical arts, I would see Spiritist Ragnar. He has a shop just outside of the palace.
end



## Signals

if(e.signal == 1) then


>**Elder Spiritist Grawleh says:** I know many of the taverns and eateries have their own barrels, but you may want to try Jakhal and Kahala's Brewery. You can find it in the southwestern section of the Merchant's Quarter, or Corridor of Heroes, as I like to call it..
end



## Turn-Ins



local text = "This item, by itself, means nothing to me.";



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1136.png" alt="" /> <a
                                href="/item/30962" data-url="30962" class="tooltip-link link">A Frosted Bag</a>) then


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15225" data-url="15225" class="tooltip-link link">Spell: Endure Cold</a> 

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18551" data-url="18551" class="tooltip-link link">A Dar Khura Guild Summons</a>) then 


>**Elder Spiritist Grawleh says:** Good Soandso, I am honored to meet you. You have come of age and it is time for you to register for citzenship of Shar Vahl. The Dar Khura, spiritual guides of our people, have sensed your spirit and deem you to be worthy of our training. First things first, take this application to Registrar Bindarah and return to me with proof of citzenship.


>**Elder Spiritist Grawleh says:** I know that you may be nervous right now... after all, this should be very exciting first step for you. If you happen to get lost while looking for the registrar, just ask one of the other citizens or guards for directions. They will most likely know where to find the place or person that you are looking for.


eq.set_global("Shar_Vahl_Cit","1",5,"F");


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_869.png" alt="" /> <a
                                href="/item/2873" data-url="2873" class="tooltip-link link">Application for Citizenship</a> (+20 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_869.png" alt="" /> <a
                                href="/item/2897" data-url="2897" class="tooltip-link link">Notarized Application</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1036.png" alt="" /> <a
                                href="/item/2877" data-url="2877" class="tooltip-link link">Acrylia Slate of Shar Vahl</a>) then 


>**Elder Spiritist Grawleh says:** Welcome back, Soandso! I see that your documents are in order and you are an official citizen of Shar Vahl, which is great news! Let me be the first to welcome you to the ranks of the Dar Khura! Here, take this cloak and wear it with pride.


>**Elder Spiritist Grawleh says:** Present your acrylia slate to spiritist Fehril and he will guide you through your early training. May the strongest of our ancestral spirits be your inspiration.


eq.set_global("Shar_Vahl_Cit","7",5,"F");


 &#127873; **You receive:** GiveAll( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1036.png" alt="" /> <a
                                href="/item/2877" data-url="2877" class="tooltip-link link">Acrylia Slate of Shar Vahl</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_656.png" alt="" /> <a
                                href="/item/2878" data-url="2878" class="tooltip-link link">Initiate's Cloak of Shar Vahl</a>) (+450 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1137.png" alt="" /> <a
                                href="/item/30963" data-url="30963" class="tooltip-link link">Claw of Frost</a>) then


>*Elder Spiritist Grawleh examines the contents of the bag carefully. This is no ordinary spirit Soandso. It is a whisperling, a bringer of dreams. You are quite lucky, I think she will go with you. She will be able to protect you from cold magic. If you need more protection you can call on her to help you endure the cold. This is how the Dar Khura weave their spells, we ask the spirits for their aid. This scroll will show you how to call on her for her protection. You will also need to construct her a more suitable spirit anchor. This claw will not contain her much longer. Please hurry to Ragnar with the claw and a fresh [bloodling carapace]. It may buy us some time before she fades away.*


 &#127873; **You receive:** GiveAll( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15225" data-url="15225" class="tooltip-link link">Spell: Endure Cold</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1137.png" alt="" /> <a
                                href="/item/30964" data-url="30964" class="tooltip-link link">Siver's Claw</a>) (+1000 exp)

 

**This NPC *should* return incorrect items given.**
