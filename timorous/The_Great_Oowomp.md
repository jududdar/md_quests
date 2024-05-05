# The Great Oowomp



[The Great Oowomp](/npc/96004) is a level 34 Ogre Shaman that spawns in [Timorous Deep](/zone/96).




## Dialog

**You say:** `hail`



>*The Great Oowomp gestures as if casting a powerful spell...'Come forward, adventurer! Come and [see the dancing skeleton]. I shall cast a powerfull spell and bring forth this operatic, clattering jumble of bones and he shall do a fine dance for you. From the nether regions and planes beyond, I call forth this bardic, magical, rhyming, tap-dancing hunk of undead!! I am Oowomp the Great!!'*


e.self:DoAnim(43);

**You say:** `see the dancing skeleton`



>**The Great Oowomp says:** Oh!!  You wish to see the great Oowomp perform his magic!! I have studied with the grand mages and wise [McMerin clan] of Norrath. as my speech implies. I can call forth the skeleton with but a twinkling of my power and five of your gold.


e.self:DoAnim(49);

**You say:** `McMerin clan`



>**The Great Oowomp says:** Clan McMerin were wise shamans from the North. They allowed me to study with them. I learned many spells while I communed with them.  From them, I sto.., I mean, I learned the secret of McMerin's Feast. If you want to know the secret, you could [help gather components] for future rituals.


e.self:DoAnim(48);

**You say:** `gather components`



>**The Great Oowomp says:** Actually... Not so much help as do - ALL - of the gathering. In the lands of Kunark are clay of Ghiosk, crushed dread diamond and powder of Yun. A rare find would be the bones of one who touched the Bath of Obulus. Find and return these to me and the shaman secret of McMerin's Feast is yours.


e.self:DoAnim(65);
end



## Turn-Ins



if( **You turn in:** gold = 5) then


>*The Great Oowomp flings the coins into the air and they all fall neatly into his oversized coin pouch. <Tink, tink, tink, tink, TINK!!> 'Gaze upon my awsome powers of the arcane!! You, a simple " .. e.other:Race() .. ", shall see my power. Allakabam!!'*


**Spawn NPC:**  [a dancing skeleton](/npc/96088) at (**y:** 5725.2, **x:** 3122.8)


**Set a timer** named *dance* for 3 seconds

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1095.png" alt="" /> <a
                                href="/item/12942" data-url="12942" class="tooltip-link link">Strange Ochre Clay</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1075.png" alt="" /> <a
                                href="/item/12945" data-url="12945" class="tooltip-link link">Crushed Diamonds</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_733.png" alt="" /> <a
                                href="/item/12944" data-url="12944" class="tooltip-link link">Yun Shaman Powder</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_804.png" alt="" /> <a
                                href="/item/12943" data-url="12943" class="tooltip-link link">Greyish Bone Chips</a>) then


>*The Great Oowomp begins to jump for joy. The ground trembles. 'Grand! Here is the secret of McMerin's Feast. Scribe it and you shall learn more of its power.*


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/12941" data-url="12941" class="tooltip-link link">Spell: Cannibalize II</a> (+45000 exp)

 

**This NPC *should* return incorrect items given.**



## Timer(s)

if(e.timer == "dance") then


**Signaled to:**  [a dancing skeleton](/npc/96088)


**Stop timer** named *dance*
end
