# Master Raska



[Master Raska](/npc/106098) is a level 61 Iksar GM Monk that spawns in [Cabilis East](/zone/106).



## Dialog

**You say:** `hail`



>**Master Raska says:** Hmmph!! Expect to be a great master such as I? Maybe. You still appear to be a [whiff].

**You say:** `whiff`



>**Master Raska says:** A whiff is the sound of a tail striking air. A whiff is you. Inexperienced. I can help you, if you want to earn the [second shackle].

**You say:** `second shackle`



if **Faction** >= Amiable then



>**Master Raska says:** Then you shall perform the first rite. Take this pack. To the Outlands you will go. You will fill and combine the pack with one of each of the following: goblin scout beads, a large scorpion pincer, a froglok skipper skipping stone, and a sabertooth cub canine. Bring these to me and you shall prove yourself a monk.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_565.png" alt="" /> <a
                                href="/item/17026" data-url="17026" class="tooltip-link link">First Rite Pack</a>


elseif **Faction** >= Indifferent then



>**Master Raska says:** The Swifttail Caste desires further service before I can share this with you.


else



>**Master Raska says:** Leave at once!  I will warn you no longer.  You are no friend to the Swifttail Caste.


**You say:** `shackle.* stone`



if **Faction** >= Amiable then



>**Master Raska says:** Interested in the shackle of stone are we? They are made for monks who have earned their first two shackles and are ready to climb up to the next rung. A monk who feels he is ready to wear the shackle of stone must first perform the [task of cleansing].


elseif **Faction** >= Indifferent then



>**Master Raska says:** The Swifttail Caste desires further service before I can share this with you.


else



>**Master Raska says:** Leave at once!  I will warn you no longer.  You are no friend to the Swifttail Caste.


**You say:** `task.* cleansing`



if **Faction** >= Amiable then



>**Master Raska says:** Go forth to the outer gates and seek out the Iksar bandits. They have refused to bow to the will of the empire and shall pay dearly for their traitorous ways. They often wear bandit masks. If you return with two bandit masks and the shackles of dust and clay then I shall reward you with the shackle of stone.


elseif **Faction** >= Indifferent then



>**Master Raska says:** The Swifttail Caste desires further service before I can share this with you.


else



>**Master Raska says:** Leave at once!  I will warn you no longer.  You are no friend to the Swifttail Caste.


**You say:** `gandan tailfist`



if **Faction** >= Amiable then



>**Master Raska says:** Gandan Tailfist was the commander of a small band of Swifttails which I sent in search of the [Whistling Fists]. That was one season ago. I have heard that the Iksar Bandits have information regarding him. If you have a clue as to his whereabouts, hand it over. Unless it is merely half a note. That would do you no good. I require the full note.


elseif **Faction** >= Indifferent then



>**Master Raska says:** The Swifttail Caste desires further service before I can share this with you.


else



>**Master Raska says:** Leave at once!  I will warn you no longer.  You are no friend to the Swifttail Caste.


**You say:** `whistling fist`



if **Faction** >= Amiable then



>**Master Raska says:** The legendary Whistling Fists are said to work only on the hands of a monk. They are said to bestow great power on the wielder.  It is written that they were crafted by the gods who devised the disciplines of this caste.


elseif **Faction** >= Indifferent then



>**Master Raska says:** The Swifttail Caste desires further service before I can share this with you.


else



>**Master Raska says:** Leave at once!  I will warn you no longer.  You are no friend to the Swifttail Caste.

end



## Turn-Ins



local text1 = "You will get nothing until I hold two bandit masks and the shackles of dust and clay.";



if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_565.png" alt="" /> <a
                                href="/item/12427" data-url="12427" class="tooltip-link link">Full First Rite Pack</a>) then


>**Master Raska says:** You have succeeded, young Soandso! You have proven yourself a skilled monk. You will now wear the shackle of clay. You will now be required to increase your intensity of training in hopes that you may soon be able to earn your [shackle of stone].


Your faction standing with [Swift Tails](/faction/444) got better (<span class='text-success'>+10</span>)


Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+2</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_637.png" alt="" /> <a
                                href="/item/4191" data-url="4191" class="tooltip-link link">Shackle of Clay</a> (+5000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0-10 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_637.png" alt="" /> <a
                                href="/item/4190" data-url="4190" class="tooltip-link link">Shackle of Dust</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_637.png" alt="" /> <a
                                href="/item/4191" data-url="4191" class="tooltip-link link">Shackle of Clay</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_938.png" alt="" /> <a
                                href="/item/12428" data-url="12428" class="tooltip-link link">Iksar Bandit Mask</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_938.png" alt="" /> <a
                                href="/item/12428" data-url="12428" class="tooltip-link link">Iksar Bandit Mask</a>) then


>**Master Raska says:** You have done supremely, Soandso. You have earned your shackle of stone. Mistress Niska will now help you on your way to earning the shackle of rock. May the elements guide you to the next rung.


Your faction standing with [Swift Tails](/faction/444) got better (<span class='text-success'>+10</span>)


Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+2</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1235.png" alt="" /> <a
                                href="/item/4192" data-url="4192" class="tooltip-link link">Shackle of Stone</a> (+10000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0-10 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_789.png" alt="" /> <a
                                href="/item/18469" data-url="18469" class="tooltip-link link">Faded White Tome</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1132.png" alt="" /> <a
                                href="/item/12822" data-url="12822" class="tooltip-link link">A Mechanical Iksar Tail</a>) then


>*Master Raska smiles at your dedication to Cazic Thule and hands you a small gem.*


Your faction standing with [Swift Tails](/faction/444) got better (<span class='text-success'>+5</span>)


Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/7881" data-url="7881" class="tooltip-link link">Mark of Clarity</a> (+20000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_789.png" alt="" /> <a
                                href="/item/18470" data-url="18470" class="tooltip-link link">Pure White Tome</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_865.png" alt="" /> <a
                                href="/item/22924" data-url="22924" class="tooltip-link link">Sealed Journal</a>) then


>*Master Raska smiles at your dedication to Cazic Thule and hands you a small gem.*


Your faction standing with [Swift Tails](/faction/444) got better (<span class='text-success'>+5</span>)


Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/7881" data-url="7881" class="tooltip-link link">Mark of Clarity</a> (+20000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_869.png" alt="" /> <a
                                href="/item/18232" data-url="18232" class="tooltip-link link">First Half of Torn Note</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_869.png" alt="" /> <a
                                href="/item/18233" data-url="18233" class="tooltip-link link">Second Half of Torn Note</a>) then


>**Master Raska says:** This is all that was ever found of Gandan Tailfist. I wish you luck in your quest. May you fare better than he did.


Your faction standing with [Swift Tails](/faction/444) got better (<span class='text-success'>+5</span>)


Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_751.png" alt="" /> <a
                                href="/item/12429" data-url="12429" class="tooltip-link link">Ancient Thin Flute</a> (+5000 exp)

 

**This NPC *should* return incorrect items given.**






