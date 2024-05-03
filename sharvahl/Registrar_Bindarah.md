# Registrar Bindarah









## Dialog

local qglobals = eq.get_qglobals(e.self,e.other);







**You say:** `certificate`



>**Registrar Bindarah says:** Luckily for you, someone found this blowing around the plaza.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_860.png" alt="" /> <a
                                href="/item/2874" data-url="2874" class="tooltip-link link">Certificate of Taxability</a>

**You say:** `note`



>**Registrar Bindarah says:** Luckily for you, someone found this stuck in a bush.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/18299" data-url="18299" class="tooltip-link link">Note to King Raja</a>

**You say:** `application`



>**Registrar Bindarah says:** Luckily for you, someone found this on the floor in the bakery.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_869.png" alt="" /> <a
                                href="/item/2897" data-url="2897" class="tooltip-link link">Notarized Application</a>

**You say:** `acrylia slate`






 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1036.png" alt="" /> <a
                                href="/item/2877" data-url="2877" class="tooltip-link link">Acrylia Slate of Shar Vahl</a>
end



## Turn-Ins



local text = "This item, by itself, means nothing to me.";





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_869.png" alt="" /> <a
                                href="/item/2873" data-url="2873" class="tooltip-link link">Application for Citizenship</a>) then


>**Registrar Bindarah says:** Young Soandso, I will be happy to process your registration for you. While I etch your name on our people's book of records I will require you to run a couple of errands. Take this certificate to the tax collector and obtain his seal. While you're out doing that, have Mignah create your personal Acrylia slate for you. Bring both the seal and the slate to me as soon as you can.


eq.set_global("Shar_Vahl_Cit","2",5,"F");


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_860.png" alt="" /> <a
                                href="/item/2874" data-url="2874" class="tooltip-link link">Certificate of Taxability</a> (+300 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_860.png" alt="" /> <a
                                href="/item/2875" data-url="2875" class="tooltip-link link">Stamped Certificate of Taxability</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1036.png" alt="" /> <a
                                href="/item/2876" data-url="2876" class="tooltip-link link">Acrylia Slate</a>) then


>**Registrar Bindarah says:** Ahh, there you are. I was about to send someone looking for you. Everything seems to be in order here, only one task remains. You must gain audience with the king and swear fealty to his highness by handing him this document. Return to me when this is done.


eq.set_global("Shar_Vahl_Cit","4",5,"F");


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/18299" data-url="18299" class="tooltip-link link">Note to King Raja</a> (+300 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/18304" data-url="18304" class="tooltip-link link">Note from King Raja</a>) then 


>**Registrar Bindarah says:** Well done, Soandso, I am honored to be the first to welcome you to citizenship of Shar Vahl! May you serve our society as well as it serves you. Return to your guildmaster and present both the slate and the application to him. The acrylia slate shall henceforth serve as proof of your citizenship.


eq.set_global("Shar_Vahl_Cit","6",5,"F");


>**Registrar Bindarah says:** Oh, by the way, be careful with this as it will be important for recording your service to our society. If you should somehow lose it, ask me about your slate and I will issue you a new one.


Your faction standing with [Citizens of Shar Vahl](/faction/1584) got better (<span class='text-success'>+400</span>)


 &#127873; **You receive:** GiveAll( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1036.png" alt="" /> <a
                                href="/item/2877" data-url="2877" class="tooltip-link link">Acrylia Slate of Shar Vahl</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_869.png" alt="" /> <a
                                href="/item/2897" data-url="2897" class="tooltip-link link">Notarized Application</a>) (+400 exp)

 

**This NPC *should* return incorrect items given.**
