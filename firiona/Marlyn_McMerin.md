# Marlyn McMerin
## Dialog

**You say:** `hail`



>**Marlyn McMerin says:** Greetings hearty adventurer. Searching for the components necessary for fine shaman spells are we? I have come to Kunark in search of [rare alchemy components], but I have found the dangers of Kunark are far too great for me.


e.self:DoAnim(69);

**You say:** `rare alchemy components`



>**Marlyn McMerin says:** I have heard word of four rare components -  the clay of Ghiosk, crushed dread diamonds and powder of Yun.  Most rare are chips from the bones of one who has touched the Bath of Obulus.


e.self:DoAnim(27);
end

## Turn-Ins



local text = "I requested the bone chips which touched the Bath of Obulus, clay of Ghiosk, powder of Yun and crushed dread diamonds.";




if( **You turn in:** [Strange Ochre Clay](/item/12942), [Crushed Diamonds](/item/12945), [Yun Shaman Powder](/item/12944), [Greyish Bone Chips](/item/12943)) then


>**Marlyn McMerin says:** What's this? This is amazing - you collected them all! To think, the power that these items hold if properly used. Never mind that now, here, take the scroll. You've certainly earned it.


* __Faction:__ [Inhabitants of Firiona Vie](/faction/248) (5)


* __Faction:__ [Emerald Warriors](/faction/326) (3)


* __Faction:__ [Storm Guard](/faction/312) (3)


* __Faction:__ [Legion of Cabilis](/faction/441) (-1)


* __Faction:__ [Pirates of Gunthak](/faction/313) (-1)


 **You receive:**  [Spell: Cannibalize II](/item/12941) (+45000 exp)

**This NPC *should* return incorrect items given.**






