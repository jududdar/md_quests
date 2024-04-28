# Selzar L-Crit


## Dialog

if(eq.get_current_expansion() >= 4.0) then


**You say:** `hail`




>**Selzar L-Crit says:** What have we here? Another hopeful member of the House of the Ebon Mask? You've got much to learn before you will be of much use to our House or the secret operations that support both the thrones of our King and Queen. First you need to outfit yourself in a suit of [armor], Soandso.


**You say:** `armor`




>**Selzar L-Crit says:** Seek Kanthu M'Rekkor and give him this request parchment. When you have outfitted yourself in a suit of armor return to the House of the Ebon Mask and I will grant you [another task].



**You receive:**  [Note to Kanthuk](/item/2416)


**You say:** `other task`




>**Selzar L-Crit says:** Ah, you are eager to advance further within the House of the Ebon Mask. Although it is my duty to aid your training, do not allow your arrogance to blind you to your lowly position in our House. I can see that you have not yet learned to temper the use of your tongue. Your next task is to assist the construction of a [weapon] and [bow] worthy of being wielded by a Rogue of the House of the Ebon Mask.


**You say:** `bow`




>**Selzar L-Crit says:** The Halfling Druids from Rivervale that frequent the ancient druid ruins in the Nektulos Forest are guarded by Leatherfoot Warriors. The peck druids perform the rituals that they hope will prevent Innoruuks corruption from spreading deeper into the Forest and the lands beyond. Should you slay the peck warriors guarding the druids and obtain a Leatherfoot Short Bow, take the bow, a Black Mamba Skin, and a Lock of Zombie Hair to Andara C'Luzz at The Bleek Fletcher in the Neriak Commons near the headquarters of the Indigo Brotherhood.


**You say:** `weapon`




>**Selzar L-Crit says:** Beyond the mouth of Neriak lies the Nektulos Forest. There the Halflings of Rivervale have set up camps at ancient druid holy sites in an attempt to cleanse Innoruuks corruption that is spreading through the Nektulos Forest. Slay these trespassers and bring me a Large Snake Skin, a Halfling Fibula bone, and a Halfling Clavicle bone.

end

## Turn-Ins



local expansion_flag = eq.get_current_expansion();

if(expansion_flag >= 4.0 and  **You turn in:** [Halfling Clavicle](/item/19578), [Halfling Fibula](/item/19577), [Large Snake Skin](/item/13060)


>**Selzar L-Crit says:** You have slain enemies of our order. Carry your weapon with pride.


 **You receive:**  [Scaled Bone Rapier](/item/19608) (+150 exp)

**This NPC *should* return incorrect items given.**





