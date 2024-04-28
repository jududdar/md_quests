# Arch Mage Deidus



## Dialog

**You say:** `Hail`



>*Arch Mage Deidus gives a loathsome, unwavering stare upon Soandso. His features are steely and cold in their disdain. 'Kartis is the place of shadow - the cornerstone of the seed of corruption in this universe. You have no place here as you are. Return to Selia. for you will find nothing of use to you here. If you intend to decipher the purpose of the shadow or interrupt the training of our disciples, then you are grievously mistaken in your cause. We will share nothing with the likes of you in the ways of knowledge. Though slowly, if you choose to remain, we shall corrupt and contort you to our will. Even through mere acts of training, you will be fueling the shadow and will become a part of it unwittingly or no.'*
end
## Turn-Ins



local count =  **You turn in:**  { [Apothic Crown](/item/1239),  [Apothic Robe](/item/1240),  [Apothic Sleeves](/item/1241),  [Apothic Warband](/item/1242),  [Apothic Gloves](/item/1243),  [Apothic Kilt](/item/1244),  [Apothic Boots](/item/1245)}

if(count > 0) then


repeat



>**Arch Mage Deidus says:** Thank you, Soandso.



 **You receive:** eq.ChooseRandom( [Peridot](/item/10028), 10037, 22503, 15981) (+300000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





