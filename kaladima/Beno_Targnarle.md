# Beno Targnarle



[Beno Targnarle](/npc/60022) is a level 61 Dwarf GM Warrior that spawns in [South Kaladim](/zone/60).



## Dialog

**You say:** `hail`



>**Beno Targnarle says:** Step forth, young Soandso! I heard that you have come of age! The spirit of adventure has entered your body. That is good. Go and speak with the others. They shall help you. I am afraid I have no time to spend conversing. There is much I have to [ponder].

**You say:** `ponder`



if **Faction** >= Amiable then



>**Beno Targnarle says:** Must you know everyone's business? Hmm.. Maybe you can be of assistance. You see, I have been instructed by Furtog to tend to a matter of extreme urgency, which is keeping me from clearing the mines of rats. Will you assist and [exterminate the rats]?


elseif **Faction** >= Indifferent then



>**Beno Targnarle says:** Prove yourself to the Stormguard and then we shall talk.  Perhaps you may assist Master Canloe and show your worth to us.


else



>**Beno Targnarle says:** Your shifty eyes tell me that you are no ally of the Stormguard.


**You say:** `exterminate`



if **Faction** >= Amiable then



>**Beno Targnarle says:** Very good! I shall reward you for every four giant rat pelts returned to me. And be on the lookout for a [metal rat]!


elseif **Faction** >= Indifferent then



>**Beno Targnarle says:** Prove yourself to the Stormguard and then we shall talk.  Perhaps you may assist Master Canloe and show your worth to us.


else



>**Beno Targnarle says:** Your shifty eyes tell me that you are no ally of the Stormguard.


**You say:** `metal`



if **Faction** >= Amiable then



>**Beno Targnarle says:** I cannot tell you how many reports I have heard of metal rats in Kaladim. I first thought it was a vision obtained from having too many Tumpy Tonics, but Furtog himself is said to have seen them. If you ever catch sight of the little metal beast, give chase!! Return its metal carcass to me and I shall reward you.


elseif **Faction** >= Indifferent then



>**Beno Targnarle says:** Prove yourself to the Stormguard and then we shall talk.  Perhaps you may assist Master Canloe and show your worth to us.


else



>**Beno Targnarle says:** Your shifty eyes tell me that you are no ally of the Stormguard.


**You say:** `matter`



if **Faction** >= Amiable then



>**Beno Targnarle says:** I am apprehensive about sending one who is so young out into the world, but I have a good feeling about you, Soandso. Someone has stolen the [Eye of Stormhammer]. You must journey to Antonica and go to a place called Highpass Hold. The rogue who has it is locked up in the prison. We have arranged for his extradition to Kaladim. Please give the jail clerk this note of release.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/18935" data-url="18935" class="tooltip-link link">A Sealed Note</a>


elseif **Faction** >= Indifferent then



>**Beno Targnarle says:** Prove yourself to the Stormguard and then we shall talk.  Perhaps you may assist Master Canloe and show your worth to us.


else



>**Beno Targnarle says:** Your shifty eyes tell me that you are no ally of the Stormguard.


**You say:** `eye`



if **Faction** >= Indifferent then



>**Beno Targnarle says:** The great statue of Kazon Stormhammer was once encrusted with two great gems from the mines of Butcherblock. So big were they that it took the magic of the high elves to assist us in lifting them to the statue's face. In the year 2995, somehow, someone stole one of the eyes. We decided to keep the remaining eye in the vault. Now, even that has been stolen from us! Only the most trusted warriors may be involved in this [important Stormguard matter].


else



>**Beno Targnarle says:** Your shifty eyes tell me that you are no ally of the Stormguard.


**You say:** `doran`



if **Faction** >= Indifferent then



>**Beno Targnarle says:** Doran resides on an island in the Ocean of Tears. The island is filled with beautiful maidens. I could think of worse places to live.


else



>**Beno Targnarle says:** Your shifty eyes tell me that you are no ally of the Stormguard.


**You say:** `irontoe`



>**Beno Targnarle says:** The Irontoe Brigade was formed by Drumpy Irontoe. It was once the finest band of warriors in Kaladim. They were the elite branch of the Stormguard. King Kazon sent them on a mission to the lands of the Crushbone orcs. At the Battle of Busted Skull they met their fate.

**You say:** `tumpy`



>**Beno Targnarle says:** If you frequent the pubs, you just may run into Tumpy Irontoe. He was once the brave leader of the Irontoe Brigade. Whatever you do, do not mention the Battle of Busted Skull. I am sure that would bring back some bad memories for him.

**You say:** `trondle`



>**Beno Targnarle says:** Trondle Ogrebane is the legendary dwarven warrior who single-handedly exterminated the ogre clan called the [Mudtoes]. He was recently killed in battle. It took an entire legion of Crushbone orcs to bring him down. Furtog is still fuming about that.

**You say:** `mudtoes`



>**Beno Targnarle says:** The Mudtoes were a small clan of ogres. They lived somewhere in the Butcherblock Mountains. They had an insatiable appetite for dwarves. They were finally destroyed by the hand of Trondle Ogrebane.

