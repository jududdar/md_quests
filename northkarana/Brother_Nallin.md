# Brother Nallin



[Brother Nallin](/npc/13049) is a level 31 Human Cleric that spawns in [Northern Plains of Karana](/zone/13).



## Dialog

**You say:** `hail`



if **Faction** >= Indifferent then



>**Brother Nallin says:** May the Prime Healer watch over your body as you pass through  these dangerous lands.  I am Brother Nallin of the [Temple of Life].  I was dispatched to aid the guards and residents of the plains.  I can assist you if you have need of me to [cure poison] or [cure disease].


else



>**Brother Nallin says:** Your mere presence disgusts me. Please remove yourself from my sight. Until you change yourself and your ways, you are unwelcome in the Temple of Life.


**You say:** `cure disease`



if **Faction** >= Indifferent then



>**Brother Nallin says:** Yes,  I can cast the disease from your body with the power of the Prime Healer.  First, you must make an offering to the Temple of Life.  The offering is five gold coins.


else



>**Brother Nallin says:** Your mere presence disgusts me. Please remove yourself from my sight. Until you change yourself and your ways, you are unwelcome in the Temple of Life.


**You say:** `cure poison`



if **Faction** >= Indifferent then



>**Brother Nallin says:** If you would like me to cure poison, you must offer me four water flasks.  I shall see that the residents of the plains get your donation and we shall try to cast the toxin from your body.


else



>**Brother Nallin says:** Your mere presence disgusts me. Please remove yourself from my sight. Until you change yourself and your ways, you are unwelcome in the Temple of Life.


**You say:** `temple of life`



>**Brother Nallin says:** Within the walls of Qeynos can be found the home of the Priests of Life, the Temple of Life.  It is there that good people pay tribute to the great Prime Healer, Rodcet Nife.

**You say:** `heal`



>**Brother Nallin says:** I am afraid I was not authorized by the High Priests of the Temple of Life to perform such an act, however, I'm certain you can obtain such a service within the walls of Qeynos.
end



## Turn-Ins




if **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_584.png" alt="" /> <a
                                href="/item/13006" data-url="13006" class="tooltip-link link">Water Flask</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_584.png" alt="" /> <a
                                href="/item/13006" data-url="13006" class="tooltip-link link">Water Flask</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_584.png" alt="" /> <a
                                href="/item/13006" data-url="13006" class="tooltip-link link">Water Flask</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_584.png" alt="" /> <a
                                href="/item/13006" data-url="13006" class="tooltip-link link">Water Flask</a>) then


>**Brother Nallin says:** May Rodcet Nife breathe upon your body and soul and banish the evil from within.


**Brother Nallin casts:** [Cure Poison](/spell/203) on target.

elseif **Faction** >= Indifferent and  **You turn in:** gold = 5) then


>**Brother Nallin says:** May Rodcet Nife breathe upon your body and soul and banish the evil from within.


**Brother Nallin casts:** [Cure Disease](/spell/213) on target.

else



>**Brother Nallin says:** Your mere presence disgusts me. Please remove yourself from my sight. Until you change yourself and your ways, you are unwelcome in the Temple of Life.

**This NPC *should* return incorrect items given.**

end