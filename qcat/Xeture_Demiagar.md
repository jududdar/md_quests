# Xeture Demiagar



[Xeture Demiagar](/npc/45089) is a level 61 Human GM Cleric that spawns in [Qeynos Aqueduct System](/zone/45).



## Dialog

if(eq.get_current_expansion() >= 4.0) then


**You say:** `hail`




if **Faction** >= Dubious then





>**Xeture Demiagar says:** I have much to do here for the defense of our Temple and the appeasing of our patron Bertoxxulous, the Plague Lord. If the Plague Lord has gifted you with the desire to [serve his will] as a priest of the Bloodsabers I will assist in your training. If not, then leave me now and do not interrupt me again.



else




>**Xeture Demiagar says:** The lair of the Bloodsabers is no place for you...  begone, or be dead!





**You say:** `serve his will`




if **Faction** >= Dubious then




>**Xeture Demiagar says:** By spreading the disease, decay, and destructive powers of the Plague Lord you will in turn be gifted with great insight and power. First however you must learn to survive in this city, surrounded by those who would see you destroyed for your faith. Take this note to Torin Krentar. He will instruct you on how to acquire a suit of armor to protect you from the weapons of our [enemies].




 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_864.png" alt="" /> <a
                                href="/item/20207" data-url="20207" class="tooltip-link link">Note to Torin Krentar</a>



else




>**Xeture Demiagar says:** The lair of the Bloodsabers is no place for you...  begone, or be dead!





**You say:** `enemies`




if **Faction** >= Dubious then




>**Xeture Demiagar says:** The self-righteous ruler of this city, Antonius Bayle IV, is backed by the Knights of Thunder, paladins and clerics of the Storm Lord Karana, and the Temple Life, paladins and clerics of the Prime-Healer, Rodcet Nife. Be wary when not within the security of our temple here in the Qeynos Catacombs, should the Qeynos Guards discover you allegiances they would have you executed. Once you have been properly armored return to me and I will give you [further instruction].



else




>**Xeture Demiagar says:** The lair of the Bloodsabers is no place for you...  begone, or be dead!





**You say:** `further instruction`




if **Faction** >= Dubious then




>**Xeture Demiagar says:** The Priests of Life, those who claim allegiance to the Prime Healer, Rodcet Nife, have proven to be a large obstacle in our conversion of the people of Qeynos to the ways of the Plague Bringer. Lately a Priest of Life by the name of Rolon Banari has been campaigning amongst the beggars and sickly, a social group from which we have gained many converts. Find this meddling priest and bring me his head.



else




>**Xeture Demiagar says:** The lair of the Bloodsabers is no place for you...  begone, or be dead!





end



## Turn-Ins



local expansion_flag = eq.get_current_expansion();

if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_864.png" alt="" /> <a
                                href="/item/18716" data-url="18716" class="tooltip-link link">A tattered note</a>) then 


>**Xeture Demiagar says:** Hmmm. Another rat has found its way to my doorstep, huh? Well, we may have use for you. Go find Rihtur, maybe he has an errand for you.


Your faction standing with [Bloodsabers](/faction/221) got better (<span class='text-success'>+100</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got worse (<span class='text-danger'>-15</span>)


Your faction standing with [Opal Darkbriar](/faction/296) got better (<span class='text-success'>+10</span>)


Your faction standing with [Priests of Life](/faction/341) got worse (<span class='text-danger'>-25</span>)


Your faction standing with [Corrupt Qeynos Guards](/faction/230) got better (<span class='text-success'>+5</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_678.png" alt="" /> <a
                                href="/item/13598" data-url="13598" class="tooltip-link link">Ruined Training Tunic*</a> (+100 exp)

 

elseif(expansion_flag >= 4.0 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_982.png" alt="" /> <a
                                href="/item/20197" data-url="20197" class="tooltip-link link">Rolon Banari's Head</a>) then


>**Xeture Demiagar says:** You have done well, Soandso. Take this Rusty Bloodsaber Mace to a forge and clean it up with a Sharpening Stone. It may take you several attempts to get all the rust off if you are not familiar with the process. Once that is done take the Refined Bloodsaber Mace to Torin Krentar with a Giant King Snake Skin and he will put the finishing touches on the weapon.


Your faction standing with [Bloodsabers](/faction/221) got better (<span class='text-success'>+10</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Opal Darkbriar](/faction/296) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Priests of Life](/faction/341) got worse (<span class='text-danger'>-2</span>)


Your faction standing with [Corrupt Qeynos Guards](/faction/230) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_741.png" alt="" /> <a
                                href="/item/20198" data-url="20198" class="tooltip-link link">Rusty Bloodsaber Mace</a> 

 

**This NPC *should* return incorrect items given.**
