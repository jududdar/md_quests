# Megan OReilly
## Dialog

**You say:** `hail`



>**Megan OReilly says:** Brrrr.. It.. Is sooo.. c-cold!! I never.. sh-should've j-joined.. the.. the W-wolves of the N-north!!

**You say:** `ivan's remains`



if( **Faction is** > Indifferent) then 



>**Megan OReilly says:** You were sent to retrieve the remains? I am sorry, I lost them. It was not my fault! There was no escort as I was told. I got lost returning to Halas and ended up on a frozen river. The ice broke and the remains were scattered into the freezing water. Will you [dive for the remains]?


elseif( **Faction is** == Indifferent) then



>**Megan OReilly says:** The Wolves o' the North show ye no ill will, but there's much ye must do t' earn our trust.  Perhaps ye should speak with Lysbith and inquire o' the [gnoll bounty].


elseif( **Faction is** < Indifferent) then



>**Megan OReilly says:** Run while ye still can!! The Wolves o' the North will not tolerate yer presence!



**You say:** `dive for the remains`



if( **Faction is** > Indifferent) then 



>**Megan OReilly says:** Thank the Tribunal!! I would have, but I cannot swim. Take this chest. Fill it with the four pieces which fell below the surface. I know not what else lies within. When you fill the box and combine the items, return it to Renth. Good luck, Soandso.



**You receive:**  [Empty Box](/item/17945)


elseif( **Faction is** == Indifferent) then



>**Megan OReilly says:** The Wolves o' the North show ye no ill will, but there's much ye must do t' earn our trust.  Perhaps ye should speak with Lysbith and inquire o' the [gnoll bounty].


elseif( **Faction is** < Indifferent) then



>**Megan OReilly says:** Run while ye still can!! The Wolves o' the North will not tolerate yer presence!



end

## Turn-Ins




if( **Faction is** > Indifferent and  **You turn in:** [One Quarter of Elixir](/item/13244)) then 


>**Megan OReilly says:** Oh thank you. Sorry, but the bottle is empty now. I hope you did't need any. Take the empty bottle back to Dargon. He may refill it for you.





* __Faction:__ [Wolves of the North](/faction/320) (5)


* __Faction:__ [Shamen of Justice](/faction/327) (1)


* __Faction:__ [Merchants of Halas](/faction/328) (1)


* __Faction:__ [Steel Warriors](/faction/311) (1)


 **You receive:**  [Empty Bottle of Elixir](/item/13245) (+150 exp)

**This NPC *should* return incorrect items given.**
;
## Arrive at Waypoint Script

if(e.wp == 3) then


e.self:SetRunning(true);

elseif(e.wp == 6) then


e.self:SetRunning(false);
end


