# Gillarian Naelev



[Gillarian Naelev](/npc/3025) is a level 61 Human GM Ranger that spawns in [Surefall Glade](/zone/3).



## Dialog

**You say:** `hail`



>**Gillarian Naelev says:** Welcome, friend. Welcome to Surefall Glade. I need not remind you about [poaching], I hope

**You say:** `poaching`



>**Gillarian Naelev says:** Poaching is illegal. We here are the Protectors of the Pine, rangers sworn to protect our land and all its inhabitants. This includes the wildlife. We spend a lot of time hunting poachers. If you want to [join the hunt], just let me know.

**You say:** `join the hunt`



if **Faction** >= Indifferent then 



>**Gillarian Naelev says:** Very good, friend. Be on the lookout for poachers in Surefall Glade or Qeynos Hills, especially in the nearby caves. The poachers are not always human. Often times we find ourselves a Blackburrow gnoll or two. Bring me back their heads. Let's see how they look mounted above the mantle! Be on your way, then.



else



>**Gillarian Naelev says:** You dare show your face around here, as bad as your reputation is with the Protectors of Jaggedpine? Begone, enemy of the forest!




**You say:** `master poacher`



>**Gillarian Naelev says:** 'The master poacher is Talym Shoontar. If you wish to collect the bounty on this vile man, be sure to speak with our leader, Hager Sureshot. No doubt you will find him practicing his skills at the archery range.

**You say:** `leader`



>**Gillarian Naelev says:** The land of Surefall Glade is ruled by no single hand other than Tunare, but if guidance is what you seek, I would suggest you speak with Te\`Anara.  She is the head of the Jaggedpine Treefolk.  Otherwise, you could speak with Hager Sureshot of the Protectors of the Pine.

**You say:** `mammoth`



>**Gillarian Naelev says:** That information is best kept secret.

**You say:** `druid guild`



>**Gillarian Naelev says:** The Jaggedpine Treefolk are the local druids.  The masters can be found here within the great tree.

**You say:** `forge`



>**Gillarian Naelev says:** We have nothing like that here in Surefall Glade.  You must venture to Qeynos.

**You say:** `armor`



>**Gillarian Naelev says:** Oftentimes you can find a traveling merchant in one of the nearby houses.  Other than that you would have to travel to Qeynos.

**You say:** `qeynos`



>**Gillarian Naelev says:** The great city of Qeynos can be found by walking along the path outside of Surefall Glade.  Many of our rangers and druids serve alongside the Qeynos Guard when the need arises.

**You say:** `bank`



>**Gillarian Naelev says:** There is no need for a vault among our people.  You could try the Qeynos Hold in Qeynos.

**You say:** `chanda`



>**Gillarian Naelev says:** The entire Miller family are nothing more than scum.  It is they who entice poachers to continue with their slaughter so they can profit from the skins of the wildlife.


**You say:** `tunarbos`



>**Gillarian Naelev says:** Long ago, centuries before the Combine Era even, there grew a great tree upon Norrath.  It stretched to the stars and was as wide as the span of Erud's Crossing.  From the roots of this tree sprung all the woodlands of Norrath.  An unknown force struck it down.  Some say it was the great dragon, Veeshan!  Whatever the force, the Great Tunarbos was shattered.  Lost forever.  Now the wood chips lie scattered across the face of Norrath.  To hold a shard of the Great Tunarbos is to hold the hand of Tunare.
end



## Turn-Ins




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_744.png" alt="" /> <a
                                href="/item/13813" data-url="13813" class="tooltip-link link">Gnoll Head</a>) then 


>**Gillarian Naelev says:** Fantastic work!! Hager will be pleased. Not only do we rid ourself of a poacher, but we rid the land of these destructive gnolls. Our fletchers crafted this for me... Please take it as thanks.


Your faction standing with [Protectors of Pine](/faction/302) got better (<span class='text-success'>+25</span>)


Your faction standing with [Jaggedpine Treefolk](/faction/272) got better (<span class='text-success'>+6</span>)


Your faction standing with [Sabertooths of Blackburrow](/faction/306) got worse (<span class='text-danger'>-3</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+6</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_597.png" alt="" /> <a
                                href="/item/8803" data-url="8803" class="tooltip-link link">Rough Elm Recurve Bow</a> (+6000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 2 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_982.png" alt="" /> <a
                                href="/item/13825" data-url="13825" class="tooltip-link link">Poacher's Head</a>) then 


>**Gillarian Naelev says:** Your deeds are great indeed. We shall cleanse our land of these poachers once and for all. A report has surfaced of a [master poacher].


Your faction standing with [Protectors of Pine](/faction/302) got better (<span class='text-success'>+15</span>)


Your faction standing with [Jaggedpine Treefolk](/faction/272) got better (<span class='text-success'>+3</span>)


Your faction standing with [Sabertooths of Blackburrow](/faction/306) got worse (<span class='text-danger'>-2</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+3</span>)


 &#127873; **You receive:** 0 (+6000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 2 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**
;