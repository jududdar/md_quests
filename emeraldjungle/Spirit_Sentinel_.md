# Spirit Sentinel 



[Spirit Sentinel ](/npc/94013) is a level 1 Wolf Warrior that spawns in [The Emerald Jungle](/zone/94).





## Dialog

**You say:** `is lost`



>**Spirit Sentinel  says:** The mantle was the product of thousands of faithless individuals. Not the single shroud we believed existed. Torsis is now truly cursed for all eternity as a great stain upon the universe. Today is a sad day, indeed. However, some good can still come of this. Your sacrifice and spiritual devotion in this matter have become legendary. You have waited for us at the bottom of the ocean. You have rubbed out a mighty rogue spirit. You have endured the black hole of Torsis and entered the abode of Fear itself to save a child from eternal suffering. It is only fitting that we reward you with our greatest treasure, the [Spear of Fate].

**You say:** `Spear of Fate`



>**Spirit Sentinel  says:** The spear was constructed millennia ago by Thalger, the first human Heyokah. One of the most destructive wasichu of Norrath, Miragul, as he is known, had been traveling the world searching out all known magic. Wherever he went, he discovered and experimented with all forms of dangerous magic. Most of the world cannot even fathom what the Arch Necromancer was capable of. He had haphazardly discovered a way to directly create a mantle of negative spiritual energy similar to what curses Torsis. He himself had willed into existence one of these [black holes].

**You say:** `black hole`



>**Spirit Sentinel  says:** Miragul often retreated to the frigid northlands to experiment in solitude. It was here that he created a black hole.  Unfortunately for the small tribes of men who made the northlands their home, this new black hole threatened not only their livelihood but their entire existence. The mantle was so powerful it not only drained the spiritual energy of everything within its gaze, it also drained the life force as well. The tribes were threatened with complete annihilation. But one [powerful shaman] stepped forward and struck against Miragul's mantle.

**You say:** `powerful shaman`



>**Spirit Sentinel  says:** Thalger had been the first to pass our tests and the timing was lucky indeed. We supplied him with materials needed to construct a weapon that could pierce the very fabric of the [cosmos]. First, was the sharpened shoulder blade of an ancient lion matriarch. Then Thalger found a young sapling for the shaft and shaped it over the course of 45 days using nothing but his fingernails. He then split the top of the flexible shaft, lodged the blade into place and bound them together with the tanned entrails of an ox. Finally, he adorned the spear with the magical feathers of an aviak elder.

**You say:** `cosmos`



>**Spirit Sentinel  says:** Miragul's casting was strong but it was a force brought into existence. This force was positive in nature, the opposite of nothingness. Even though it worked like a void, it was still created by an imposition of will. We figured that if we could rupture the planar boundary and create enough anti-existence or non-matter, the mantle might destroy itself. Thalger volunteered immediately to pierce the mantle as no spirits could even get close to it. In one act of devotion and singular purpose, Thalger rode the wind far above the land and with one colossal arch ripped a [breach] across the planes.

**You say:** `breach`



>**Spirit Sentinel  says:** The tear in the fabric of existence created enough negative material to cancel out Miragul's abomination. Thalger's strike was so perfect that he cut just enough planar material to destroy the mantle and nothing else. Unfortunately, Thalger himself was lost in the process. All that was left was the spear that fell from the heavens to the ground where we recovered it. We have kept it since then and now we wish you to have it. When you strike with it, you must have the same singularity of purpose as did Thalger when he defeated Miragul's mantle. Thank you, Heyokah Soandso.
end



## Turn-Ins




if **Faction** >= Kindly +100 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_865.png" alt="" /> <a
                                href="/item/18456" data-url="18456" class="tooltip-link link">Historic Article</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_865.png" alt="" /> <a
                                href="/item/18457" data-url="18457" class="tooltip-link link">Crusades of the High Scale</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_865.png" alt="" /> <a
                                href="/item/18458" data-url="18458" class="tooltip-link link">Head Housekeepers Log</a>) then 


>**Spirit Sentinel  says:** Hmmm, it appears the queen's disappearance wasn't as random as we thought. It also looks as if this High Scale was having some sort of affair with Neh. We have little but speculation at this point so making it known to Nak'Ashiir would do nothing. Perhaps finding the resting place of the High Scale will show us more in the way of what really happened. We suspect the icon mentioned in this log could now be located in the city's old temple. Find the icon and bring it to Kirn, wherever he is. Tell me what you learn afterwards.


Your faction standing with [Truespirit](/faction/404) got better (<span class='text-success'>+100</span>)

elseif **Faction** >= Warmly +150 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1234.png" alt="" /> <a
                                href="/item/1674" data-url="1674" class="tooltip-link link">Iksar Scale</a>) then 


>*Spirit Sentinel  What is this?  The scale of Rak'Ashiir's father?  Then Rak has repented his mistake?  But why is the mantle still in place?  If Rak has repented, then the mantle should have dissolved since he was the one who initiated its construction.  But is its initiation the key?  How could we have been so blind?  Kirn said Rak'Ashiir had the blood of his people on his hands but that is false. Rak merely pointed to a path that would lead them to destruction.  It was the people who chose to follow. Now all [is lost].*


Your faction standing with [Truespirit](/faction/404) got worse (<span class='text-danger'>-2000</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1187.png" alt="" /> <a
                                href="/item/10651" data-url="10651" class="tooltip-link link">Spear of Fate</a> (+75000 exp)

 

local returned = item_lib.return_items(e.self, e.other, e.trade, false)

if ( returned ) then


>**Spirit Sentinel  says:** You need to prove your dedication to our cause before I can discuss such matters with you.
end
