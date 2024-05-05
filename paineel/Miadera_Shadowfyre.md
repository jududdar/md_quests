# Miadera Shadowfyre



[Miadera Shadowfyre](/npc/75070) is a level 61 Erudite GM Cleric that spawns in [Paineel](/zone/75).



## Dialog

**You say:** `hail`



>**Miadera Shadowfyre says:** Ahhhahahaha! The terror that lays over this city like a blanket tingles my bones with vigor. I seek a fellow apostle of Cazic-Thule to assist me in the [summoning of Terror].

**You say:** `summoning of terror`



if **Faction** >= Amiable then



>**Miadera Shadowfyre says:** It will be a frightfully fulfilling summons. To do this, I need an eye of urd, some basalt drake scales, the lens of Lord Soptyvr, and a lock of widowmistress hair.


elseif **Faction** >= Indifferent then



>**Miadera Shadowfyre says:** I sense the potential to learn the ways of fear within you. Continue striving to master your fear and one day perhaps you can be of service to our Lord Cazic-Thule.




else



>**Miadera Shadowfyre says:** Begone from this place! Infidels like you have no place among the faithful of Cazic-Thule!




end



## Turn-Ins



local text = "I require all four reagents, anything less is useless. Incompetence will get you nowhere amongst the faithful of Cazic-Thule!";



if( **Faction is** > Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_885.png" alt="" /> <a
                                href="/item/10523" data-url="10523" class="tooltip-link link">Eye of Urd</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_733.png" alt="" /> <a
                                href="/item/19032" data-url="19032" class="tooltip-link link">Basalt Drake Scales</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_507.png" alt="" /> <a
                                href="/item/14110" data-url="14110" class="tooltip-link link">Lens of Lord Soptyvr</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_782.png" alt="" /> <a
                                href="/item/14109" data-url="14109" class="tooltip-link link">Widowmistress Hair</a>) then 


>**Miadera Shadowfyre says:** Yes! Can you feel the terror in the air, prickling your flesh, and standing your hair on The chanters have summoned the avatar of Terror! Quickly take this mundane mask to him and he shall forge it into a valuable symbol to be worn by loyal apostles of Terror!


Your faction standing with [Heretics](/faction/265) got better (<span class='text-success'>+200</span>)


Your faction standing with [Deepwater Knights](/faction/242) got worse (<span class='text-danger'>-200</span>)


Your faction standing with [Gate Callers](/faction/254) got worse (<span class='text-danger'>-200</span>)


Your faction standing with [Craftkeepers](/faction/231) got worse (<span class='text-danger'>-200</span>)


Your faction standing with [Crimson Hands](/faction/233) got worse (<span class='text-danger'>-200</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_528.png" alt="" /> <a
                                href="/item/14106" data-url="14106" class="tooltip-link link">Mundane Mask</a> (+5000 exp)

**You receive coin:** 1-9 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-9 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-9 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-9 <img src='/static/icons/item_647.png' width='14' height='14'/> 


**Spawn NPC:**  [avatar of terror](/npc/75195) at (**y:** 1182, **x:** 421)

**This NPC *should* return incorrect items given.**
;





