# Tax Collector Khugra









## Dialog

local qglobals = eq.get_qglobals(e.self,e.other);

**You say:** `Hail`



>**Tax Collector Khugra says:** Well met. Friend.  May I be of assistance?

**You say:** `certificate`



>**Tax Collector Khugra says:** I suppose I can issue another one. Just give me a second.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_860.png" alt="" /> <a
                                href="/item/2875" data-url="2875" class="tooltip-link link">Stamped Certificate of Taxability</a>
end



## Turn-Ins





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_860.png" alt="" /> <a
                                href="/item/2874" data-url="2874" class="tooltip-link link">Certificate of Taxability</a>) then


>*Tax Collector Khugra places his seal on the certificate before returning it to you.*


>**Tax Collector Khugra says:** Ahh, a new taxpayer, wonderful! You must always remember that it is a distinct privilege to contribute to the upkeep of our noble society and not merely a duty or a burden. I look forward to collecting your honorable taxes in the future. May the spirits prosper you, Soandso.


eq.set_global("Shar_Vahl_Cit","3",5,"F");





 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_860.png" alt="" /> <a
                                href="/item/2875" data-url="2875" class="tooltip-link link">Stamped Certificate of Taxability</a> 

 

**This NPC *should* return incorrect items given.**





