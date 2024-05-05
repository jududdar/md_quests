# Tack Shieldson



[Tack Shieldson](/npc/160398) is a level 43 Dwarf Warrior that spawns in [Katta Castellum](/zone/160).





## Dialog

local rowle = eq.get_entity_list():GetMobByNpcTypeID(160207);

**You say:** `share a pint`



if(rowle.valid) then



rowle:Say("That'd be great! By Brell, a short beer or a honey mead'd be a nice change from?");



>**Tack Shieldson says:** Shhhhhh!!' He runs over and kicks Rowle in the kneecap and chuckles under his beard in your direction. Speaking under his breath to Rowle, 'Don' be such an idjit, now this lad came all the way from Norrath, why not try some of the fabled ales we'd heard our pappy's talkin' of?


if(rowle.valid) then



rowle:Emote("catches on slowly, 'ahhh, roight! Good show, Tack! D'ye think 'e would go te that kinda trouble fer us?'");


**You say:** `trouble`



if(rowle.valid) then



rowle:Emote("clears his throat and flashes a broken-toothed grin your way, 'Ye know, me dwarven heart longs for me first taste o' some underfoot brown, a reputed fine stout not available 'ere on Luclin... Ye know, if ye can manage it that is.'");



>**Tack Shieldson says:** Ahhh, worthy o' Brell hisself or so they say. Ye know when I was just a pup, back before the exodus, me uncle used te talk about stompin' trolls and then sitting back with a  Boot Beer te celebrate the day's victory. I, ummm, really would be able te get in touch with me heritage were I able to sample some o' that fine stout. Ye'd be a true friend to the Validus Custodus fer helpin' us out friend. My thanks to ye in advance.
end




## Turn-Ins





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_633.png" alt="" /> <a
                                href="/item/19188" data-url="19188" class="tooltip-link link">Boot Beer</a>) then


>*Tack Shieldson gingerly takes the boot from you, handling it as though it were a fine porcelain. With a look of thanks to you he slowly lifts it to his lips and suddenly tips it back to empty it in one gulp, frothing his beard in the process. 'Yar! That's the ticket! Damn fine stuff that is, just like me uncle always said. A service to the Validus Custodus have ye done, my friend... And I'd be happy to assist ye in that service again sometime. HAR!'*


Your faction standing with [Validus Custodus](/faction/1503) got better (<span class='text-success'>+1</span>)


Your faction standing with [Katta Castellum Citizens](/faction/1502) got better (<span class='text-success'>+1</span>)


Your faction standing with [Magus Conlegium](/faction/1504) got better (<span class='text-success'>+1</span>)


Your faction standing with [Nathyn Illuminious](/faction/1505) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Coterie of the Eternal Night](/faction/1506) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Seru](/faction/1483) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Hand of Seru](/faction/1484) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Eye of Seru](/faction/1485) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Hand Legionnaries](/faction/1541) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:** 0 (+10000 exp)

 

**This NPC *should* return incorrect items given.**
