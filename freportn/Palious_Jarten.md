# Palious Jarten


## Dialog

**You say:** `hail`



>**Palious Jarten says:** It is good to see you, Soandso!! Do not forget that the clerics of Mithaniel Marr are here to help those who pay tribute to Him. Should you require me to [cure disease], just mention it.

**You say:** `cure disease`



>**Palious Jarten says:** If you require me to cure disease, it will cost you 10 gold coins.
end



## Turn-Ins




if( **You turn in:** gold = 10) then


>**Palious Jarten says:** May the valor of Mithaniel Marr burn brightly in our soul!


**Palious Jarten casts:** [Cure Disease](/spell/213) on target.

**This NPC *should* return incorrect items given.**
