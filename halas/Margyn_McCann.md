# Margyn McCann
## Dialog

**You say:** `hail`



>**Margyn McCann says:** Hail, young adventurer! I'm the chief overseer o' the Shamans o' Justice. We serve the will o' the Tribunal. Justice is our way. Within Halas, there are none who are above the scales o' justice. There are still some who have defied our laws. We wish to [apprehend the fugitives].

**You say:** `apprehend the fugitives`



if **Faction** >= Amiable then 



**You say:** `apprehend the fugitives`





>**Margyn McCann says:** Maybe so, however, there are some who may be too much fer ye to handle. I'll need to know if ye're a [young shaman] or a [standin' member of the court].



**You say:** `young shaman`





>**Margyn McCann says:** We seek a former member who dared to curse the righteousness of the Tribunal. We'll have his head for that remark. His name is Granin O'Gill and he has run to the wastelands of Everfrost seeking safe haven. Find him. Return his head to me. Do so, and earn the ninth circle spell, Spirit o' the Bear. Go at once!



**You say:** `member of the court`





>**Margyn McCann says:** At the moment, I've no word o' heretics about for ye to hunt down. I pray that there will be no more, too!












elseif **Faction** >= Indifferent then



>**Margyn McCann says:** Ye're no criminal to the Shamans o' Justice, but ye've yet to prrove yer devotion to justice.


else



>**Margyn McCann says:** The scales o' the Shamans o' Justice dinnae tip in yer favor. Ye'd best flee while ye still have the chance.



## Turn-Ins



if **Faction** >= Amiable and  **You turn in:** [Barbarian Head](/item/13729)) then 




>**Margyn McCann says:** We can now rest assured that justice has been served. Ye'll be a valuable asset to our court. Take and remember this spell, Spirit o' the Bear. I hope ye've attained the necessary skills to scribe it. If not, I'm sure ye soon will. Go now, and serve justice.





* __Faction:__ [Shamen of Justice](/faction/327) (20)
















* __Faction:__ [Merchants of Halas](/faction/328) (3)
















* __Faction:__ [Circle of Unseen Hands](/faction/223) (-3)
















* __Faction:__ [Coalition of Tradefolk Underground](/faction/336) (-3)
















* __Faction:__ [Ebon Mask](/faction/244) (-4)
















 **You receive:**  [Spell: Spirit of Bear](/item/15279) (+1000 exp)

elseif( **You turn in:** [A tattered note](/item/18761)) then


>**Margyn McCann says:** Welcome t' the Church o' the Tribunal. Here, we practice the will o' the Six Hammers. This is our guild tunic - wear it with pride and represent us well.


* __Faction:__ [Shamen of Justice](/faction/327) (100)
















* __Faction:__ [Merchants of Halas](/faction/328) (15)
















* __Faction:__ [Circle of Unseen Hands](/faction/223) (-15)
















* __Faction:__ [Coalition of Tradefolk Underground](/faction/336) (-15)
















* __Faction:__ [Ebon Mask](/faction/244) (-20)
















 **You receive:**  [Faded Blue Tunic*](/item/13512) (+20 exp)











**This NPC *should* return incorrect items given.**
