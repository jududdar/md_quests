# Hogunk Ventille


## Dialog

**You say:** `Hail`



>**Hogunk Ventille says:** Hail. and welcome to Stormguard Hall. home to all great warriors! Are you also a [warrior of the Stormguard] or do you [follow another guild]?

**You say:** `i am a warrior of the stormguard`



if **Faction** >= Amiable then



>**Hogunk Ventille says:** As I thought. You do not appear to be one who relies on wits rather than brawn. no offense. I have word that a Stormguard on duty has deserted his post at one of the guardposts in the Butcherblocks. I want you to go and seek him out. He is Guard Bundin. Return his Stormguard axe to me. along with his head. There shall be no cowards in the Stormguard!!


elseif( **Faction is** == Indifferent) then



>**Hogunk Ventille says:** Prove yourself to the Stormguard and then we shall talk.  Perhaps you may assist Master Canloe and show your worth to us.


else



>**Hogunk Ventille says:** Your shifty eyes tell me that you are no ally of the Stormguard.


**You say:** `i follow another guild`



>**Hogunk Ventille says:** Then go to your guild. This is the hall of the dwarven warriors - not a place for common folk to lounge around.

**You say:** `irontoe`



>**Hogunk Ventille says:** The Irontoe Brigade was formed by Drumpy Irontoe. It was once the finest band of warriors in Kaladim. They were the elite branch of the Stormguard. King Kazon sent them on a mission to the lands of the Crushbone orcs. At the Battle of Busted Skull they met their fate.

**You say:** `tumpy`



>**Hogunk Ventille says:** If you frequent the pubs, you just may run into Tumpy Irontoe. He was once the brave leader of the Irontoe Brigade. Whatever you do, do not mention the Battle of Busted Skull. I am sure that would bring back some bad memories for him.

**You say:** `trondle`



>**Hogunk Ventille says:** Trondle Ogrebane is the legendary dwarven warrior who single-handedly exterminated the ogre clan called the [Mudtoes]. He was recently killed in battle. It took an entire legion of Crushbone orcs to bring him down. Furtog is still fuming about that.

**You say:** `mudtoes`



>**Hogunk Ventille says:** The Mudtoes were a small clan of ogres. They lived somewhere in the Butcherblock Mountains. They had an insatiable appetite for dwarves. They were finally destroyed by the hand of Trondle Ogrebane.

**You say:** `crushbone orc`



>**Hogunk Ventille says:** The army of the Crushbone orcs is deadly indeed. They are great military strategists. It was a legion of them that brought down the great [Trondle Ogrebane]. Speak with Furtog Ogrebane about the Crushbones. He has need of warriors such as you.

**You say:** `battle of busted skull`



>**Hogunk Ventille says:** The Battle of Busted Skull was fought in the land of the Crushbone orcs.  King Kazon sent the entire Irontoe Brigade to retrieve an ancient artifact from an old dwarven outpost.  The battle was fierce.  At its only a handful of Irontoes made it back.  After that, the Irontoe Brigade survivors left Kaladim for good.  All except Tumpy Irontoe.
end



## Turn-Ins



local text = "Aren't you forgetting something? I instructed you to return with Guard Bundin's Head and his Stormguard axe.";



if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_990.png" alt="" /> <a
                                href="/item/12156" data-url="12156" class="tooltip-link link">Dwarf Head</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_569.png" alt="" /> <a
                                href="/item/5014" data-url="5014" class="tooltip-link link">Rusty Axe</a>) then


>**Hogunk Ventille says:** I shall display this in the guard hall. Let it be a warning to all those who dare to run from battle. As for you, that was splendid work, but next time, remember to wrap decapitated heads in something drip-proof. Those stains will never come out! Oh yes, and here is your reward.


Your faction standing with [Kazon Stormhammer](/faction/274) got better (<span class='text-success'>+2</span>)


Your faction standing with [Storm Guard](/faction/312) got better (<span class='text-success'>+15</span>)


Your faction standing with [Miners Guild 249](/faction/293) got better (<span class='text-success'>+2</span>)


Your faction standing with [Kaladim Merchants](/faction/5025) got better (<span class='text-success'>+3</span>)


Your faction standing with [Craknek Warriors](/faction/232) got worse (<span class='text-danger'>-3</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_590.png" alt="" /> <a
                                href="/item/5027" data-url="5027" class="tooltip-link link">Bronze Long Sword</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_604.png" alt="" /> <a
                                href="/item/5034" data-url="5034" class="tooltip-link link">Bronze Scimitar</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_578.png" alt="" /> <a
                                href="/item/6019" data-url="6019" class="tooltip-link link">Bronze Mace</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_741.png" alt="" /> <a
                                href="/item/6024" data-url="6024" class="tooltip-link link">Bronze Morning Star</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_762.png" alt="" /> <a
                                href="/item/7013" data-url="7013" class="tooltip-link link">Bronze Rapier</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_601.png" alt="" /> <a
                                href="/item/6018" data-url="6018" class="tooltip-link link">Cracked Staff</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_519.png" alt="" /> <a
                                href="/item/5070" data-url="5070" class="tooltip-link link">Tarnished Two Handed Sword</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_568.png" alt="" /> <a
                                href="/item/5071" data-url="5071" class="tooltip-link link">Tarnished Two Handed Battle Axe</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_741.png" alt="" /> <a
                                href="/item/6351" data-url="6351" class="tooltip-link link">Fine Steel Morning Star</a>) (+5000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-16 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**