**You say:** `crushbone orc`



>**Beno Targnarle says:** The army of the Crushbone orcs is deadly indeed. They are great military strategists. It was a legion of them that brought down the great [Trondle Ogrebane]. Speak with Furtog Ogrebane about the Crushbones. He has need of warriors such as you.

**You say:** `battle of busted skull`



>**Beno Targnarle says:** The Battle of Busted Skull was fought in the land of the Crushbone orcs.  King Kazon sent the entire Irontoe Brigade to retrieve an ancient artifact from an old dwarven outpost.  The battle was fierce.  At its only a handful of Irontoes made it back.  After that, the Irontoe Brigade survivors left Kaladim for good.  All except Tumpy Irontoe.
end



## Turn-Ins



local temphandins = 0;

local text = "Good work, but I require four giant rat pelts.";


if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_554.png" alt="" /> <a
                                href="/item/13054" data-url="13054" class="tooltip-link link">Giant Rat Pelt</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_554.png" alt="" /> <a
                                href="/item/13054" data-url="13054" class="tooltip-link link">Giant Rat Pelt</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_554.png" alt="" /> <a
                                href="/item/13054" data-url="13054" class="tooltip-link link">Giant Rat Pelt</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_554.png" alt="" /> <a
                                href="/item/13054" data-url="13054" class="tooltip-link link">Giant Rat Pelt</a>) then 


>**Beno Targnarle says:** Great work, young one! We shall soon rid our mines of these pests. Keep a lookout for that [metal rat]. Here is a small reward for such fine work. Soon, you shall be know as Kaladim's resident exterminator.


Your faction standing with [Storm Guard](/faction/312) got better (<span class='text-success'>+10</span>)


Your faction standing with [Kazon Stormhammer](/faction/274) got better (<span class='text-success'>+1</span>)


Your faction standing with [Miners Guild 249](/faction/293) got better (<span class='text-success'>+1</span>)


Your faction standing with [Merchants of Kaladim](/faction/290) got better (<span class='text-success'>+2</span>)


Your faction standing with [Craknek Warriors](/faction/232) got worse (<span class='text-danger'>-2</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_703.png" alt="" /> <a
                                href="/item/13036" data-url="13036" class="tooltip-link link">Dwarven Ale</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_841.png" alt="" /> <a
                                href="/item/1051" data-url="1051" class="tooltip-link link">Rat Pelt Cape</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_684.png" alt="" /> <a
                                href="/item/13003" data-url="13003" class="tooltip-link link">Small Lantern</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_547.png" alt="" /> <a
                                href="/item/13002" data-url="13002" class="tooltip-link link">Torch</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_944.png" alt="" /> <a
                                href="/item/10015" data-url="10015" class="tooltip-link link">Malachite</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_812.png" alt="" /> <a
                                href="/item/13009" data-url="13009" class="tooltip-link link">Bandages</a>) (+4200 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-5 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1031.png" alt="" /> <a
                                href="/item/13282" data-url="13282" class="tooltip-link link">Scrap Metal</a>) then 


>**Beno Targnarle says:** I thank you, my friend. I was to destroy this metal monster months ago. I could never find him. Please accept this reward for such good service. Oh yes.. And take this card to a man named [Doran Vargnus]. He is a fine blacksmith. I am sure he will reward you with one of his finest suits of armor. Perhaps you may now assist in an [important Stormguard matter].


Your faction standing with [Storm Guard](/faction/312) got better (<span class='text-success'>+20</span>)


Your faction standing with [Kazon Stormhammer](/faction/274) got better (<span class='text-success'>+5</span>)


Your faction standing with [Miners Guild 249](/faction/293) got better (<span class='text-success'>+3</span>)


Your faction standing with [Merchants of Kaladim](/faction/290) got better (<span class='text-success'>+5</span>)


Your faction standing with [Craknek Warriors](/faction/232) got worse (<span class='text-danger'>-5</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_654.png" alt="" /> <a
                                href="/item/13995" data-url="13995" class="tooltip-link link">Knight</a> (+5000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_958.png" alt="" /> <a
                                href="/item/13321" data-url="13321" class="tooltip-link link">Eye of Stormhammer</a>) then 





>**Beno Targnarle says:** You've found it! I'm glad you managed to hunt down and return the stolen eye for us, Soandso. Such effort requires a similar reward so take this and use it well.


Your faction standing with [Storm Guard](/faction/312) got better (<span class='text-success'>+20</span>)


Your faction standing with [Kazon Stormhammer](/faction/274) got better (<span class='text-success'>+5</span>)


Your faction standing with [Miners Guild 249](/faction/293) got better (<span class='text-success'>+3</span>)


Your faction standing with [Merchants of Kaladim](/faction/290) got better (<span class='text-success'>+5</span>)


Your faction standing with [Craknek Warriors](/faction/232) got worse (<span class='text-danger'>-5</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_568.png" alt="" /> <a
                                href="/item/5415" data-url="5415" class="tooltip-link link">Avenger Battle Axe</a> (+5000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-5 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**
