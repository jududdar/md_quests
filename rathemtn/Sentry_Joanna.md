# Sentry Joanna
## Dialog

**You say:** `hail`



>**Sentry Joanna says:** Love and passion to you. my friend.  Seek you the [Gauntlets of Ro]?  If not. then I offer you the safety of this camp.

**You say:** `gauntlets of ro`



if **Faction** >= Indifferent +50 then



>**Sentry Joanna says:** I will give you the mold. but first you will complete a task in the name of Erollisi Marr.  My fellow Sentry. Alechin. was bitten by a wolf while he journeyed to Qeynos.  He now turns into a werewolf at night. forced to kill innocent travelers.  Go toward Qeynos.  Release him from life and his curse and return his locket to me.


elseif **Faction** >= Indifferent then



>**Sentry Joanna says:** Erollisi would not approve of our alliance. not yet at least.  Go to Freeport and serve the Temple of Marr.  When you can ask Gygus Remnara if you are an [honored member] and have him answer yes. then we can join forces.


else



>**Sentry Joanna says:** The passion of the Queen of Love does not favor you. Begone from my sight!



end


## Turn-Ins




if **Faction** >= Indifferent +50 and  **You turn in:** [A Locket](/item/12312)


>**Sentry Joanna says:** Thank you my friend.  It is good to see him free at last.  I shall miss him.  Here now is the mold of gauntlets as promised. Go and speak with Thomas for information about [Lord Searfire].


* __Faction:__ [Knights of Truth](/faction/281) (3)


* __Faction:__ [The Freeport Militia](/faction/330) (-2)


* __Faction:__ [Priests of Marr](/faction/362) (20)


 **You receive:**  [Mold of Ro Gauntlets](/item/12302) (+1000 exp)

**This NPC *should* return incorrect items given.**






