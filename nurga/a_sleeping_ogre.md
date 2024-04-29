# a sleeping ogre

## On NPC Spawn

**Set a timer** named *appearance* for 1 seconds
## Timer(s)

**Stop timer** named *appearance*

e.self:SetAppearance(3);
## Dialog

**You say:** `hail`



>*a sleeping ogre snorts a bit and continues sleeping.*
end

## Turn-Ins



if( **You turn in:** [Breath of Gwan](/item/1685)) then 


e.self:SetAppearance(0);


>**a sleeping ogre says:** Your path of wanton destruction ends here. Gwan and Eejag were impatient and hot-headed. You will not defeat me, for I have the patience and perseverance of stone, unlike the children you have beaten before me. Are you sure you want to challenge me?


**Spawn NPC:**  [Trunt](/npc/107000) at this location.


**a sleeping ogre despawns.**

**This NPC *should* return incorrect items given.**
