# Guard Weleth
## Dialog

**You say:** `hail`



>**Guard Weleth says:** Hail, Soandso. My name is Weleth Nagoh. In addition to my patrol, I am in charge of keeping the guardhouse stocked with supplies. I must get back to my duties. Farewell.

**You say:** `nesiff`



>**Guard Weleth says:** Nesiff Tallaherd owns the wooden weapons shop in Merchant's Square in South Qeynos.

**You say:** `arrows`



if **Faction** >= Indifferent +50 then



>**Guard Weleth says:** Oh, thank you! Here is the crate. Make sure [Nesiff] sends me back a new invoice. [Lieutenant Dagarok] would have my head if he found out this happened again!



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_723.png" alt="" /> <a
                                href="/item/13925" data-url="13925" class="tooltip-link link">Crate of Defective Arrows</a>


elseif **Faction** >= Indifferent then



>**Guard Weleth says:** While I do realize you are a loyal citizen, I cannot help you with that... yet.




else



>**Guard Weleth says:** I do not trust or like you, so be on your way, Soandso.





**You say:** `crate`



>**Guard Weleth says:** Oh, we just received a shipment of arrows from [Nesiff] in South Qeynos. The arrows in this box are missing their fletchings and I can't leave my patrol to take them back.

**You say:** `Lieutenant Dagarok`



>**Guard Weleth says:** Lieutenant Dagarok is the officer in charge of all of North Qeynos.  He is difficult to get along with and I [do not trust him].

**You say:** `do not trust him`



if( **Faction is** < Indifferent) then



>**Guard Weleth says:** I don't feel comfortable talking to you about that.



elseif( **Faction is** < Kindly) then



>**Guard Weleth says:** While I do realize you are a loyal citizen, I cannot help you with that... yet.


else



>**Guard Weleth says:** Late one night not long ago, after I was off duty, I witnessed Lieutenant Dagarok and a few others slay someone they claimed was a suspected necromancer. I had met their victim the day before and I know he was an innocent paladin from Freeport. What really shocked me was that Dagarok was bathed in an evil green glow as their victim crumpled to the ground. I don't know who to trust any more!


**You say:** `weapon`



>**Guard Weleth says:** This city has been blessed with the craftsmanship of the Ironforges.  Their weapons are supreme.  Their shop can be found near the Temple of Life in North Qeynos.  You may also try the local warrior guild.

**You say:** `order of the three`



>**Guard Weleth says:** The Order of Three consists of the three positive circles of the arcane known as magic, enchantment and wizardry.  This guild keeps very busy in its hall near the arena.  All in Qeynos respect their powers.

**You say:** `monk guild`



>**Guard Weleth says:** In North Qeynos sits the house of the Silent Fist Clan.  These monks are welcome in Qeynos and often assist in training the Qeynos Guard in hand to hand combat.

**You say:** `bank`



>**Guard Weleth says:** Qeynos Hold in South Qeynos is just across from the arena.  You know, over the bridge behind Firepride's.

**You say:** `port`



>**Guard Weleth says:** The port of Qeynos is located in South Qeynos.  From here one may catch the ship to Erudin.

**You say:** `kane`



>**Guard Weleth says:** Commander Kane Bayle is the commander of all the Qeynos Guard.  He is second only to his brother, Antonius Bayle.  His post is in the guard house at the city gates.  Mind you, do not bother him, he has a bit of a temper.

**You say:** `circle.* unseen hand`



>**Guard Weleth says:** The Circle of the Unseen Hand?  I have heard nothing of them.  Are they some sort of performing magic troupe?

**You say:** `paladin guild`



>**Guard Weleth says:** Within Qeynos are the Knights of Thunder and the Priests of Life.  Both of these orders consist of clerics and paladins and are respected by all.  The Hall of Thunder lies in South Qeynos and the Temple of Life is in North Qeynos.

**You say:** `necromancer guild`



>**Guard Weleth says:** What gibberish are you spouting?  There is not, nor will there ever be, such an organization as that within a hundred miles of Qeynos, not with the Qeynos Guard on patrol.  Next you will be inquiring of a rogue guild!  Really!

**You say:** `ranger guild`




>**Guard Weleth says:** I believe you shall find the Protectors of the Pine and Jaggedpine Treefolk in the hollow of Surefall Glade.


**You say:** `jaggedpine treefolk`



>**Guard Weleth says:** In Surefall Glade there are druids called the Jaggedpine Treefolk.  These men and women often assist our army during times of war.

**You say:** `linarius`



>**Guard Weleth says:** The Qeynos Tower Guards of the hills and plains are commanded by Captain Linarius Graffe.  He often has much to report.  He is posted in a keep which spans a river.  I believe it is in the northern Plains of Karana.

**You say:** `south qeynos`



>**Guard Weleth says:** The passages to North Qeynos can be found near the bard's guild or next to the Clock of Ak'Anon.

**You say:** `inn`




>**Guard Weleth says:** If you need a place to rest, I highly recommend the Lion's Mane Inn and Tavern.  Poor adventurers all huddle together in one of the backrooms of Fish's.

**You say:** `antonius`



>**Guard Weleth says:** Antonius Bayle is the ruler of Qeynos. He is such a great man that they renamed this continent after him. He brought Qeynos to the glory it now is. He formed the mightest army on Norrath, the Qeynos Guard. It is through his guidance that we shall protect all nations of Antonica from any evil threat. He does not venture into the city streets often. He is quite busy.

**You say:** `tillin`



>**Guard Weleth says:** Captain Tillin Brightblade is the commander of the Qeynos City Guard. Extermination of the Sabertooths is his paramount concern. He has recently begun to hire mercenaries to assist in the extermination. If you wish to help out then go and speak with him. He is most often found discussing tactics with Ebon Strongbear at arena.

**You say:** `saber`



>**Guard Weleth says:** What was that you said? You mentioned the Sabertooths of Blackburrow? Those gnolls have caused this city trouble harm for too long. We have yet to force them from Qeynos Hills. I hear rumors of a few merchants who even dare to sell the outland Blackburrow Stout which is brewed by the gnolls. Foolish!! We call upon all citizens to assist in ridding our land of the gnolls. If you wish to join the fight then speak with Captain Tillin.
end

## Turn-Ins




if **Faction** >= Indifferent +50 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_870.png" alt="" /> <a
                                href="/item/18824" data-url="18824" class="tooltip-link link">A Slip of Parchment</a>) then 


>**Guard Weleth says:** Thank you so much for the favor. Please be careful here in Qeynos. I have come to suspect that even some of my fellow guards are not to be trusted - Lieutenant Dagarok, for one.





Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+25</span>)


Your faction standing with [Antonius Bayle](/faction/219) got better (<span class='text-success'>+3</span>)


Your faction standing with [Circle of Unseen Hands](/faction/223) got worse (<span class='text-danger'>-3</span>)


Your faction standing with [Corrupt Qeynos Guards](/faction/230) got worse (<span class='text-danger'>-6</span>)


Your faction standing with [Merchants of Qeynos](/faction/291) got better (<span class='text-success'>+2</span>)


 &#127873; **You receive:** 0 (+250 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-5 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**

## Arrive at Waypoint Script

if(e.wp == 8) then


>**Guard Weleth says:** Argh. Not again. This whole crate needs to be returned!
end
