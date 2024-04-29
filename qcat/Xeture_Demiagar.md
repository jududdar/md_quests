# Xeture Demiagar
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




**You receive:**  [Note to Torin Krentar](/item/20207)



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

if( **You turn in:** [A tattered note](/item/18716)) then 


>**Xeture Demiagar says:** Hmmm. Another rat has found its way to my doorstep, huh? Well, we may have use for you. Go find Rihtur, maybe he has an errand for you.


* __Faction:__ [Bloodsabers](/faction/221) (100)


* __Faction:__ [Guards of Qeynos](/faction/262) (-15)


* __Faction:__ [Opal Darkbriar](/faction/296) (10)


* __Faction:__ [Priests of Life](/faction/341) (-25)


* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (5)


 **You receive:**  [Ruined Training Tunic*](/item/13598) (+100 exp)

elseif(expansion_flag >= 4.0 and  **You turn in:** [Rolon Banari's Head](/item/20197)) then


>**Xeture Demiagar says:** You have done well, Soandso. Take this Rusty Bloodsaber Mace to a forge and clean it up with a Sharpening Stone. It may take you several attempts to get all the rust off if you are not familiar with the process. Once that is done take the Refined Bloodsaber Mace to Torin Krentar with a Giant King Snake Skin and he will put the finishing touches on the weapon.


* __Faction:__ [Bloodsabers](/faction/221) (10)


* __Faction:__ [Guards of Qeynos](/faction/262) (-1)


* __Faction:__ [Opal Darkbriar](/faction/296) (-1)


* __Faction:__ [Priests of Life](/faction/341) (-2)


* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (1)


 **You receive:**  [Rusty Bloodsaber Mace](/item/20198) 

**This NPC *should* return incorrect items given.**
