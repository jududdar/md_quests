# Guard Valon



[Guard Valon](/npc/21109) is a level 30 Guard Warrior that spawns in [West Commonlands](/zone/21).





## Dialog

**You say:** `hail`



>**Guard Valon says:** Greetings, traveler! If you wish to walk upon the road to Freeport, you will pay the toll of two silver pieces. And you should. It is not safe to stray from the pathway. There are many [dangers in the Commonlands].

**You say:** `dangers in the commonlands`



>**Guard Valon says:** The orcs have been a nuisance of late. Many travelers have perished at the hands of the orc pawns. Would you like to [assist the Freeport Militia] in ridding the lands of the orcs?

**You say:** `assist the freeport militia`



>**Guard Valon says:** Sir Lucan would be proud!! Patrol the Commonlands and watch for any orc pawns. Should you find any orc pawn picks on them, I will pay you for every four you return to me. Be off, then! For the glory of Freeport!!

**You say:** `hunt dervish cutthroats`



if **Faction** >= Amiable then



>**Guard Valon says:** You will make a fine reserve!! Take this bag and fill it with Dervish Cutthroat Insignia Rings. When they are combined and returned to me you shall be accepted into the Reserve Freeport Militia!!



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_690.png" alt="" /> <a
                                href="/item/17975" data-url="17975" class="tooltip-link link">Bag for Cutthroat Rings</a>


elseif **Faction** >= Indifferent then



>**Guard Valon says:** Doing away with more orc pawns, and perhaps turning in the orc pawn picks to me, may increase my trust in you.


else



>**Guard Valon says:** Stand where you are, citizen. I believe you are wanted by the Freeport Militia.

end



## Turn-Ins



local text = "I cannot reward you until you hand me four orc pawn picks. So says Captain Hazran.";


if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_768.png" alt="" /> <a
                                href="/item/13885" data-url="13885" class="tooltip-link link">Orc Pawn Pick</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_768.png" alt="" /> <a
                                href="/item/13885" data-url="13885" class="tooltip-link link">Orc Pawn Pick</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_768.png" alt="" /> <a
                                href="/item/13885" data-url="13885" class="tooltip-link link">Orc Pawn Pick</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_768.png" alt="" /> <a
                                href="/item/13885" data-url="13885" class="tooltip-link link">Orc Pawn Pick</a>) then


>**Guard Valon says:** You have done well. Keep up the good work and we may trust you to [hunt dervish cutthroats] which in turn will allow you to join the Reserve Freeport Militia.


Your faction standing with [The Freeport Militia](/faction/330) got better (<span class='text-success'>+3</span>)


Your faction standing with [Coalition of Tradefolk Underground](/faction/336) got better (<span class='text-success'>+1</span>)


Your faction standing with [Knights of Truth](/faction/281) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Priests of Marr](/faction/362) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:** 0 (+500 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-5 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_565.png" alt="" /> <a
                                href="/item/12272" data-url="12272" class="tooltip-link link">Bag of Cutthroat Rings</a>) then


>**Guard Valon says:** Excellent work, Soandso!! You are quite formidable. Maybe soon you shall aid in our efforts to rid the Northern part of Freeport of the paladins!! Until then keep up the good work. Take this Armory Token to the Militia Armorer in the Militia House in Freeport to receive your tunic. He may not be there, but I assure you he will show up at some time. On the second floor. Hail Sir Lucan!!


Your faction standing with [The Freeport Militia](/faction/330) got better (<span class='text-success'>+10</span>)


Your faction standing with [Coalition of Tradefolk Underground](/faction/336) got better (<span class='text-success'>+1</span>)


Your faction standing with [Knights of Truth](/faction/281) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Priests of Marr](/faction/362) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_646.png" alt="" /> <a
                                href="/item/12273" data-url="12273" class="tooltip-link link">Militia Armory Token</a> (+500 exp)

 

**This NPC *should* return incorrect items given.**
;

