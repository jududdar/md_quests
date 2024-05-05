# Arch Duke Xog



[Arch Duke Xog](/npc/106109) is a level 61 Iksar GM Shadow Knight that spawns in [Cabilis East](/zone/106).



## Dialog

**You say:** `hail`



>**Arch Duke Xog says:** These are the sacred unholy grounds of the Crusaders of Greenmist and the Scaled Mystics. If you do not belong to us, you must leave this temple at once or learn great suffering in the name of Cazic-Thule.

**You say:** `greenmist`





>*Arch Duke Xog appears surprised at your words. 'You know of Greenmist? The Unholy Khukri of Rile? We once had knowledge of this weapon, but when our great cities were destroyed in 1056 A.G., so, too, were all the great libraries. We lost all records. An explorer named [Argest] claimed to have found one library still intact. Pure babble.'*

**You say:** `who is argest`






>**Arch Duke Xog says:** Once a Lord of Pain, Argest is now a great explorer. No lizard has seen more of Kunark than he. He returned one season ago to tell tales of an [ancient library]. He said that he believed that there he would find a tome which would reveal the location of the ancient crusader weapon, Greenmist.

**You say:** `ancient`



>**Arch Duke Xog says:** There are many ancient libraries yet to be discovered. Our once great cities have been decimated, if not by our foes, then by nature itself. Within the outlands are many ruins which have yet to reveal themselves. We look forward to the discovery of these ruins by such explorers as Lord Argest the Great. If only we knew [where] he was...

**You say:** `where is argest`






>*Arch Duke Xog becomes despondent at your question. 'Alas, our chance of locating Greenmist is lost as long as Argest remains missing. Reports have come in from the Legion's deep range patrols that he may be in the Frontier Mountain range. At least, that is where the patrol captain found Argest's walking staff. He might have been captured, killed or even digested!!'*

**You say:** `strange iksar`



>**Arch Duke Xog says:** Yes, he was dressed in rags and hadn't eaten in days. He rambled on about seemingly nothing, obviously he had lost his mind at some point. The guards brought him in because he told them he had valuable information concerning a captured Crusader. According to the mad man, our missing knight was captured by a group of cultists that follow a false god. The cultists intend on converting him apparently. Your [test] will concern Geanik.

**You say:** `test`



>**Arch Duke Xog says:** Learning Righteousness is learning to listen to one's own heart. At all times our Lord of Fear speaks to us. Our heart is through which he speaks. If we are pure in action and undistracted in mind we can hear the very words of our Father. Your test will be to find our lost Crusader. When you find him you must listen, and act based on what you hear. If your actions are Righteous, I will give you my reference. Bring me proof of your action and two sapphires.
end



## Turn-Ins



local text1 = "Where is the rest, maggot?! I said the traitor's head and two star rubies!";

local text2 = "Where is the rest, maggot?! I said proof of your action and two sapphires!";


local text3 = "A true crusader would have brought to me what I requested. The Hero Khukri and the Tome of Vok Na Zov.";




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18205" data-url="18205" class="tooltip-link link">Guild Summons</a>) then 






>**Arch Duke Xog says:** Welcome into our brotherhood. Know you that our way is the way of pain. Do as we say and you shall climb the rungs of knighthood. Listen well to the Lords of Pain within this temple and follow the words of the hierophants, for Cazic-Thule speaks to us through them. Take this khukri. It is the chosen weapon of the Crusaders and can deliver great pain unto our foes. Go now and learn our ways. Seek out Lord Gikzic.


Your faction standing with [Crusaders of Greenmist](/faction/442) got better (<span class='text-success'>+100</span>)



Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+25</span>)






 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1174.png" alt="" /> <a
                                href="/item/5120" data-url="5120" class="tooltip-link link">Pawn's Khukri</a> (+200 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-3 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_647.png' width='14' height='14'/> 


elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18051" data-url="18051" class="tooltip-link link">Stupendous Tome</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1184.png" alt="" /> <a
                                href="/item/5126" data-url="5126" class="tooltip-link link">Hero's Khukri</a>) then 


>**Arch Duke Xog says:** A legible tome of the scrolls of Vok Na Zov! What a find this is!! May the unholy curses of Cazic flow through you. Please accept the weapon of a Lord of Pain. To abandon it is to abandon our ways and earn yourself the hatred of our order.


Your faction standing with [Crusaders of Greenmist](/faction/442) got better (<span class='text-success'>+10</span>)


Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+2</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1184.png" alt="" /> <a
                                href="/item/5128" data-url="5128" class="tooltip-link link">Lord of Pain's Khukri</a> (+25000 exp)

**You receive coin:** 1-8 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1003.png" alt="" /> <a
                                href="/item/14807" data-url="14807" class="tooltip-link link">Traitors Heart</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_963.png" alt="" /> <a
                                href="/item/10034" data-url="10034" class="tooltip-link link">Sapphire</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_963.png" alt="" /> <a
                                href="/item/10034" data-url="10034" class="tooltip-link link">Sapphire</a>) then


>**Arch Duke Xog says:** Thanks for resolving this issue. Here is your reward


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_862.png" alt="" /> <a
                                href="/item/14808" data-url="14808" class="tooltip-link link">Xog's Reference: Bracer</a> (+10000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1208.png" alt="" /> <a
                                href="/item/14806" data-url="14806" class="tooltip-link link">Head of Blackhand</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_961.png" alt="" /> <a
                                href="/item/10032" data-url="10032" class="tooltip-link link">Star Ruby</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_961.png" alt="" /> <a
                                href="/item/10032" data-url="10032" class="tooltip-link link">Star Ruby</a>) then


>**Arch Duke Xog says:** Well done, Soandso.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_862.png" alt="" /> <a
                                href="/item/14809" data-url="14809" class="tooltip-link link">Xog's Reference: Gauntlet</a> (+10000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/14814" data-url="14814" class="tooltip-link link">Greenmist Icon</a>) then


>*Arch Duke Xog takes the icon and stares at it. His face twists into a look of disdain and he suddenly throws the icon off the balcony. It lands in the water some distance away. Without even a glance at you he says in disgust, 'You're an idiot, Soandso. You fit your profession well. Leave my sight.'*


Your faction standing with [Crusaders of Greenmist](/faction/442) got worse (<span class='text-danger'>-25</span>)


Your faction standing with [Legion of Cabilis](/faction/441) got worse (<span class='text-danger'>-6</span>)

**This NPC *should* return incorrect items given.**





