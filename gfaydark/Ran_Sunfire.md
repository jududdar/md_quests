# Ran Sunfire
## Dialog

**You say:** `hail`



>**Ran Sunfire says:** Hail. Soandso! I trust you are not afraid of heights. Kelethin is a grand city. but it is also a safe haven from predators and evil beings. About the only thing to fear are the [pixie tricksters].

**You say:** `pixie trickster`



>**Ran Sunfire says:** An irritating lot of fairy folk. They have been starting fires in our great forest. They may just burn our grand community down. We will have to [exterminate the pixies]. It is unfortunate. but it is for the good of the entire forest.

**You say:** `grynn`



>**Ran Sunfire says:** Grynn is my friend. He chose to follow me one day and has been here ever since. He tells me much of the goings-on in the woods. Lately, he has mentioned a problem with the [pixie tricksters].

**You say:** `exterminate the pixie`



if **Faction** >= Amiable then



>**Ran Sunfire says:** Then I give you this pouch. Should you fill and combine it with pixie dust, I shall pay you greatly for your deeds. We may even find a use for the dust itself. Careful, small though they may be, many are quite strong. Search for the weak ones for now.



**You receive:**  [Empty Pouch](/item/17957)


elseif( **Faction is** == Indifferent) then



>**Ran Sunfire says:** Faydark's Champions cannot call you foe. but you have yet to earn our trust.


else



>**Ran Sunfire says:** Your ways are considered vile to Faydark's Champions. Leave before my rage overcomes my restraint.

end

## Turn-Ins





if **Faction** >= Amiable and ( **You turn in:** [Pouch of Pixie Dust](/item/12109) )) then 


>**Ran Sunfire says:** We thank you for your deed. Here, then, is a small reward. Nothing more than long forgotten equipment, but it may be useful to a young ranger.


* __Faction:__ [Faydarks Champions](/faction/246) (20)


* __Faction:__ [King Tearis Thex](/faction/279) (5)


* __Faction:__ [Clerics of Tunare](/faction/226) (5)


* __Faction:__ [Soldiers of Tunare](/faction/310) (5)


* __Faction:__ [Crushbone Orcs](/faction/234) (-5)


 **You receive:** eq.ChooseRandom( [Patchwork Pants](/item/2111), [Patchwork Boots](/item/2112), [Patchwork Tunic](/item/2104), [Patchwork Sleeves](/item/2108), [Patchwork Cloak](/item/2106), [Raw-hide Belt](/item/2143), [Raw-hide Boots](/item/2148), [Raw-hide Cloak](/item/2142), [Raw-hide Gloves](/item/2146), [Raw-hide Gorget](/item/2139), [Raw-hide Leggings](/item/2147), [Raw-hide Mask](/item/2138), [Raw-hide Shoulderpads](/item/2141), [Raw-hide Skullcap](/item/2137), [Raw-hide Sleeves](/item/2144), [Raw-hide Tunic](/item/2140), [Raw-hide Wristbands](/item/2145)) (+1000 exp)

**This NPC *should* return incorrect items given.**
;

