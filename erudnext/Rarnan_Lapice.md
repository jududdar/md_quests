# Rarnan Lapice



[Rarnan Lapice](/npc/24048) is a level 61 Erudite GM Cleric that spawns in [Erudin](/zone/24).



## Dialog

**You say:** `hail`



>**Rarnan Lapice says:** It is good to meet you. Soandso.  To enter the Temple of Divine Light is to invite Quellious into your body and soul.  Tranquility is our way and. as such. we do all we can to uphold it.  Are you a [cleric of Quellious]. or am I mistaken?

**You say:** `cleric of Quellious`



if **Faction** >= Amiable then



>**Rarnan Lapice says:** I have a small task for you then. Go to the city library and ask the librarian for the book 'The Testament of Vanear'. I shall require it for further studies. Do not return empty-handed or you shall know my rage.


elseif **Faction** >= Indifferent then



>**Rarnan Lapice says:** You have not done much to upset the Peacekeepers of this temple. but we must ask you to prove yourself to us before we may discuss things such as this.


else



>**Rarnan Lapice says:** Leave my sight at once! You are no friend to the Peacekeepers of the Temple of Divine Light.

end



## Turn-Ins




if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_865.png" alt="" /> <a
                                href="/item/13991" data-url="13991" class="tooltip-link link">Testament of Vanear</a>) then


>**Rarnan Lapice says:** I sent you after that book ages ago! What took you so long? I have already completed my studies. Luckily I found the original manuscript under my bedroll. I forgot I had kept it there. Take this as a token of my apology. Maybe it will aid you in your next book hunt. I know how cunning those books can be.


Your faction standing with [Peace Keepers](/faction/298) got better (<span class='text-success'>+50</span>)


Your faction standing with [Heretics](/faction/265) got better (<span class='text-success'>+12</span>)


Your faction standing with [High Council of Erudin](/faction/266) got worse (<span class='text-danger'>-12</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15302" data-url="15302" class="tooltip-link link">Spell: Languid Pace</a> (+12500 exp)

**You receive coin:** 3 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**
;

