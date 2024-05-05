# Furtog Ogrebane



[Furtog Ogrebane](/npc/60023) is a level 61 Dwarf GM Warrior that spawns in [South Kaladim](/zone/60).



## Dialog

**You say:** `hail`



>**Furtog Ogrebane says:** Hail, mighty Soandso! Welcome to Stormguard Hall. I am Captain Furtog Ogrebane, only surviving descendant of the legendary Trondle Ogrebane, slayer of the [Mudtoes]. If you wish to serve the grand city of Kaladim. I urge you to speak with any of the trainers. Good day.

**You say:** `mudtoes`



>**Furtog Ogrebane says:** The Mudtoes were a small but mighty clan of ogres. My great father [Trondle] destroyed them. I have heard disturbing rumors of one Mudtoe surviving. Would you mind [searching for the Mudtoes] or have you other duties to perform?

**You say:** `trondle`



>**Furtog Ogrebane says:** Trondle was my great father and slayer of the Mudtoes. He was killed by those vile Crushbone orcs. If you truly wish to help Kaladim remain safe. speak with trainer Canloe Nusback. Say that you are ready to serve Kaladim.

**You say:** `searching`



>**Furtog Ogrebane says:** I have heard persistent rumors of two Mudtoe ogres who survived the slaughter.  Go to the port of Butcherblock.  Those dock hands must have heard of the name [Mudtoe].  Bring me the remaining heads of the Mudtoes!!  I want all the Mudtoes dead!!  Do not return until you have them both!!

**You say:** `irontoe`



>**Furtog Ogrebane says:** The Irontoe Brigade was formed by Drumpy Irontoe. It was once the finest band of warriors in Kaladim. They were the elite branch of the Stormguard. King Kazon sent them on a mission to the lands of the Crushbone orcs. At the Battle of Busted Skull they met their fate.

**You say:** `tumpy`



>**Furtog Ogrebane says:** If you frequent the pubs, you just may run into Tumpy Irontoe. He was once the brave leader of the Irontoe Brigade. Whatever you do, do not mention the Battle of Busted Skull. I am sure that would bring back some bad memories for him.

**You say:** `crushbone orc`



>**Furtog Ogrebane says:** The army of the Crushbone orcs is deadly indeed. They are great military strategists. It was a legion of them that brought down the great [Trondle Ogrebane]. Speak with Furtog Ogrebane about the Crushbones. He has need of warriors such as you.

**You say:** `battle of busted skull`



>**Furtog Ogrebane says:** The Battle of Busted Skull was fought in the land of the Crushbone orcs.  King Kazon sent the entire Irontoe Brigade to retrieve an ancient artifact from an old dwarven outpost.  The battle was fierce.  At its only a handful of Irontoes made it back.  After that, the Irontoe Brigade survivors left Kaladim for good.  All except Tumpy Irontoe.
end



## Turn-Ins



local text = "There is another! I have reports that there were two Mudtoe ogres on the island chain in the Ocean of Tears. I want both heads!";



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18766" data-url="18766" class="tooltip-link link">Recruitment Letter</a>) then 


>**Furtog Ogrebane says:** Greetings, friend, and welcome to Stormguard Hall! I am Furtog Ogrebane, Captain of the Guard. We shall train you to be a fearless warrior, who will serve and protect King Kazon well. Here is your tunic.  Now, let's begin your training.


Your faction standing with [Storm Guard](/faction/312) got better (<span class='text-success'>+100</span>)


Your faction standing with [Kazon Stormhammer](/faction/274) got better (<span class='text-success'>+15</span>)


Your faction standing with [Miners Guild 249](/faction/293) got better (<span class='text-success'>+15</span>)


Your faction standing with [Merchants of Kaladim](/faction/290) got better (<span class='text-success'>+25</span>)


Your faction standing with [Craknek Warriors](/faction/232) got worse (<span class='text-danger'>-25</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_678.png" alt="" /> <a
                                href="/item/13515" data-url="13515" class="tooltip-link link">Dirt Stained Tunic*</a> (+20 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_920.png" alt="" /> <a
                                href="/item/13316" data-url="13316" class="tooltip-link link">Ogre Head</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_920.png" alt="" /> <a
                                href="/item/13317" data-url="13317" class="tooltip-link link">Ogre Head</a>) then 


>**Furtog Ogrebane says:** Finally my great father's work has been completed. All the Mudtoe ogres have been exterminated. Thank you. Take this weapon which my father pried from the cold, dead hands of the Mudtoe ogre captain. It is called an ogre war maul. May you wield it with honor in the name of Kaladim.





Your faction standing with [Storm Guard](/faction/312) got better (<span class='text-success'>+50</span>)


Your faction standing with [Kazon Stormhammer](/faction/274) got better (<span class='text-success'>+7</span>)


Your faction standing with [Miners Guild 249](/faction/293) got better (<span class='text-success'>+7</span>)


Your faction standing with [Merchants of Kaladim](/faction/290) got better (<span class='text-success'>+12</span>)


Your faction standing with [Craknek Warriors](/faction/232) got worse (<span class='text-danger'>-12</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_581.png" alt="" /> <a
                                href="/item/6302" data-url="6302" class="tooltip-link link">Ogre War Maul</a> (+250 exp)

**You receive coin:** 1-3 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**
