# Channeler Olaemos

## Dialog

**You say:** `Hail`



>**Channeler Olaemos says:** Greetings, Soandso. I am channeler Olaemos, one of five scholars in the art of evocation to reside here in Myrist. We have volunteered to temporarily halt our personal quests for knowledge and power beyond the material world so that we may aid the travelers in our midst. The spells we have scribed are native to your world, though in our hands they are available to all practitioners of the evocational arts despite race or religious differences. There is one other thing that I can aid you with should you truly be a wizard and that is the scribing of a most foreign and potent spell. I require you to find a piece of the untainted, fledgling magical manifestations upon the plane. These items appear as scrolls or runes that seem mundane to the eyes of mortals, though they are far more powerful than you realize. If you are fortunate enough to stumble across such a treasure, do not discard it but return it to me and I shall turn it into a power most befitting of the plane's travelers.
end

## Turn-Ins



local ethereal =  **You turn in:**  { [Ethereal Parchment](/item/29112)}

local spectral =  **You turn in:**  { [Spectral Parchment](/item/29131)}

local glyphed =  **You turn in:**  { [Glyphed Rune Word](/item/29132)}

if(ethereal > 0) then


repeat



>*Channeler Olaemos almost brashly snatches the item out of your grip with his small, cold froglok hands. The wizard eyes the item quickly, nodding and mumbling to himself at an inaudible tone. Eventually, the wizard begins to weave a spell around the item, which seems to become saturated with the conjured magic. Runes of a brilliant, shimmering azure appear upon the parchment, which is now wholly tangible in its form. As the spell ends, the froglok inspects his work one last time before offering the spell to you, 'Take this, Soandso. Do not use it without caution or discipline, for the power is unlike anything you have wielded in the past. It will affect both the divine and primal realms, despite its astral birth.*



 **You receive:** eq.ChooseRandom( [Spell: Greater Fetter](/item/26944), 28413, 28438, 28437, 21662, 28440, 28441, 28442) 



ethereal = ethereal - 1;


until ethereal == 0;

if(spectral > 0) then


repeat



>*Channeler Olaemos almost brashly snatches the item out of your grip with his small, cold froglok hands. The wizard eyes the item quickly, nodding and mumbling to himself at an inaudible tone. Eventually, the wizard begins to weave a spell around the item, which seems to become saturated with the conjured magic. Runes of a brilliant, shimmering azure appear upon the parchment, which is now wholly tangible in its form. As the spell ends, the froglok inspects his work one last time before offering the spell to you, 'Take this, Soandso. Do not use it without caution or discipline, for the power is unlike anything you have wielded in the past. It will affect both the divine and primal realms, despite its astral birth.*



 **You receive:** eq.ChooseRandom( [Spell: Force Shield](/item/28414), 28445, 28446, 28448, 26940, 28415, 28444, 28447) 



spectral = spectral - 1;


until spectral == 0;

if(glyphed > 0) then


repeat



>*Channeler Olaemos almost brashly snatches the item out of your grip with his small, cold froglok hands. The wizard eyes the item quickly, nodding and mumbling to himself at an inaudible tone. Eventually, the wizard begins to weave a spell around the item, which seems to become saturated with the conjured magic. Runes of a brilliant, shimmering azure appear upon the parchment, which is now wholly tangible in its form. As the spell ends, the froglok inspects his work one last time before offering the spell to you, 'Take this, Soandso. Do not use it without caution or discipline, for the power is unlike anything you have wielded in the past. It will affect both the divine and primal realms, despite its astral birth.*



 **You receive:** eq.ChooseRandom( [Spell: Shock of Magic](/item/26942), 21663, 28443, 28450) 



glyphed = glyphed - 1;


until glyphed == 0;

**This NPC *should* return incorrect items given.**






