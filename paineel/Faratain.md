# Faratain



[Faratain](/npc/75046) is a level 50 Erudite Shopkeeper that spawns in [Paineel](/zone/75).



## Dialog

if(eq.get_current_expansion() >= 4.0) then


**You say:** `hail`




>**Faratain says:** Salutations Soandso. If you are here to make use of the forges then feel free to pursue your crafts within this chamber. If you are a new Fell Blade in need of a suit of armor and weapon then I will assist you in crafting [armaments] fitting of a young Shadow Knight.


**You say:** `armament`




>**Faratain says:** You will require this specially prepared Mail Assembly Kit in order to construct a suit of Fell Blade Armor. The materials required vary depending on the piece of armor you desire to craft. Once you have been outfitted in the Fell Blade Armor. return to me and I will present you with a somewhat important [task]. Do you desire to craft a [fell blade helm], a [fell blade bracer], [fell blade gauntlets], [fell blade boots], [fell blade vambraces], [fell blade greaves], or a [fell blade breastplate]?



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_730.png" alt="" /> <a
                                href="/item/17124" data-url="17124" class="tooltip-link link">Mail Assembly Kit</a>


**You say:** `task`




>**Faratain says:** The blacksmiths of [Clan Kolbok] craft weapons using an ancient Kobold tradition that has been long forgotten by most of the kobold clans. I believe there is something to be learned from their traditions should we discover their intricacies. Go into the Warrens and locate the chambers of the kobold blacksmiths. There you should be able to find some record of their traditional techniques to return to me here in Paineel where they can be translated and studied.


**You say:** `greaves`




>**Faratain says:** To assemble Fell blade Greaves you will need to obtain two bricks of crude bronze and smelt them in a forge with a Water Flask and this Crude Greaves Mold. Once that is done combine the Crude Bronze Greaves with two Intact Kobold Pelts and two Calcified Tibia in the Mail Assembly Kit.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1151.png" alt="" /> <a
                                href="/item/19636" data-url="19636" class="tooltip-link link">Crude Greaves Mold</a>


**You say:** `helm`




>**Faratain says:** To assemble a Fell blade Helm you will need to obtain two bricks of crude bronze and smelt them in a forge with a Water Flask and this Crude Helm Mold. Once that is done combine the Crude Bronze Helm with a Ruined Kobold Pelt and a Calcified Skull in the Mail Assembly Kit.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1151.png" alt="" /> <a
                                href="/item/19631" data-url="19631" class="tooltip-link link">Crude Helm Mold</a>


**You say:** `boot`




>**Faratain says:** To assemble Fell blade Boots you will need to obtain two bricks of crude bronze and smelt them in a forge with a Water Flask and this crude Boot Mold. Once that is done combine the Crude Bronze Boots with two Ruined Kobold Pelts. and two Calcified Foot Bones in the Mail Assembly Kit.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1151.png" alt="" /> <a
                                href="/item/19634" data-url="19634" class="tooltip-link link">Crude Boot Mold</a>


**You say:** `bracer`




>**Faratain says:** To assemble a Fell blade Bracer you will need to obtain a brick of crude bronze and smelt it in a forge with a Water Flask and this Crude Bracer Mold. Once that is done, combine the Crude Bronze Bracer with a Ruined Kobold Pelt and a Calcified Ulna Bone in the Mail Assembly Kit.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1151.png" alt="" /> <a
                                href="/item/19632" data-url="19632" class="tooltip-link link">Crude Bracer Mold</a>


**You say:** `breastplate`




>**Faratain says:** To assemble a Fell blade Breastplate you will need to obtain four bricks of crude bronze and smelt them in a forge with a Water Flask and this Crude Breastplate Mold. Once that is done combine the Crude Bronze Breastplate with a Pristine Kobold Pelt, a calcified sternum, and a calcified ribcage in the Mail Assembly Kit.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1151.png" alt="" /> <a
                                href="/item/19637" data-url="19637" class="tooltip-link link">Crude Breastplate Mold</a>


**You say:** `gauntlet`




>**Faratain says:** To assemble Fell blade Gauntlets you will need to obtain two bricks of crude bronze and smelt them in a forge with a Water Flask and this crude Gauntlet Mold. Once that is done combine the Crude Bronze Gauntlets with a Ruined Kobold Pelt and two Calcified Finger Bones in the Mail Assembly Kit.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1151.png" alt="" /> <a
                                href="/item/19633" data-url="19633" class="tooltip-link link">Crude Gauntlets Mold</a>


**You say:** `vambrace`




>**Faratain says:** To assemble Fell blade Vambraces you will need to obtain two bricks of crude bronze and smelt them in a forge with a Water Flask and this Crude Vambrace Mold. Once that is done combine the Crude Bronze Vambraces with an Intact Kobold Pelt and two Calcified Humerus Bones in the Mail Assembly Kit.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1151.png" alt="" /> <a
                                href="/item/19635" data-url="19635" class="tooltip-link link">Crude Vambrace Mold</a>

end



## Turn-Ins



local expansion_flag = eq.get_current_expansion();


if(expansion_flag >= 4.0 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_863.png" alt="" /> <a
                                href="/item/20421" data-url="20421" class="tooltip-link link">Clan Kolbok Blacksmith Traditions</a>) then


>**Faratain says:** Well done Soandso. I will have this translated immediately so that it may be studied. Take this Dull Fell Blade Cutlass and sharpen it in a forge with a sharpening stone. It may take you several attempts if you are unfamiliar with the process. Once that is done bring me the Sharp Fell Blade Cutlass, a Large Briar Snake Skin, and a Petrified Eyeball and I will put the finishing touches on the weapon.


Your faction standing with [Heretics](/faction/265) got better (<span class='text-success'>+5</span>)


Your faction standing with [Deepwater Knights](/faction/242) got worse (<span class='text-danger'>-5</span>)


Your faction standing with [Gate Callers](/faction/254) got worse (<span class='text-danger'>-5</span>)


Your faction standing with [Craftkeepers](/faction/231) got worse (<span class='text-danger'>-5</span>)


Your faction standing with [Crimson Hands](/faction/233) got worse (<span class='text-danger'>-5</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_604.png" alt="" /> <a
                                href="/item/20403" data-url="20403" class="tooltip-link link">Dull Fell Blade Cutlass</a> 

 

elseif(expansion_flag >= 4.0 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_604.png" alt="" /> <a
                                href="/item/20404" data-url="20404" class="tooltip-link link">Sharp Fell Blade Cutlass</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_813.png" alt="" /> <a
                                href="/item/20355" data-url="20355" class="tooltip-link link">Large Briar Snake Skin</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_917.png" alt="" /> <a
                                href="/item/20402" data-url="20402" class="tooltip-link link">Petrified Eyeball</a>) then


>*Faratain Faratain fashions a grip from the large briar snake skin, fastens the petrified eyeball to the pommel of the hilt, and polishes the blade with a shimmering black substance. I present you with your Fell Blade Cutlass. May it serve you well in the name of Cazic Thule.*


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_580.png" alt="" /> <a
                                href="/item/20416" data-url="20416" class="tooltip-link link">Fell Blade Cutlass</a> 

 
end





