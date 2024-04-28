# Arnis McLish
## Dialog

**You say:** `hail`



>**Arnis McLish says:** My word!! I cannot believe how cold it is out here. I must keep running around just to keep warm.

**You say:** `megan`



if( **Faction is** > Indifferent) then



>**Arnis McLish says:** I heard she got lost on the plains. You should go ask her dog, Snowflake, where she is. I hear she is somewhere around the pass to Halas.


elseif( **Faction is** == Indifferent) then



>**Arnis McLish says:** The Wolves o' the North show ye no ill will, but there's much ye must do t' earn our trust.  Perhaps ye should speak with Lysbith and inquire o' the [gnoll bounty].


else



>**Arnis McLish says:** Run while ye still can!! The Wolves o' the North will not tolerate yer presence!

end

## Turn-Ins




if( **Faction is** > Indifferent and  **You turn in:** [One Half of Elixir](/item/13243)


>**Arnis McLish says:** Mmmm.. Thank you stranger. I feel a lot warmer now. You should now go and find [Megan] O'Reilly.





* __Faction:__ [Wolves of the North](/faction/320) (5)


* __Faction:__ [Shamen of Justice](/faction/327) (1)


* __Faction:__ [Merchants of Halas](/faction/328) (1)


* __Faction:__ [Steel Warriors](/faction/311) (1)


 **You receive:**  [One Quarter of Elixir](/item/13244) (+150 exp)

**This NPC *should* return incorrect items given.**
;
## On NPC Spawn

e.self:SetRunning(true);

