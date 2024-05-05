# Dill Fireshine



[Dill Fireshine](/npc/54109) is a level 61 Wood Elf GM Ranger that spawns in [Greater Faydark](/zone/54).





## Dialog

**You say:** `hail`



>**Dill Fireshine says:** Welcome to the treetops and the home of Faydark's Champions. We are the skilled rangers of the Faydarks. You are safe in Kelethin. but watch yourself upon the forest floor. I hear the [blue meanies] have been on the rise.

**You say:** `blue meanies`



>**Dill Fireshine says:** That is a little name I have given the Crushbone orcs. It appears they have increased their numbers. The Emerald Warriors are charged with our defense against them. We rangers are to seek out the [orc saboteurs].

**You say:** `orc saboteurs`



if **Faction** >= Amiable then



>**Dill Fireshine says:** As others move to battle the orc armies. we have word that the orc pawns have been sent into the woods to damage the great trees which support Kelethin. We shall employ the talents of our young rangers to halt their efforts. I currently seek those who will [hunt the orc pawns].


elseif **Faction** >= Indifferent then



>**Dill Fireshine says:** Faydark's Champions cannot call you foe. but you have yet to earn our trust.


else



>**Dill Fireshine says:** Your ways are considered vile to Faydark's Champions. Leave before my rage overcomes my restraint.


**You say:** `hunt.* orc pawn`



if **Faction** >= Amiable then



>**Dill Fireshine says:** Go to the forest floor and seek out the orc pawns. Within their ranks can sometimes be found orc hatchetmen. They carry orc hatchets which you must return and I shall reward you for every two orc hatchets and perhaps offer you a weapon in return. should we have any to spare at the time.


elseif **Faction** >= Indifferent then



>**Dill Fireshine says:** Faydark's Champions cannot call you foe. but you have yet to earn our trust.


else



>**Dill Fireshine says:** Your ways are considered vile to Faydark's Champions. Leave before my rage overcomes my restraint.


**You say:** `crushbone allies`



if **Faction** >= Amiable then



>**Dill Fireshine says:** It seems the orcs have allied themselves with the wicked Teir'Dal. We know of this through reports of a Teir'Dal presence within Crushbone. We must [intercept the Crushbone runners] and find a reason for their union.


elseif **Faction** >= Indifferent then



>**Dill Fireshine says:** Faydark's Champions cannot call you foe. but you have yet to earn our trust.


else



>**Dill Fireshine says:** Your ways are considered vile to Faydark's Champions. Leave before my rage overcomes my restraint.


**You say:** `intercept.* crushbone runner`



if **Faction** >= Amiable then



>**Dill Fireshine says:** Go to the Butcherblocks. You stand a greater chance of finding the runners there. I shall pay a bounty for all returned runner pouches.


elseif **Faction** >= Indifferent then



>**Dill Fireshine says:** Faydark's Champions cannot call you foe. but you have yet to earn our trust.


else



>**Dill Fireshine says:** Your ways are considered vile to Faydark's Champions. Leave before my rage overcomes my restraint.

end



## Turn-Ins



local text = "I expect to receive TWO orc hatchets.";





if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_569.png" alt="" /> <a
                                href="/item/12108" data-url="12108" class="tooltip-link link">Orc Hatchet</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_569.png" alt="" /> <a
                                href="/item/12108" data-url="12108" class="tooltip-link link">Orc Hatchet</a>) then 


>**Dill Fireshine says:** Fantastic work!! Your actions shall earn you the respect of all Fier'Dal!  Take this as a small bounty for your deed.  We have heard of [Crushbone allies] who wish our demise.


Your faction standing with [Faydarks Champions](/faction/246) got better (<span class='text-success'>+10</span>)


Your faction standing with [King Tearis Thex](/faction/279) got better (<span class='text-success'>+2</span>)


Your faction standing with [Clerics of Tunare](/faction/226) got better (<span class='text-success'>+2</span>)


Your faction standing with [Soldiers of Tunare](/faction/310) got better (<span class='text-success'>+2</span>)


