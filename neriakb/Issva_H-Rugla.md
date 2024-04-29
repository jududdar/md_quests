# Issva H-Rugla



## Dialog

if(eq.get_current_expansion() >= 4.0) then


**You say:** `Hail`




>**Issva H-Rugla says:** If you're looking for chit chat you can bugger off. I'm here to sell supplies not company.


**You say:** `materials`




>**Issva H-Rugla says:** Many species of dangerous creatures, the walking dead, and invading Deathfist Orcs inhabit the Nektulos Forest. You must defeat these creatures and undead in order to obtain the materials. The materials you seek depend on the piece of armor you desire. Do you desire to craft [gauntlets], [boots], a [bracer], a [helm], [greaves], [vambraces], or a [breastplate]?


**You say:** `gauntlet`




>**Issva H-Rugla says:** To craft Orc Slayer Gauntlets you require two [silk thread], a cracked pyre beetle carapace, and two orc finger bones. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Glove Pattern.



**You receive:**  [Tattered Glove Pattern](/item/19559)


**You say:** `boot`




>**Issva H-Rugla says:** To craft Orc Slayer Boots you require two [silk thread], two cracked pyre beetle carapaces, and two orc foot bones. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Boot Pattern.



**You receive:**  [Tattered Boot Pattern](/item/19561)


**You say:** `bracer`




>**Issva H-Rugla says:** To craft an Orc Slayer Bracer you require a [silk thread], a cracked pyre beetle carapace, and an orc ulna bone. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Bracer Pattern.



**You receive:**  [Tattered Wristband Pattern](/item/19558)


**You say:** `helm`




>**Issva H-Rugla says:** To craft an Orc Slayer Helm you require two [silk thread], a cracked pyre beetle carapace, and an orc skull. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Cap Pattern.



**You receive:**  [Tattered Cap Pattern](/item/19555)


**You say:** `greave`




>**Issva H-Rugla says:** To craft Orc Slayer Greaves you require three [silk thread], a pyre beetle carapace, two orc tibia, and an orc pelvis bone. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Leggings Pattern.



**You receive:**  [Tattered Pant Pattern](/item/19560)


**You say:** `vambrace`




>**Issva H-Rugla says:** To craft Ord Slayer Vambraces you require two [silk thread], a pyre beetle carapace, and two orc humerus bones. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Sleeves Pattern.



**You receive:**  [Tattered Sleeve Pattern](/item/19557)


**You say:** `breastplate`




>**Issva H-Rugla says:** To craft an Orc Slayer Breastplate you require four [silk thread], a pristine pyre beetle carapace, an orc sternum, and an orc ribcage. Once you have the necessary components combine them in your Mail Assembly Kit with this Tattered Tunic Pattern.



**You receive:**  [Tattered Tunic Pattern](/item/19556)

end

## Turn-Ins



local expansion_flag = eq.get_current_expansion();

if(expansion_flag >= 4.0 and  **You turn in:** [Request Form](/item/31753)) then 


>**Issva H-Rugla says:** So you are one of Jarrex's new recruits. You are to assist in the construction of the armor you will don as a new Warrior of the Indigo Brotherhood. I have assembled a kit that is used in the crafting of Orc Slayer Mail. You must travel beyond Neriak into the Nektulos Forest for the [materials] that compose the armor.


 **You receive:**  [Mail Assembly Kit](/item/17124) 

**This NPC *should* return incorrect items given.**






