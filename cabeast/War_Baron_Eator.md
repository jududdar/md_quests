# War Baron Eator



[War Baron Eator](/npc/106080) is a level 61 Iksar GM Warrior that spawns in [Cabilis East](/zone/106).



## Dialog

**You say:** `Hail`



>*War Baron Eator turns to you and snorts in anger. Some mucus lands on your cheek. 'Troopers! I thought I ordered you to keep all new recruits away from this chamber! Go, child. The War Baron of Cabilis has no time for games. See this intruder out!!'*

**You say:** `memory`



if **Faction** >= Amiable then



>*War Baron Eator takes a step back and thinks to himself. Phlegm dribbles off his lips. 'The Memory of Sebilis. Kept within my personal chambers. They have been taken. Taken by some croakin' Forsaken no doubt!! You have been sent to me because you show excellent prowess. Find my Memory and bring it to me with your footman's pike.'*


elseif **Faction** >= Indifferent then



>**War Baron Eator says:** No Iksar resident will have anything to do with you!


else



>**War Baron Eator says:** Hiss!  Fool!  Fear the Legion of Cabilis for you are no ally to us.  Leave while you can.


**You say:** `trooper`



if **Faction** >= Amiable then



>**War Baron Eator says:** So you are a trooper? Word of your deeds has been spreading through the legion. If you truly wield the pike of a trooper, then go and serve the garrisons of swamp, lake and woods. Report to the Warlord and tell him you are a [trooper reporting for duty]. Their recommendations and your trooper pike shall earn you the rank of legionnaire.


elseif **Faction** >= Indifferent then



>**War Baron Eator says:** No Iksar resident will have anything to do with you!


else



>**War Baron Eator says:** Hiss!  Fool!  Fear the Legion of Cabilis for you are no ally to us.  Leave while you can.

end



## Turn-Ins



local text1 = "I await three letters of recommendation and your trooper pike.";


local text2 = "shines a bright smile which quickly fades to a frown. 'The memory is not complete. ..sniff, sniff.. A reward for my memory and your footman's pike.";




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_789.png" alt="" /> <a
                                href="/item/18464" data-url="18464" class="tooltip-link link">Dark Grey Tome</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1221.png" alt="" /> <a
                                href="/item/22919" data-url="22919" class="tooltip-link link">Sarnak Hide</a>) then


>*War Baron Eator smiles at your dedication to Cazic Thule and hands you a small gem.*


Your faction standing with [Swift Tails](/faction/444) got better (<span class='text-success'>+2</span>)


Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/7881" data-url="7881" class="tooltip-link link">Mark of Clarity</a> (+20000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_789.png" alt="" /> <a
                                href="/item/18463" data-url="18463" class="tooltip-link link">Light Black Tome</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1233.png" alt="" /> <a
                                href="/item/22918" data-url="22918" class="tooltip-link link">Chokadai Scale</a>) then


>*War Baron Eator smiles at your dedication to Cazic Thule and hands you a small gem.*


Your faction standing with [Swift Tails](/faction/444) got better (<span class='text-success'>+2</span>)


Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/7881" data-url="7881" class="tooltip-link link">Mark of Clarity</a> (+20000 exp)

 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_957.png" alt="" /> <a
                                href="/item/12899" data-url="12899" class="tooltip-link link">An Emerald</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_954.png" alt="" /> <a
                                href="/item/12898" data-url="12898" class="tooltip-link link">A Sapphire</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_960.png" alt="" /> <a
                                href="/item/12896" data-url="12896" class="tooltip-link link">A Ruby</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_736.png" alt="" /> <a
                                href="/item/5132" data-url="5132" class="tooltip-link link">Footman's Pike</a>) then


>*War Baron Eator gulps down a wad of phlegm. 'My memory has returned! Soandso! You are no footman. I grant you the rank of soldier. Go and forge your weapon. Do not return to me until you become a [brave trooper of the empire].'*


Your faction standing with [Cabilis Residents](/faction/440) got better (<span class='text-success'>+20</span>)


Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+5</span>)


Your faction standing with [Scaled Mystics](/faction/445) got better (<span class='text-success'>+5</span>)


Your faction standing with [Swift Tails](/faction/444) got better (<span class='text-success'>+5</span>)


Your faction standing with [Crusaders of Greenmist](/faction/442) got better (<span class='text-success'>+5</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_864.png" alt="" /> <a
                                href="/item/12476" data-url="12476" class="tooltip-link link">Soldier Head Plans</a> (+800 exp)

 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18073" data-url="18073" class="tooltip-link link">Legionnaire Recommendation</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18072" data-url="18072" class="tooltip-link link">Legionnaire Recommendation</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18074" data-url="18074" class="tooltip-link link">Legionnaire Recommendation</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_736.png" alt="" /> <a
                                href="/item/5134" data-url="5134" class="tooltip-link link">Trooper's Pike</a>) then


>*War Baron Eator takes away your pike and hands you plans not for a pike head, but for the crown of another polearm. 'It is time to wield the weapon of a [true warrior of the legion]. You have done well, Legionnaire Soandso!'*


Your faction standing with [Cabilis Residents](/faction/440) got better (<span class='text-success'>+2</span>)


Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+2</span>)


Your faction standing with [Scaled Mystics](/faction/445) got better (<span class='text-success'>+2</span>)


Your faction standing with [Swift Tails](/faction/444) got better (<span class='text-success'>+2</span>)


Your faction standing with [Crusaders of Greenmist](/faction/442) got better (<span class='text-success'>+2</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_864.png" alt="" /> <a
                                href="/item/12478" data-url="12478" class="tooltip-link link">Legionnaire Crown Plans</a> (+4000 exp)

 

**This NPC *should* return incorrect items given.**





