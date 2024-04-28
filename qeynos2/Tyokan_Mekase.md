# Tyokan Mekase
## Dialog

**You say:** `hail`



>**Tyokan Mekase says:** Please look around. We have many items exclusively for the members of the Temple of Life. We also have [scroll strongboxes]. If you are unsure of what an item is, feel free to ask me.

**You say:** `scroll strongbox`



if **Faction** >= Indifferent then



>**Tyokan Mekase says:** The scroll strongboxes are merely personal safes. Most of the members use them. I am afraid all are taken, but if you are here to remove a scroll, merely hand me your key and I shall get it for you. I handle all 20 numbered keys and [Whysia] handles all 30 and 40 numbered keys.


else



>**Tyokan Mekase says:** Your mere presence disgusts me. Please remove yourself from my sight. Until you change yourself and your ways, you are unwelcome in the Temple of Life.



**You say:** `whysia`



>**Tyokan Mekase says:** Whysia works the night shift here.  She is quite the night owl.

**You say:** `prayer beads`



>**Tyokan Mekase says:** The prayer beads are the blessed necklaces of the Priests of Life.  The beads have a few charges of minor healing.  I recharge them for all members in  good standing.  All I need are the beads and a donation of 100 gold pieces.
end

## Turn-Ins



local text = "As instructed by High Priestess Jahnda I must ask for the beads and a donation of 100 gold coins.";


if **Faction** >= Amiable and  **You turn in:** [T.O.L. 2020](/item/13306)


>**Tyokan Mekase says:** Oh, turning in your key, are you? Very well, defender of life. Here you are.


 **You receive:** eq.ChooseRandom( [Spell: Inspire Fear](/item/15126), [Spell: Greater Healing](/item/15015), [Spell: Ward Summoned](/item/15248)) 

elseif **Faction** >= Amiable and  **You turn in:** [Prayer Beads](/item/13296), gold=100


>**Tyokan Mekase says:** I see your beads need to be charged. Very well, here you are. Use them and good health to you!!!


 **You receive:**  [Prayer Beads](/item/13296) 

**This NPC *should* return incorrect items given.**
