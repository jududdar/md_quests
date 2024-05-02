# Byzar Bloodforge



## Dialog

**You say:** `hail`



>**Byzar Bloodforge says:** State your business!!  I have no time for chitchat.  Well..  speak up. toad!!  What?!!..  Have you come here to [return goblin beads]?

**You say:** `return goblin beads`



>**Byzar Bloodforge says:** If you wish to return Runnyeye Warbeads you best have at least four of them.  Do not waste my time with any less.  If I am in a good mood I just may reward you with some trash, err..  I mean equipment from our armory.

**You say:** `Zarchoomi`




>**Byzar Bloodforge says:** Do not speak the names of Zarchoomi and Corflunk!!  I have heard enough of those ogres!!  I would pay greatly for their heads!!

**You say:** `take a little trip`



if **Faction** >= Amiable then



>**Byzar Bloodforge says:** Yes.  You will do.  My sister was once engaged to a fellow warrior.  He disgraced her and left her crying at the altar.  I will have his head for such a slap in the face of my family.  His name was Trumpy Irontoe, once a member of the now defunct Irontoe Brigade.  I know not where he went.  Find his whereabouts and return his head to me.  Do so, and I shall make you an honorary member of the Bloodforge Brigade.


elseif **Faction** >= Indifferent then



>**Byzar Bloodforge says:** Prove yourself to the Stormguard and then we shall talk.  Perhaps you may assist Master Canloe and show your worth to us.


else



>**Byzar Bloodforge says:** Your shifty eyes tell me that you are no ally of the Stormguard.


**You say:** `irontoe`



>**Byzar Bloodforge says:** The Irontoe Brigade was formed by Drumpy Irontoe. It was once the finest band of warriors in Kaladim. They were the elite branch of the Stormguard. King Kazon sent them on a mission to the lands of the Crushbone orcs. At the Battle of Busted Skull they met their fate.

**You say:** `tumpy`



>**Byzar Bloodforge says:** If you frequent the pubs, you just may run into Tumpy Irontoe. He was once the brave leader of the Irontoe Brigade. Whatever you do, do not mention the Battle of Busted Skull. I am sure that would bring back some bad memories for him.

**You say:** `trondle`



>**Byzar Bloodforge says:** Trondle Ogrebane is the legendary dwarven warrior who single-handedly exterminated the ogre clan called the [Mudtoes]. He was recently killed in battle. It took an entire legion of Crushbone orcs to bring him down. Furtog is still fuming about that.

**You say:** `mudtoes`



>**Byzar Bloodforge says:** The Mudtoes were a small clan of ogres. They lived somewhere in the Butcherblock Mountains. They had an insatiable appetite for dwarves. They were finally destroyed by the hand of Trondle Ogrebane.

**You say:** `crushbone orc`



>**Byzar Bloodforge says:** The army of the Crushbone orcs is deadly indeed. They are great military strategists. It was a legion of them that brought down the great [Trondle Ogrebane]. Speak with Furtog Ogrebane about the Crushbones. He has need of warriors such as you.

**You say:** `battle of busted skull`



>**Byzar Bloodforge says:** The Battle of Busted Skull was fought in the land of the Crushbone orcs.  King Kazon sent the entire Irontoe Brigade to retrieve an ancient artifact from an old dwarven outpost.  The battle was fierce.  At its only a handful of Irontoes made it back.  After that, the Irontoe Brigade survivors left Kaladim for good.  All except Tumpy Irontoe.
end

## Turn-Ins



local text = "What good is one?! I called for the heads of both Corflunk and Zarchoomi!";



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_848.png" alt="" /> <a
                                href="/item/13931" data-url="13931" class="tooltip-link link">RunnyEye Warbeads</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_848.png" alt="" /> <a
                                href="/item/13931" data-url="13931" class="tooltip-link link">RunnyEye Warbeads</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_848.png" alt="" /> <a
                                href="/item/13931" data-url="13931" class="tooltip-link link">RunnyEye Warbeads</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_848.png" alt="" /> <a
                                href="/item/13931" data-url="13931" class="tooltip-link link">RunnyEye Warbeads</a>) then


>**Byzar Bloodforge says:** You finally have proven yourself a warrior, a slow one!!  Take this reward and ask for nothing else.  You should be proud to defend Kaladim and expect no reward.


Your faction standing with [Storm Guard](/faction/312) got better (<span class='text-success'>+5</span>)


Your faction standing with [Kazon Stormhammer](/faction/274) got better (<span class='text-success'>+1</span>)


Your faction standing with [Miners Guild 249](/faction/293) got better (<span class='text-success'>+1</span>)


