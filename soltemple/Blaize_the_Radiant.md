# Blaize the Radiant


## Dialog

**You say:** `Hail`



>**Blaize the Radiant says:** Hail, faithful one. I am Blaize the Radiant. Brother Gavel and I are well known among clerics for our forging skills, but special payment is required for our services. Special [Ingots and Icons] given to our members have been lost, and we will reward whoever retrieves them for us.

**You say:** `ingots and icons`



>**Blaize the Radiant says:** The Ingots and Icons are all named after the virtues of the cleric who held them. The virtues I require are those of the [Reliant], the [Ardent], the [Fervent] and the [Penitent].

**You say:** `reliant`



>**Blaize the Radiant says:** Turgan the Reliant lived in a cabin in the Kithicor woods until there was a great fire. Searching the burned cabins there may turn something up. He always loved Lake Rathetear as well. Bring me the Ingot of the Reliant, the Icon of the Reliant, and one Enchanted Platinum Bar and I will forge them into a reward for you.

**You say:** `ardent`



>**Blaize the Radiant says:** Theo the Ardent was in constant war with a gnome necromancer in Befallen named Babbinsbort, but he never could defeat him. Poor Theo drown on an expedition to Everfrost when the ice of the frozen river gave way underneath him. Bring me the Ingot of the Ardent, the Icon of the Ardent, and 1 Galvanized Platinum Bar and I will forge them into a reward for you.

**You say:** `fervent`



>**Blaize the Radiant says:** Jovan the Fervent was always prone to vice. He lost his ingot in a game of Kings Court with an aviak named Gull in the Ocean of Tears. After that he became a drunkard and it has been said he lurks around the bars in Highpass Hold. Bring me the Ingot of the Fervent, the Icon of the Fervent, and 1 Vulcanized Platinum Bar and I will forge them into a reward for you.

**You say:** `penitent`



>**Blaize the Radiant says:** Astrid the Penitent often visited the frogloks of Upper Guk. She once told me her ingot was hidden underwater there. I found that strange because she couldn't swim. She was also a good friend to the Kerrans of Kerra Ridge, where she lost her life fighting against the Erudite hereitic Maugarim. Bring me the Ingot of the Penitent, the Icon of the Penitent, and one Magnetized Platinum Bar and I will forge them into a reward for you.
end

## Turn-Ins



local text = "Impressive, do you have the rest?";


if **You turn in:** [Ingot of the Reliant](/item/19001), [Icon of the Reliant](/item/19002), [Enchanted Platinum Bar](/item/16507)


>**Blaize the Radiant says:** Wear this with pride!


 **You receive:**  [Boots of the Reliant](/item/4921) (+1000 exp)

elseif **You turn in:** [Ingot of the Penitent](/item/19007), [Icon of the Penitent](/item/19008), [Magnetized Platinum Bar](/item/19049)


>**Blaize the Radiant says:** Wear this with pride!


 **You receive:**  [Greaves of the Penitent](/item/4924) (+1000 exp)

elseif **You turn in:** [Ingot of the Ardent](/item/19003), [Icon of the Ardent](/item/19004), [Galvanized Platinum Bar](/item/19047)


>**Blaize the Radiant says:** Wear this with pride!


 **You receive:**  [Gauntlets of the Ardent](/item/4922) (+1000 exp)

elseif **You turn in:** [Ingot of the Fervent](/item/19005), [Icon of the Fervent](/item/19006), [Vulcanized Platinum Bar](/item/19048)


>**Blaize the Radiant says:** Wear this with pride!


 **You receive:**  [Vambraces of the Fervent](/item/4923) (+1000 exp)
end






