# Luminare Pasinia
## Dialog

**You say:** `hail`



>*Luminare Pasinia waves her hands as if to cast a spell.  'GREETINGS!!  I am the Luminare of Firiona.  By decree of his royal highness, King Thex, I am here to research spells and artifacts.  I have much to do.  I welcome any enchanter who offers to [assist the great Luminare].'*


e.self:DoAnim(43);

**You say:** `assist`



>**Luminare Pasinia says:** And great I am, indeed!! Alas, not great enough to be everywhere at once. I would gladly reward you if you would [collect] components for me.


e.self:DoAnim(42);

**You say:** `collect`



>**Luminare Pasinia says:** Then go into the wilds beyond the outpost and upon your return, you shall give me one Nok Shaman Powder, one Heart of Ice, one Ton Warrior Totem, and one Sabertooth Tiger Mane. This shall earn you knowledge of an enchanter spell I recently scribed.


e.self:DoAnim(64);
end

## Turn-Ins



local text = "Do you not remember that I asked for powder of Nok, a Ton warrior totem, a heart of ice and a sabertooth tiger mane? Incomplete deeds shall fetch no enchanter reward.";






if **You turn in:** [Nok Shaman Powder](/item/12948), [Heart of Ice](/item/12834), [Ton Warrior Totem](/item/12743), [Sabertooth Tiger Mane](/item/12824)


>*Luminare Pasinia places the items into a sack and removes a scroll from her robe. This is yours. A spell I discovered and translated for one with less intelligence than the great Luminare of Firiona Vie. You may kiss my feet now.*


* __Faction:__ [Inhabitants of Firiona Vie](/faction/248) (3)


* __Faction:__ [Emerald Warriors](/faction/326) (2)


* __Faction:__ [Storm Guard](/faction/312) (2)


* __Faction:__ [Legion of Cabilis](/faction/441) (-1)


* __Faction:__ [Pirates of Gunthak](/faction/313) (-1)


 **You receive:**  [Vision of Sebilite](/item/12949) (+250 exp)

**This NPC *should* return incorrect items given.**





