# Arch Mage Narik




## Dialog

**You say:** `Hail`



if(e.other:Race() == "Dark Elf" or e.other:Race() == "Iksar" or e.other:Race() == "Troll" or e.other:Race() == "Ogre" or e.other:Class() == "Shadowknight" or e.other:Class() == "Necromancer") then



e.self:DoAnim(26);



e.self:Emote("raises a brow and gives an emotionless stare of objective study toward Soandso, 'You seem out of place 


else



e.self:DoAnim(48);



>*Arch Mage Narik gives a gentle smile and polite bow of respect to Soandso, 'Greetings and welcome to the district of Tanaan, traveler. This place of neutrality is quite content to have you among us, learning from us what we humbly can teach you. Many adepts who were adventurers not too different from yourself have stepped forward and offered their memories as present lessons to those willing to learn of them. I myself was a master of the elements in my time, though I do not make this declaration as one that craves due respect for the title. Rather, I hope that you may perhaps be of the same path and if you need tutoring in the way of skills, then I would be more than pleased to oblige your needs.'*


**You say:** `jewel`



>*Arch Mage Narik slams his book shut. 'So, the snake has legs after all! Tell Onirelin if he wants this back, he can come here himself and kiss my. . ., no wait. I have a better idea.' He draws closer and whispers, 'Did Onirelin tell you why I took this jewel? I did it in response to him taking my lady love, Elisha Dirtyshoes. We were to be married until she ran off with him. However, she also ran off with my engagement ring I gave to her. It is quite valuable to me, and I would be most happy to have it back. If you can procure it from her, I'll give Onirelin his jewel back. He's suffered long enough, I think.'*
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

if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1064.png" alt="" /> <a
                                href="/item/28087" data-url="28087" class="tooltip-link link">Nariks Ring</a>) then 


>**Arch Mage Narik says:** This is truly excellent. You have done well recovering this for me. You may take Onirelin's jewel and also tell him never to set foot near me again. Leave me now, I have much work to do.





 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/28088" data-url="28088" class="tooltip-link link">Onirelins Jewel</a> (+100 exp)

 



if(count > 0) then


repeat



>**Arch Mage Narik says:** Thank you, Soandso.



 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_957.png" alt="" /> <a
                                href="/item/10028" data-url="10028" class="tooltip-link link">Peridot</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/10037" data-url="10037" class="tooltip-link link">Diamond</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/22503" data-url="22503" class="tooltip-link link">Blue Diamond</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/15981" data-url="15981" class="tooltip-link link">Raw Diamond</a>) (+300000 exp)

 



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**
