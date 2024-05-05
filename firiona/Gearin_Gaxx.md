# Gearin Gaxx



[Gearin Gaxx](/npc/84191) is a level 40 High Elf Shopkeeper that spawns in [Firiona Vie](/zone/84).



## Dialog

**You say:** `Hail`



>**Gearin Gaxx says:** Welcome. friend!  If armor is what you seek. let the house of Gaxx provide you with the finest.  Our metalwork is second to none.  Every now and again we may even create [rare armor] for the general public to purchase.


e.self:DoAnim(29);

**You say:** `rare armor?`



>**Gearin Gaxx says:** I have found many exotic materials in Kunark with which I can create rare armor.  I currently am working on the [Guard of Ik] and the [Hate Tail Guard] shields.  I have no armor as of yet. but I am experimenting with new designs.

**You say:** `guard of ik`



>**Gearin Gaxx says:** The Guards of Ik are made from shields found in the jungles.  I would be selling them if it were not for the unfortunate fact that the shields are spectral and vanish overnight.  Another bit of bad news is that the formula I was working on to stabilize the essence of the metal was stolen by local pirates.  I need two more shields and my formula.  Bring these to me and I shall not charge you.

**You say:** `hate tail guard`



>**Gearin Gaxx says:** I can create the Hate Tail Guard using both metal and scorpion carapaces. I have the metal. I will make you one for the price of 100 gold coins - I accept only gold. I will also need two flawless carapaces from giant hate tail scorpions.
end



## Turn-Ins



local text1 = "Hey?! We had a deal! I get two ik shields and my ik formula!";

local text2 = "Like this is going to get you anything.  I can't work with this!  The going rate is 100 gold pieces and you supply the two flawless hate tail carapaces.";





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_676.png" alt="" /> <a
                                href="/item/12883" data-url="12883" class="tooltip-link link">Trooper Shield</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_676.png" alt="" /> <a
                                href="/item/12883" data-url="12883" class="tooltip-link link">Trooper Shield</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_864.png" alt="" /> <a
                                href="/item/12971" data-url="12971" class="tooltip-link link">scribbled note</a>) then


>*Gearin Gaxx places the formula in a box which appears to have similar copies in it. Thank you! I can now reward you with this Guard of Ik shield I had lying around.*


Your faction standing with [Inhabitants of Firiona Vie](/faction/248) got better (<span class='text-success'>+5</span>)


Your faction standing with [Emerald Warriors](/faction/326) got better (<span class='text-success'>+3</span>)


Your faction standing with [Storm Guard](/faction/312) got better (<span class='text-success'>+3</span>)


Your faction standing with [Legion of Cabilis](/faction/441) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Pirates of Gunthak](/faction/313) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_676.png" alt="" /> <a
                                href="/item/12972" data-url="12972" class="tooltip-link link">Guard of Ik</a> (+1500 exp)

 

**This NPC *should* return incorrect items given.**





