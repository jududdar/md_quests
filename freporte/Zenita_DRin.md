# Zenita DRin
## Dialog

**You say:** `hail`



>**Zenita DRin says:** Greetings. I would love to chat with you, but I just realized something.. I do not waste time with whelps.

**You say:** `lens`



>**Zenita DRin says:** So you seek the Spare Lens. Yes. I have it. There are only two ways you can obtain it, [fight] the great Zenita or [play a game of chance].

**You say:** `play a game of chance`



>**Zenita DRin says:** Great. It is rather simple. I have five cards and only one is King Naythox. Find it. In order to get one card all you need to do is buy me a bottle of Innoruuks Kiss of Death from the barkeep in Chops N Hops. One bottle for one card. Return the King Naythox card to me and you shall get the Spare Lens.

**You say:** `fight`



>**Zenita DRin says:** Darn!! I was hoping not to hear that word, fight. Oh well.


**Zenita DRin attacks you.**
end

## Turn-Ins




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_653.png" alt="" /> <a
                                href="/item/22298" data-url="22298" class="tooltip-link link">King Card</a>) then


>**Zenita DRin says:** Why I will be.. You got it!! I thought I took it out of the deck. Very well. You win the Spare Lens fair and square. Here you are. Now get out of my sight.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1129.png" alt="" /> <a
                                href="/item/13279" data-url="13279" class="tooltip-link link">A Telescope Lens</a> (+500 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_827.png" alt="" /> <a
                                href="/item/13121" data-url="13121" class="tooltip-link link">Innoruuk's Kiss of Death</a>) then


>**Zenita DRin says:** Let see what card you pulled.


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_648.png" alt="" /> <a
                                href="/item/22293" data-url="22293" class="tooltip-link link">Castle Card</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_649.png" alt="" /> <a
                                href="/item/22294" data-url="22294" class="tooltip-link link">Beggar Card</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_650.png" alt="" /> <a
                                href="/item/22295" data-url="22295" class="tooltip-link link">Joker Card</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_651.png" alt="" /> <a
                                href="/item/22296" data-url="22296" class="tooltip-link link">Wild Card</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_652.png" alt="" /> <a
                                href="/item/22297" data-url="22297" class="tooltip-link link">Queen Card</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_653.png" alt="" /> <a
                                href="/item/22298" data-url="22298" class="tooltip-link link">King Card</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_654.png" alt="" /> <a
                                href="/item/22299" data-url="22299" class="tooltip-link link">Knight Card</a>) 

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_654.png" alt="" /> <a
                                href="/item/22299" data-url="22299" class="tooltip-link link">Knight Card</a>) then


e.self:Say(string.format("Bad luck must be one of your strong suits. You should have been a beggar because you sure aren't a very good %s. You lose!",e.other:Class()));

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_650.png" alt="" /> <a
                                href="/item/22295" data-url="22295" class="tooltip-link link">Joker Card</a>) then


e.self:Say(string.format("I see you have drawn the card that best represents a %s such as yourself. You lose!",e.other:Race()));

**This NPC *should* return incorrect items given.**


