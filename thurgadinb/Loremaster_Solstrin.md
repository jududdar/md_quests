# Loremaster Solstrin


## Dialog

**You say:** `hail`



>*Loremaster Solstrin bows before you and says, 'Greetings to you as well, Soandso. I have recently heard many tales of your people and their glory. I am honored to welcome you to the Hall of Ancestors. Here our people come to pay tribute to the bravest and wisest of our kin who have passed from this life into Brell's holy domain. If you are interested I'd be happy to tell you a little bit about the heroes buried here.*


e.self:DoAnim(70);

**You say:** `heroes`



if **Faction** >= Amiable then 



>*Loremaster Solstrin smiles at you, obviously pleased by your interest. 'This hall contains the bodies of Dain Frostreavers the I, II, and III as well as his grace Grand Historian Nicmar. There is also an empty bier in the back awaiting the next hero of our people. But the most sacred tomb of all lies right behind me here.'*


elseif **Faction** >= Indifferent then



>**Loremaster Solstrin says:** My instincts tell me you are almost ready to share in the knowledge of our greatest people, but you have a little ways to go to prove yourself worthy of such an honor.


else



>**Loremaster Solstrin says:** You have yet to prove yourself as an ally to my people, Soandso. Therefore, you have yet to earn the honor of sharing in the knowledge of these heroes.


**You say:** `nicmar`



if **Faction** >= Amiable then 



eq.move_to(244,746,-41,0,false);



>**Loremaster Solstrin says:** Here lies the body of his grace Grand Historian Nicmar. Nicmar was a very prominent priest, scholar, architect, and artist. As an advisor to both Dain Frostreaver II and his son, Dain Frostreaver III, Nicmar still holds the record for oldest Coldain before dying of old age at the onset of the War of Yesterwinter. Nicmar was the chief architect of Thurgadin.  He also built this Hall of Ancestors and sculpted the statues in Remembrance Park.


elseif **Faction** >= Indifferent then



>**Loremaster Solstrin says:** My instincts tell me you are almost ready to share in the knowledge of our greatest people, but you have a little ways to go to prove yourself worthy of such an honor.


else



>**Loremaster Solstrin says:** You have yet to prove yourself as an ally to my people, Soandso. Therefore, you have yet to earn the honor of sharing in the knowledge of these heroes.


**You say:** `dain frostreaver i`



if **Faction** >= Amiable then 



eq.move_to(244,714,-41,128,false);



>**Loremaster Solstrin says:** Here lies the body of his majesty Dain Frostreaver I. As the son of Colin Dain, he was the first crowned Dain of our people and also the first to carry the name Frostreaver, which was given to him by our people for his skills of dispatching Kromrif in melee combat. Original keeper of the magic axe Frostreaver, which has been passed down to our current Dain, he was a close friend of Glight Snowchipper and aided him in engineering the crystal caverns. It was there he met his death on a mining expedition deep into the caverns. No one was ever quite sure what killed him, only that the bodies of him and his party were found bloated and corrupted by foul poisons.


elseif **Faction** >= Indifferent then



>**Loremaster Solstrin says:** My instincts tell me you are almost ready to share in the knowledge of our greatest people, but you have a little ways to go to prove yourself worthy of such an honor.


else



>**Loremaster Solstrin says:** You have yet to prove yourself as an ally to my people, Soandso. Therefore, you have yet to earn the honor of sharing in the knowledge of these heroes.


**You say:** `dain frostreaver ii`



if **Faction** >= Amiable then 



eq.move_to(214,714,-41,128,false);



>**Loremaster Solstrin says:** Here lies the body of his majesty Dain Frostreaver II. Known as the Priest King, he was the only Dain whot was a loremaster before his father died and he was crowned Dain. It was by his will that we left our home in the Crystal Caves and founded Thurgadin. He worked closely with the architects and miners to ensure Thurgadin would be built secretly and defensively. Dain Frostreaver II died of old age with his dream intact, our city had yet to be discovered and our people lived in relative peace and safety for more than five centuries.


elseif **Faction** >= Indifferent then



>**Loremaster Solstrin says:** My instincts tell me you are almost ready to share in the knowledge of our greatest people, but you have a little ways to go to prove yourself worthy of such an honor.


else



>**Loremaster Solstrin says:** You have yet to prove yourself as an ally to my people, Soandso. Therefore, you have yet to earn the honor of sharing in the knowledge of these heroes.


**You say:** `dain frostreaver iii`



if **Faction** >= Amiable then 



eq.move_to(214,746,-41,0,false);



