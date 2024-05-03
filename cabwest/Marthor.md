# Marthor




## Dialog

local qglobals = eq.get_qglobals(e.self,e.other);

**You say:** `hail`



>*Marthor hiccups and breathes drunken breath in your face saying, Leave me be, can't you see that I am meditating or something?*

**You say:** `master tynn`



>**Marthor says:** Supreme Master Tynn was the only one that has even seen the weapon. I do not know its origin. I tell you though, you would need to be as powerful as he was to be able to wield the weapon. Only an Iksar of the last rung would be able to use it, come back and show me you have earned your [Tynnonium Shackle] and I will discuss with you what I know.

**You say:** `tynnonium`



>**Marthor says:** Veltar was one with the ways of Tynn. He did return to Cabilis, I know you have rescued him from his cell. He has traveled afar to clear his mind of his torture in the mines. He did not say where his travels would take him. You will have to find him once more and ask him about the Tynnonium Shackle he still wears.
end



## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_830.png" alt="" /> <a
                                href="/item/8348" data-url="8348" class="tooltip-link link">Trog Brew</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_830.png" alt="" /> <a
                                href="/item/8348" data-url="8348" class="tooltip-link link">Trog Brew</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_830.png" alt="" /> <a
                                href="/item/8348" data-url="8348" class="tooltip-link link">Trog Brew</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_830.png" alt="" /> <a
                                href="/item/8348" data-url="8348" class="tooltip-link link">Trog Brew</a>) then


>**Marthor says:** Ha! How did you know my favorite drink? Master Rinmark told you? That crazy old monk spends his days sitting on that mountain in Timorous Deep doesn't he? And they call me a drunkard! Anyhow, I bet he told you about the Whistling Fists. I have never seen them myself, and have only heard legend passed down by [Master Tynn].


eq.set_global("Brew","1",1,"F");


eq.set_global("Brew1","1",1,"F");


eq.set_global("Brew2","1",1,"F");

if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_671.png" alt="" /> <a
                                href="/item/4199" data-url="4199" class="tooltip-link link">Shackle of Tynnonium</a>) then


>**Marthor says:** You earned the Tynnonium Shackle? I am sure you wish to seek the fists of lore. Gandan has come as close as anyone, you would have to talk to him. Last I heard his expedition has taken him to the Howling Stones.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_671.png" alt="" /> <a
                                href="/item/4199" data-url="4199" class="tooltip-link link">Shackle of Tynnonium</a> 

 

**This NPC *should* return incorrect items given.**





