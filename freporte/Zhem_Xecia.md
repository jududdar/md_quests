# Zhem Xecia



[Zhem Xecia](/npc/10095) is a level 61 Human GM Cleric that spawns in [East Freeport](/zone/10).



## Dialog

if(eq.get_current_expansion() >= 4.0) then


**You say:** `hail`




>**Zhem Xecia says:** What is it maggot? I have only time for new clerics who have chosen to [serve the Dismal Rage]. If you are looking for meaningless banter. than I suggest you find a bar wench.


**You say:** `serve the dismal rage`




>**Zhem Xecia says:** The clerics of the Dismal Rage must be strong and familiar with battle. There are many beings across Norrath who oppose our deity and our dogma. Take this note to Jerra Renlock and she will aid you in obtaining a suit of armor to protect you from the physical threats of our enemies and the creatures of the wild.  Once you have been properly outfitted return to me and will offer you [further instruction].



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_868.png" alt="" /> <a
                                href="/item/19844" data-url="19844" class="tooltip-link link">Note to Jerra Renlock</a>


**You say:** `further instruction`




>**Zhem Xecia says:** So you think you are ready to face the enemies of the Dismal Rage? Be careful to not be blinded by your arrogance or anger. You must focus the rage in your soul and refine it into patient and insidious hatred. A cleric of the Sentries of Passion. Ulia Yovar. has been attempting to uncover our allies among the citizens of Freeport and is believed to be in hiding in the sewer tunnels under the western quarter of Freeport. Seek this enemy of the Dismal Rage and bring me her head.

end



## Turn-Ins



local expansion_flag = eq.get_current_expansion();

if(expansion_flag >= 4.0 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_983.png" alt="" /> <a
                                href="/item/19933" data-url="19933" class="tooltip-link link">Ulia Yovar's Head</a>) then


>**Zhem Xecia says:** I see your mission was a success. Take this Rough Dismal Flail and refine it in forge with a sharpening stone. It may take you several attempts if you are unfamiliar with the process. Once that is done take the Refined Dismal Flail and a Giant Rattlesnake Skin to Jerra Renlock. She will put the finishing touches on your new weapon.


Your faction standing with [Dismal Rage](/faction/271) got better (<span class='text-success'>+10</span>)


Your faction standing with [Knights of Truth](/faction/281) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Opal Darkbriar](/faction/296) got better (<span class='text-success'>+2</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_741.png" alt="" /> <a
                                href="/item/19922" data-url="19922" class="tooltip-link link">Rough Dismal Flail</a> (+100 exp)

 

**This NPC *should* return incorrect items given.**


