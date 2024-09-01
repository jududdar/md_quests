# Savage Lord Cedrean

[Savage Lord Cedrean](/npc/202236) is a level 61 Barbarian GM Beastlord that spawns in [Plane of Knowledge](/zone/202).

Their primary faction is [Inhabitants of Tanaan](/faction/1636).





## Dialog

**You say:** `Hail`


>*Savage Lord Cedrean in an almost arcane motion, gives a mystic gesture of ancient greetings. 'The light of Selia shines upon you most brightly, Soandso. Be at ease, and know that all answers you seek will be delivered in time. The library of Myrist, though lacking the purity of the virtues we hold most dear to our selves in valiant memory of our mortal endeavors, is truly an unrivaled source of infinite knowledge. However, if you seek the comfort of your own light and goodly virtues, then Selia shall provide whatever it can to accommodate your needs while in our midst. Unfortunately, the ruling of the council has limited each individual citizen of the city to one particular specialty so that each have their equal opportunity to share their unique knowledge. In my former life, I was a master of the beasts and crusader of Mithaniel Marr. If you share the same profession as I and are in need of training, then I am more than pleased to oblige you.'*









## Turn-Ins



local count =  **You turn in:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_637.png" alt="" /> <a
                                href="/item/7817" data-url="7817" class="tooltip-link link">Anthemion Wristguard</a>, 7818, 7819, 7832, 7833, 7834, 7835 x 1

if(count > 0) then

repeat

>**Savage Lord Cedrean says:** Thank you, Soandso.

 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_957.png" alt="" /> <a
                                href="/item/10028" data-url="10028" class="tooltip-link link">Peridot</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/10037" data-url="10037" class="tooltip-link link">Diamond</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/22503" data-url="22503" class="tooltip-link link">Blue Diamond</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/15981" data-url="15981" class="tooltip-link link">Raw Diamond</a>) (+300000 exp)

 

count = count - 1;

until count == 0;



**This NPC *should* return incorrect items given.**












