# Bonlarg
## Dialog

**You say:** `Hail`



>**Bonlarg says:** Shadowknight master me be!!  Soandso prove to me that Soandso be worthy to be one with Greenblood and me give Soandso black shadow tunic.  You [want black shadow tunic]?

**You say:** `want black shadow tunic`



if **Faction** >= Amiable then



>**Bonlarg says:** You hunt lizard scouts. Them sometimes carry special fife to talk to other lizards far away. Greenbloods stop them. Bring Bonlarg three lizard scout fifes and green stained skin tunic you gots when you first talk to Soonog. Give all to Bonlarg and get tunic.




elseif **Faction** >= Indifferent then



>**Bonlarg says:** Help Greenbloods you will. Give lizard tails to Grevak.  Den maybe we trust.


else



>**Bonlarg says:** Foe of Greenbloods you are. In two I will rip you. Best if run.



end

## Turn-Ins



local text = "Fool! Bonlarg say THREE lizardman scout fifes and green stained skin tunic.";




if **Faction** >= Amiable and  **You turn in:** [Lizardman Scout Fife](/item/12198), [Lizardman Scout Fife](/item/12198), [Lizardman Scout Fife](/item/12198), [Green Stained Skin Tunic*](/item/13527)) then


>**Bonlarg says:** Took you long time! It easy task, but me guess you still earn black shadow tunic. You wear to show all that you young shadowknight. It help you be smarter likes Bonlarg. It only for young Greenblood shadowknight. Maybe later green shadow tunic you earn or maybe dead you be


* __Faction:__ [Green Blood Knights](/faction/261) (5)


* __Faction:__ [Clurg](/faction/228) (2)


* __Faction:__ [Storm Guard](/faction/312) (-1)


* __Faction:__ [Shadowknights of Night Keep](/faction/308) (-1)


 **You receive:**  [Black Shadow Tunic](/item/12199) (+500 exp)

**This NPC *should* return incorrect items given.**





