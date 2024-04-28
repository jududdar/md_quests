# Gavel the Temperant


## Dialog

**You say:** `hail`



>**Gavel the Temperant says:** May the fires of Solusek Ro warm your innards! I am Gavel the Temperant. I work with Sister Blaize to forge the most elegant finery for clerics known to man or beast. Because we have no need for material wealth here in the temple, we ask that you retrieve [ingots and icons] from the lost or fallen brothers and sisters of our order. When mixed with some enchanted, [galvanized], [vulcanized], or [magnetized] platinum into an alloy, the items I can forge are splendid indeed!

**You say:** `ingots and icons`



>**Gavel the Temperant says:** The ingots and icons are all named after the virtues of the cleric who held them. The virtues I require are those of the [reverent], the [constant], and the [devout].

**You say:** `reverent`



>**Gavel the Temperant says:** Regis the Reverent fell in love with a consortium woman named Lianna Ferasa who lives in the Rathe Mountains. Ask her what has become of him. Bring me the ingot of the Reverent, the icon of the Reverent, and two enchanted platinum bars and I will forge them into a reward for you.

**You say:** `constant`



>**Gavel the Temperant says:** Althuryn the Constant was brutally slain by two aqua goblins. The one called Sludge fled to Runnyeye. The one called Dwigus lives in Dagnor's Cauldron. Bring me the ingot of the Constant, the icon of the Constant, and two galvanized platinum bars and I will forge them into a reward for you.

**You say:** `devout`



>**Gavel the Temperant says:** Nebbletob the Devout was once a slave in the mines of Meldrath. The Minotaur Sentry there was particularly cruel to him. He was in the expedition to Everfrost when Brother Theo drowned. When trying to rescue Theo, he came upon some caves under the river. He also narrowly escaped death when a great white beast attacked him. He never saw what the beast was, but it shredded his pack where he kept his icon. Bring me the ingot of the Devout, the icon of the Devout, and two vulcanized platinum bars and I will forge them into a reward for you.

**You say:** `sacrament`



>**Gavel the Temperant says:** The Ingot and icon of Sacrament are believed to be just legend, but I sometimes dream of what I could forge with them and 2 magnetized platinum bars!


**You say:** `galvanized`



>**Gavel the Temperant says:** Enchanted platinum bars can be galvanized by Genni, vulcanized by Vilissia, and magnetized by Ostorm. Just give them the enchanted platinum bar and they will do the rest.

**You say:** `vulcanized`



>**Gavel the Temperant says:** Enchanted platinum bars can be galvanized by Genni, vulcanized by Vilissia, and magnetized by Ostorm. Just give them the enchanted platinum bar and they will do the rest.

**You say:** `magnetized`



>**Gavel the Temperant says:** Enchanted platinum bars can be galvanized by Genni, vulcanized by Vilissia, and magnetized by Ostorm. Just give them the enchanted platinum bar and they will do the rest.
end

## Turn-Ins



local text = "Impressive, do you have the rest?";



if **You turn in:** [Enchanted Platinum Bar](/item/16507), [Enchanted Platinum Bar](/item/16507), [Icon of the Reverent](/item/19010), [Ingot of the Reverent](/item/19009)


>**Gavel the Temperant says:** Wear this with pride!


 **You receive:**  [Bracers of the Reverent](/item/4925) (+1000 exp)

elseif **You turn in:** [Magnetized Platinum Bar](/item/19049), [Magnetized Platinum Bar](/item/19049), [Icon of Sacrament](/item/19016), [Ingot of Sacrament](/item/19015)


>**Gavel the Temperant says:** It is an honor to forge such a weapon. Wield it with pride!


 **You receive:**  [Caduceus of Sacrament](/item/6407) (+1000 exp)

elseif **You turn in:** [Galvanized Platinum Bar](/item/19047), [Galvanized Platinum Bar](/item/19047), [Ingot of the Constant](/item/19011), [Icon of the Constant](/item/19012)


>**Gavel the Temperant says:** Wear this with pride!


 **You receive:**  [Chestplate of the Constant](/item/4926) (+1000 exp)

elseif **You turn in:** [Vulcanized Platinum Bar](/item/19048), [Vulcanized Platinum Bar](/item/19048), [Ingot of the Devout](/item/19013), [Icon of the Devout](/item/19014)


>**Gavel the Temperant says:** Wear this with pride!


 **You receive:**  [Shield of the Devout](/item/9427) (+1000 exp)

**This NPC *should* return incorrect items given.**






