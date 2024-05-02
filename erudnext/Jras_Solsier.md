# Jras Solsier
## Dialog

**You say:** `hail`



>**Jras Solsier says:** Welcome to the Temple of Divine Light.  We are the Peacekeepers. followers of Quellious.  If you are a paladin of this temple. you can assist us by showing a desire to [protect the peace].

**You say:** `protect the peace`



if **Faction** >= Amiable then 



**You say:** `protect the peace`





>**Jras Solsier says:** It was a fine decision. We are in need of your services.  It seems there is a disturbance in Toxxulia Forest.  There are poachers from other nations who have sought to cause turbulence among the creatures there.  Will you help us [catch the poachers] or are you skeptical about this mission?



**You say:** `catch the poachers`







>**Jras Solsier says:** The infidels are in Toxxulia Forest. They have begun hunting the kobolds. We have no love of the kobolds. but cannot allow the lands of Odus to be overrun by outsiders. The ways of tranquility are balanced with harmony. We will not allow chaos to take hold of our land.  Go and find these poachers. Bring me their heads!!




elseif **Faction** >= Indifferent then




>**Jras Solsier says:** You have not done much to upset the Peacekeepers of this temple, but we must ask you to prove yourself to us before we may discuss things such as this.


else




>**Jras Solsier says:** Leave my sight at once! You are no friend to the Peacekeepers of the Temple of Divine Light.


end

## Turn-Ins




if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_982.png" alt="" /> <a
                                href="/item/13825" data-url="13825" class="tooltip-link link">Poacher's Head</a>) then 


>**Jras Solsier says:** You have served us well. The harmony of the forest shall be preserved. I have word that theses infidels were all working for one man. Find me evidence pertaining to this man. Surely one of these poachers has something which could aid in finding this man. We must stop him to stop the poachers. Go in peace.





Your faction standing with [Peace Keepers](/faction/298) got better (<span class='text-success'>+5</span>)


Your faction standing with [High Council of Erudin](/faction/266) got better (<span class='text-success'>+1</span>)


Your faction standing with [Heretics](/faction/265) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_748.png" alt="" /> <a
                                href="/item/10004" data-url="10004" class="tooltip-link link">Copper Band</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_684.png" alt="" /> <a
                                href="/item/13003" data-url="13003" class="tooltip-link link">Small Lantern</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_944.png" alt="" /> <a
                                href="/item/10015" data-url="10015" class="tooltip-link link">Malachite</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_776.png" alt="" /> <a
                                href="/item/7009" data-url="7009" class="tooltip-link link">Rusty Spear</a>) (+3000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-5 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_980.png" alt="" /> <a
                                href="/item/13913" data-url="13913" class="tooltip-link link">Barbarian Head</a>) then 


>**Jras Solsier says:** It is done! Quellious will look favorably upon our church and we will look favorably upon you. Go in peace.





Your faction standing with [Peace Keepers](/faction/298) got better (<span class='text-success'>+10</span>)


Your faction standing with [High Council of Erudin](/faction/266) got better (<span class='text-success'>+2</span>)


Your faction standing with [Heretics](/faction/265) got worse (<span class='text-danger'>-2</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15202" data-url="15202" class="tooltip-link link">Spell: Courage</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15011" data-url="15011" class="tooltip-link link">Spell: Holy Armor</a>) (+5000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-5 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**
;

