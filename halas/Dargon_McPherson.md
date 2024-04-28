# Dargon McPherson
## Dialog

**You say:** `Hail`



>**Dargon McPherson says:** Hail, mighty Soandso! I assume ye must be a [warrior o' the Wolves]. Why else would ye approach a trainer such as meself, then?

**You say:** `warrior o' the Wolves`



if( **Faction is** > Indifferent) then 



>**Dargon McPherson says:** Aye, 'tis as I thought. I'm glad t' see we've warriors such as yerself amongst the Wolves o' the North. Lately, Kylan's been allowing too many scrawny warriors in, methinks. Nor have they fared well in Everfrrost. Many frreeze to death, ye know... Will ye assist me and [deliver an elixir to young warriors] in Everfrost?


elseif( **Faction is** == Indifferent) then



>**Dargon McPherson says:** The Wolves o' the North show ye no ill will, but there's much ye must do t' earn our trust.  Perhaps ye should speak with Lysbith and inquire o' the [gnoll bounty].


elseif( **Faction is** < Indifferent) then



>**Dargon McPherson says:** Run while ye still can!! The Wolves o' the North will not tolerate yer presence!


**You say:** `deliver an elixir to young warriors`



if( **Faction is** > Indifferent) then 



>**Dargon McPherson says:** Ach, 'tis good o' ye! Take this bottle of elixir to Everfrost Peaks. Find Talin O'Donal. He'll take the first sip, and then instruct ye on who else ye need to find. Do that, and I'll give ye a fine reward when ye return the empty elixir bottle. Good luck, then. Don't die.



**You receive:**  [Full Bottle of Elixir](/item/13241)


elseif( **Faction is** == Indifferent) then



>**Dargon McPherson says:** The Wolves o' the North show ye no ill will, but there's much ye must do t' earn our trust.  Perhaps ye should speak with Lysbith and inquire o' the [gnoll bounty].


elseif( **Faction is** < Indifferent) then



>**Dargon McPherson says:** Run while ye still can!! The Wolves o' the North will not tolerate yer presence!

end

## Turn-Ins



if( **Faction is** > Indifferent and  **You turn in:** [Empty Bottle of Elixir](/item/13245)


>**Dargon McPherson says:** Ye've proven yerself to be a cut above the rest and aided yer fellow warriors, no matter how worthless they were. Ye may take this. It was found in the snow by one of our foraging parties. I hope it can be of use to a warrior like yerself.





* __Faction:__ [Wolves of the North](/faction/320) (5)


* __Faction:__ [Shamen of Justice](/faction/327) (1)


* __Faction:__ [Merchants of Halas](/faction/328) (1)


* __Faction:__ [Steel Warriors](/faction/311) (1)


 **You receive:** None 

**This NPC *should* return incorrect items given.**
