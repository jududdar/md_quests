# Warlord Gligoth

## Dialog

**You say:** `Hail`



>*Warlord Gligoth glares coldly, his mouth twisted in a gruesome sneer of disgust. 'Kartis is place of shadow, not gud for light crawlers. But yu here, yu want something from shadow? Yes, yu want shadow to teach yu - yu want shadow to feed yu secrets, but yu will only fuel shadow's power in learning from it. If yu still want to stay in Kartis, then yu will only give power to shadow that yu say yu hate. I will teach yu, light crawler, if yu still tink yu can outsmart shadow's soldiers. I'll make that puny stick-thing yu light crawlers call weapons into fierce tools of war and no matter who dey kill, yu will kill in the shadow's name.'*
end
## Turn-Ins



local count =  **You turn in:**  { [Indicolite Helm](/item/4911),  [Indicolite Breastplate](/item/4912),  [Indicolite Vambraces](/item/4913),  [Indicolite Bracer](/item/4914),  [Indicolite Gauntlets](/item/4915),  [Indicolite Greaves](/item/4916),  [Indicolite Boots](/item/4917)}

if(count > 0) then


repeat



>**Warlord Gligoth says:** Thank you, Soandso.



 **You receive:** eq.ChooseRandom( [Peridot](/item/10028), 10037, 22503, 15981) (+300000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





