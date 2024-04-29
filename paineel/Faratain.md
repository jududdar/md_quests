# Faratain
## Dialog

if(eq.get_current_expansion() >= 4.0) then


**You say:** `hail`




>**Faratain says:** Salutations Soandso. If you are here to make use of the forges then feel free to pursue your crafts within this chamber. If you are a new Fell Blade in need of a suit of armor and weapon then I will assist you in crafting [armaments] fitting of a young Shadow Knight.


**You say:** `armament`




>**Faratain says:** You will require this specially prepared Mail Assembly Kit in order to construct a suit of Fell Blade Armor. The materials required vary depending on the piece of armor you desire to craft. Once you have been outfitted in the Fell Blade Armor. return to me and I will present you with a somewhat important [task]. Do you desire to craft a [fell blade helm], a [fell blade bracer], [fell blade gauntlets], [fell blade boots], [fell blade vambraces], [fell blade greaves], or a [fell blade breastplate]?



**You receive:**  [Mail Assembly Kit](/item/17124)


**You say:** `task`




>**Faratain says:** The blacksmiths of [Clan Kolbok] craft weapons using an ancient Kobold tradition that has been long forgotten by most of the kobold clans. I believe there is something to be learned from their traditions should we discover their intricacies. Go into the Warrens and locate the chambers of the kobold blacksmiths. There you should be able to find some record of their traditional techniques to return to me here in Paineel where they can be translated and studied.


**You say:** `greaves`




>**Faratain says:** To assemble Fell blade Greaves you will need to obtain two bricks of crude bronze and smelt them in a forge with a Water Flask and this Crude Greaves Mold. Once that is done combine the Crude Bronze Greaves with two Intact Kobold Pelts and two Calcified Tibia in the Mail Assembly Kit.



**You receive:**  [Crude Greaves Mold](/item/19636)


**You say:** `helm`




>**Faratain says:** To assemble a Fell blade Helm you will need to obtain two bricks of crude bronze and smelt them in a forge with a Water Flask and this Crude Helm Mold. Once that is done combine the Crude Bronze Helm with a Ruined Kobold Pelt and a Calcified Skull in the Mail Assembly Kit.



**You receive:**  [Crude Helm Mold](/item/19631)


**You say:** `boot`




>**Faratain says:** To assemble Fell blade Boots you will need to obtain two bricks of crude bronze and smelt them in a forge with a Water Flask and this crude Boot Mold. Once that is done combine the Crude Bronze Boots with two Ruined Kobold Pelts. and two Calcified Foot Bones in the Mail Assembly Kit.



**You receive:**  [Crude Boot Mold](/item/19634)


**You say:** `bracer`




>**Faratain says:** To assemble a Fell blade Bracer you will need to obtain a brick of crude bronze and smelt it in a forge with a Water Flask and this Crude Bracer Mold. Once that is done, combine the Crude Bronze Bracer with a Ruined Kobold Pelt and a Calcified Ulna Bone in the Mail Assembly Kit.



**You receive:**  [Crude Bracer Mold](/item/19632)


**You say:** `breastplate`




>**Faratain says:** To assemble a Fell blade Breastplate you will need to obtain four bricks of crude bronze and smelt them in a forge with a Water Flask and this Crude Breastplate Mold. Once that is done combine the Crude Bronze Breastplate with a Pristine Kobold Pelt, a calcified sternum, and a calcified ribcage in the Mail Assembly Kit.



**You receive:**  [Crude Breastplate Mold](/item/19637)


**You say:** `gauntlet`




>**Faratain says:** To assemble Fell blade Gauntlets you will need to obtain two bricks of crude bronze and smelt them in a forge with a Water Flask and this crude Gauntlet Mold. Once that is done combine the Crude Bronze Gauntlets with a Ruined Kobold Pelt and two Calcified Finger Bones in the Mail Assembly Kit.



**You receive:**  [Crude Gauntlets Mold](/item/19633)


**You say:** `vambrace`




>**Faratain says:** To assemble Fell blade Vambraces you will need to obtain two bricks of crude bronze and smelt them in a forge with a Water Flask and this Crude Vambrace Mold. Once that is done combine the Crude Bronze Vambraces with an Intact Kobold Pelt and two Calcified Humerus Bones in the Mail Assembly Kit.



**You receive:**  [Crude Vambrace Mold](/item/19635)

end

## Turn-Ins



local expansion_flag = eq.get_current_expansion();


if(expansion_flag >= 4.0 and  **You turn in:** [Clan Kolbok Blacksmith Traditions](/item/20421)) then


>**Faratain says:** Well done Soandso. I will have this translated immediately so that it may be studied. Take this Dull Fell Blade Cutlass and sharpen it in a forge with a sharpening stone. It may take you several attempts if you are unfamiliar with the process. Once that is done bring me the Sharp Fell Blade Cutlass, a Large Briar Snake Skin, and a Petrified Eyeball and I will put the finishing touches on the weapon.


* __Faction:__ [Heretics](/faction/265) (5)


* __Faction:__ [Deepwater Knights](/faction/242) (-5)


* __Faction:__ [Gate Callers](/faction/254) (-5)


* __Faction:__ [Craftkeepers](/faction/231) (-5)


* __Faction:__ [Crimson Hands](/faction/233) (-5)


 **You receive:**  [Dull Fell Blade Cutlass](/item/20403) 

elseif(expansion_flag >= 4.0 and  **You turn in:** [Sharp Fell Blade Cutlass](/item/20404), [Large Briar Snake Skin](/item/20355), [Petrified Eyeball](/item/20402)) then


>*Faratain Faratain fashions a grip from the large briar snake skin, fastens the petrified eyeball to the pommel of the hilt, and polishes the blade with a shimmering black substance. I present you with your Fell Blade Cutlass. May it serve you well in the name of Cazic Thule.*


 **You receive:**  [Fell Blade Cutlass](/item/20416) 
end





