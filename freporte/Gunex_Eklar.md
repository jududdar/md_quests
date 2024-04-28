# Gunex Eklar
## Dialog

if(eq.get_current_expansion() >= 4.0) then


**You say:** `hail`




>**Gunex Eklar says:** Begone lest you seek instruction, I am very busy. I teach those who [follow the path of rage] as a Shadowknight, the leaders of the Dismal Rage.


**You say:** `follow the path of rage`




>**Gunex Eklar says:** As the leaders of the Dismal Rage we Shadowknights forefront of our struggles. We use the spiritual guidance of our Clerics, the Dark Arts of our Necromancers, and the tactics of our Warriors to advance the causes and secure the needs of our followers. If you aspire to be of importance to your colleagues you must first obtain a suit of armor to defend you from the aggressions of our enemies. Take this note to Quan Nektogo here in the eastern quarter of Freeport. He will aid you in the construction of your armor. When you are properly outfitted return to me and I will present you with an [important task].



**You receive:**  [Note to Quan Nektogo](/item/19845)


**You say:** `important task`




>**Gunex Eklar says:** It has come to our attention that a paladin of the Sentries of Passion, Raenna Griff, has been aiding sympathizers and wanted members of the Sentries of Passion and the Knights of Truth in the sewer tunnels beneath the western quarter of Freeport. The incompetent Freeport Militia has yet to capture these wanted followers of the Mar twins. We will wait for their capture no longer. Seek this Raenna Griff individual and slay her. I want her head presented to me this very night!

end

## Turn-Ins



local expansion_flag = eq.get_current_expansion();



if(expansion_flag >= 4.0 and  **You turn in:** [Raenna Griff's Head](/item/19934)


>**Gunex Eklar says:** It took you long enough. I wonder if the Militia will be able to identify the body minus its head. Take this Dull Dismal Long Sword and sharpen it in a forge with a sharpening stone. It may take you several attempts if you are unfamiliar with the process. Once that is accomplished deliver the Sharpened Dismal Long Sword and a Giant Rattlesnake Skin to Quan Nektogo. He will make the final preparations on your weapon.


* __Faction:__ [Dismal Rage](/faction/271) (10)


* __Faction:__ [Knights of Truth](/faction/281) (-1)


* __Faction:__ [Opal Darkbriar](/faction/296) (2)


 **You receive:**  [Dull Dismal Long Sword](/item/19923) (+200 exp)

**This NPC *should* return incorrect items given.**
;

