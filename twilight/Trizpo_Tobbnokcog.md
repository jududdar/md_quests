# Trizpo Tobbnokcog



[Trizpo Tobbnokcog](/npc/170130) is a level 40 Gnome Magician that spawns in [Twilight](/zone/170).



## Dialog

**You say:** `hail`



>**Trizpo Tobbnokcog says:** Hi there, who are you?  What are you doing here? Oh I'm one of Vornol's four apprentices.  I specialize in the element of earth.

**You say:** `armor`



>**Trizpo Tobbnokcog says:** Oh you've been to see Gazoon on his island. Yep he gave me some of his fancy finger waggler armor, are ya a wizard?

**You say:** `wizard`



>**Trizpo Tobbnokcog says:** Wonderful, then you'll probably be wanting the mask, cloak, gloves, choker, belt and staff I have

**You say:** `mask`



>**Trizpo Tobbnokcog says:** For the mask you'll have to get me a meteor jewel, a mark of potential, and an iron tipped wand.
  
**You say:** `cloak`



>**Trizpo Tobbnokcog says:** For the cloak you'll have to get me an astral jewel, a mark of temper, a vial of firewater, and some iced nectar.
  
**You say:** `gloves`



>**Trizpo Tobbnokcog says:** For the gloves you'll have to get me a sun jewel, a mark of might, and a book of solutions.
  
**You say:** `choker`



>**Trizpo Tobbnokcog says:** For the choker you'll have to get me a moon jewel, a mark of destruction, and a stick of mastery.
  
**You say:** `belt`



>**Trizpo Tobbnokcog says:** For the belt you'll have to get me a star jewel, a mark of thaumaturgy, a loop of energy, and a small magnifying lens.
  
**You say:** `staff`



>**Trizpo Tobbnokcog says:** For the staff you'll have to get me a cloud jewel, a mark of detonation, opaque glasses, and a pyro wand.
end



## Turn-Ins



local text = "You have done well to bring me this, but there is more needed before you get your reward.";



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_757.png" alt="" /> <a
                                href="/item/4736" data-url="4736" class="tooltip-link link">Loop of Energy</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/4735" data-url="4735" class="tooltip-link link">Mark of Thaumaturgy</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1129.png" alt="" /> <a
                                href="/item/4738" data-url="4738" class="tooltip-link link">Small Magnifying Lens</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4490" data-url="4490" class="tooltip-link link">Star Jewel</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_572.png" alt="" /> <a
                                href="/item/3721" data-url="3721" class="tooltip-link link">Belt of Detonation</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/4734" data-url="4734" class="tooltip-link link">Mark of Destruction</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4489" data-url="4489" class="tooltip-link link">Moon Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_601.png" alt="" /> <a
                                href="/item/4737" data-url="4737" class="tooltip-link link">Stick of Mastery</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1046.png" alt="" /> <a
                                href="/item/3720" data-url="3720" class="tooltip-link link">Choker of Detonation</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4494" data-url="4494" class="tooltip-link link">Astral Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1029.png" alt="" /> <a
                                href="/item/4731" data-url="4731" class="tooltip-link link">Iced Nectar</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/4729" data-url="4729" class="tooltip-link link">Mark of Temper</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1157.png" alt="" /> <a
                                href="/item/4730" data-url="4730" class="tooltip-link link">Vial of Firewater</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_842.png" alt="" /> <a
                                href="/item/3718" data-url="3718" class="tooltip-link link">Cloak of Detonation</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_865.png" alt="" /> <a
                                href="/item/4733" data-url="4733" class="tooltip-link link">Book of Solutions</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/4732" data-url="4732" class="tooltip-link link">Mark of Might</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4488" data-url="4488" class="tooltip-link link">Sun Jewel</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_517.png" alt="" /> <a
                                href="/item/3719" data-url="3719" class="tooltip-link link">Gloves of Detonation</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4491" data-url="4491" class="tooltip-link link">Cloud Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/4739" data-url="4739" class="tooltip-link link">Mark of Detonation</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1161.png" alt="" /> <a
                                href="/item/4740" data-url="4740" class="tooltip-link link">Opaque Glasses</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_809.png" alt="" /> <a
                                href="/item/5973" data-url="5973" class="tooltip-link link">Pyro Wand</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_601.png" alt="" /> <a
                                href="/item/3722" data-url="3722" class="tooltip-link link">Staff of Detonation</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_810.png" alt="" /> <a
                                href="/item/4728" data-url="4728" class="tooltip-link link">Iron Tipped Wand</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/4727" data-url="4727" class="tooltip-link link">Mark of Potential</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4493" data-url="4493" class="tooltip-link link">Meteor Jewel</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_677.png" alt="" /> <a
                                href="/item/3717" data-url="3717" class="tooltip-link link">Veil of Detonation</a> (+25000 exp)

 

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Trizpo Tobbnokcog says:** Soandso take this and use it with pride.

Your faction standing with [Vornol Transon](/faction/1547) got better (<span class='text-success'>+5</span>)