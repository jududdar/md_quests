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



if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_980.png" alt="" /> <a
                                href="/item/13729" data-url="13729" class="tooltip-link link">Barbarian Head</a>) then 




>**Margyn McCann says:** We can now rest assured that justice has been served. Ye'll be a valuable asset to our court. Take and remember this spell, Spirit o' the Bear. I hope ye've attained the necessary skills to scribe it. If not, I'm sure ye soon will. Go now, and serve justice.





Your faction standing with [Shamen of Justice](/faction/327) got better (<span class='text-success'>+20</span>)
















Your faction standing with [Merchants of Halas](/faction/328) got better (<span class='text-success'>+3</span>)
















Your faction standing with [Circle of Unseen Hands](/faction/223) got worse (<span class='text-danger'>-3</span>)
















Your faction standing with [Coalition of Tradefolk Underground](/faction/336) got worse (<span class='text-danger'>-3</span>)
















Your faction standing with [Ebon Mask](/faction/244) got worse (<span class='text-danger'>-4</span>)
















 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15279" data-url="15279" class="tooltip-link link">Spell: Spirit of Bear</a> (+1000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 5-10 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18761" data-url="18761" class="tooltip-link link">A tattered note</a>) then


>**Margyn McCann says:** Welcome t' the Church o' the Tribunal. Here, we practice the will o' the Six Hammers. This is our guild tunic - wear it with pride and represent us well.


Your faction standing with [Shamen of Justice](/faction/327) got better (<span class='text-success'>+100</span>)
















Your faction standing with [Merchants of Halas](/faction/328) got better (<span class='text-success'>+15</span>)
















Your faction standing with [Circle of Unseen Hands](/faction/223) got worse (<span class='text-danger'>-15</span>)
















Your faction standing with [Coalition of Tradefolk Underground](/faction/336) got worse (<span class='text-danger'>-15</span>)
















Your faction standing with [Ebon Mask](/faction/244) got worse (<span class='text-danger'>-20</span>)
















 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_678.png" alt="" /> <a
                                href="/item/13512" data-url="13512" class="tooltip-link link">Faded Blue Tunic*</a> (+20 exp)

 











**This NPC *should* return incorrect items given.**
