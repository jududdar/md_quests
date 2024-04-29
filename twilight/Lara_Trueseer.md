# Lara Trueseer
## Dialog

**You say:** `hail`



>*Lara Trueseer grimaces in pain. 'The visions are so strong they hurt...please make them stop..*

**You say:** `vision`



>**Lara Trueseer says:** I keep getting these random visions of places unknown to me. Perhaps you could help me with a cure.

**You say:** `help`



>**Lara Trueseer says:** Ah my thanks! For doing this I can reward you with pieces of a set of armor for enchanters. Are you an enchanter?

**You say:** `enchanter`



>**Lara Trueseer says:** Very good. I have a cap, robe, sleeves, pants, shawl, and bracer. My friend Xavier has the rest just ask him about armor.

**You say:** `cap`



>**Lara Trueseer says:** For the cap I will need an astral jewel, a golden flower, a grail of enchantment, and a mark of beauty.

**You say:** `robe`



>**Lara Trueseer says:** For the robe I will need a sun jewel, the eye of the enraptured, a mark of affection, and a book of inspiration.

**You say:** `sleeves`



>**Lara Trueseer says:** For the sleeves I will need a moon jewel, a page of prose, a mark of reality, and a truncated ring.

**You say:** `pants`



>**Lara Trueseer says:** For the pants I will need a star jewel, a mark of passion, an adamantium quill, and pristine shik-nar claws.

**You say:** `shawl`



>**Lara Trueseer says:** For the shawl I will need a cloud jewel, a mark of understanding, and a hope emerald.

**You say:** `bracer`



>**Lara Trueseer says:** For the bracer I will need a sky jewel, a mark of elegance, and a hope sapphire.
end

## Turn-Ins



local text = "You have done well to bring me this, but there is more needed before you get your reward.";



if( **You turn in:** [Astral Jewel](/item/4494), [Golden Flower](/item/4675), [Grail of Enchantment](/item/4676), [Mark of Beauty](/item/4677)) then 


 **You receive:**  [Cap of Enrapturement](/item/3697) (+25000 exp)

elseif( **You turn in:** [Sun Jewel](/item/4488), [Eye of the Enraptured](/item/4678), [Mark of Affection](/item/4679), [Book of Inspiration](/item/4680)) then 


 **You receive:**  [Robe of Enrapturement](/item/3698) (+25000 exp)

elseif( **You turn in:** [Moon Jewel](/item/4489), [Page of Prose](/item/4681), [Mark of Reality](/item/4682), [Truncated Ring](/item/4683)) then 


 **You receive:**  [Sleeves of Enrapturement](/item/3699) (+25000 exp)

elseif( **You turn in:** [Star Jewel](/item/4490), [Mark of Passion](/item/4684), [Adamantium Quill](/item/4685), [Pristine Shik-Nar Claws](/item/4686)) then 


 **You receive:**  [Pants of Enrapturement](/item/3700) (+25000 exp)

elseif( **You turn in:** [Cloud Jewel](/item/4491), [Mark of Understanding](/item/4687), [Hope Emerald](/item/4688)) then 


 **You receive:**  [Shawl of Enrapturement](/item/3701) (+25000 exp)

elseif( **You turn in:** [Sky Jewel](/item/4492), [Mark of Elegance](/item/4689), [Hope Sapphire](/item/4690)) then 


 **You receive:**  [Bracer of Enrapturement](/item/3702) (+25000 exp)

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Lara Trueseer says:** Soandso take this and use it with pride.

* __Faction:__ [Katta Castellum Citizens](/faction/1502) (5)

* __Faction:__ [Validus Custodus](/faction/1503) (1)

* __Faction:__ [Magus Conlegium](/faction/1504) (1)

* __Faction:__ [Citizens of Seru](/faction/1499) (-2)

* __Faction:__ [Seru](/faction/1483) (-1)

* __Faction:__ [Shoulders of Seru](/faction/1487) (-1)