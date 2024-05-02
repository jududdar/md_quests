# Vynon Estaliun
## Dialog

**You say:** `hail`



>**Vynon Estaliun says:** I welcome you to the temple of the Peacekeepers. The ways of peace and tranquility are ours to uphold. May you find a place among us. We have much work to do. If you are a paladin of this temple. you must [desire to face fear].

**You say:** `desire to face fear`



if **Faction** >= Amiable then 



>**Vynon Estaliun says:** Very well. You shall face it. In Toxxulia Forest. you shall seek out Kerra Ridge. Once found. you will bring me the tail of a catfisher. Somehow. you shall find a way. They are weak. but they only work near the opposite side of the bridge. along the water's edge.


elseif **Faction** >= Indifferent then



>**Vynon Estaliun says:** You have not done much to upset the Peacekeepers of this temple, but we must ask you to prove yourself to us before we may discuss things such as this.


else



>**Vynon Estaliun says:** Leave my sight at once! You are no friend to the Peacekeepers of the Temple of Divine Light.


end

## Turn-Ins




if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_813.png" alt="" /> <a
                                href="/item/13884" data-url="13884" class="tooltip-link link">Fishy Cat Tail</a>) then 


>**Vynon Estaliun says:** Good work. I knew you could do it. Take this as reward.





Your faction standing with [Peace Keepers](/faction/298) got better (<span class='text-success'>+5</span>)


Your faction standing with [High Council of Erudin](/faction/266) got better (<span class='text-success'>+1</span>)


Your faction standing with [Heretics](/faction/265) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_547.png" alt="" /> <a
                                href="/item/13002" data-url="13002" class="tooltip-link link">Torch</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_615.png" alt="" /> <a
                                href="/item/13053" data-url="13053" class="tooltip-link link">Brass Ring</a>) (+2000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**
;

