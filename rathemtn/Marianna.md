# Marianna
## Dialog

**You say:** `hail`



>**Marianna says:** Rodcet Nife welcomes you into our noble camp.  I am the keeper of the [Vambraces of Ro].

**You say:** `vambraces of ro`



if **Faction** >= Indifferent +50 then



>**Marianna says:** The mold will be offered to you when you have performed a task for the Temple of Life.  The oceans near our home are host to a plague..  the plague sharks!!  They have been infected with a deadly malady which has been turning up in the Qeynos Hills.  Kill the sharks and bring me two of their rotten shark portions as proof.


elseif **Faction** >= Indifferent then



>**Marianna says:** In the name of Rodcet Nife, I must ask you to venture to Qeynos and find the Temple of Life.  There you shall serve until High Priestess Jhanda responds when you ask her, am [I an honored member]?


else



>**Marianna says:** Foolish person!! The word is out amongst the followers of the Prime Healer not to trust you.

end

## Turn-Ins



local text = "I said two portions of rotten shark meat.";



if **Faction** >= Indifferent +50 and  **You turn in:** [Rotten Shark Meat](/item/12310), [Rotten Shark Meat](/item/12310)


>**Marianna says:** You now own a mold for the Vambraces of Ro.  Go and ask Thomas of [Lord Searfire] for the final component.


* __Faction:__ [Priests of Life](/faction/341) (20)


* __Faction:__ [Knights of Thunder](/faction/280) (6)


* __Faction:__ [Guards of Qeynos](/faction/262) (10)


* __Faction:__ [Bloodsabers](/faction/221) (-5)


* __Faction:__ [Antonius Bayle](/faction/219) (3)


 **You receive:**  [Mold of Ro Vambrace](/item/12300) (+1000 exp)

**This NPC *should* return incorrect items given.**







