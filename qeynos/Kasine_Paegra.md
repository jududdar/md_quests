# Kasine Paegra



[Kasine Paegra](/npc/1045) is a level 61 Human GM Paladin that spawns in [South Qeynos](/zone/1).



## Dialog

**You say:** `hail`



if **Faction** >= Apprehensive then



>**Kasine Paegra says:** May the blessings of the Rainkeeper protect you in your travels. I am Kasine Paegra, keeper of the [Order of Thunder] medallions.


else



>**Kasine Paegra says:** You have proven yourself not only an enemy of the Knights of Thunder, but an enemy of Karana himself.  Now leave, sewer rat!


**You say:** `order of thunder`



if **Faction** >= Indifferent then



>**Kasine Paegra says:** The Order of Thunder is the medal awarded to a Knight of Thunder who has proven himself superior to the average warrior. All knights and priests of Thunder have one, save for the youngest members. Along with the medal comes great respect. You might say the wearer becomes more charismatic. Should you find one, please return it to Kasine Paegra, unless told otherwise.


else



>**Kasine Paegra says:** You have proven yourself not only an enemy of the Knights of Thunder, but an enemy of Karana himself.  Now leave, sewer rat!


**You say:** `karana`



>**Kasine Paegra says:** Karana, the Rainkeeper, is the provider of the storms. If it were not for the storms of Karana, life would not flourish. All should pay tribute to the Rainkeeper.

**You say:** `enchant`



if **Faction** >= Warmly +150 then



>**Kasine Paegra says:** If you wish the power of the Rainkeeper to once again whine upon your weapon, you must hand me Bonethunder and 500 Gold Coins.


elseif **Faction** >= Indifferent then



>**Kasine Paegra says:** Well, friend, the Temple of Thunder has recognized and appreciates your past deeds for us. But this matter is of vital importance to us and we need more proof of your devotion to our cause.


else



>**Kasine Paegra says:** You have proven yourself not only an enemy of the Knights of Thunder, but an enemy of Karana himself.  Now leave, sewer rat!

end



## Turn-Ins



local text = "I am ordered to only enchant the spell when I have both Bonethunder and 500 gold coins.";



if **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1002.png" alt="" /> <a
                                href="/item/13287" data-url="13287" class="tooltip-link link">Order of Thunder</a>) then 


>**Kasine Paegra says:** You are a very honorable person. You have returned an Order of Thunder which you truly do not need. I give you the protection of the Rainkeeper to watch over you. May it keep you from harm. Go and serve.





**Kasine Paegra casts:** [Holy Armor](/spell/11) on target.


Your faction standing with [Knights of Thunder](/faction/280) got better (<span class='text-success'>+10</span>)




Your faction standing with [Bloodsabers](/faction/221) got worse (<span class='text-danger'>-10</span>)



Your faction standing with [Priests of Life](/faction/341) got better (<span class='text-success'>+7</span>)




Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+7</span>)




 &#127873; **You receive:** 0 (+1000 exp)

 

elseif **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1002.png" alt="" /> <a
                                href="/item/13288" data-url="13288" class="tooltip-link link">Order of Thunder</a>) then 


>**Kasine Paegra says:** You have returned an Order of Thunder which has been drained of all its power.  I wonder how this could have happened.  No doubt evil is behind this.  Thank you for its return.  I give you the blessings of Karana.  Go and serve the Rainkeeper.


**Kasine Paegra casts:** [Minor Healing](/spell/200) on target.


Your faction standing with [Knights of Thunder](/faction/280) got better (<span class='text-success'>+20</span>)




Your faction standing with [Bloodsabers](/faction/221) got worse (<span class='text-danger'>-20</span>)



Your faction standing with [Priests of Life](/faction/341) got better (<span class='text-success'>+15</span>)




Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+15</span>)




 &#127873; **You receive:** 0 (+1000 exp)

 

elseif **Faction** >= Warmly +150 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_602.png" alt="" /> <a
                                href="/item/6358" data-url="6358" class="tooltip-link link">Bonethunder Staff</a>, gold = 500) then 


>**Kasine Paegra says:** The Rainkeeper has bestowed this weapon with power once more. Take it and defend our temple.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_602.png" alt="" /> <a
                                href="/item/6358" data-url="6358" class="tooltip-link link">Bonethunder Staff</a> (+0 exp)

 

**This NPC *should* return incorrect items given.**

