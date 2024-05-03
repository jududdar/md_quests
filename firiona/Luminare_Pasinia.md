# Luminare Pasinia


## Dialog

**You say:** `hail`



>*Luminare Pasinia waves her hands as if to cast a spell.  'GREETINGS!!  I am the Luminare of Firiona.  By decree of his royal highness, King Thex, I am here to research spells and artifacts.  I have much to do.  I welcome any enchanter who offers to [assist the great Luminare].'*


e.self:DoAnim(43);

**You say:** `assist`



>**Luminare Pasinia says:** And great I am, indeed!! Alas, not great enough to be everywhere at once. I would gladly reward you if you would [collect] components for me.


e.self:DoAnim(42);

**You say:** `collect`



>**Luminare Pasinia says:** Then go into the wilds beyond the outpost and upon your return, you shall give me one Nok Shaman Powder, one Heart of Ice, one Ton Warrior Totem, and one Sabertooth Tiger Mane. This shall earn you knowledge of an enchanter spell I recently scribed.


e.self:DoAnim(64);
end



## Turn-Ins



local text = "Do you not remember that I asked for powder of Nok, a Ton warrior totem, a heart of ice and a sabertooth tiger mane? Incomplete deeds shall fetch no enchanter reward.";






if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_733.png" alt="" /> <a
                                href="/item/12948" data-url="12948" class="tooltip-link link">Nok Shaman Powder</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_963.png" alt="" /> <a
                                href="/item/12834" data-url="12834" class="tooltip-link link">Heart of Ice</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_894.png" alt="" /> <a
                                href="/item/12743" data-url="12743" class="tooltip-link link">Ton Warrior Totem</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_555.png" alt="" /> <a
                                href="/item/12824" data-url="12824" class="tooltip-link link">Sabertooth Tiger Mane</a>) then


>*Luminare Pasinia places the items into a sack and removes a scroll from her robe. This is yours. A spell I discovered and translated for one with less intelligence than the great Luminare of Firiona Vie. You may kiss my feet now.*


Your faction standing with [Inhabitants of Firiona Vie](/faction/248) got better (<span class='text-success'>+3</span>)


Your faction standing with [Emerald Warriors](/faction/326) got better (<span class='text-success'>+2</span>)


Your faction standing with [Storm Guard](/faction/312) got better (<span class='text-success'>+2</span>)


Your faction standing with [Legion of Cabilis](/faction/441) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Pirates of Gunthak](/faction/313) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/12949" data-url="12949" class="tooltip-link link">Vision of Sebilite</a> (+250 exp)

 

**This NPC *should* return incorrect items given.**





