# Rihtur Fullome
## Dialog

**You say:** `hail`



if **Faction** >= Indifferent then 



>**Rihtur Fullome says:** Hail, Soandso! I hope the trek into our shrine has not scarred you in any way. Our defenses have been increased lately. Many of the citizens have heard rumors about our shrine. I say it is all due to that [soldier].


else



>**Rihtur Fullome says:** The lair of the Bloodsabers is no place for you...  begone, or be dead!


**You say:** `soldier`



if **Faction** >= Indifferent then



>**Rihtur Fullome says:** The soldier I refer to is Commander Kane Bayle. The supreme officer himself. Don't get me wrong. I trust Kane. He has quite a black heart. I just don't trust that girl, [Nerissa].


else



>**Rihtur Fullome says:** The lair of the Bloodsabers is no place for you...  begone, or be dead!


**You say:** `nerissa`



if **Faction** >= Indifferent then



>**Rihtur Fullome says:** Nerissa Clothspinner. Her sister was a good friend of Kane's. When she left Qeynos to venture into the world, she asked Kane to watch over the girl. Now Kane tries to hide from this child the fact that he is allied with our church. I do not think he has hidden it well. I have told the others. but they do not believe me. I do not care. I have my own [plans].


else



>**Rihtur Fullome says:** The lair of the Bloodsabers is no place for you...  begone, or be dead!


**You say:** `plan`



if **Faction** >= Amiable then



>**Rihtur Fullome says:** Nerissa is well protected by Kane. She will no doubt attempt to inform someone of her suspicions, most likely her sister, Milea. You must find Milea Clothspinner and kill her. No word of our operations must leak out. Return with proof of Milea's death and we shall see to a reward.


elseif **Faction** >= Indifferent then



>**Rihtur Fullome says:** While the Bloodsabers appreciate your past contributions to Bertoxxulous and our cause, we do not feel you can be trusted with vital information yet.


else



>**Rihtur Fullome says:** The lair of the Bloodsabers is no place for you...  begone, or be dead!


end

## Turn-Ins





if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_677.png" alt="" /> <a
                                href="/item/13302" data-url="13302" class="tooltip-link link">Monogrammed Cloth</a>) then


>**Rihtur Fullome says:** You have done a truly wicked deed. Good work! Milea was a prestigious member of the Hall of Steel and a friend to the Knights of Truth. It is better that she now fertilizes the flowers of the Plains of Karana. Here. A fitting reward for such a deed.


Your faction standing with [Bloodsabers](/faction/221) got better (<span class='text-success'>+10</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Opal Darkbriar](/faction/296) got better (<span class='text-success'>+1</span>)


Your faction standing with [Priests of Life](/faction/341) got worse (<span class='text-danger'>-2</span>)


Your faction standing with [Corrupt Qeynos Guards](/faction/230) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:** 0 (+1000 exp)

 

**This NPC *should* return incorrect items given.**
