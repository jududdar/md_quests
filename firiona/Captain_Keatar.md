# Captain Keatar
## Dialog

**You say:** `hail`



>**Captain Keatar says:** Hail! Beware of the [goblin raiders] roaming the plains outside of Firiona Vie. They ahve caused much trouble and continue to assault this outpost.

**You say:** `goblin raider`



>**Captain Keatar says:** The goblin raiders have been quite a nuisance to my trackers. I implore you to aid my men and lessen teh presence of the vile beasts. Bring me proof that you ahve taken at least four of these raiders down. You shall earn the respect of this outpost and insure your own well-being.

**You say:** `goblin battlemaster`



if **Faction** >= Amiable then





>**Captain Keatar says:** The goblin battlemasters are formidable fighters.  They have defeated many of the patrols I sent into the plains.  Bring me proof of four of these fallen goblins and I shall reward you with a piece of Faydark ringmail armor.




elseif **Faction** >= Indifferent then



>**Captain Keatar says:** I cannot trust you fully.  When you have performed more deeds in the name of the Union of Vie, then and only then shall I trust you.


else



>**Captain Keatar says:** You are no ally of the Union of Vie!  Leave my sight before I incarcerate you.

end

## Turn-Ins





if( **You turn in:** [Red Headband](/item/12922), [Red Headband](/item/12922), [Red Headband](/item/12922), [Red Headband](/item/12922)) then


>**Captain Keatar says:** You serve this outpost well. Here is a small reward. You should try to hunt down [goblin battlemasters]. I have very few resources to send into the plains to track them down. Perhaps you can help us.


* __Faction:__ [Inhabitants of Firiona Vie](/faction/248) (5)


* __Faction:__ [Emerald Warriors](/faction/326) (3)


* __Faction:__ [Storm Guard](/faction/312) (3)


* __Faction:__ [Legion of Cabilis](/faction/441) (-1)


* __Faction:__ [Pirates of Gunthak](/faction/313) (-1)


 **You receive:** 0 (+1000 exp)

elseif **Faction** >= Amiable and  **You turn in:** [Goblin Bracer](/item/12923), [Goblin Bracer](/item/12923), [Goblin Bracer](/item/12923), [Goblin Bracer](/item/12923)) then


>**Captain Keatar says:** Good work! Please accept this piece of armor. It was crafted in Felwithe for the swiftly moving rangers of this outpost.


* __Faction:__ [Inhabitants of Firiona Vie](/faction/248) (10)


* __Faction:__ [Emerald Warriors](/faction/326) (6)


* __Faction:__ [Storm Guard](/faction/312) (6)


* __Faction:__ [Legion of Cabilis](/faction/441) (-2)


* __Faction:__ [Pirates of Gunthak](/faction/313) (-2)


 **You receive:** eq.ChooseRandom( [Faydark Ringmail Coif](/item/12924), [Faydark Ringmail Collar](/item/12925), [Faydark Ringmail Coat](/item/12926), [Faydark Ringmail Mantle](/item/12927), [Faydark Ringmail Skirt](/item/12928), [Faydark Ringmail Sleeves](/item/12929), [Faydark Ringmail Bracer](/item/12930), [Faydark Ringmail Gloves](/item/12931), [Faydark Ringmail Pants](/item/12932), [Faydark Ringmail Boots](/item/12933)) (+5000 exp)

**This NPC *should* return incorrect items given.**
