# Ulazia W\`Selo



[Ulazia W\`Selo](/npc/42080) is a level 61 Dark Elf GM Cleric that spawns in [Neriak - 3rd Gate](/zone/42).



## Dialog

**You say:** `hail`



>**Ulazia W-Selo says:** Welcome to the Spires of Innoruuk.  May your destiny be paved with the Words of Innoruuk.  What is it you seek? [Healing]?  [Curing of disease]?  [Curing of poison]?  That is my divine duty.  So commands Master Zexus.

**You say:** `disease`



if **Faction** >= Indifferent then



>**Ulazia W-Selo says:** Whatever the malady, I can surely rid you of it.  First, you must donate 6 gold coins.  The power of life is not easily acquired when you follow the unholy might of Innoruuk.


else



>**Ulazia W-Selo says:** No sane member of the Priests of Innoruuk would tolerate your presence. Begone or more than words shall I lay upon thee.




**You say:** `poison`



if **Faction** >= Indifferent then



>**Ulazia W-Selo says:** So, a toxic substance races to your heart?  It is best we stop that at once!  Ah...  But, before I go on, you must pay the required donation of 8 gold coins.


else



>**Ulazia W-Selo says:** No sane member of the Priests of Innoruuk would tolerate your presence. Begone or more than words shall I lay upon thee.




**You say:** `heal`



if **Faction** >= Indifferent then



>**Ulazia W-Selo says:** So, it is the binding of wounds you desire. I could hardly tell with the smell of sacrifice drifting through the corridors of the Spires of Innoruuk. To be healed, I require a donation of 10 gold coins.


else



>**Ulazia W-Selo says:** No sane member of the Priests of Innoruuk would tolerate your presence. Begone or more than words shall I lay upon thee.




**You say:** `curing`



if **Faction** >= Indifferent then



>**Ulazia W-Selo says:** So curing is what you have come for! Seek out Mistress Ulazia W'selo.


else



>**Ulazia W-Selo says:** No sane member of the Priests of Innoruuk would tolerate your presence. Begone or more than words shall I lay upon thee.




**You say:** `i.* heal`



if **Faction** >= Indifferent then



>**Ulazia W-Selo says:** So, it is the binding of wounds you desire. I could hardly tell with the smell of sacrifice drifting through the corridors of the Spires of Innoruuk. To be healed, I require a donation of 10 gold coins.


else



>**Ulazia W-Selo says:** No sane member of the Priests of Innoruuk would tolerate your presence. Begone or more than words shall I lay upon thee.




**You say:** `innoruuk`



if **Faction** >= Indifferent then



>**Ulazia W-Selo says:** You speak the name of the Prince of Hate. He is the higher power who set the Teir'Dal upon this land. All Teir'Dal pay homage to Him. If they do not, they are surely [heretics]. And, if they are heretics, they surely must die!


else



>**Ulazia W-Selo says:** No sane member of the Priests of Innoruuk would tolerate your presence. Begone or more than words shall I lay upon thee.




**You say:** `heretic`



if **Faction** >= Indifferent then



>**Ulazia W-Selo says:** Speak not of Teir'Dal heretics. Those Teir'Dal who do not follow Innoruuk shall be cut down! Master Kerton R'dev of the Spires of Innoruuk is seeing to that.


else



>**Ulazia W-Selo says:** No sane member of the Priests of Innoruuk would tolerate your presence. Begone or more than words shall I lay upon thee.




**You say:** `teir`



if **Faction** >= Indifferent then



>**Ulazia W-Selo says:** I see the ancient language of the elf kind has been neglected. We dark elves are the Teir'Dal, superior to all elves. The high elves are known as the Koada'Dal and the wood elves are the Feir'Dal. There was once another, but that race is now extinct.


else



>**Ulazia W-Selo says:** No sane member of the Priests of Innoruuk would tolerate your presence. Begone or more than words shall I lay upon thee.




**You say:** `master`



if **Faction** >= Amiable then



>**Ulazia W-Selo says:** All members of the Priests of Innoruuk look to the unholy might of Perrir Zexus for direction.


elseif **Faction** >= Indifferent then



>**Ulazia W-Selo says:** Your devotion to the Priests of Innoruuk has yet to be proven to the desired extent.





else



>**Ulazia W-Selo says:** No sane member of the Priests of Innoruuk would tolerate your presence. Begone or more than words shall I lay upon thee.



end



## Turn-Ins




if **Faction** >= Indifferent and  **You turn in:** gold = 6) then


>**Ulazia W-Selo says:** May the breath of life pass through your failing body and cast its foes from you. Unnngh... Praise Innoruuk!


**Ulazia W-Selo casts:** [Counteract Disease](/spell/96) on target.

elseif **Faction** >= Indifferent and  **You turn in:** gold = 8) then


>**Ulazia W-Selo says:** May the breath of life pass through your failing body and cast its foes from you. Unnngh... Praise Innoruuk!


**Ulazia W-Selo casts:** [Counteract Poison](/spell/95) on target.

elseif **Faction** >= Indifferent and  **You turn in:** gold = 10) then


>**Ulazia W-Selo says:** May the breath of life pass through your failing body and cast its foes from you. Unnngh... Praise Innoruuk!


**Ulazia W-Selo casts:** [Healing](/spell/12) on target.

**This NPC *should* return incorrect items given.**

end