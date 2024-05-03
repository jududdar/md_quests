# Gkrean Prophet of Tallon


## Dialog

if( **Faction is** > Indifferent) then


**You say:** `hail`




>**Gkrean Prophet of Tallon says:** You have entered the sacred temple of Tallon Zek. This is the Temple of Tactics, where we teach what must be done to achieve goals in the most efficient manner.


**You say:** `teach`




>**Gkrean Prophet of Tallon says:** I cannot teach one of your kind the arts of war. I must teach the other Kromzek at this time. If you were to serve the Temple of Tactics I might consider giving you a few words of wisdom.


**You say:** `serve the temple`




>**Gkrean Prophet of Tallon says:** The great father of war, Rallos Zek, wishes the destruction of the inferior race known as the Coldain. As the high priest of Tallon Zek, I see that they use great tactics to evade destruction. Find the ones who teach these tactics to the other Coldain and bring back the books that contain the ancient Coldain tactics and strategies. Do not waste my time without a scroll or book that those tiny beasts hold.


elseif( **Faction is** > Apprehensive) then


>**Gkrean Prophet of Tallon says:** You need to prove your dedication to our cause before I can discuss such matters with you.

else


**Gkrean Prophet of Tallon says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.
end



## Turn-Ins





if( **Faction is** > Indifferent and ( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_865.png" alt="" /> <a
                                href="/item/24987" data-url="24987" class="tooltip-link link">Brells Divine Strategy</a> or  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/24988" data-url="24988" class="tooltip-link link">War Tactics of the Frostreavers</a>)) then


>**Gkrean Prophet of Tallon says:** You are a brave little beast to gain this tome. Let me impart a bit of wisdom to you. Tactics must change - if you do not ever adapt to new surroundings, environments and rules, you will surely perish.


Your faction standing with [Kromzek](/faction/448) got better (<span class='text-success'>+20</span>)


Your faction standing with [Kromrif](/faction/419) got better (<span class='text-success'>+5</span>)


Your faction standing with [King Tormax](/faction/429) got better (<span class='text-success'>+5</span>)


Your faction standing with [Claws of Veeshan](/faction/430) got worse (<span class='text-danger'>-10</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_523.png" alt="" /> <a
                                href="/item/25037" data-url="25037" class="tooltip-link link">Circlet of Tallon</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_777.png" alt="" /> <a
                                href="/item/25038" data-url="25038" class="tooltip-link link">Book of Tactics</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_529.png" alt="" /> <a
                                href="/item/25039" data-url="25039" class="tooltip-link link">Gauntlets of Iron Tactics</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1040.png" alt="" /> <a
                                href="/item/25042" data-url="25042" class="tooltip-link link">Bracelet of Sacrifice</a>) (+50000 exp)

 

**This NPC *should* return incorrect items given.**

