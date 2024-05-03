# Bonlarg


## Dialog

**You say:** `Hail`



>**Bonlarg says:** Shadowknight master me be!!  Soandso prove to me that Soandso be worthy to be one with Greenblood and me give Soandso black shadow tunic.  You [want black shadow tunic]?

**You say:** `want black shadow tunic`



if **Faction** >= Amiable then



>**Bonlarg says:** You hunt lizard scouts. Them sometimes carry special fife to talk to other lizards far away. Greenbloods stop them. Bring Bonlarg three lizard scout fifes and green stained skin tunic you gots when you first talk to Soonog. Give all to Bonlarg and get tunic.




elseif **Faction** >= Indifferent then



>**Bonlarg says:** Help Greenbloods you will. Give lizard tails to Grevak.  Den maybe we trust.


else



>**Bonlarg says:** Foe of Greenbloods you are. In two I will rip you. Best if run.



end



## Turn-Ins



local text = "Fool! Bonlarg say THREE lizardman scout fifes and green stained skin tunic.";




if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_751.png" alt="" /> <a
                                href="/item/12198" data-url="12198" class="tooltip-link link">Lizardman Scout Fife</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_751.png" alt="" /> <a
                                href="/item/12198" data-url="12198" class="tooltip-link link">Lizardman Scout Fife</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_751.png" alt="" /> <a
                                href="/item/12198" data-url="12198" class="tooltip-link link">Lizardman Scout Fife</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_538.png" alt="" /> <a
                                href="/item/12199" data-url="12199" class="tooltip-link link">Black Shadow Tunic</a> (+500 exp)

 

**This NPC *should* return incorrect items given.**





