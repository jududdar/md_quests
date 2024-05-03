# King Raja Kerrath









## Dialog

local qglobals = eq.get_qglobals(e.self,e.other);

**You say:** `Hail`



>**King Raja Kerrath says:** Greetings citizen... you are very brave to approach me in this manner.  That sort of bravery warrants my respect.  How may I help you?

**You say:** `note`



>**King Raja Kerrath says:** I guess I can write you a new note. Try not to lose it this time.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/18304" data-url="18304" class="tooltip-link link">Note from King Raja</a>
end



## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/18299" data-url="18299" class="tooltip-link link">Note to King Raja</a>) then


>**King Raja Kerrath says:** Your humility and willingness to serve shall not be wasted. There is much to be done, Soandso, and our people thank you in advance for your selfless service.


eq.set_global("Shar_Vahl_Cit","5",5,"F");





 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/18304" data-url="18304" class="tooltip-link link">Note from King Raja</a> (+300 exp)

 

**This NPC *should* return incorrect items given.**





