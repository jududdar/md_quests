# Trizam N\`Tan



[Trizam N\`Tan](/npc/41065) is a level 61 Dark Elf GM Warrior that spawns in [Neriak - Commons](/zone/41).



## Dialog

**You say:** `hail`



>**Trizam N-Tan says:** And who do you think you are? To step into the Cauldron of Hate one should have the black soul of a warrior. For one to speak with Trizam he should have good reason. Perhaps you return with tales of [deathfist] agendas. If so, then you're a year too late.

**You say:** `deathfist`



if **Faction** >= Amiable then



>**Trizam N-Tan says:** Have you been spending day and night at the Malden's Fancy?!! The Deathfist Orcs in the Commonlands are up to something. As the inept humans in Freeport hunt down the warrior orcs, the pawns run about on some secret mission. I have been appointed by King Nathox to attend to this matter and hire young warriors who wish to [collect] pawn kills.


elseif **Faction** >= Indifferent then



>**Trizam N-Tan says:** Go! Return when you have done more to serve the Indigo Brotherhood of Neriak. Fewer Leatherfoot Raiders in Nektulos and a few Leatherfoot skullcaps in the palms of Master Narex shall prove your true warrior nature and loyalty to our house.


else



>**Trizam N-Tan says:** Your head will make a fine trophy in the halls of the Indigo Brotherhood.




**You say:** `collect`



if **Faction** >= Amiable then



>**Trizam N-Tan says:** Yes, You will. You need not know the reason why. I command you by order of King Naythox Thex to venture forth to the Commonlands and slay all the orc pawns you see. Return with four pawn picks and maybe I shall even reward you. Leave at once or you shall find yourself hanging from the Hooks of Innoruuk!


elseif **Faction** >= Indifferent then



>**Trizam N-Tan says:** Go! Return when you have done more to serve the Indigo Brotherhood of Neriak. Fewer Leatherfoot Raiders in Nektulos and a few Leatherfoot skullcaps in the palms of Master Narex shall prove your true warrior nature and loyalty to our house.


else



>**Trizam N-Tan says:** Your head will make a fine trophy in the halls of the Indigo Brotherhood.



end



## Turn-Ins



local text = "I instructed you to return with no fewer than four pawn picks!";



if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_768.png" alt="" /> <a
                                href="/item/13885" data-url="13885" class="tooltip-link link">Orc Pawn Pick</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_768.png" alt="" /> <a
                                href="/item/13885" data-url="13885" class="tooltip-link link">Orc Pawn Pick</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_768.png" alt="" /> <a
                                href="/item/13885" data-url="13885" class="tooltip-link link">Orc Pawn Pick</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_768.png" alt="" /> <a
                                href="/item/13885" data-url="13885" class="tooltip-link link">Orc Pawn Pick</a>) then


>**Trizam N-Tan says:** So you have done your part to serve the King. As instructed, I shall reward your good deed. But I choose to reward you with provisions from the pantries of Neriak. They shall keep you strong.


Your faction standing with [Indigo Brotherhood](/faction/270) got better (<span class='text-success'>+10</span>)


Your faction standing with [Emerald Warriors](/faction/326) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Steel Warriors](/faction/311) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Primordial Malice](/faction/1522) got worse (<span class='text-danger'>-20</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_832.png" alt="" /> <a
                                href="/item/13022" data-url="13022" class="tooltip-link link">Rotgrub Rye</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_825.png" alt="" /> <a
                                href="/item/13021" data-url="13021" class="tooltip-link link">Neriak Nectar</a>) (+1000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 2 <img src='/static/icons/item_645.png' width='14' height='14'/> 5 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**








