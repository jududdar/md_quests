# Gunex Eklar


## Dialog

if(eq.get_current_expansion() >= 4.0) then


**You say:** `hail`




>**Gunex Eklar says:** Begone lest you seek instruction, I am very busy. I teach those who [follow the path of rage] as a Shadowknight, the leaders of the Dismal Rage.


**You say:** `follow the path of rage`




>**Gunex Eklar says:** As the leaders of the Dismal Rage we Shadowknights forefront of our struggles. We use the spiritual guidance of our Clerics, the Dark Arts of our Necromancers, and the tactics of our Warriors to advance the causes and secure the needs of our followers. If you aspire to be of importance to your colleagues you must first obtain a suit of armor to defend you from the aggressions of our enemies. Take this note to Quan Nektogo here in the eastern quarter of Freeport. He will aid you in the construction of your armor. When you are properly outfitted return to me and I will present you with an [important task].



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_868.png" alt="" /> <a
                                href="/item/19845" data-url="19845" class="tooltip-link link">Note to Quan Nektogo</a>


**You say:** `important task`




>**Gunex Eklar says:** It has come to our attention that a paladin of the Sentries of Passion, Raenna Griff, has been aiding sympathizers and wanted members of the Sentries of Passion and the Knights of Truth in the sewer tunnels beneath the western quarter of Freeport. The incompetent Freeport Militia has yet to capture these wanted followers of the Mar twins. We will wait for their capture no longer. Seek this Raenna Griff individual and slay her. I want her head presented to me this very night!

end



## Turn-Ins



local expansion_flag = eq.get_current_expansion();



if(expansion_flag >= 4.0 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_983.png" alt="" /> <a
                                href="/item/19934" data-url="19934" class="tooltip-link link">Raenna Griff's Head</a>) then 


>**Gunex Eklar says:** It took you long enough. I wonder if the Militia will be able to identify the body minus its head. Take this Dull Dismal Long Sword and sharpen it in a forge with a sharpening stone. It may take you several attempts if you are unfamiliar with the process. Once that is accomplished deliver the Sharpened Dismal Long Sword and a Giant Rattlesnake Skin to Quan Nektogo. He will make the final preparations on your weapon.


Your faction standing with [Dismal Rage](/faction/271) got better (<span class='text-success'>+10</span>)


Your faction standing with [Knights of Truth](/faction/281) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Opal Darkbriar](/faction/296) got better (<span class='text-success'>+2</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_590.png" alt="" /> <a
                                href="/item/19923" data-url="19923" class="tooltip-link link">Dull Dismal Long Sword</a> (+200 exp)

 

**This NPC *should* return incorrect items given.**
;

