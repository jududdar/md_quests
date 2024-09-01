# Treasurer Lynn

[Treasurer Lynn](/npc/6077) is a level 30 Human Shopkeeper that spawns in [High Keep](/zone/6).

Their primary faction is [Merchants of Highpass](/faction/331).



## On NPC Spawn

**Set a timer** named *pick_up* for 2 seconds







## Timer(s)

if ( e.timer == "pick_up" ) then

while ( e.self:CheckGround() ) do

>*Treasurer Lynn picks up something from the ground.*











## Dialog

**You say:** `hail`


>**Treasurer Lynn says:** Greetings!!  Welcome to Highkeep. home of the greatest casino in all of Norrath.  Please visit our fine casino on the second floor.

**You say:** `lottery`


>**Treasurer Lynn says:** Interested in the Highkeep lotter, are we?  I am afraid it as been put on hold.  We found last season's winner to be holding a counterfeit ticket.  We now await [last season's winner] to step foward with the winning ticket - ticket number 16568.  His prize is the key to the royal suite.

**You say:** `last season`


>**Treasurer Lynn says:** Last season's winner is not known.  I have heard from my sources that he was some sort of merchant of used goods.









## Turn-Ins





if( **You turn in:**   <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_867.png" alt="" /> <a
                                href="/item/12261" data-url="12261" class="tooltip-link link">Lottery Ticket # 15600</a> ) then

>**Treasurer Lynn says:** You have the runner up ticket from last season!! Here is your reward. Remember, a copper gambled is a plat earned!!

 &#127873; **You receive:** No item given (+500 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-15 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-20 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif( **You turn in:**   <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_867.png" alt="" /> <a
                                href="/item/12266" data-url="12266" class="tooltip-link link">Lottery Ticket # 16568</a> ) then

>**Treasurer Lynn says:** Congratulations!! You are the winner of last season's Highkeep lottery. Here is the key to the royal suite. You should find this room on the third floor.

 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1077.png" alt="" /> <a
                                href="/item/12267" data-url="12267" class="tooltip-link link">Highkeep Royal Suite</a> (+500 exp)

 



**This NPC *should* return incorrect items given.**






