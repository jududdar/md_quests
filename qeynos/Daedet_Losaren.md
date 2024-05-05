# Daedet Losaren



[Daedet Losaren](/npc/1067) is a level 61 Human GM Cleric that spawns in [South Qeynos](/zone/1).



## Dialog

local fac = e.other:GetFaction(e.self);

**You say:** `hail`



>**Daedet Losaren says:** Welcome, Soandso. I am Deadet Losaren, faithful priest of Karana. You appear to be in search of [guidance] or perhaps you are merely a [visitor to the temple of thunder] wishing the blessing of [holy armor]?

**You say:** `guidance`



if(fac < 5) then



>**Daedet Losaren says:** So it is guidance you seek. You will begin on the bottom rung. There is much more to our temple than the bashing of foes. We will need you to [collect donations].


elseif(fac == 5) then



>**Daedet Losaren says:** Well, friend, the Temple of Thunder has recognized and appreciates your past deeds for us. But this matter is of vital importance to us and we need more proof of your devotion to our cause.


elseif(fac > 5) then



>**Daedet Losaren says:** You have proven yourself not only an enemy of the Knights of Thunder, but an enemy of Karana himself. Now leave, sewer rat!






**You say:** `collect donation`



if(fac < 5) then



>**Daedet Losaren says:** Then you are a new acolyte. Take this Chest of Faith into Qeynos and Qeynos Hills. Find me six residents will to donate to the Temple of Thunder. Combine these donations within the Chest of Faith and return it to me. Do so and I shall reward you with the spell 'Ward Undead.' Now go and spread the Word of Karana.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_608.png" alt="" /> <a
                                href="/item/17925" data-url="17925" class="tooltip-link link">Chest of Faith</a>


elseif(fac == 5) then



>**Daedet Losaren says:** Well, friend, the Temple of Thunder has recognized and appreciates your past deeds for us. But this matter is of vital importance to us and we need more proof of your devotion to our cause.


elseif(fac > 5) then



>**Daedet Losaren says:** You have proven yourself not only an enemy of the Knights of Thunder, but an enemy of Karana himself. Now leave, sewer rat!






**You say:** `visitor to the temple of thunder`



>**Daedet Losaren says:** Then feel free to look around and speak with the priests and paladins of Thunder. May you find ways to serve the Rainkeeper.

**You say:** `holy armor`



>**Daedet Losaren says:** Holy Armor? I offer the blessing of Holy Armor to members in good standing of the Knights of Thunder. I must charge ten gold for the service. [Components] are expensive these days!

**You say:** `components`



>**Daedet Losaren says:** Components are required for my daily tribute to the Rainkeeper. It is he whose power flows from my body. I require a faithful acolyte to [gather the required items].

**You say:** `gather the required items`



if(fac < 5) then



>**Daedet Losaren says:** Very noble of you. Take this chest. I will require it to be filled with flame beetle eyes. Four normal beetles and four [Kerra Isle beetles]. Combine these items within the chest and return it to me. I shall reward you with the protection of Holy Armor.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_608.png" alt="" /> <a
                                href="/item/17934" data-url="17934" class="tooltip-link link">Beetle Eye Chest</a>


elseif(fac == 5) then



>**Daedet Losaren says:** Well, friend, the Temple of Thunder has recognized and appreciates your past deeds for us. But this matter is of vital importance to us and we need more proof of your devotion to our cause.


elseif(fac > 5) then



>**Daedet Losaren says:** You have proven yourself not only an enemy of the Knights of Thunder, but an enemy of Karana himself. Now leave, sewer rat!






**You say:** `Kerra Isle beetles`



>**Daedet Losaren says:** Kerra Isle beetles are normally found in the vicinity of the Kerra catpeople. They can be found in Kerra Ridge, but a closer and perhaps safer location would be on the island between Antonica and Odus. The outcast catpeople of that island are far less dangerous.

**You say:** `karana`



>**Daedet Losaren says:** Karana, the Rainkeeper, is the provider of the storms. If it were not for the storms of Karana, life would not flourish. All should pay tribute to the Rainkeeper.

**You say:** `Bertoxxulous`



>**Daedet Losaren says:** Bertoxxulous, the Plaguebringer, is the Lord of Disease. It is he who smites Norrath with his diseases and imperfections. Those who follow him are called [Bloodsabers].





**You say:** `Bloodsabers`



>**Daedet Losaren says:** It is rumored that there is a shrine in the great city of Qeynos which pays homage to the Plaguebringer, Bertoxxulous. The members of this vile church of the damned are called the Bloodsabers. They are dreaded shadowknights, necromancers and evil clerics. It is our duty to destroy all who dare to pray to such a deity. Join our fight. Speak more of this matter with Chesgard Sydwend.



**You say:** `drosco`



>**Daedet Losaren says:** Have you knowledge of Sir Drosco? He is a Knight of Thunder and reports to Sir Wolten. He has been missing for quite some time. I believe Sir Wolten has begun a search for him.


**You say:** `healer`



>**Daedet Losaren says:** If you need to be healed, I suggest you speak with the Priests of Life. You can find them in the Temple of Life on the other side of Qeynos. The only service you can pay for here is holy armor. Daedet Losaren charges followers of Karana for that blessing.



 



## Turn-Ins

local fac = e.other:GetFaction(e.self);



if( **You turn in:** gold = 20 and (fac < 5)) then


>**Daedet Losaren says:** This should help you remain safe.


e.other:SelfCast(11);

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_608.png" alt="" /> <a
                                href="/item/13395" data-url="13395" class="tooltip-link link">Beetle Eye Chest</a>) then 


>**Daedet Losaren says:** You have done well. Karana is pleased. I cannot say the same for the cat people. I now bestow upon you the knowledge of Holy Armor. Study the words and soon the power shall be bestowed upon you by the greatness that is the Rainkeeper.





Your faction standing with [Knights of Thunder](/faction/280) got better (<span class='text-success'>+10</span>)


Your faction standing with [Bloodsabers](/faction/221) got worse (<span class='text-danger'>-10</span>)


Your faction standing with [Priests of Life](/faction/341) got better (<span class='text-success'>+7</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+7</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15011" data-url="15011" class="tooltip-link link">Spell: Holy Armor</a> (+200 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-20 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_836.png" alt="" /> <a
                                href="/item/13289" data-url="13289" class="tooltip-link link">Chest of Faith</a>) then 


>**Daedet Losaren says:** You have done supremely well, my young acolyte of Thunder. For your great service to the Temple of Thunder. Now go and cast the storm into the populace of Antonica.





Your faction standing with [Knights of Thunder](/faction/280) got better (<span class='text-success'>+10</span>)


Your faction standing with [Bloodsabers](/faction/221) got worse (<span class='text-danger'>-10</span>)


Your faction standing with [Priests of Life](/faction/341) got better (<span class='text-success'>+7</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+7</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15218" data-url="15218" class="tooltip-link link">Spell: Ward Undead</a> (+200 exp)

 

**This NPC *should* return incorrect items given.**
