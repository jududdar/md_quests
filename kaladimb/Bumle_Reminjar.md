# Bumle Reminjar


## Dialog

**You say:** `hail`



>**Bumle Reminjar says:** Welcome, Soandso. The Cathedral of Underfoot welcomes all good persons. May you find peace from the dangers of Butcherblock within these walls. The paladins of this holy place are very much aware of the evils outside Kaladim. The threat of goblins and [birdmen] has increased.

**You say:** `birdmen`



>**Bumle Reminjar says:** The birdmen I speak of are the aviak krags. These vile creatures have desecrated our land. They have dared to perch upon our great statue. The king has instructed all noble paladins in this order to [destroy the krag chicks].

**You say:** `chicks`



if **Faction** >= Amiable then



>**Bumle Reminjar says:** Yes. You are known to have aided our cause. You shall continue by returning any aviak chick talons to me. I will reward you for the return of no fewer than four at a time. Go, and serve the will of the king!


elseif **Faction** >= Indifferent then



>**Bumle Reminjar says:** The Clerics of Underfoot have yet to see your faith directed towards our wills. Perhaps you should assist Master Gunlok Jure in the crusade against the undead.


else



>**Bumle Reminjar says:** How dare you approach a member of the Clerics of Underfoot?!  Dogs such as you lie in the same bed as aviaks and ogres!


**You say:** `elders`



if **Faction** >= Kindly then 



>**Bumle Reminjar says:** The krag elders are the strongest of the aviaks. Their might has been well-documented by our order. Our high ranking paladins are ordered to slay the eagles. If you are with us, return four aviak talons to me and a fine reward shall be yours. Perhaps even our cathedral tailors and scribes may donate to your quest.


elseif **Faction** >= Indifferent then



>**Bumle Reminjar says:** The Clerics of Underfoot have yet to see your faith directed towards our wills. Perhaps you should assist Master Gunlok Jure in the crusade against the undead.


else



>**Bumle Reminjar says:** How dare you approach a member of the Clerics of Underfoot?!  Dogs such as you lie in the same bed as aviaks and ogres!

end



## Turn-Ins



local text = "I shall reward you for no less than four aviak chick talons.";

local text1 = "There is only a reward for the return of four aviak talons.";



if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1067.png" alt="" /> <a
                                href="/item/12157" data-url="12157" class="tooltip-link link">Aviak Chick Talon</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1067.png" alt="" /> <a
                                href="/item/12157" data-url="12157" class="tooltip-link link">Aviak Chick Talon</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1067.png" alt="" /> <a
                                href="/item/12157" data-url="12157" class="tooltip-link link">Aviak Chick Talon</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1067.png" alt="" /> <a
                                href="/item/12157" data-url="12157" class="tooltip-link link">Aviak Chick Talon</a>) then


>**Bumle Reminjar says:** You have done well. Your deeds shall be recorded within our journals. Here, then, is your reward. May you strive to serve us to the full extent of your powers. The [elders] must also die.





Your faction standing with [Clerics of Underfoot](/faction/227) got better (<span class='text-success'>+5</span>)


Your faction standing with [Kazon Stormhammer](/faction/274) got better (<span class='text-success'>+5</span>)


