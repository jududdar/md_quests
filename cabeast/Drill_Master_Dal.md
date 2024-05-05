# Drill Master Dal



[Drill Master Dal](/npc/106079) is a level 61 Iksar GM Warrior that spawns in [Cabilis East](/zone/106).



## Dialog

**You say:** `Hail`



>**Drill Master Dal says:** Yes, yes!!  What do I have here?!!  Another [new recruit]?  If so, then speak up!  If not, then leave and do not waste my time nor risk your life.  I also seek a [legion soldier] if you be one.

**You say:** `new recruit`



if **Faction** >= Amiable then



>**Drill Master Dal says:** Yes.  You have the look of the Partisan.  I trust you have begun your blacksmith training.  If not, then do so.  Also, you should read all the books available to you in Fortress Talishan.  We are not dimwitted broodlings here.  You shall need the knowledge soon. That, or a coffin.  Ha!!  Here is your task, are you [ready for your task]?


elseif **Faction** >= Indifferent then



>**Drill Master Dal says:** No Iksar resident will have anything to do with you!


else



>**Drill Master Dal says:** Hiss!  Fool!  Fear the Legion of Cabilis for you are no ally to us.  Leave while you can.


**You say:** `soldier`



if **Faction** >= Amiable then



>**Drill Master Dal says:** Good news to my ears!!  I seek to prove to the War Baron that the infamous forsaken band of thieves who call themselves Marrtail's Marauders are operating within earshot of our city.  You must bring me proof that you encountered no fewer than four of these thieves.  Do so and I shall offer you an armor item unavailable to most.


elseif **Faction** >= Indifferent then



>**Drill Master Dal says:** No Iksar resident will have anything to do with you!


else



>**Drill Master Dal says:** Hiss!  Fool!  Fear the Legion of Cabilis for you are no ally to us.  Leave while you can.


**You say:** `ready`



if **Faction** >= Amiable then



>**Drill Master Dal says:** Yes. yes!!  It does not matter.  You must be ready.  I will hand you the Partisan pack.  Into it you shall combine one giant blood sac of the giant leech;  scout beads from a goblin scout; one sabertooth kitten canine and finally, three bone shards from decaying skeletons.  Hopefully, you will survive your attempt to obtain these items.  Return the full Partisan pack and you shall be rewarded with a curscale shield.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_565.png" alt="" /> <a
                                href="/item/17997" data-url="17997" class="tooltip-link link">Partisan Pack</a>


elseif **Faction** >= Indifferent then



>**Drill Master Dal says:** No Iksar resident will have anything to do with you!


else



>**Drill Master Dal says:** Hiss!  Fool!  Fear the Legion of Cabilis for you are no ally to us.  Leave while you can.

end



## Turn-Ins




if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_757.png" alt="" /> <a
                                href="/item/12915" data-url="12915" class="tooltip-link link">Marauder Snout Ring 'MM'</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_757.png" alt="" /> <a
                                href="/item/12915" data-url="12915" class="tooltip-link link">Marauder Snout Ring 'MM'</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_757.png" alt="" /> <a
                                href="/item/12915" data-url="12915" class="tooltip-link link">Marauder Snout Ring 'MM'</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_757.png" alt="" /> <a
                                href="/item/12915" data-url="12915" class="tooltip-link link">Marauder Snout Ring 'MM'</a>) then


>*Drill Master Dal hands you a shimmering black piece of armor which smells quite horrid. You find it hard to keep it from slithering out of your hand. 'Here is the armor the tailors have been working on for the legion. You may test it for us. Keep up your fine work and I may have other pieces available for you to test.'*


Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+5</span>)


Your faction standing with [Cabilis Residents](/faction/440) got better (<span class='text-success'>+1</span>)


Your faction standing with [Scaled Mystics](/faction/445) got better (<span class='text-success'>+1</span>)


Your faction standing with [Crusaders of Greenmist](/faction/442) got better (<span class='text-success'>+1</span>)


Your faction standing with [Swift Tails](/faction/444) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_632.png" alt="" /> <a
                                href="/item/12917" data-url="12917" class="tooltip-link link">Leech Husk Tunic</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_635.png" alt="" /> <a
                                href="/item/12918" data-url="12918" class="tooltip-link link">Leech Husk Leggings</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_636.png" alt="" /> <a
                                href="/item/12919" data-url="12919" class="tooltip-link link">Leech Husk Gloves</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_637.png" alt="" /> <a
                                href="/item/12920" data-url="12920" class="tooltip-link link">Leech Husk Wrist Bands</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_633.png" alt="" /> <a
                                href="/item/12921" data-url="12921" class="tooltip-link link">Leech Husk Boots</a>) (+1000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-15 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_565.png" alt="" /> <a
                                href="/item/12673" data-url="12673" class="tooltip-link link">Full Partisan Pack</a>) then


>**Drill Master Dal says:** Fantastic work, Partisan Soandso. Here is your reward. You may continue to perform this task as the baron has found it aids in our defense. I shall always pay for a good day's work. Just let me know if you are still [ready for the task]. As for the curskin shield, you may only have one. Perhaps soon you will prove yourself a formidable fighter and you can earn a militia pike from Drill Master Vygan.


Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+5</span>)


Your faction standing with [Cabilis Residents](/faction/440) got better (<span class='text-success'>+1</span>)


Your faction standing with [Scaled Mystics](/faction/445) got better (<span class='text-success'>+1</span>)


Your faction standing with [Crusaders of Greenmist](/faction/442) got better (<span class='text-success'>+1</span>)


Your faction standing with [Swift Tails](/faction/444) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_759.png" alt="" /> <a
                                href="/item/12674" data-url="12674" class="tooltip-link link">Curscale Buckler</a> (+250 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-15 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**
