# an undead foreman



[an undead foreman](/npc/93082) is a level 50 Undead Iksar Warrior that spawns in [The Overthere](/zone/93).



## Dialog

**You say:** `hail`



>*an undead foreman turns to face you. You can see a faint green glow emanating from his vacant eye sockets. 'Are you a [new worker]? Huh? Speak or go!!'*

**You say:** `new worker`



if( **Faction is** >= Amiable) then



>**an undead foreman says:** Hmmph!! Too much flesh!! If you want to work, you must first fill my eye sockets with my favorite gem. This shall be your payment for your sledgehammer.


else



>**an undead foreman says:** I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

end



## Turn-Ins





if( **Faction is** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_952.png" alt="" /> <a
                                href="/item/10023" data-url="10023" class="tooltip-link link">Jade</a>) then 


>*an undead foreman an undead foreman places the gem deep within his hollow eye socket. He pulls a giant sledgehammer from thin air and hands it to you.*


>**an undead foreman says:** Here!! You shall be assigned to the lower decks of the Scaled Trident.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_567.png" alt="" /> <a
                                href="/item/12863" data-url="12863" class="tooltip-link link">Worker Sledgemallet</a> 

 

local returned = item_lib.return_items(e.self, e.other, e.trade, false)

if ( returned ) then


>**an undead foreman says:** I do not know you well enough to entrust such an item to you, yet.
end
