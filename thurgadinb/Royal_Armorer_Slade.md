# Royal Armorer Slade


## Dialog

**You say:** `hail`



if **Faction** >= Warmly then



>**Royal Armorer Slade says:** Welcome, Soandso. I'm Slade, Royal Armorer to the Dain and his personal guardsmen. I've heard yer name once or twice in these halls and apparently ye've earned the respect of my people. In light of that I'm willin ta offer my [services] to you if'n ye need them.


elseif **Faction** >= Indifferent then



>**Royal Armorer Slade says:** I'm sorry, Soandso, while I've heard good things about ye you've yet to prove yerself enough to my people to earn my services.


else



>**Royal Armorer Slade says:** Leave me be, " .. e.other:Race() .. ". I have no reason to trust you yet.


**You say:** `service`



if **Faction** >= Warmly then



>**Royal Armorer Slade says:** If'n ye've had the fortune to earn any of the plate helms that are made by my people in the city then I can use my skills to custom fit and detail it for a " .. e.other:Race() .. " of yer like. I can do this fer the Dark Runed Crown, the Runed Protector's Helm, the Resonant Helm, the Crown of Forbidden Rites, Crown of the Kromzek Kings, Frostreaver's Velium Crown, Cowl of Mortality, and the Champions Crown. Simply hand me one of these and I'll do the work for you.


elseif **Faction** >= Indifferent then



>**Royal Armorer Slade says:** I'm sorry, Soandso, while I've heard good things about ye you've yet to prove yerself enough to my people to earn my services.


else



>**Royal Armorer Slade says:** Leave me be, " .. e.other:Race() .. ". I have no reason to trust you yet.

end

## Turn-Ins





if( **Faction is** >= Kindly) then 


if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_746.png" alt="" /> <a
                                href="/item/31084" data-url="31084" class="tooltip-link link">Champion's Crown</a>) then



>**Royal Armorer Slade says:** Here you are Soandso. Ah, a perfect fit! May it serve you well.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_746.png" alt="" /> <a
                                href="/item/31519" data-url="31519" class="tooltip-link link">Custom Champion's Crown</a> 

 


elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_625.png" alt="" /> <a
                                href="/item/26025" data-url="26025" class="tooltip-link link">Cowl of Mortality</a>) then



>**Royal Armorer Slade says:** Here you are Soandso. Ah, a perfect fit! May it serve you well.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_625.png" alt="" /> <a
                                href="/item/2612" data-url="2612" class="tooltip-link link">Custom Cowl of Mortality</a> 

 


elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_523.png" alt="" /> <a
                                href="/item/31042" data-url="31042" class="tooltip-link link">Crown of Forbidden Rites</a>) then



>**Royal Armorer Slade says:** Here you are Soandso. Ah, a perfect fit! May it serve you well.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_523.png" alt="" /> <a
                                href="/item/31518" data-url="31518" class="tooltip-link link">Custom Crown of Forbidden Rites</a> 

 


elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_523.png" alt="" /> <a
                                href="/item/25194" data-url="25194" class="tooltip-link link">Crown of the Kromzek Kings</a>) then



>**Royal Armorer Slade says:** Here you are Soandso. Ah, a perfect fit! May it serve you well.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_523.png" alt="" /> <a
                                href="/item/2611" data-url="2611" class="tooltip-link link">Custom Crown of the Kromzek Kings</a> 

 


elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_523.png" alt="" /> <a
                                href="/item/31000" data-url="31000" class="tooltip-link link">Dark Runed Crown</a>) then



>**Royal Armorer Slade says:** Here you are Soandso. Ah, a perfect fit! May it serve you well.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_523.png" alt="" /> <a
                                href="/item/31515" data-url="31515" class="tooltip-link link">Custom Dark Runed Crown</a> 

 


elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_523.png" alt="" /> <a
                                href="/item/30507" data-url="30507" class="tooltip-link link">Frostreaver's Velium Crown</a>) then



>**Royal Armorer Slade says:** Here you are Soandso. Ah, a perfect fit! May it serve you well.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_523.png" alt="" /> <a
                                href="/item/2610" data-url="2610" class="tooltip-link link">Custom Frostreavers Velium Crown</a> 

 


elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_746.png" alt="" /> <a
                                href="/item/31035" data-url="31035" class="tooltip-link link">Resonant Helm</a>) then



>**Royal Armorer Slade says:** Here you are Soandso. Ah, a perfect fit! May it serve you well.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_746.png" alt="" /> <a
                                href="/item/31517" data-url="31517" class="tooltip-link link">Custom Resonant Helm</a> 

 


elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_746.png" alt="" /> <a
                                href="/item/31021" data-url="31021" class="tooltip-link link">Runed Protector's Helm</a>) then



>**Royal Armorer Slade says:** Here you are Soandso. Ah, a perfect fit! May it serve you well.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_746.png" alt="" /> <a
                                href="/item/31516" data-url="31516" class="tooltip-link link">Custom Runed Protector's Helm</a> 

 


**This NPC *should* return incorrect items given.**

