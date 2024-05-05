# Arch Mage Deidus



[Arch Mage Deidus](/npc/202259) is a level 61 Dark Elf GM Magician that spawns in [Plane of Knowledge](/zone/202).






## Dialog

**You say:** `Hail`



>*Arch Mage Deidus gives a loathsome, unwavering stare upon Soandso. His features are steely and cold in their disdain. 'Kartis is the place of shadow - the cornerstone of the seed of corruption in this universe. You have no place here as you are. Return to Selia. for you will find nothing of use to you here. If you intend to decipher the purpose of the shadow or interrupt the training of our disciples, then you are grievously mistaken in your cause. We will share nothing with the likes of you in the ways of knowledge. Though slowly, if you choose to remain, we shall corrupt and contort you to our will. Even through mere acts of training, you will be fueling the shadow and will become a part of it unwittingly or no.'*
end


## Turn-Ins



local count =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_523.png" alt="" /> <a
                                href="/item/1239" data-url="1239" class="tooltip-link link">Apothic Crown</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_930.png" alt="" /> <a
                                href="/item/1240" data-url="1240" class="tooltip-link link">Apothic Robe</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_634.png" alt="" /> <a
                                href="/item/1241" data-url="1241" class="tooltip-link link">Apothic Sleeves</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_516.png" alt="" /> <a
                                href="/item/1242" data-url="1242" class="tooltip-link link">Apothic Warband</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_636.png" alt="" /> <a
                                href="/item/1243" data-url="1243" class="tooltip-link link">Apothic Gloves</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_843.png" alt="" /> <a
                                href="/item/1244" data-url="1244" class="tooltip-link link">Apothic Kilt</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_633.png" alt="" /> <a
                                href="/item/1245" data-url="1245" class="tooltip-link link">Apothic Boots</a>}

if(count > 0) then


repeat



>**Arch Mage Deidus says:** Thank you, Soandso.



 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_957.png" alt="" /> <a
                                href="/item/10028" data-url="10028" class="tooltip-link link">Peridot</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/10037" data-url="10037" class="tooltip-link link">Diamond</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/22503" data-url="22503" class="tooltip-link link">Blue Diamond</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/15981" data-url="15981" class="tooltip-link link">Raw Diamond</a>) (+300000 exp)

 



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





