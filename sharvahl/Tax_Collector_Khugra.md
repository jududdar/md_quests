# Tax Collector Khugra







## Dialog

local qglobals = eq.get_qglobals(e.self,e.other);

**You say:** `Hail`



>**Tax Collector Khugra says:** Well met. Friend.  May I be of assistance?

**You say:** `certificate`



>**Tax Collector Khugra says:** I suppose I can issue another one. Just give me a second.


**You receive:**  [Stamped Certificate of Taxability](/item/2875)
end

## Turn-Ins





if( **You turn in:** [Certificate of Taxability](/item/2874)) then


>*Tax Collector Khugra places his seal on the certificate before returning it to you.*


>**Tax Collector Khugra says:** Ahh, a new taxpayer, wonderful! You must always remember that it is a distinct privilege to contribute to the upkeep of our noble society and not merely a duty or a burden. I look forward to collecting your honorable taxes in the future. May the spirits prosper you, Soandso.


eq.set_global("Shar_Vahl_Cit","3",5,"F");





 **You receive:**  [Stamped Certificate of Taxability](/item/2875) 

**This NPC *should* return incorrect items given.**