Your faction standing with [Miners Guild 249](/faction/293) got better (<span class='text-success'>+3</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_640.png" alt="" /> <a
                                href="/item/2113" data-url="2113" class="tooltip-link link">Small Tattered Skullcap</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_771.png" alt="" /> <a
                                href="/item/2114" data-url="2114" class="tooltip-link link">Small Tattered Mask</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_643.png" alt="" /> <a
                                href="/item/2115" data-url="2115" class="tooltip-link link">Small Tattered Gorget</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_632.png" alt="" /> <a
                                href="/item/2116" data-url="2116" class="tooltip-link link">Small Patchwork Tunic</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_668.png" alt="" /> <a
                                href="/item/2117" data-url="2117" class="tooltip-link link">Small Tattered Shoulderpads</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_660.png" alt="" /> <a
                                href="/item/2118" data-url="2118" class="tooltip-link link">Small Patchwork Cloak</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_564.png" alt="" /> <a
                                href="/item/2119" data-url="2119" class="tooltip-link link">Small Tattered Belt</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_634.png" alt="" /> <a
                                href="/item/2120" data-url="2120" class="tooltip-link link">Small Patchwork Sleeves</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_637.png" alt="" /> <a
                                href="/item/2121" data-url="2121" class="tooltip-link link">Small Tattered Wristbands</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_636.png" alt="" /> <a
                                href="/item/2122" data-url="2122" class="tooltip-link link">Small Tattered Gloves</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_635.png" alt="" /> <a
                                href="/item/2123" data-url="2123" class="tooltip-link link">Small Patchwork Pants</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_633.png" alt="" /> <a
                                href="/item/2124" data-url="2124" class="tooltip-link link">Small Patchwork Boots</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_590.png" alt="" /> <a
                                href="/item/5045" data-url="5045" class="tooltip-link link">Tarnished Long Sword</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_567.png" alt="" /> <a
                                href="/item/6041" data-url="6041" class="tooltip-link link">Cast-Iron Warhammer</a>) (+5000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0-3 <img src='/static/icons/item_645.png' width='14' height='14'/> 0-5 <img src='/static/icons/item_646.png' width='14' height='14'/> 0-5 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif **Faction** >= Kindly and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1067.png" alt="" /> <a
                                href="/item/12158" data-url="12158" class="tooltip-link link">Aviak Talon</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1067.png" alt="" /> <a
                                href="/item/12158" data-url="12158" class="tooltip-link link">Aviak Talon</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1067.png" alt="" /> <a
                                href="/item/12158" data-url="12158" class="tooltip-link link">Aviak Talon</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1067.png" alt="" /> <a
                                href="/item/12158" data-url="12158" class="tooltip-link link">Aviak Talon</a>) then 


>**Bumle Reminjar says:** Fine work! You shall be known for your great deeds. Take this and may it aid you in your defense of Kaladim. Hail King Kazon!





Your faction standing with [Clerics of Underfoot](/faction/227) got better (<span class='text-success'>+10</span>)


Your faction standing with [Kazon Stormhammer](/faction/274) got better (<span class='text-success'>+10</span>)


Your faction standing with [Miners Guild 249](/faction/293) got better (<span class='text-success'>+7</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_640.png" alt="" /> <a
                                href="/item/2113" data-url="2113" class="tooltip-link link">Small Tattered Skullcap</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_771.png" alt="" /> <a
                                href="/item/2114" data-url="2114" class="tooltip-link link">Small Tattered Mask</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_643.png" alt="" /> <a
                                href="/item/2115" data-url="2115" class="tooltip-link link">Small Tattered Gorget</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_632.png" alt="" /> <a
                                href="/item/2116" data-url="2116" class="tooltip-link link">Small Patchwork Tunic</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_668.png" alt="" /> <a
                                href="/item/2117" data-url="2117" class="tooltip-link link">Small Tattered Shoulderpads</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_660.png" alt="" /> <a
                                href="/item/2118" data-url="2118" class="tooltip-link link">Small Patchwork Cloak</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_564.png" alt="" /> <a
                                href="/item/2119" data-url="2119" class="tooltip-link link">Small Tattered Belt</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_634.png" alt="" /> <a
                                href="/item/2120" data-url="2120" class="tooltip-link link">Small Patchwork Sleeves</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_637.png" alt="" /> <a
                                href="/item/2121" data-url="2121" class="tooltip-link link">Small Tattered Wristbands</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_636.png" alt="" /> <a
                                href="/item/2122" data-url="2122" class="tooltip-link link">Small Tattered Gloves</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_635.png" alt="" /> <a
                                href="/item/2123" data-url="2123" class="tooltip-link link">Small Patchwork Pants</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_633.png" alt="" /> <a
                                href="/item/2124" data-url="2124" class="tooltip-link link">Small Patchwork Boots</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_590.png" alt="" /> <a
                                href="/item/5082" data-url="5082" class="tooltip-link link">Cast-Iron Long Sword</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_567.png" alt="" /> <a
                                href="/item/6041" data-url="6041" class="tooltip-link link">Cast-Iron Warhammer</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_578.png" alt="" /> <a
                                href="/item/6042" data-url="6042" class="tooltip-link link">Cast-Iron Mace</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_567.png" alt="" /> <a
                                href="/item/6046" data-url="6046" class="tooltip-link link">Cast-Iron Two Handed Hammer</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_762.png" alt="" /> <a
                                href="/item/7032" data-url="7032" class="tooltip-link link">Cast-Iron Rapier</a>) (+10000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 0-5 <img src='/static/icons/item_646.png' width='14' height='14'/> 0-5 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**
