# Larn Brugal


## Dialog

**You say:** `hail`



>**Larn Brugal says:** Good day to you Soandso I hope you yearn to become a Steel Warrior as we all are here in the Bunker. We are in need of more recruits to continue the [war].

**You say:** `war`



>**Larn Brugal says:** The war I speak of is the one we Steel Warriors have sworn to wage agianst [Clan Deathfist] in the Commonlands. We are doing a fine job but we require more weapons. We are expecting a shipment of blades from Groflahs Forge. We require a warrior of the bunker to [get our shipment]. Maybe you.

**You say:** `clan deathfist`



>**Larn Brugal says:** If you do not know of Clan Deathfist go ask Cain who they are. He will not only tell you he will sign you up to help fight our war!

**You say:** `shipment`



if **Faction** >= Amiable then



>**Larn Brugal says:** We would be most thankful for your service. Please take this voucher over to Groflah at Groflahs Forge in North Freeport. He will give you the shipment of weapons.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/18820" data-url="18820" class="tooltip-link link">A Sealed Letter</a>


elseif( **Faction is** == Indifferent) then



>**Larn Brugal says:** The Steel Warriors have no cause to dislike you, but you have yet to truly prove your worth to this guild.


else



>**Larn Brugal says:** Your head shall look grand mounted on the wall of the Steel Warriors Arena!!

end



## Turn-Ins



local text = "This is only one sword. I requested four altogether. You shall not get your payment until I get my fourth sword."


if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_580.png" alt="" /> <a
                                href="/item/12241" data-url="12241" class="tooltip-link link">Raw Short Sword 1</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_580.png" alt="" /> <a
                                href="/item/12242" data-url="12242" class="tooltip-link link">Raw Short Sword 2</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_580.png" alt="" /> <a
                                href="/item/12243" data-url="12243" class="tooltip-link link">Raw Short Sword 3</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_580.png" alt="" /> <a
                                href="/item/12244" data-url="12244" class="tooltip-link link">Raw Short Sword 4</a>) then 


>**Larn Brugal says:** Good work, Soandso. The bunker shall be well stocked. Here you are, my friend. Take this raw blade. You can take it to Groflah - he will sharpen and polish it for you. It should be a formidable weapon.


Your faction standing with [Steel Warriors](/faction/311) got better (<span class='text-success'>+20</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+4</span>)


Your faction standing with [Corrupt Qeynos Guards](/faction/230) got worse (<span class='text-danger'>-3</span>)


Your faction standing with [The Freeport Militia](/faction/330) got worse (<span class='text-danger'>-3</span>)


Your faction standing with [Knights of Truth](/faction/281) got better (<span class='text-success'>+4</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_580.png" alt="" /> <a
                                href="/item/13919" data-url="13919" class="tooltip-link link">Reward Raw Short Sword</a> (+1000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**
;