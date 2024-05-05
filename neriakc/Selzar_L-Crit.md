# Selzar L\`Crit



[Selzar L\`Crit](/npc/42085) is a level 61 Dark Elf GM Rogue that spawns in [Neriak - 3rd Gate](/zone/42).





## Dialog

if(eq.get_current_expansion() >= 4.0) then


**You say:** `hail`




>**Selzar L-Crit says:** What have we here? Another hopeful member of the House of the Ebon Mask? You've got much to learn before you will be of much use to our House or the secret operations that support both the thrones of our King and Queen. First you need to outfit yourself in a suit of [armor], Soandso.


**You say:** `armor`




>**Selzar L-Crit says:** Seek Kanthu M'Rekkor and give him this request parchment. When you have outfitted yourself in a suit of armor return to the House of the Ebon Mask and I will grant you [another task].



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/2416" data-url="2416" class="tooltip-link link">Note to Kanthuk</a>


**You say:** `other task`




>**Selzar L-Crit says:** Ah, you are eager to advance further within the House of the Ebon Mask. Although it is my duty to aid your training, do not allow your arrogance to blind you to your lowly position in our House. I can see that you have not yet learned to temper the use of your tongue. Your next task is to assist the construction of a [weapon] and [bow] worthy of being wielded by a Rogue of the House of the Ebon Mask.


**You say:** `bow`




>**Selzar L-Crit says:** The Halfling Druids from Rivervale that frequent the ancient druid ruins in the Nektulos Forest are guarded by Leatherfoot Warriors. The peck druids perform the rituals that they hope will prevent Innoruuks corruption from spreading deeper into the Forest and the lands beyond. Should you slay the peck warriors guarding the druids and obtain a Leatherfoot Short Bow, take the bow, a Black Mamba Skin, and a Lock of Zombie Hair to Andara C'Luzz at The Bleek Fletcher in the Neriak Commons near the headquarters of the Indigo Brotherhood.


**You say:** `weapon`




>**Selzar L-Crit says:** Beyond the mouth of Neriak lies the Nektulos Forest. There the Halflings of Rivervale have set up camps at ancient druid holy sites in an attempt to cleanse Innoruuks corruption that is spreading through the Nektulos Forest. Slay these trespassers and bring me a Large Snake Skin, a Halfling Fibula bone, and a Halfling Clavicle bone.

end



## Turn-Ins



local expansion_flag = eq.get_current_expansion();

if(expansion_flag >= 4.0 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_907.png" alt="" /> <a
                                href="/item/19578" data-url="19578" class="tooltip-link link">Halfling Clavicle</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_907.png" alt="" /> <a
                                href="/item/19577" data-url="19577" class="tooltip-link link">Halfling Fibula</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_813.png" alt="" /> <a
                                href="/item/13060" data-url="13060" class="tooltip-link link">Large Snake Skin</a>) then


>**Selzar L-Crit says:** You have slain enemies of our order. Carry your weapon with pride.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_762.png" alt="" /> <a
                                href="/item/19608" data-url="19608" class="tooltip-link link">Scaled Bone Rapier</a> (+150 exp)

 

**This NPC *should* return incorrect items given.**





