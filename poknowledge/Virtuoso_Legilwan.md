# Virtuoso Legilwan

[Virtuoso Legilwan](/npc/202244) is a level 61 Half Elf GM Bard that spawns in [Plane of Knowledge](/zone/202).

Their primary faction is [Inhabitants of Tanaan](/faction/1636).







## Dialog

**You say:** `Hail`


if(e.other:Race() == "Dark Elf" or e.other:Race() == "Iksar" or e.other:Race() == "Troll" or e.other:Race() == "Ogre" or e.other:Class() == "Shadowknight" or e.other:Class() == "Necromancer") then

e.self:DoAnim(60)

>*Virtuoso Legilwan raises a brow sharply and gains a face of almost belittling amusement as he eyes Soandso before him. 'Do you not think yourself out of place here, dark one? Please, do not be offended, for that is not my intent in the least, of course. I would rather see your needs fulfilled to the utmost of your necessity than see you leave this place no more knowledgeable than before your arrival. The library of Myrist in the center of our city is home to the scholars of New Tanaan, who believe themselves to have ascended beyond the 'petty mortal squabbles*

else

e.self:DoAnim(48);

>*Virtuoso Legilwan gives a gentle, though formal nod of his head in warm greetings. 'Welcome, Soandso, to the district of Tanaan. We have the utmost faith that this humble place will accommodate your every need most generously. The merchants in scattered throughout our region are quite useful to any tradesmen or adventurer seeking to restock on supplies and the devises of teleportation found in this district should be more than suitable for one of your ilk. If you have come to Tanaan seeking guidance in the ways of mentorship and skills, then know only success in your search for we are more than prepared to accommodate the needs of almost any adventurer. The bards of Norrath who seek guidance without the ravings of a philosophical, political, or religious zealot will find myself to be a most formidable suitor to their needs.'*











## Turn-Ins



local count =  **You turn in:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_746.png" alt="" /> <a
                                href="/item/4861" data-url="4861" class="tooltip-link link">Imbrued Platemail Helm</a>, 4862, 4863, 4864, 4865, 4866, 4867 x 1

if(count > 0) then

repeat

>**Virtuoso Legilwan says:** Thank you, Soandso.

 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_957.png" alt="" /> <a
                                href="/item/10028" data-url="10028" class="tooltip-link link">Peridot</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/10037" data-url="10037" class="tooltip-link link">Diamond</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/22503" data-url="22503" class="tooltip-link link">Blue Diamond</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/15981" data-url="15981" class="tooltip-link link">Raw Diamond</a>) (+300000 exp)

 

count = count - 1;

until count == 0;



**This NPC *should* return incorrect items given.**












