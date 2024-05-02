# Harbinger Glosk
## Dialog

**You say:** `hail`



>*Harbinger Glosk halts his chanting. 'You dare to interrupt me? You had best have a good reason. I care not for small talk.'*

**You say:** `keepers grotto`



>**Harbinger Glosk says:** Keepers Grotto is where you shall find the Keepers. They study and scribe the spells of our dark circle. The grotto is not far from here, near the arena called the Gauntlet.

**You say:** `new revenant`



if **Faction** >= Amiable +100 then



>**Harbinger Glosk says:** Yes. You are. You shall do as I command. Take this. It is incomplete and must be ready for the emperor within the half season. You must find the [Four Missing Gems]. When you have them, then you will have to Quest for the [Grand Forge of Dalnir]. Within it's fire, all shall combine. Return the Sceptre to me with your Revenant Skullcap. Go.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_578.png" alt="" /> <a
                                href="/item/12873" data-url="12873" class="tooltip-link link">Unfinished Sceptre</a>










elseif **Faction** >= Indifferent then



>**Harbinger Glosk says:** When you have shown more devotion to the Brood of Kotiz, we can discuss such things.


else



>**Harbinger Glosk says:** You are a true simpleton to think you can speak to me.  You are no ally to the Brood of Kotiz.  Begone, before I make your blood boil!


**You say:** `four missing gems`



if **Faction** >= Amiable +100 then



>**Harbinger Glosk says:** The missing sceptre gems are: an Eye of Rokgus, a Gem of Yet to Come, a Heart of Torsis and the Crown Jewel of Ganak.


elseif **Faction** >= Indifferent then



>**Harbinger Glosk says:** When you have shown more devotion to the Brood of Kotiz, we can discuss such things.


else



>**Harbinger Glosk says:** You are a true simpleton to think you can speak to me.  You are no ally to the Brood of Kotiz.  Begone, before I make your blood boil!


**You say:** `forge of dalnir`



if **Faction** >= Amiable +100 then



>*Harbinger Glosk scratches his chin. 'I know little of it other than that it once belonged to the ancient Haggle Baron, Dalnir. From what I have read, its fires require no skill, but will melt any common forge hammer used. Dalnir was said to have called upon the ancients for a hammer which could tolerate the magical flames.'*


elseif **Faction** >= Indifferent then



>**Harbinger Glosk says:** When you have shown more devotion to the Brood of Kotiz, we can discuss such things.


else



>**Harbinger Glosk says:** You are a true simpleton to think you can speak to me.  You are no ally to the Brood of Kotiz.  Begone, before I make your blood boil!

end

## Turn-Ins



local text = "I await both the sceptre and your revenant skullcap.";




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18207" data-url="18207" class="tooltip-link link">Guild Summons</a>) then 



>**Harbinger Glosk says:** Another apprentice has reached rebirth. You now have become one with the Brood of Kotiz. We study the ancient writing of Kotiz. Through his writing we have found the power of the dark circles. Listen well to the scholars within this tower and seek the [Keepers Grotto] for knowledge of our spells. This drape shall be the sign to all Iksar that you walk with the Brood. Now go speak with Xydoz.


Your faction standing with [Brood of Kotiz](/faction/443) got better (<span class='text-success'>+100</span>)










Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+25</span>)













 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_929.png" alt="" /> <a
                                href="/item/12407" data-url="12407" class="tooltip-link link">Drape of the Brood</a> (+500 exp)

 




elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_578.png" alt="" /> <a
                                href="/item/12874" data-url="12874" class="tooltip-link link">Sceptre of Emperor Vekin</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1070.png" alt="" /> <a
                                href="/item/4265" data-url="4265" class="tooltip-link link">Revenant Skullcap</a>) then


>*Harbinger Glosk presents to you a glowing skullcap. 'This is the treasured cap of the sorcerers of this tower. Let all gaze upon you in awe. You are what others aspire to be. I look forward to reading of your adventures, Sorceror Soandso.'*


Your faction standing with [Brood of Kotiz](/faction/443) got better (<span class='text-success'>+10</span>)


Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+2</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1070.png" alt="" /> <a
                                href="/item/4266" data-url="4266" class="tooltip-link link">Sorcerer Skullcap</a> (+10000 exp)

**You receive coin:** 2 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 












elseif( **You turn in:** item1 =  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_868.png" alt="" /> <a
                                href="/item/14794" data-url="14794" class="tooltip-link link">Illegible Note: Boots</a>) then


>*Harbinger Glosk hisses and says venomously, 'And I am disturbed yet again. I hope for your sake it is important.'*


>*Harbinger Glosk The gaunt necromancer looks down at the paper in his hands and after reading a few lines gasps, then falls into a violent coughing fit. After recovering he takes a deep breath, puffs his chest out and hands the paper back to you. With his head held high, he says in a raspy voice, 'Show this to Rixiz. He will test you.'*


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_868.png" alt="" /> <a
                                href="/item/14794" data-url="14794" class="tooltip-link link">Illegible Note: Boots</a> 

 

elseif( **You turn in:** item1 =  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_868.png" alt="" /> <a
                                href="/item/14793" data-url="14793" class="tooltip-link link">Illegible Note: Greaves</a>) then


>*Harbinger Glosk snatches the note out of your hands, obviously irritated. After reading a few lines, he glances up at you, his brow furrowed, then looks down again to continue reading. When he's finished, he hands the note back to you and takes a deep breath, shuddering slightly. He then says, 'Xydoz. Take this to Xydoz. He will test you.'*


>*Harbinger Glosk watches you carefully as you leave.*


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_868.png" alt="" /> <a
                                href="/item/14793" data-url="14793" class="tooltip-link link">Illegible Note: Greaves</a> 

 

**This NPC *should* return incorrect items given.**
 