Your faction standing with [Merchants of Kaladim](/faction/290) got better (<span class='text-success'>+1</span>)


Your faction standing with [Craknek Warriors](/faction/232) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_640.png" alt="" /> <a
                                href="/item/2113" data-url="2113" class="tooltip-link link">Small Tattered Skullcap</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_771.png" alt="" /> <a
                                href="/item/2114" data-url="2114" class="tooltip-link link">Small Tattered Mask</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_643.png" alt="" /> <a
                                href="/item/2115" data-url="2115" class="tooltip-link link">Small Tattered Gorget</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_632.png" alt="" /> <a
                                href="/item/2116" data-url="2116" class="tooltip-link link">Small Patchwork Tunic</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_668.png" alt="" /> <a
                                href="/item/2117" data-url="2117" class="tooltip-link link">Small Tattered Shoulderpads</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_660.png" alt="" /> <a
                                href="/item/2118" data-url="2118" class="tooltip-link link">Small Patchwork Cloak</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_564.png" alt="" /> <a
                                href="/item/2119" data-url="2119" class="tooltip-link link">Small Tattered Belt</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_634.png" alt="" /> <a
                                href="/item/2120" data-url="2120" class="tooltip-link link">Small Patchwork Sleeves</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_637.png" alt="" /> <a
                                href="/item/2121" data-url="2121" class="tooltip-link link">Small Tattered Wristbands</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_636.png" alt="" /> <a
                                href="/item/2122" data-url="2122" class="tooltip-link link">Small Tattered Gloves</a>) (+1000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-5 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-5 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif **Faction** >= Apprehensive and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_920.png" alt="" /> <a
                                href="/item/13741" data-url="13741" class="tooltip-link link">Ogre Head</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_920.png" alt="" /> <a
                                href="/item/13740" data-url="13740" class="tooltip-link link">Ogre Head</a>) then


>**Byzar Bloodforge says:** I underestimated you.  You are truly a great warrior.  I reward you with a piece of my own Bloodforge armor.  You would be fine Bloodforge Brigade material!  How would you like to [take a little trip] in the name of the Bloodforge Brigade?


Your faction standing with [Storm Guard](/faction/312) got better (<span class='text-success'>+20</span>)


Your faction standing with [Kazon Stormhammer](/faction/274) got better (<span class='text-success'>+3</span>)


Your faction standing with [Miners Guild 249](/faction/293) got better (<span class='text-success'>+3</span>)


Your faction standing with [Merchants of Kaladim](/faction/290) got better (<span class='text-success'>+5</span>)


Your faction standing with [Craknek Warriors](/faction/232) got worse (<span class='text-danger'>-5</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_523.png" alt="" /> <a
                                href="/item/3090" data-url="3090" class="tooltip-link link">Bloodforge Helm</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_538.png" alt="" /> <a
                                href="/item/3091" data-url="3091" class="tooltip-link link">Bloodforge Mail</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_543.png" alt="" /> <a
                                href="/item/3092" data-url="3092" class="tooltip-link link">Bloodforge Armplates</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_620.png" alt="" /> <a
                                href="/item/3093" data-url="3093" class="tooltip-link link">Bloodforge Bracers</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_846.png" alt="" /> <a
                                href="/item/3094" data-url="3094" class="tooltip-link link">Bloodforge Gauntlets</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_845.png" alt="" /> <a
                                href="/item/3095" data-url="3095" class="tooltip-link link">Bloodforge Legplates</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_844.png" alt="" /> <a
                                href="/item/3096" data-url="3096" class="tooltip-link link">Bloodforge Boots</a>) (+1000 exp)

 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_990.png" alt="" /> <a
                                href="/item/12136" data-url="12136" class="tooltip-link link">Dwarf Head</a>) then


>**Byzar Bloodforge says:** Ha!! His death brings me great happiness.  I owe you much.  Take this hammer.  It is the hammer of the Bloodforge Brigade.  May it serve you well.  Now go, so I can enjoy this moment of happiness alone.


Your faction standing with [Storm Guard](/faction/312) got better (<span class='text-success'>+5</span>)


Your faction standing with [Kazon Stormhammer](/faction/274) got better (<span class='text-success'>+1</span>)


Your faction standing with [Miners Guild 249](/faction/293) got better (<span class='text-success'>+1</span>)


Your faction standing with [Merchants of Kaladim](/faction/290) got better (<span class='text-success'>+1</span>)


Your faction standing with [Craknek Warriors](/faction/232) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_567.png" alt="" /> <a
                                href="/item/13314" data-url="13314" class="tooltip-link link">Bloodforge Hammer</a> (+10000 exp)

 

**This NPC *should* return incorrect items given.**
