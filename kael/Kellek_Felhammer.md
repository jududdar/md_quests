# Kellek Felhammer
## Dialog

**You say:** `hail`



if **Faction** >= Apprehensive then



>**Kellek Felhammer says:** If you want a conversation, find one of your own kind to talk to.  I'm just here to sell this fine ale.


else



**Kellek Felhammer says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

end

## Turn-Ins





if( **You turn in:** [Voucher for Toolset](/item/25279)) then 


>**Kellek Felhammer says:** Here you go Soandso. I dunno why master Wenglawks trusts you with this but take it anyways and don't mess up.' smacks his fists together as he looks at you.


 **You receive:**  [Coldain Toolset](/item/25104) 

elseif( **You turn in:** [Voucher for Spear](/item/25280)) then 


>**Kellek Felhammer says:** Another delivery eh? Be careful with this spear, if you break it I'll break you.


 **You receive:**  [Bekeraks New Spear](/item/25106) 

elseif( **You turn in:** [Voucher for Mechanical Net](/item/25281)) then 


>**Kellek Felhammer says:** It's hard to believe a " .. e.other:Race() .. " like you is going to make a trip like this. I don't envy you little fool.


 **You receive:**  [Mechanical Net](/item/25107) 

elseif( **You turn in:** [Helssen's Voucher](/item/1722)) then 


>**Kellek Felhammer says:** I still cannot believe we are giving such a prized possesion as the Collar of the Storm to a mere mercenary. You better pray you don't bring shame upon the smith who created and enchanted this item. Oh and here is your seal as Helssen has ordered me to give you. It is proof of your service to us.


 **You receive:**  [Noble's Seal](/item/1723) (+2000 exp)


 **You receive:**  [Collar of the Storm](/item/1721) 

**This NPC *should* return incorrect items given.**