>**Loremaster Solstrin says:** Here lies the body of his majesty Dain Frostreaver III. Known as the War King for his hot temper and brutal combat tactics, he ran a brutally offensive campaign that routed most of the giants from the Great Divide and half of the Eastern Wastes. Eventually, with the powerful magic of the Kromzek and the overwhelming might of the Kromrif, his armies were forced to retreat to the border of the Great Divide where he was killed on the battlefield in single combat at the hand of King Tormax. This war is now known as the War of Yesterwinter.


elseif **Faction** >= Indifferent then



>**Loremaster Solstrin says:** My instincts tell me you are almost ready to share in the knowledge of our greatest people, but you have a little ways to go to prove yourself worthy of such an honor.


else



>**Loremaster Solstrin says:** You have yet to prove yourself as an ally to my people, Soandso. Therefore, you have yet to earn the honor of sharing in the knowledge of these heroes.


**You say:** `sacred tomb`



>**Loremaster Solstrin says:** In this block of ice lie the sole remnants of our great father, leader, and founder, Colin Dain. While leading our people to the safety of the mountains following the destruction of our beloved Froststone. Colin came to a grim realization. He knew that there was no way our people could outrun the giants and safely get away. And so he took thirty volunteers and led them in a suicide ambush to halt the giants' chase while the rest of our people got away. Without his sacrifice, the Coldain might very well have been wiped out that day. Once we were safe, scouts were dispatched to the battle with the hope of finding survivors. Amidst the field of bodies they found this crown, axe, and breastplate which belonged to our beloved leader. Of Colin's actual body, no remnant was ever found.

**You say:** `working with gemstone`



>**Loremaster Solstrin says:** Aye, gems are placed within the armor. Brell is pleased with this fusion of ore and gem. The combination produces a sturdy piece of armor. You will need some Etching Tools to work with the gems. If you ask Meg Tucter for a set, she should have some laying about.

**You say:** `issue kit`



>**Loremaster Solstrin says:** The Standard Issue Kit is what we issue to soldiers at the beginning of their mission. I have this empty one here. Before I give it to you, could you show me your Runed Coldain Prayer Shawl? I would like to see how skilled you are.
end



## Turn-Ins





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_860.png" alt="" /> <a
                                href="/item/8896" data-url="8896" class="tooltip-link link">Royal Coldain Orders</a>) then


>**Loremaster Solstrin says:** So, the Dain needs your assistance with the Field Plate. The Dain must trust you a great deal to impart the wisdom of our armor creation to you. Here are the tomes. The first details how to make the basic armor, the other details how to begin [working with gemstones]. If the Dain is asking you for them you should place them in an [Issue Kit]. May Brell guide your hand friend, good luck to you.


 &#127873; **You receive:** GiveAll( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18611" data-url="18611" class="tooltip-link link">Forge of Icewell Arms</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18610" data-url="18610" class="tooltip-link link">Forge of Icewell Arms</a>) 

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_642.png" alt="" /> <a
                                href="/item/1199" data-url="1199" class="tooltip-link link">Runed Coldain Prayer Shawl</a>) then 


>**Loremaster Solstrin says:** Incredible! Never before has an outlander been skilled and determined enough to craft our sacred rune. You are now worthy of the Dain's most perilous task. You should seek an audience with the Dain immediately. Show him your Runed Prayer Shawl; he will give you the task that has been prepared for you. If the Dain is away show your Shawl to Chamberlain Krystorf and he will call for him.


 &#127873; **You receive:** GiveAll( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_642.png" alt="" /> <a
                                href="/item/1199" data-url="1199" class="tooltip-link link">Runed Coldain Prayer Shawl</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_837.png" alt="" /> <a
                                href="/item/17651" data-url="17651" class="tooltip-link link">Empty Coldain Issue Kit</a>) 

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_642.png" alt="" /> <a
                                href="/item/8895" data-url="8895" class="tooltip-link link">Runed Coldain Prayer Shawl</a>) then 


>**Loremaster Solstrin says:** Incredible! Never before has an outlander been skilled and determined enough to craft our sacred rune. You are now worthy of the Dain's most perilous task. You should seek an audience with the Dain immediately. Show him your Runed Prayer Shawl; he will give you the task that has been prepared for you. If the Dain is away show your Shawl to Chamberlain Krystorf and he will call for him.


 &#127873; **You receive:** GiveAll( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_642.png" alt="" /> <a
                                href="/item/8895" data-url="8895" class="tooltip-link link">Runed Coldain Prayer Shawl</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_837.png" alt="" /> <a
                                href="/item/17651" data-url="17651" class="tooltip-link link">Empty Coldain Issue Kit</a>) 

 

**This NPC *should* return incorrect items given.**
