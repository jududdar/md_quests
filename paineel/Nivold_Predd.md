# Nivold Predd



[Nivold Predd](/npc/75071) is a level 61 Erudite GM Cleric that spawns in [Paineel](/zone/75).



## Dialog

**You say:** `hail`



if **Faction** >= Amiable then



>**Nivold Predd says:** What do you want? Do not disturb me lest you plan to assist in my [summoning of Dread].


elseif **Faction** >= Indifferent then



>**Nivold Predd says:** I sense the potential to learn the ways of fear within you. Continue striving to master your fear and one day perhaps you can be of service to our Lord Cazic-Thule.




else



>**Nivold Predd says:** Begone from this place! Infidels like you have no place among the faithful of Cazic-Thule!





**You say:** `summoning of dread`



if **Faction** >= Amiable then



>**Nivold Predd says:** There are some components essential to the summoning of the avatar of Dread. I require the eye of a griffon. some [powder of reanimation]. the brain of the Ishva Mal. and the toes of an ice giant. Fetch me these reagents so that we may summon the avatar to forge a shield worn only by the mightiest apostles of Cazic-Thule.


elseif **Faction** >= Indifferent then



>**Nivold Predd says:** I sense the potential to learn the ways of fear within you. Continue striving to master your fear and one day perhaps you can be of service to our Lord Cazic-Thule.




else



>**Nivold Predd says:** Begone from this place! Infidels like you have no place among the faithful of Cazic-Thule!





**You say:** `powder of reanimation`



if **Faction** >= Amiable then



>**Nivold Predd says:** There is a gnome necromancer who has been experimenting with a powder used in reanimating long dead organic tissue. He is known to frequent places populated by undead in order to pursue his research. Seek him out and procure a bit of his powder.


elseif **Faction** >= Indifferent then



>**Nivold Predd says:** I sense the potential to learn the ways of fear within you. Continue striving to master your fear and one day perhaps you can be of service to our Lord Cazic-Thule.




else



>**Nivold Predd says:** Begone from this place! Infidels like you have no place among the faithful of Cazic-Thule!




end



## Turn-Ins



local text = "I require all four reagents, anything less is useless. Incompetence will get you nowhere amongst the faithful of Cazic-Thule!";



if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1094.png" alt="" /> <a
                                href="/item/16540" data-url="16540" class="tooltip-link link">Ice Giant Toes</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_885.png" alt="" /> <a
                                href="/item/13739" data-url="13739" class="tooltip-link link">Griffon Eye</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1018.png" alt="" /> <a
                                href="/item/14111" data-url="14111" class="tooltip-link link">Brain of the Ishva Mal</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_582.png" alt="" /> <a
                                href="/item/14112" data-url="14112" class="tooltip-link link">Powder of Reanimation</a>) then


>**Nivold Predd says:** Commendable work, you have proven yourself a valuable member of our order. Our chanters have summoned the avatar of Dread. Hurry and take him this mundane shield so that he may forge it into a truly valuable symbol of your devotion to the lord of Fear!


Your faction standing with [Heretics](/faction/265) got better (<span class='text-success'>+400</span>)


Your faction standing with [Deepwater Knights](/faction/242) got worse (<span class='text-danger'>-400</span>)


Your faction standing with [Gate Callers](/faction/254) got worse (<span class='text-danger'>-400</span>)


Your faction standing with [Craftkeepers](/faction/231) got worse (<span class='text-danger'>-400</span>)


Your faction standing with [Crimson Hands](/faction/233) got worse (<span class='text-danger'>-400</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_805.png" alt="" /> <a
                                href="/item/14105" data-url="14105" class="tooltip-link link">Mundane Shield</a> (+5000 exp)

**You receive coin:** 1-9 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-9 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-9 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-9 <img src='/static/icons/item_647.png' width='14' height='14'/> 


**Spawn NPC:**  [avatar of dread](/npc/75194) at (**y:** 1230, **x:** 474)

**This NPC *should* return incorrect items given.**
;

