# Jarrex N-Ryt




## Dialog

if(eq.get_current_expansion() >= 4.0) then


**You say:** `hail`




>**Jarrex N-Ryt says:** What have we here? A new weakling that wishes to reap some sort of self-value and renown through service to the Indigo Brotherhood perhaps? Well speak up whelp!! Have you come to [destroy the enemies of Neriak] or are you a coward better suited to mop the filth from the back rooms of the Maidens Fancy.


**You say:** `destroy the enemies`




if(e.other:GetClass() == 1 and e.other:GetRace() == 6) then




>**Jarrex N-Ryt says:** If you are going to be of any value to the Indigo Brotherhood you will need to outfit yourself in a suit of armor that will turn aside the blades of enemy forces. From the looks of you even the tiny fangs of a moss snake could bring you death. Take this request form to Issva H'Rugla to get yourself started on the assembly of your armor. When you have procured some protection for your weakling body return to me for [further instruction].




 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_868.png" alt="" /> <a
                                href="/item/31753" data-url="31753" class="tooltip-link link">Request Form</a>



else




>**Jarrex N-Ryt says:** Begone fool, you are no member of the Indigo Brotherhood!




**You say:** `further instruction`




>**Jarrex N-Ryt says:** Ah, you are eager to advance further within the Indigo Brotherhood. Although it is my duty to aid your training, do not allow your arrogance to blind you to your lowly position amongst the Kings most loyal subjects. Your next task is to assist the construction of a [weapon] and [shield] worthy of being wielded by a Warrior of the Indigo Brotherhood.


**You say:** `weapon`




>**Jarrex N-Ryt says:** Beyond the mouth of Neriak lies the Nektulos Forest. There the Deathfist Clan of Orcs has set up camps in an attempt to invade and claim the Nektulos Forest. Slay these invaders and bring to me an Orc Templar Scalp, an Orc Fibula bone, and an Orc Clavicle bone.


**You say:** `shield`




>**Jarrex N-Ryt says:** Young Kodiak Bears often wander into the Nektulos Forest from the Commonlands searching for food. You do not appear to have the strength to arm wrestle a pixie. If you prove me wrong by slaying Young Kodiaks and bringing me four Young Kodiak Femurs I will guide you in the construction of a shield worthy of a warrior of the Indigo Brotherhood.

end

## Turn-Ins



if(eq.get_current_expansion() >= 4.0) then


if(e.other:GetClass() == 1 and e.other:GetRace() == 6) then



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_555.png" alt="" /> <a
                                href="/item/16173" data-url="16173" class="tooltip-link link">Deathfist Templar Scalp</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_907.png" alt="" /> <a
                                href="/item/19565" data-url="19565" class="tooltip-link link">Orc Clavicle</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_907.png" alt="" /> <a
                                href="/item/19564" data-url="19564" class="tooltip-link link">Orc Fibula</a>) then




>**Jarrex N-Ryt says:** Excellent.  Here is your weapon, Soandso.  Use it to slay more!




 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_577.png" alt="" /> <a
                                href="/item/19606" data-url="19606" class="tooltip-link link">Jagged Orc Slayer Sword</a> 

 



elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_905.png" alt="" /> <a
                                href="/item/19562" data-url="19562" class="tooltip-link link">Young Kodiak Femur</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_905.png" alt="" /> <a
                                href="/item/19562" data-url="19562" class="tooltip-link link">Young Kodiak Femur</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_905.png" alt="" /> <a
                                href="/item/19562" data-url="19562" class="tooltip-link link">Young Kodiak Femur</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_905.png" alt="" /> <a
                                href="/item/19562" data-url="19562" class="tooltip-link link">Young Kodiak Femur</a>) then




>**Jarrex N-Ryt says:** So you have more strength than you seem to.  Hmm...here is your shield, Soandso.




 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_759.png" alt="" /> <a
                                href="/item/19609" data-url="19609" class="tooltip-link link">Black Femur Shield</a> 

 




**This NPC *should* return incorrect items given.**





