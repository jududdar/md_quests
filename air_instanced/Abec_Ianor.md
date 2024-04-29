# Abec Ianor
## On NPC Spawn

**Set a timer** named *depop* for 300 seconds
## Dialog

**You say:** `hail`



>**Abec Ianor says:** Great, let us waste no more time! Do you wish to begin your test of conception, visualization, or preparation?

**You say:** `conception`





>**Abec Ianor says:** Conception is vital. Travel beyond and bring forth an Efreeti Statuette, a Mithril Air Ring, and a Box of Winds. From these I will produce a ring that will protect you where ever you go.

**You say:** `visualization`




>**Abec Ianor says:** Visualize and succeed. Proceed upward and bring to me a White-Tipped Spiroc Feather, a Pulsating Sapphire, and an Amethyst Amulet. With these items, I will be able to produce an amulet that will aid in your travels to our home.

**You say:** `preparation`





>**Abec Ianor says:** Always be prepared. Adventure and return an Efreeti War Staff, some Lush Nectar, a Copper Air Band, and a large Sky Sapphire and you shall be rewarded with the Staff of Storms.
end

## Turn-Ins



if( **You turn in:** [Efreeti Statuette](/item/20951), [Mithril  Air Ring](/item/20747), [Box of Winds](/item/20748)) then








>**Abec Ianor says:** Excellent! Take this.


 **You receive:**  [Solidate Mithril Ring](/item/11686) (+100000 exp)


**Abec Ianor despawns.**

elseif( **You turn in:** [White-tipped Spiroc Feather](/item/20958), [Pulsating Sapphire](/item/20749), [Amethyst Amulet](/item/20750)) then







>**Abec Ianor says:** Excellent! Take this.


 **You receive:**  [Amulet of the Void](/item/27710) (+100000 exp)


**Abec Ianor despawns.**

elseif( **You turn in:** [Efreeti War Staff](/item/20753), [Lush Nectar](/item/20965), [Copper Air Band](/item/20751), [Large Sky Sapphire](/item/20752)) then



>**Abec Ianor says:** Excellent! Take this.


 **You receive:**  [Nargon's Staff](/item/11685) (+100000 exp)


**Abec Ianor despawns.**

**This NPC *should* return incorrect items given.**

## Timer(s)

**Stop timer** named *depop*

**Abec Ianor despawns.**




