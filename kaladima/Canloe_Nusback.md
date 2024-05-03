# Canloe Nusback


## Dialog

**You say:** `hail`



>**Canloe Nusback says:** Step forward and speak up, young Soandso! Kaladim can always use another warrior. Are you [ready to serve Kaladim] or has a yellow streak appeared down your back?

**You say:** `ready to serve kaladim`



>**Canloe Nusback says:** Then serve you shall. Let your training begin on the battlefields of Faydwer. Seek out and destroy all [Crushbone orcs]. Return their belts to me.  I shall also reward you for every two orc legionnaire shoulder pads  returned.  A warrior great enough to slay one legionnaire shall surely have no problem with another.  Go. and let the cleansing of Faydwer begin.

**You say:** `crushbone orcs`



>**Canloe Nusback says:** The army of the Crushbone orcs is deadly indeed. They are great military strategists. It was a legion of them that brought down the great [Trondle Ogrebane]. Speak with Furtog Ogrebane about the Crushbones. He has need of warriors such as you.

**You say:** `trondle`



>**Canloe Nusback says:** Trondle Ogrebane is the legary dwarven warrior who single-handedly exterminated the ogre clan called the [Mudtoes]. He was recently killed in battle. It took an entire legion of Crushbone orcs to bring him down. Furtog is still fuming about that.

**You say:** `mudtoes`



>**Canloe Nusback says:** The Mudtoes were a small clan of ogres. They lived somewhere in the Butcherblock Mountains. They had an insatiable appetite for dwarves. They were finally destroyed by the hand of Trondle Ogrebane.

**You say:** `irontoe`



>**Canloe Nusback says:** The Irontoe Brigade was formed by Drumpy Irontoe. It was once the finest band of warriors in Kaladim. They were the elite branch of the Stormguard. King Kazon sent them on a mission to the lands of the Crushbone orcs. At the Battle of Busted Skull they met their fate.

**You say:** `tumpy`



>**Canloe Nusback says:** If you frequent the pubs, you just may run into Tumpy Irontoe. He was once the brave leader of the Irontoe Brigade. Whatever you do, do not mention the Battle of Busted Skull. I am sure that would bring back some bad memories for him.

**You say:** `battle of busted skull`



>**Canloe Nusback says:** The Battle of Busted Skull was fought in the land of the Crushbone orcs.  King Kazon sent the entire Irontoe Brigade to retrieve an ancient artifact from an old dwarven outpost.  The battle was fierce.  At its only a handful of Irontoes made it back.  After that, the Irontoe Brigade survivors left Kaladim for good.  All except Tumpy Irontoe.
end



## Turn-Ins







local belt =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_564.png" alt="" /> <a
                                href="/item/13318" data-url="13318" class="tooltip-link link">Crushbone Belt</a>}

local shoulder =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_668.png" alt="" /> <a
                                href="/item/13319" data-url="13319" class="tooltip-link link">Crushbone Shoulderpads</a>}, 2

local text = "Yes, yes!! You have slain one legionnaire, but I reward for proof of two. Certainly you do not find another battle with the legionnaires difficult!!";



if(belt > 0) then


repeat



>**Canloe Nusback says:** Good work, warrior! Now continue with your training. Only on the battlefield can one become a great warrior.



Your faction standing with [Storm Guard](/faction/312) got better (<span class='text-success'>+10</span>)



Your faction standing with [Kazon Stormhammer](/faction/274) got better (<span class='text-success'>+1</span>)



Your faction standing with [Miners Guild 249](/faction/293) got better (<span class='text-success'>+2</span>)



Your faction standing with [Merchants of Kaladim](/faction/290) got better (<span class='text-success'>+1</span>)



Your faction standing with [Craknek Warriors](/faction/232) got worse (<span class='text-danger'>-2</span>)



 &#127873; **You receive:** eq.ChooseRandom(5,6,7,8,9,10,11,12,13,14,15) (+0 exp)

 



belt = belt - 1;


until belt == 0




if(shoulder > 0) then


repeat



>**Canloe Nusback says:** Aha!! You have downed a Crushbone legionnaire!! You have shown yourself to be a strong warrior. Take this. This is more becoming of a great warrior such as yourself. Let no creature stand in the way of the Stormguard!



Your faction standing with [Storm Guard](/faction/312) got better (<span class='text-success'>+15</span>)



Your faction standing with [Kazon Stormhammer](/faction/274) got better (<span class='text-success'>+2</span>)



Your faction standing with [Miners Guild 249](/faction/293) got better (<span class='text-success'>+2</span>)



Your faction standing with [Merchants of Kaladim](/faction/290) got better (<span class='text-success'>+3</span>)



Your faction standing with [Craknek Warriors](/faction/232) got worse (<span class='text-danger'>-3</span>)



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_946.png" alt="" /> <a
                                href="/item/10017" data-url="10017" class="tooltip-link link">Turquoise</a> (+29400 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 4 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 



shoulder = shoulder - 1;


until shoulder == 0;

**This NPC *should* return incorrect items given.**






