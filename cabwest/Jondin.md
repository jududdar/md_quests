# Jondin

## Dialog

**You say:** `Hail`



>**Jondin says:** Greetings. friend.  I have many fine herbs for sale.  My prices are reasonable for I am not governed by the [Haggle Baron].  If you fancy yourself an adventurer. I would like to hire you for a [simple mission].

**You say:** `haggle baron`



>**Jondin says:** Haggle Baron Klok Dun Ree is the current Haggle Baron. It is written in the law that all services shall be governed by the Haggle Baron. To do business outside of the law is forbidden, but the merchants of the Tower of Death are exempt from this rule. Klok will not test the temper of the Harbinger and Baron Eator will not upset his most powerful ally.

**You say:** `simple mission`



>**Jondin says:** I actually have a few items I am presently low on.  I would appreciate some assistance to [collect fern flowers] or maybe you are an alchemist who can [gather bone chips].

**You say:** `fern flowers`



>**Jondin says:** I have run low on fern flowers and must have more of them.  Take this [flower pouch].  Outside the city can be found carnivorous plants and a strain of them buds the flower in question.  Collect enough of these flowers to fill and combine the pouch and I shall reward you.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_582.png" alt="" /> <a
                                href="/item/17025" data-url="17025" class="tooltip-link link">Fern Flower Pouch</a>

**You say:** `bone chips`



>**Jondin says:** I should tell you. I do not need the bone chips.  I need bone granite powder.  In order to get it. you must find some granite pebbles and then three piles of bone chips from decaying skeletons.  After you gather the items you will have to use your skill in alchemy to combine the items and create bone granite powder.  The powder is what I need.
end

## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1074.png" alt="" /> <a
                                href="/item/12442" data-url="12442" class="tooltip-link link">Bone Granite Powder</a>) then


>**Jondin says:** You have done well. Here is your reward.


Your faction standing with [Brood of Kotiz](/faction/443) got better (<span class='text-success'>+1</span>)


Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+1</span>)


if(math.random(100) < 35) then



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_776.png" alt="" /> <a
                                href="/item/12443" data-url="12443" class="tooltip-link link">Kromdul Toothpick</a> 

 

end
