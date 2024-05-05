# Larsk Juton



[Larsk Juton](/npc/3024) is a level 61 Human GM Ranger that spawns in [Surefall Glade](/zone/3).





## Dialog

**You say:** `hail`



>**Larsk Juton says:** Hail, Adventurer! I hope you are enjoying your time in Surefall Glade. You must be careful when leaving the Jaggedpine. There have been many report of [Sabertooths] attacking travelers.

**You say:** `sabertooth`



>**Larsk Juton says:** The gnolls of Blackburrow are called Sabertooths. They have been seen in force on a regular basis. They are surely up to something. We have even heard rumors of a [pact] between Qeynos merchants and the dogs.

**You say:** `pact`



>**Larsk Juton says:** Sources have come forward to tell of a pact between a merchant of Qeynos and the Sabertooths. It all has to do with blades and brew. We hear that a meeting will occur soon, somewhere in the Qeynos Hills at night. Do not fear, we shall find a brave ranger to [halt this meeting].

**You say:** `halt.* meeting`



if **Faction** >= Amiable then



>**Larsk Juton says:** Very good of you. Stop this meeting by killing the gnoll in Qeynos Hills. We hear that he shall be there in the late evening, and that his name is Furgoot or Furgy, something like that. Find him and kill him. I want his head. And if you should find any evidence of who the merchant is, be sure to hand it over to me.


elseif **Faction** >= Indifferent then



>**Larsk Juton says:** Well, I, and the Protectors of Jaggedpine, have noticed your helpful deeds so far...  just keep up the good work, and you will soon be trusted enough to handle such important matters.




else



>**Larsk Juton says:** You dare show your face around here, as bad as your reputation is with the Protectors of Jaggedpine? Begone, enemy of the forest!




**You say:** `assist.* extermination of.* gnoll brewer`



if **Faction** >= Amiable then



>**Larsk Juton says:** Within the bowels of Blackburrow, our scouts have reported seeing the gnoll brewers.  You will go and brave the lair of the dogs and slay these brewers in order to cease the flow of Blackburrow Stout.  During your mission, should you find any Blackburrow casks, you must return them to me.  When you have recovered three of these casks, I shall award you the [Cloak of Jaggedpine].


elseif **Faction** >= Indifferent then



>**Larsk Juton says:** Well, I, and the Protectors of Jaggedpine, have noticed your helpful deeds so far...  just keep up the good work, and you will soon be trusted enough to handle such important matters.




else



>**Larsk Juton says:** You dare show your face around here, as bad as your reputation is with the Protectors of Jaggedpine? Begone, enemy of the forest!


**You say:** `blackburrow stout`



>**Larsk Juton says:** Blackburrow Stout is a grog created by the gnolls of Blackburrow.  It is no surprise that the grog is illegal in Qeynos.  Even so, I hear there are some barkeeps who dare sell it.

**You say:** `Cloak of Jaggedpine`



>**Larsk Juton says:** The Cloak of Jaggedpine was made for those loyal to the ways of the forest.  It is enchanted to increase one's dexterity.  It is awarded to those who have aided in our cause to rid the land of those vile dogs called the Sabertooths.  Should you earn one, be sure to hold onto it - you never know when we may alter the enchantments placed upon the cloak.

**You say:** `leader`



