# Tynkale



[Tynkale](/npc/61024) is a level 61 High Elf GM Paladin that spawns in [Northern Felwithe](/zone/61).



## Dialog

**You say:** `hail`



>**Tynkale says:** Hail noble, Soandso!  Can you be of [service to the Clerics of Tunare] or are you not from our order?

**You say:** `service to the clerics of tunare`



if **Faction** >= Amiable then




>**Tynkale says:** That is good. Prove yourself, then.  Are you [new to Felwithe] or have I been conversing with a [veteran of the good fight]?


elseif **Faction** >= Indifferent then



>**Tynkale says:** When you have furthered your service to the Paladins of Tunare, we shall make conversation.


else



>**Tynkale says:** You have some nerve to approach a loyal member of the Paladins of Tunare! Run, while you can!


**You say:** `new to felwithe`



if **Faction** >= Amiable then




>**Tynkale says:** Then stand at attention when I speak.  I want you to venture to Kelethin and seek out Tandan Nybright.  He is an old member of ours.  He had some hardships and he fell from Tunare's grace, yet he is still a member of our family.  He will be the one who reeks of elven wine.  Greet him by name.  We are worried for him.


elseif **Faction** >= Indifferent then



>**Tynkale says:** When you have furthered your service to the Paladins of Tunare, we shall make conversation.


else



>**Tynkale says:** You have some nerve to approach a loyal member of the Paladins of Tunare! Run, while you can!


**You say:** `veteran of the good fight`



if **Faction** >= Amiable then




>**Tynkale says:** I command you to venture to Innothule and seek a beast called Jojongua, a name penned by the trolls.  It is said to be ten feet tall and nothing but fury.  Some say it resembles a kobold, but how can that be?  You bring this beast's hide to me and then I will believe you to be a veteran.  Beware!  Innothule is a very dangerous place even for a noble veteran.


elseif **Faction** >= Indifferent then



>**Tynkale says:** When you have furthered your service to the Paladins of Tunare, we shall make conversation.


else



>**Tynkale says:** You have some nerve to approach a loyal member of the Paladins of Tunare! Run, while you can!


**You say:** `honored member`



if **Faction** >= Indifferent +50 then




>**Tynkale says:** Yes. The light of righteousness shines from within you.


elseif **Faction** >= Indifferent then



>**Tynkale says:** When you have furthered your service to the Paladins of Tunare, we shall make conversation.


else



>**Tynkale says:** You have some nerve to approach a loyal member of the Paladins of Tunare! Run, while you can!

end



## Turn-Ins




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18781" data-url="18781" class="tooltip-link link">A tattered note</a>) then 


>**Tynkale says:** Greetings. young paladin!  I am Master Tynkale of the Clerics of Tunare.  Here. we shall teach and train you in the skills needed to defeat our evil and diseased enemies.  Take this, our guild tunic - it will help protect you. Wear it with pride, for you are now one of us.


Your faction standing with [Clerics of Tunare](/faction/226) got better (<span class='text-success'>+100</span>)


Your faction standing with [King Tearis Thex](/faction/279) got better (<span class='text-success'>+100</span>)


Your faction standing with [Anti-mage](/faction/5002) got better (<span class='text-success'>+75</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_678.png" alt="" /> <a
                                href="/item/13591" data-url="13591" class="tooltip-link link">Used Gold Training Tunic*</a> (+20 exp)

 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_554.png" alt="" /> <a
                                href="/item/13351" data-url="13351" class="tooltip-link link">A Very Large Pelt</a>) then


>**Tynkale says:** So you have proven yourself to be a great slayer of beasts.Now it is time to prove yourself to be an asset to the Crown. You are to meet a man named Tolon Nurbyte. He will be at the local inn. Go to him and repeat the phrase, 'The glory of the Mother shines bright.' I can say no more. Oh.. and here. This may help you on your upcoming adventure.


Your faction standing with [Clerics of Tunare](/faction/226) got better (<span class='text-success'>+20</span>)


Your faction standing with [King Tearis Thex](/faction/279) got better (<span class='text-success'>+20</span>)


 &#127873; **You receive:** 0 (+250 exp)

 

**This NPC *should* return incorrect items given.**
;

