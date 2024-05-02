# Tabure Ahendle
## Dialog

**You say:** `hail`



>**Tabure Ahendle says:** What have we here?  Perhaps a future Ebon Strongbear?  A [member of the Steel Warriors]?  If the way of the warrior is not to your liking, might I suggest joining the League of Antonican Bards?  The only damage you might take there is a sore throat! HAHAHA!

**You say:** `steel warrior`



if **Faction** >= Amiable then



>**Tabure Ahendle says:** A warrior, you say?  I have never met you.  You must be from the [bunker] or perhaps just a new recruit.  You should test your skills with Brin Stolunger.  When you have done that, then, maybe you could [assist] me.


elseif **Faction** >= Indifferent then








>**Tabure Ahendle says:** The Steel Warriors have no cause to dislike you, but you have yet to truly prove your worth to this guild.


else



>**Tabure Ahendle says:** Your head shall look grand mounted on the wall of the Steel Warriors Arena!!


**You say:** `assist`



if **Faction** >= Amiable then



>**Tabure Ahendle says:** So, you think you be of assistance to me? Let me test your skill. Travel to Erudin and seek out the beasts which are called Kobolds. I have never seen one and would very much like to have four Kobold Hides with which to make a rug. To do so would earn you some barely used rawhide armor - maybe even a shield.


elseif **Faction** >= Indifferent then








>**Tabure Ahendle says:** The Steel Warriors have no cause to dislike you, but you have yet to truly prove your worth to this guild.


else



>**Tabure Ahendle says:** Your head shall look grand mounted on the wall of the Steel Warriors Arena!!


**You say:** `dangerous task`



if **Faction** >= Amiable then



>**Tabure Ahendle says:** A ship sank while returning from Odus. On this ship was my squire, Tombor. He sank to the bottom and there he still lies. With him went a map. I would very much like you to search for this sunken ship. Return the map to me. I am sure it is still in the rotting hands of Tombor.









elseif **Faction** >= Indifferent then








>**Tabure Ahendle says:** The Steel Warriors have no cause to dislike you, but you have yet to truly prove your worth to this guild.


else



>**Tabure Ahendle says:** Your head shall look grand mounted on the wall of the Steel Warriors Arena!!


**You say:** `bunker`



if **Faction** >= Amiable then



>**Tabure Ahendle says:** Far to the eastern coast of Antonica lies the great trade city of Freeport.  It is there that our second chapter of Steel Warriors has built the arena called the bunker.




elseif **Faction** >= Indifferent then








>**Tabure Ahendle says:** The Steel Warriors have no cause to dislike you, but you have yet to truly prove your worth to this guild.


else



>**Tabure Ahendle says:** Your head shall look grand mounted on the wall of the Steel Warriors Arena!!

end

## Turn-Ins



local text = "I believe I stated that I need four kobold hides to make a rug.";


if( **Faction is** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_864.png" alt="" /> <a
                                href="/item/13423" data-url="13423" class="tooltip-link link">A Blurred Map</a>) then 


>**Tabure Ahendle says:** The map!! It is all blurred. The ink has run. I shall never be able to decipher it now. Still, I owe you for completion of your mission. May these be of assistance. It is always good for a warrior to be well supplied.





Your faction standing with [Steel Warriors](/faction/311) got better (<span class='text-success'>+5</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+1</span>)


Your faction standing with [Corrupt Qeynos Guards](/faction/230) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [The Freeport Militia](/faction/330) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Knights of Truth](/faction/281) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_590.png" alt="" /> <a
                                href="/item/5082" data-url="5082" class="tooltip-link link">Cast-Iron Long Sword</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_759.png" alt="" /> <a
                                href="/item/9001" data-url="9001" class="tooltip-link link">Buckler</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_736.png" alt="" /> <a
                                href="/item/5024" data-url="5024" class="tooltip-link link">Rusty Halberd</a>) (+5000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-5 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif( **Faction is** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_834.png" alt="" /> <a
                                href="/item/13424" data-url="13424" class="tooltip-link link">Kobold Hide</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_834.png" alt="" /> <a
                                href="/item/13424" data-url="13424" class="tooltip-link link">Kobold Hide</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_834.png" alt="" /> <a
                                href="/item/13424" data-url="13424" class="tooltip-link link">Kobold Hide</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_834.png" alt="" /> <a
                                href="/item/13424" data-url="13424" class="tooltip-link link">Kobold Hide</a>) then


>**Tabure Ahendle says:** Incredible!! Such grand tones. It shall make a fine rug. You have shown me that you cannot always judge a book by its cover. You are quite skilled. Would you like to perform a [dangerous task] for me?





Your faction standing with [Steel Warriors](/faction/311) got better (<span class='text-success'>+20</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+4</span>)


Your faction standing with [Corrupt Qeynos Guards](/faction/230) got worse (<span class='text-danger'>-3</span>)


Your faction standing with [The Freeport Militia](/faction/330) got worse (<span class='text-danger'>-3</span>)


Your faction standing with [Knights of Truth](/faction/281) got better (<span class='text-success'>+4</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_632.png" alt="" /> <a
                                href="/item/2140" data-url="2140" class="tooltip-link link">Raw-hide Tunic</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_635.png" alt="" /> <a
                                href="/item/2147" data-url="2147" class="tooltip-link link">Raw-hide Leggings</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_542.png" alt="" /> <a
                                href="/item/9002" data-url="9002" class="tooltip-link link">Round Shield</a>) (+5000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-5 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**


