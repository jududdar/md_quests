# Ogog
## On NPC Spawn

**Set a timer** named *depop* for 300 seconds
## Dialog

**You say:** `hail`



>**Ogog says:** Ogog not smart, but Ogog smarter than you.  You ready for Ogog or no?

**You say:** `ready`



>**Ogog says:** Ok, Soandso.  Ogog got some hard things for you.  You do bash, smash, or think test?

**You say:** `think`



>**Ogog says:** think

**You say:** `smash`



>**Ogog says:** Ogog smash good. . . Ogog no think you can smash good.  But Ogog let you try.  You get Ogog Djinni War Blade, some virulent wasp poison, and a mottled spiroc feather.  Ogog say you good warrior if you do this!

**You say:** `bash`



>**Ogog says:** This one hard, Ogog like it.  Ogog need efreeti battle axe, some honey nectar, bottled djinni, and ethereal emerald. Then Ogog make you best basher.
end

## Turn-Ins



if( **You turn in:** [Efreeti Battle Axe](/item/20983), [Honeyed Nectar](/item/20963), [Bottled Djinni](/item/20981), [Ethereal Emerald](/item/20982)) then 


>**Ogog says:** Good job! Ogog give you Fangol for being good smasher!


 **You receive:**  [Fangol](/item/11675) (+100000 exp)


**Ogog despawns.**

elseif( **You turn in:** [Djinni War Blade](/item/20980), [Virulent Poison](/item/20979), [Mottled Spiroc Feather](/item/20956)) then 


>**Ogog says:** This Dagas, blade of stinging wind. You bash good with this.


 **You receive:**  [Dagas](/item/11674) (+100000 exp)


**Ogog despawns.**

elseif( **You turn in:** [Efreeti Belt](/item/20976), [Spiroc Wind Totem](/item/20977), [Wind Tablet](/item/20978)) then 


>**Ogog says:** Yuz do good! Take dis!


 **You receive:**  [Belt of the Four Winds](/item/11673) (+100000 exp)


**Ogog despawns.**

**This NPC *should* return incorrect items given.**

## Timer(s)

**Stop timer** named *depop*

**Ogog despawns.**



