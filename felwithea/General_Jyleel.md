# General Jyleel
## Dialog

**You say:** `hail`



>**General Jyleel says:** Stand at attention!!  I am General Jyleel. of the Koada'Vie. defenders of Felwithe.  Do you [follow Tunare]. the Mother of All. or do you still [seek your enlightenment]?

**You say:** `follow tunare`



if **Faction** >= Amiable then




>**General Jyleel says:** Then you are wise indeed.  Would you like to [assist the defenders] in our conflicts or have you other business to attend to?


elseif( **Faction is** == Indifferent) then



>**General Jyleel says:** No.  You have yet to prove yourself a truly faithful defender of the Clerics of Tunare.  I await your return when you complete your service to the temple.


else



>**General Jyleel says:** You have some nerve to approach a loyal member of the Paladins of Tunare! Run, while you can!


**You say:** `seek my enlightenment`



>**General Jyleel says:** Then seek it within these walls.  We welcome all fine upstanding Koada'Dal.

**You say:** `assist the defenders`



if **Faction** >= Amiable then



>**General Jyleel says:** Seek out the Crushbone orcs of the Faydarks.  We must have their oracle scrolls.  They are illegible to you, but we will study them here in Felwithe.  Only the orc oracles will carry them, so be very careful.  There is also the problem with the [Crushbone runners].


elseif( **Faction is** == Indifferent) then



>**General Jyleel says:** No.  You have yet to prove yourself a truly faithful defender of the Clerics of Tunare.  I await your return when you complete your service to the temple.


else



>**General Jyleel says:** You have some nerve to approach a loyal member of the Paladins of Tunare! Run, while you can!


**You say:** `crushbone runners`



if **Faction** >= Amiable then



>**General Jyleel says:** The Crushbone orcs are sending messages across the Ocean of Tears to Antonica.  Why. we do not know.  The runner is usually spotted on the open pathways of Butcherblock. running toward the docks.  Find him. kill him. and return his note pouch.


elseif( **Faction is** == Indifferent) then



>**General Jyleel says:** No.  You have yet to prove yourself a truly faithful defender of the Clerics of Tunare.  I await your return when you complete your service to the temple.


else



>**General Jyleel says:** You have some nerve to approach a loyal member of the Paladins of Tunare! Run, while you can!


**You say:** `faithful paladin`



if **Faction** >= Amiable then



>**General Jyleel says:** I command you to seek out this Ambassor DVinn and rip his heart from his lifeless body. Next, find the supreme caster of the orcs and, finally, find the spot where supplies are dropped by the Teir\`Dal for the orcs. There you should find the supply crate. Return all 3 items and you shall wield the falchion.


elseif( **Faction is** == Indifferent) then



>**General Jyleel says:** No.  You have yet to prove yourself a truly faithful defender of the Clerics of Tunare.  I await your return when you complete your service to the temple.


else



>**General Jyleel says:** You have some nerve to approach a loyal member of the Paladins of Tunare! Run, while you can!

end

## Turn-Ins




if **Faction** >= Amiable and  **You turn in:** [Illegible Scroll](/item/13225)


>**General Jyleel says:** Very fine work. A pity you are not Koada'Vie. Here is a small reward for you. Anytime you come upon an oracle. remember to return its scroll to me. Go and find your fate on the field of battle.


* __Faction:__ [Clerics of Tunare](/faction/226) (5)


* __Faction:__ [King Tearis Thex](/faction/279) (5)


* __Faction:__ [Anti-mage](/faction/5002) (3)


if(math.random(100) > 10) then



 **You receive:** eq.ChooseRandom( [Small Lantern](/item/13003), [Large Lantern](/item/13004), [Potion of Sustenance](/item/14013), [Dagger](/item/7001), [Iron Ration](/item/13005), [Bandages](/item/13009)) (+500 exp)


else



 **You receive:** eq.ChooseRandom( [Spell: Pillage Enchantment](/item/15025), [Spell: Brilliance](/item/15033), [Spell: Plague](/item/15032), [Spell: Minor Conjuration: Air](/item/15623)) (+500 exp)


elseif **Faction** >= Amiable and  **You turn in:** [Runner Pouch](/item/13226)


>**General Jyleel says:** So, you succeeded in stopping a Crushbone runner! That is good. Now take this as reward. Keep up your fine work. The people of Felwithe are grateful.


* __Faction:__ [Clerics of Tunare](/faction/226) (5)


* __Faction:__ [King Tearis Thex](/faction/279) (5)


* __Faction:__ [Anti-mage](/faction/5002) (3)


if(math.random(100) > 10) then 



 **You receive:** eq.ChooseRandom( [Small Lantern](/item/13003), [Large Lantern](/item/13004), [Potion of Sustenance](/item/14013), [Dagger](/item/7001), [Iron Ration](/item/13005), [Bandages](/item/13009)) (+500 exp)


else



 **You receive:** eq.ChooseRandom( [Spell: Pillage Enchantment](/item/15025), [Spell: Brilliance](/item/15033), [Spell: Plague](/item/15032), [Spell: Minor Conjuration: Air](/item/15623)) (+500 exp)



elseif **Faction** >= Amiable and  **You turn in:** [A Sealed Letter](/item/18840)


>**General Jyleel says:** So, the Teir'Dal are behind the recent advances of the orcs?!! Your news has shed light on their union. It is time to step forth and prove yourself a [faithful paladin of this court].


* __Faction:__ [Clerics of Tunare](/faction/226) (10)


* __Faction:__ [King Tearis Thex](/faction/279) (10)


* __Faction:__ [Anti-mage](/faction/5002) (7)


 **You receive:** 0 (+1000 exp)

elseif **Faction** >= Amiable +100 and  **You turn in:** [A Large Locked Crate](/item/12330), [Blue Orc Head](/item/12329), [Black Heart](/item/13227)


>**General Jyleel says:** A noble deed has been done and the alliance of evil has been stalled. I present you with the falchion of the Koada\`Vie. You are now an honorable member of our order. Hail Felwithe, and may you defender her with honor.


* __Faction:__ [Clerics of Tunare](/faction/226) (50)


* __Faction:__ [King Tearis Thex](/faction/279) (50)


* __Faction:__ [Anti-mage](/faction/5002) (3)


 **You receive:**  [Falchion of the KoadaVie](/item/5379) (+1500 exp)

**This NPC *should* return incorrect items given.**
;

