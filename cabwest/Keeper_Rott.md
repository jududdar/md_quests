# Keeper Rott
## Dialog

**You say:** `hail`



>*Keeper Rott bows before you. His eyes are kept wide by the pins which distort his eyelids. 'Greetings! You have stumbled upon the cave of the Keepers. We record the arcane secrets of the Brood of Kotiz. We have scribed many spells and make them available to all those who are deserving. Please, have a look.'*

**You say:** `chosen occultist`



if **Faction** >= Amiable then



>*Keeper Rott kneels before you abjectly. 'Oh, great occultist! I am glad you have arrived, but I do not have the artifacts Kyvix seeks. You will have to seek out the sarnak revenants who still hold the precious stem and base. Get them and take them with your occultist skullcap back to Master Kyvix. Since you are headed in the general direction, I also have an [additional mission], if you do not mind.'*


elseif **Faction** >= Indifferent then



>**Keeper Rott says:** When you have shown more devotion to the Brood of Kotiz, we can discuss such things.


else



>**Keeper Rott says:** You are a true simpleton to think you can speak to me.  You are no ally to the Brood of Kotiz.  Begone, before I make your blood boil!


**You say:** `additional mission`



if **Faction** >= Amiable then



>*Keeper Rott grabs a fist full of scribbled notes and throws them into the air in a rage. 'All these notes are useless to me without the first four note pages! While I ventured through the fields of the drixies, I was assaulted by a band of gobs. They were shamans. I heard them calling spirits. They took the first two pages before I escaped. Then I lost the [second two pages] the next day!! Blast!!'*


elseif **Faction** >= Indifferent then



>**Keeper Rott says:** When you have shown more devotion to the Brood of Kotiz, we can discuss such things.


else



>**Keeper Rott says:** You are a true simpleton to think you can speak to me.  You are no ally to the Brood of Kotiz.  Begone, before I make your blood boil!


**You say:** `second two pages`



if **Faction** >= Amiable then



>*Keeper Rott begins to curse. Luckily, you do not understand the language, but you feel a bit of spittle strike your face. '...and then there I was, almost home and the legion expedition leader decided we should explore a bit more near the lake. Then I find myself up against the same type of gobs from the fields. I just ran for the exit an never looked back, but they still managed to swipe pages 3 and 4!!'*


elseif **Faction** >= Indifferent then



>**Keeper Rott says:** When you have shown more devotion to the Brood of Kotiz, we can discuss such things.


else



>**Keeper Rott says:** You are a true simpleton to think you can speak to me.  You are no ally to the Brood of Kotiz.  Begone, before I make your blood boil!

end

## Turn-Ins



local text = "I am expecting pages one through four. Do I have to go and find them myself?!";



if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/12854" data-url="12854" class="tooltip-link link">An Illegible Note</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/12855" data-url="12855" class="tooltip-link link">An Illegible Note</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/12856" data-url="12856" class="tooltip-link link">An Illegible Note</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/12857" data-url="12857" class="tooltip-link link">An Illegible Note</a>) then


>**Keeper Rott says:** Oh, great necromancer, how can I repay you?!! I know. Here is a spell I recently researched. It should help you increase the strength of a summoned pet. Learn it well.


Your faction standing with [Brood of Kotiz](/faction/443) got better (<span class='text-success'>+3</span>)


Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/16426" data-url="16426" class="tooltip-link link">Spell: Intensify Death</a> (+1000 exp)

 

**This NPC *should* return incorrect items given.**
