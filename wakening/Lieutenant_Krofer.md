# Lieutenant Krofer
## Dialog

**You say:** `hail`




>**Lieutenant Krofer says:** Unless you're the new mercenary reinforcements I suggest you remove yourself from my presence before I decorate the bottom of my boot with your intestines.

elseif( **Faction is** > Indifferent) then


**You say:** `next assignment`




>**Lieutenant Krofer says:** Well, ready or not, this must be done now. Out there in the forest are our enemies. For us to be successful, we must know what they are doing and how they are going about it. Our probing attacks have revealed little so we've decided to send you out to gather any info you can. There must be some sort of messenger out there, bring any info you might find.


**You say:** `prepared`




>**Lieutenant Krofer says:** Very well. We've decided to attack the small Sifaye village northeast of here and I want you to coordinate the attack. I will send you into Kael Drakkel with a request for troop assistance. After the squad is assembled you will lead them to the staging point where you will oversee the battle. Here is the request. Take it to Drioc in the city and return here with the troops.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_868.png" alt="" /> <a
                                href="/item/1706" data-url="1706" class="tooltip-link link">Krofers Requisition</a>


**You say:** `reinforcement`




>**Lieutenant Krofer says:** Oh? Well then show me your assignment, " .. e.other:Race() .. ".


elseif( **Faction is** == Indifferent) then


**You say:** `next assignment`




>**Lieutenant Krofer says:** You need to prove your dedication to our cause before I can discuss such matters with you.


elseif( **Faction is** < Indifferent) then


**Lieutenant Krofer says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.
end

## Turn-Ins



local text = "Where is the rest, manling?";



if( **Faction is** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/1702" data-url="1702" class="tooltip-link link">Mercenary Assignment</a>) then 


>**Lieutenant Krofer says:** Drioc sent you? I suppose one can't expect much from a mercenary. Well then, Soandso, your first assignment will be to clear out some of this forest's annoying populace. Bring me the meat of one of the raptors, the meat of two panthers, and the remains of one of those living puddles of black sludge found in the caves. You will then have your payment.


Your faction standing with [Kromzek](/faction/448) got better (<span class='text-success'>+10</span>)


Your faction standing with [Kromrif](/faction/419) got better (<span class='text-success'>+2</span>)


Your faction standing with [King Tormax](/faction/429) got better (<span class='text-success'>+2</span>)


Your faction standing with [Claws of Veeshan](/faction/430) got worse (<span class='text-danger'>-5</span>)


 &#127873; **You receive:** 0 (+1000 exp)

 

elseif( **Faction is** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_817.png" alt="" /> <a
                                href="/item/22851" data-url="22851" class="tooltip-link link">Panther Meat</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_817.png" alt="" /> <a
                                href="/item/22851" data-url="22851" class="tooltip-link link">Panther Meat</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_817.png" alt="" /> <a
                                href="/item/22852" data-url="22852" class="tooltip-link link">Raptor Meat</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1222.png" alt="" /> <a
                                href="/item/1703" data-url="1703" class="tooltip-link link">Tar goo strands</a>) then 


>**Lieutenant Krofer says:** Well, I suppose you may be worth something more than fodder after all. Here is your payment. Speak to me again when you are ready for your next assignment. For now, get some rest, you will need it.


Your faction standing with [Kromzek](/faction/448) got better (<span class='text-success'>+10</span>)


Your faction standing with [Kromrif](/faction/419) got better (<span class='text-success'>+2</span>)


Your faction standing with [King Tormax](/faction/429) got better (<span class='text-success'>+2</span>)


Your faction standing with [Claws of Veeshan](/faction/430) got worse (<span class='text-danger'>-5</span>)


 &#127873; **You receive:** 0 (+1000 exp)

**You receive coin:** 2 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 7 <img src='/static/icons/item_646.png' width='14' height='14'/> 1 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif( **Faction is** > Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_864.png" alt="" /> <a
                                href="/item/1704" data-url="1704" class="tooltip-link link">Sifaye messengers report</a>) then 


>**Lieutenant Krofer says:** Excellent, Soandso. With this we can plan an attack that might actually accomplish something. Here is your payment. You have also earned this cloak, it should help protect you from the clawing undergrowth of this savage land. Your next mission will be more complex and dangerous, however we may be able to spare a laborer or two to assist you. Rest now, and tell me when you are prepared.


Your faction standing with [Kromzek](/faction/448) got better (<span class='text-success'>+13</span>)


Your faction standing with [Kromrif](/faction/419) got better (<span class='text-success'>+3</span>)


Your faction standing with [King Tormax](/faction/429) got better (<span class='text-success'>+3</span>)


Your faction standing with [Claws of Veeshan](/faction/430) got worse (<span class='text-danger'>-6</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_661.png" alt="" /> <a
                                href="/item/1705" data-url="1705" class="tooltip-link link">Velium Studded Cloak</a> (+1000 exp)

**You receive coin:** 1 <img src='/static/icons/item_644.png' width='14' height='14'/> 4 <img src='/static/icons/item_645.png' width='14' height='14'/> 5 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_868.png" alt="" /> <a
                                href="/item/1707" data-url="1707" class="tooltip-link link">Signed Requisition</a>) then 


>*Lieutenant Krofer takes the note and looks it over, then sighs and says, 'This will have to be enough. The squad should be here shortly. When they arrive you will march with them to the staging area near the village of those insect Sifaye. When you are satisfied with the formation, give the corporal the order to attack and observe the battle. After the village is destroyed return this report to me and we'll plan our next move.'*


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_861.png" alt="" /> <a
                                href="/item/1708" data-url="1708" class="tooltip-link link">Mission Report</a> (+1000 exp)

 


**Spawn NPC:**  [Corporal Hlash](/npc/119022) at (**y:** -699, **x:** -4975)


**Spawn NPC:**  [Berzerker Dolvad](/npc/119025) at (**y:** -697, **x:** -4954)


**Spawn NPC:**  [Berzerker Voldak](/npc/119027) at (**y:** -671, **x:** -4954)


**Spawn NPC:**  [Disciple Atharm](/npc/119028) at (**y:** -672, **x:** -4976)

**This NPC *should* return incorrect items given.**
