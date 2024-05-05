# Marlyn McMerin



[Marlyn McMerin](/npc/84192) is a level 40 Barbarian Shopkeeper that spawns in [Firiona Vie](/zone/84).



## Dialog

**You say:** `hail`



>**Marlyn McMerin says:** Greetings hearty adventurer. Searching for the components necessary for fine shaman spells are we? I have come to Kunark in search of [rare alchemy components], but I have found the dangers of Kunark are far too great for me.


e.self:DoAnim(69);

**You say:** `rare alchemy components`



>**Marlyn McMerin says:** I have heard word of four rare components -  the clay of Ghiosk, crushed dread diamonds and powder of Yun.  Most rare are chips from the bones of one who has touched the Bath of Obulus.


e.self:DoAnim(27);
end



## Turn-Ins



local text = "I requested the bone chips which touched the Bath of Obulus, clay of Ghiosk, powder of Yun and crushed dread diamonds.";




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1095.png" alt="" /> <a
                                href="/item/12942" data-url="12942" class="tooltip-link link">Strange Ochre Clay</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1075.png" alt="" /> <a
                                href="/item/12945" data-url="12945" class="tooltip-link link">Crushed Diamonds</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_733.png" alt="" /> <a
                                href="/item/12944" data-url="12944" class="tooltip-link link">Yun Shaman Powder</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_804.png" alt="" /> <a
                                href="/item/12943" data-url="12943" class="tooltip-link link">Greyish Bone Chips</a>) then


>**Marlyn McMerin says:** What's this? This is amazing - you collected them all! To think, the power that these items hold if properly used. Never mind that now, here, take the scroll. You've certainly earned it.


Your faction standing with [Inhabitants of Firiona Vie](/faction/248) got better (<span class='text-success'>+5</span>)


Your faction standing with [Emerald Warriors](/faction/326) got better (<span class='text-success'>+3</span>)


Your faction standing with [Storm Guard](/faction/312) got better (<span class='text-success'>+3</span>)


Your faction standing with [Legion of Cabilis](/faction/441) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Pirates of Gunthak](/faction/313) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/12941" data-url="12941" class="tooltip-link link">Spell: Cannibalize II</a> (+45000 exp)

 

**This NPC *should* return incorrect items given.**