>**Larsk Juton says:** The land of Surefall Glade is ruled by no single hand other than Tunare, but if guidance is what you seek, I would suggest you speak with Te\`Anara.  She is the head of the Jaggedpine Treefolk.  Otherwise, you could speak with Hager Sureshot of the Protectors of the Pine.

**You say:** `poacher`



>**Larsk Juton says:** Poachers have been plaguing our land.  We do our best to stop them.  If you wish to join the fight, seek the masters of the Protectors of the Pine.

**You say:** `mammoth`



>**Larsk Juton says:** That information is best kept secret.

**You say:** `druid guild`



>**Larsk Juton says:** The Jaggedpine Treefolk are the local druids.  The masters can be found here within the great tree.

**You say:** `forge`



>**Larsk Juton says:** We have nothing like that here in Surefall Glade.  You must venture to Qeynos.

**You say:** `armor`



>**Larsk Juton says:** Oftentimes you can find a traveling merchant in one of the nearby houses.  Other than that you would have to travel to Qeynos.

**You say:** `qeynos`



>**Larsk Juton says:** The great city of Qeynos can be found by walking along the path outside of Surefall Glade.  Many of our rangers and druids serve alongside the Qeynos Guard when the need arises.

**You say:** `bank`



>**Larsk Juton says:** There is no need for a vault among our people.  You could try the Qeynos Hold in Qeynos.

**You say:** `talym`



>**Larsk Juton says:** Talym Shoontar is a wanted man.  He is a very infamous poacher.  Hager Sureshot has placed a bounty upon his head.

**You say:** `chanda`



>**Larsk Juton says:** The entire Miller family are nothing more than scum.  It is they who entice poachers to continue with their slaughter so they can profit from the skins of the wildlife.


**You say:** `tunarbos`



>**Larsk Juton says:** Long ago, centuries before the Combine Era even, there grew a great tree upon Norrath.  It stretched to the stars and was as wide as the span of Erud's Crossing.  From the roots of this tree sprung all the woodlands of Norrath.  An unknown force struck it down.  Some say it was the great dragon, Veeshan!  Whatever the force, the Great Tunarbos was shattered.  Lost forever.  Now the wood chips lie scattered across the face of Norrath.  To hold a shard of the Great Tunarbos is to hold the hand of Tunare.
end



## Turn-Ins



local text = "Good work, but I must see at least three Blackburrow casks before I can reward you with the [Cloak of Jaggedpine].";


if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_744.png" alt="" /> <a
                                href="/item/13309" data-url="13309" class="tooltip-link link">Gnoll Head</a>) then


>**Larsk Juton says:** So, I see you rid the hills of the beast. Good work! I have a reward for you. I hope it will be usefull. I am afraid this gnoll's death will not halt the alliance between the two. I shall require your services to [assist in the extermination of the gnoll brewers].





Your faction standing with [Protectors of Pine](/faction/302) got better (<span class='text-success'>+25</span>)


Your faction standing with [Jaggedpine Treefolk](/faction/272) got better (<span class='text-success'>+6</span>)


Your faction standing with [Sabertooths of Blackburrow](/faction/306) got worse (<span class='text-danger'>-3</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_640.png" alt="" /> <a
                                href="/item/2137" data-url="2137" class="tooltip-link link">Raw-hide Skullcap</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_632.png" alt="" /> <a
                                href="/item/2140" data-url="2140" class="tooltip-link link">Raw-hide Tunic</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_542.png" alt="" /> <a
                                href="/item/9006" data-url="9006" class="tooltip-link link">Wooden Shield</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_605.png" alt="" /> <a
                                href="/item/5033" data-url="5033" class="tooltip-link link">Bronze Broad Sword</a>) (+20000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-5 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-5 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-5 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_979.png" alt="" /> <a
                                href="/item/17970" data-url="17970" class="tooltip-link link">Blackburrow Cask</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_979.png" alt="" /> <a
                                href="/item/17970" data-url="17970" class="tooltip-link link">Blackburrow Cask</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_979.png" alt="" /> <a
                                href="/item/17970" data-url="17970" class="tooltip-link link">Blackburrow Cask</a>) then


>**Larsk Juton says:** Excellent!  Ridding the area of those foul beasts will certainly slow down whatever it is they are planning.  Here is the Cloak of Jaggedpine.  You should keep this, for you never know when we may decide to alter the enchantments on it.


Your faction standing with [Protectors of Pine](/faction/302) got better (<span class='text-success'>+20</span>)


Your faction standing with [Jaggedpine Treefolk](/faction/272) got better (<span class='text-success'>+5</span>)


Your faction standing with [Sabertooths of Blackburrow](/faction/306) got worse (<span class='text-danger'>-3</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+5</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_663.png" alt="" /> <a
                                href="/item/2915" data-url="2915" class="tooltip-link link">Cloak of Jaggedpine</a> (+1000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-5 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-5 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-5 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif **Faction** >= Apprehensive and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18811" data-url="18811" class="tooltip-link link">A tattered note</a>) then


>**Larsk Juton says:** Fine Work, Soandso. Hmmm. It seems this needs taking care of. Take this note to the Captain of the City Guard in Qeynos. His name is Captain Tillin. He will have to attend to this matter. Also.. Let me see the gnoll\'s head. I must know you killed him. Be safe, my friend. I am sure that whoever this McNeal is, he was simply a lackey. Whoever he works for is most likely going to be looking for you. Watch your back in Qeynos.







Your faction standing with [Protectors of Pine](/faction/302) got better (<span class='text-success'>+5</span>)


Your faction standing with [Jaggedpine Treefolk](/faction/272) got better (<span class='text-success'>+1</span>)


Your faction standing with [Sabertooths of Blackburrow](/faction/306) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18815" data-url="18815" class="tooltip-link link">A tattered note</a> (+5000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-5 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-5 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-5 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**
;