Your faction standing with [Crushbone Orcs](/faction/234) got worse (<span class='text-danger'>-2</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_604.png" alt="" /> <a
                                href="/item/5047" data-url="5047" class="tooltip-link link">Tarnished Scimitar</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_577.png" alt="" /> <a
                                href="/item/5048" data-url="5048" class="tooltip-link link">Tarnished Bastard Sword</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_762.png" alt="" /> <a
                                href="/item/7032" data-url="7032" class="tooltip-link link">Cast-Iron Rapier</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_569.png" alt="" /> <a
                                href="/item/5046" data-url="5046" class="tooltip-link link">Tarnished Battle Axe</a>) (+2500 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_647.png' width='14' height='14'/> 


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_604.png" alt="" /> <a
                                href="/item/5047" data-url="5047" class="tooltip-link link">Tarnished Scimitar</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_577.png" alt="" /> <a
                                href="/item/5048" data-url="5048" class="tooltip-link link">Tarnished Bastard Sword</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_762.png" alt="" /> <a
                                href="/item/7032" data-url="7032" class="tooltip-link link">Cast-Iron Rapier</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_569.png" alt="" /> <a
                                href="/item/5046" data-url="5046" class="tooltip-link link">Tarnished Battle Axe</a>) 

 


if ( math.random() < 0.5 ) then



 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_604.png" alt="" /> <a
                                href="/item/5047" data-url="5047" class="tooltip-link link">Tarnished Scimitar</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_577.png" alt="" /> <a
                                href="/item/5048" data-url="5048" class="tooltip-link link">Tarnished Bastard Sword</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_762.png" alt="" /> <a
                                href="/item/7032" data-url="7032" class="tooltip-link link">Cast-Iron Rapier</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_569.png" alt="" /> <a
                                href="/item/5046" data-url="5046" class="tooltip-link link">Tarnished Battle Axe</a>) 

 


elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/18840" data-url="18840" class="tooltip-link link">A Sealed Letter</a>) then 


>**Dill Fireshine says:** Yes. A recent report has proven this to be true. An evil alliance has been made. We shall soon need many more experienced adventurers such as yourself. For now, take this reward and strengthen your skills.


Your faction standing with [Faydarks Champions](/faction/246) got better (<span class='text-success'>+30</span>)


Your faction standing with [King Tearis Thex](/faction/279) got better (<span class='text-success'>+7</span>)


Your faction standing with [Clerics of Tunare](/faction/226) got better (<span class='text-success'>+7</span>)


Your faction standing with [Soldiers of Tunare](/faction/310) got better (<span class='text-success'>+7</span>)


Your faction standing with [Crushbone Orcs](/faction/234) got worse (<span class='text-danger'>-7</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_597.png" alt="" /> <a
                                href="/item/8003" data-url="8003" class="tooltip-link link">Longbow</a> (+23400 exp)

**You receive coin:** 1 <img src='/static/icons/item_644.png' width='14' height='14'/> 1 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-9 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_690.png" alt="" /> <a
                                href="/item/13226" data-url="13226" class="tooltip-link link">Runner Pouch</a>) then 


>**Dill Fireshine says:** Good work. We shall cut off correspondence between these two. It is for the best. Remember, if you find any notes to Neriak from the ambassador in Crushbone, give them to me.


Your faction standing with [Faydarks Champions](/faction/246) got better (<span class='text-success'>+20</span>)


Your faction standing with [King Tearis Thex](/faction/279) got better (<span class='text-success'>+5</span>)


Your faction standing with [Clerics of Tunare](/faction/226) got better (<span class='text-success'>+5</span>)


Your faction standing with [Soldiers of Tunare](/faction/310) got better (<span class='text-success'>+5</span>)


Your faction standing with [Crushbone Orcs](/faction/234) got worse (<span class='text-danger'>-5</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_640.png" alt="" /> <a
                                href="/item/2001" data-url="2001" class="tooltip-link link">Leather Skullcap</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_771.png" alt="" /> <a
                                href="/item/2002" data-url="2002" class="tooltip-link link">Leather Mask</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_634.png" alt="" /> <a
                                href="/item/2008" data-url="2008" class="tooltip-link link">Leather Sleeves</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_636.png" alt="" /> <a
                                href="/item/2010" data-url="2010" class="tooltip-link link">Leather Gloves</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_632.png" alt="" /> <a
                                href="/item/2140" data-url="2140" class="tooltip-link link">Raw-hide Tunic</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_660.png" alt="" /> <a
                                href="/item/2142" data-url="2142" class="tooltip-link link">Raw-hide Cloak</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_635.png" alt="" /> <a
                                href="/item/2147" data-url="2147" class="tooltip-link link">Raw-hide Leggings</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_633.png" alt="" /> <a
                                href="/item/2148" data-url="2148" class="tooltip-link link">Raw-hide Boots</a>) (+21800 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0-10 <img src='/static/icons/item_645.png' width='14' height='14'/> 0-10 <img src='/static/icons/item_646.png' width='14' height='14'/> 0-10 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**


