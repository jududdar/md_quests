# Warlord Welorf

## Dialog

**You say:** `Hail`



>*Warlord Welorf gathers a deep breath, his body seeming unnaturally stiff within the large suit of iron. His cold, steely eyes glance over you once before addressing you in a low, baritone voice. 'You stand before Welorf, Warlord of the North and former chief of the Steel Warrior's clan. Should you be a warrior, the knowledge of my blade is at your reach and perhaps in time, and with some training, a proper warrior can borne of the weak creature I see before me.'*
end

## Turn-Ins



local count =  **You turn in:**  { [Indicolite Helm](/item/4911),  [Indicolite Breastplate](/item/4912),  [Indicolite Vambraces](/item/4913),  [Indicolite Bracer](/item/4914),  [Indicolite Gauntlets](/item/4915),  [Indicolite Greaves](/item/4916),  [Indicolite Boots](/item/4917)}

if(count > 0) then


repeat



>**Warlord Welorf says:** Thank you, Soandso.



 **You receive:** eq.ChooseRandom( [Peridot](/item/10028), 10037, 22503, 15981) (+300000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





