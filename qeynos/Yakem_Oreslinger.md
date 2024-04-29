# Yakem Oreslinger


## Dialog

**You say:** `hail`



>**Yakem Oreslinger says:** Greetings friend Soandso! I am a provider of the highest quality steel ore known to Norrath! This ore is in such demand that I often run low and find it difficult to restock my supplies. If you're [looking for a job] I will gladly pay you for some of your time.

**You say:** `looking`



>**Yakem Oreslinger says:** I need you to take this crate and fill it with either Small Bracks of Unrefined Ore or Large Bricks of Unrefined Ore then return it to me so that I may refine it and sell it. The unrefined ore that I require is often mined by the goblins in the ruins of Permafrost Keep.


**You receive:**  [Empty Ore Crate](/item/17814)

end

## Turn-Ins





if( **You turn in:** [Small Shipment of High Quality Ore](/item/10952)) then 




* __Faction:__ [Qeynos Citizens](/faction/121) (4)



>**Yakem Oreslinger says:** Thank you! I will prepare the ore for sale and be open for business again momentarily. Here is your payment for your services.


 **You receive:** 0 (+5000 exp)


**Yakem Oreslinger despawns.**

elseif( **You turn in:** [Large Shipment of High Quality Ore](/item/10953)) then 



>**Yakem Oreslinger says:** Thank you! I will prepare the ore for sale and be open for business again momentarily. Here is your payment for your services.


* __Faction:__ [Qeynos Citizens](/faction/121) (4)



 **You receive:** 0 (+3500 exp)


**Yakem Oreslinger despawns.**

**This NPC *should* return incorrect items given.**
