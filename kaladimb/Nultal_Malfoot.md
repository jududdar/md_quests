# Nultal Malfoot
## Dialog

**You say:** `hail`



>**Nultal Malfoot says:** May the power of Underfoot be with you. Welcome. I am here to serve the will of the king as should you. If you [need healing], then speak. Or perhaps you are here to [return skunk glands]?

**You say:** `healing`



if **Faction** >= Indifferent then



>**Nultal Malfoot says:** Before the power of Underfoot can attempt to bind your wounds you must pay tribute. Three gold coins!!


else



>**Nultal Malfoot says:** How dare you approach a member of the Clerics of Underfoot?!  Dogs such as you lie in the same bed as aviaks and ogres!


**You say:** `glands`



if **Faction** >= Amiable then



>**Nultal Malfoot says:** I have made an offer to all clerics of this cathedral. I shall reward one cleric scroll from our scribes for the return of four skunk scent glands. This offer is best left to our clerics.


elseif **Faction** >= Indifferent then



>**Nultal Malfoot says:** The Clerics of Underfoot have yet to see your faith directed towards our wills. Perhaps you should assist Master Gunlok Jure in the crusade against the undead.


else



>**Nultal Malfoot says:** How dare you approach a member of the Clerics of Underfoot?!  Dogs such as you lie in the same bed as aviaks and ogres!

end

## Turn-Ins



local text = "There shall be no scroll until I see four skunk scent glands.";



if **Faction** >= Indifferent and  **You turn in:** gold = 3


>**Nultal Malfoot says:** Be healed!


**Nultal Malfoot casts:** [Light Healing](/spell/17) on target.


elseif **Faction** >= Amiable and  **You turn in:** [Skunk Scent Gland](/item/14030), [Skunk Scent Gland](/item/14030), [Skunk Scent Gland](/item/14030), [Skunk Scent Gland](/item/14030)


>**Nultal Malfoot says:** I thank you for your good deed. I trust it was not a problem. Take this scroll. A cleric of this cathedral will find it useful. May the power of Underfoot be with you.


* __Faction:__ [Clerics of Underfoot](/faction/227) (5)





* __Faction:__ [Kazon Stormhammer](/faction/274) (5)




* __Faction:__ [Miners Guild 249](/faction/293) (3)




 **You receive:** eq.ChooseRandom( [Spell: Cure Poison](/item/15203), [Spell: Fear](/item/15229), [Spell: Furor](/item/15560), [Spell: Gate](/item/15036), [Spell: Stun](/item/15216), [Spell: Reckless Strength](/item/15215)) (+5000 exp)

**This NPC *should* return incorrect items given.**
