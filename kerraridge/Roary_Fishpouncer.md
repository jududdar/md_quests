# Roary Fishpouncer



[Roary Fishpouncer](/npc/74069) is a level 13 Kerran Shopkeeper that spawns in [Kerra Isle](/zone/74).



## Dialog

**You say:** `Hail`



>**Roary Fishpouncer says:** Rrrr.. catching and prrreparing fish is my specialty. Perrrhaps you could fetch for me some [rrrare fish] so that I may demonstrate my skill? Rrrr.

**You say:** `rrrare fish`



>**Roary Fishpouncer says:** Rrrr.. my most delectable dish is prrreparrred frrrom rrraw darkwater piranha. Unforrrtunately. the pirrranha only surrrvives in the murrrky waterrrs of the wicked Nektulos forrrest. I will rrreward any brrrave fisherman who can brrring me some rrraw darkwater pirranha.
end



## Turn-Ins



local text = "Rrrrr... I need both the spear and a frrresh fish to prrrepare the spear with the oil.";



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_799.png" alt="" /> <a
                                href="/item/12318" data-url="12318" class="tooltip-link link">Raw Darkwater Piranha</a>) then


>**Roary Fishpouncer says:** Rrrr... my mouth is waterrring alrrrready. Ourrr trribe shall feast well tonight. You have prrroven yourself a fisherrrman worrrthy of one of my special spearrrs. They are coated with a specially prrrepared fish oil. When all the oil has washed off, you may rrreturn the spear to me along with a frrresh fish and I will rrreapply the oil for you.


Your faction standing with [Kerra Isle](/faction/382) got better (<span class='text-success'>+20</span>)



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_740.png" alt="" /> <a
                                href="/item/7027" data-url="7027" class="tooltip-link link">Kerran Fishing Spear</a> 

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_740.png" alt="" /> <a
                                href="/item/7027" data-url="7027" class="tooltip-link link">Kerran Fishing Spear</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_775.png" alt="" /> <a
                                href="/item/13019" data-url="13019" class="tooltip-link link">Fresh Fish</a>) then 


>**Roary Fishpouncer says:** Rrrr... been doing some deepwater fishing, I presume? Here is your spear with a frrresh coat of my special oil.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_740.png" alt="" /> <a
                                href="/item/7027" data-url="7027" class="tooltip-link link">Kerran Fishing Spear</a> 

 
end





