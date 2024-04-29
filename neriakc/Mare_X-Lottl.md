# Mare X-Lottl
## On NPC Spawn

**Set a timer** named *yoohoo* for 4200 seconds
## Timer(s)

>**Mare X-Lottl says:** Yoohoo!
## Dialog

**You say:** `hail`



>**Mare X-Lottl says:** Hello there, sweetie!!  How about letting me dance for you?  Two gold and I will do a little dance for you.

**You say:** `tayla`



>**Mare X-Lottl says:** Why do you seek that little scamp when you have Mare right here? If you really want to know where she is, it will cost you. Did I ever tell you that my heart belongs to Jasper?
end

## Turn-Ins





if( **You turn in:** [Jasper](/item/10020)) then 


>**Mare X-Lottl says:** Jasper! My one and only love! All right.. That Tayla creature was lost in a game of King's Court with a very important and secret merchant. Belyea will not speak of him but that he was some sort of Baron. He did give me this trinket from his new friend and owner of the half-elf scamp. You keep it. It is worth nothing compared to sweet, beautiful Jasper.


 **You receive:**  [Klok's Seal](/item/1096) 

elseif( **You turn in:** gold = 2) then 


>**Mare X-Lottl says:** Oooh, yes! I just love a patron with an overabundance of gold.


e.self:DoAnim(58); 

**This NPC *should* return incorrect items given.**
