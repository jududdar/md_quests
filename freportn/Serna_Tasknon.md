# Serna Tasknon


## Dialog

**You say:** `hail`



>**Serna Tasknon says:** It is a good thing to see new faces visiting our temple. We are the source of strength within this city. Do not be fooled by the Freeport Militia. They are not warriors of valor. [Join the fight against the Freeport Militia].

**You say:** `join the fight`



if **Faction** >= Apprehensive then



>**Serna Tasknon says:** You are wise. If you are a paladin, either speak with Theron of this temple or visit the Hall of Truth here in North Freeport. Clerics should concetrate on keeping the knights strong and healthy. Would you care to [assist the Temple of Marr]?


else



>**Serna Tasknon says:** The passion of the Queen of Love does not favor you. Begone from my sight!


**You say:** `assist`



if **Faction** >= Amiable then



>**Serna Tasknon says:** Good. Take this Potion of Marr to the Sentries of Passion. They are the protectors of this temple. Start in alphabetical order and the first shall take but a sip then you shall take it to the next in order of the alphabet. There are but eight sentries. Sentry Andlin to Sentry Xyrin. Go.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_788.png" alt="" /> <a
                                href="/item/12127" data-url="12127" class="tooltip-link link">Full Potion of Marr</a>


elseif **Faction** >= Indifferent then



>**Serna Tasknon says:** The path you walk is correct, but you have further to travel before you need worry about this.


else



>**Serna Tasknon says:** The passion of the Queen of Love does not favor you. Begone from my sight!


**You say:** `heal`



>**Serna Tasknon says:** It is not my duty to see to the wounded. You must seek out Plur Etinu. He is in here somewhere.
end



## Turn-Ins



local text = "The arangement was for three shark bones and 10 gold coins";


if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_804.png" alt="" /> <a
                                href="/item/12126" data-url="12126" class="tooltip-link link">Shark Bones</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_804.png" alt="" /> <a
                                href="/item/12126" data-url="12126" class="tooltip-link link">Shark Bones</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_804.png" alt="" /> <a
                                href="/item/12126" data-url="12126" class="tooltip-link link">Shark Bones</a>, gold = 10) then


>**Serna Tasknon says:** I thank you for your ten gold coins. Now we can pay the weekly oxygen tax imposed by the militia. Here is the shark powder.





Your faction standing with [Priests of Marr](/faction/362) got better (<span class='text-success'>+1</span>)


Your faction standing with [The Freeport Militia](/faction/330) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Knights of Truth](/faction/281) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1075.png" alt="" /> <a
                                href="/item/12125" data-url="12125" class="tooltip-link link">Shark Powder</a> (+100 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_599.png" alt="" /> <a
                                href="/item/13983" data-url="13983" class="tooltip-link link">Inert Potion</a>) then


>**Serna Tasknon says:** I see Tonmerk has found a use for my shark powder. We agreed to this trade when last we met. Unfortunately, I am out of it. If you desire the shark powder you will have to get me three shark bones. I wish you luck. Oh. I also require a payment of ten gold pieces. The taxes in Freeport are fierce.





Your faction standing with [Priests of Marr](/faction/362) got better (<span class='text-success'>+5</span>)


Your faction standing with [The Freeport Militia](/faction/330) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Knights of Truth](/faction/281) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:** 0 (+100 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_788.png" alt="" /> <a
                                href="/item/12135" data-url="12135" class="tooltip-link link">Empty Potion of Marr</a>) then


>**Serna Tasknon says:** The Sentries of Passion informed me of your journey to the Ocean of Tears and the demise of Sentry Xyrin. You performed beyond the call of duty. This is what makes an exceptional person. Take this for your great deed. The twin deities would wish it so.


Your faction standing with [Priests of Marr](/faction/362) got better (<span class='text-success'>+5</span>)


Your faction standing with [The Freeport Militia](/faction/330) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Knights of Truth](/faction/281) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15207" data-url="15207" class="tooltip-link link">Spell: Divine Aura</a> (+1000 exp)

 

**This NPC *should* return incorrect items given.**
