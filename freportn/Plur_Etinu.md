# Plur Etinu
## Dialog

**You say:** `hail`



>**Plur Etinu says:** Your soul is welcome in our temple. The Queen of Love, Erollisi Marr, desires more to join our ranks. This city of Freeport must not stay under the control of  the Freeport Militia. I am here to [cure poison] and [cure disease], or if any [need healing].

**You say:** `cure poison`



>**Plur Etinu says:** Before the Queen of Passion can force the toxin from your system, I shall require 3 bixie stingers to perform the act.

**You say:** `cure disease`



>**Plur Etinu says:** The affliction which has been cast upon you shall be purged from your body, but first I need two portions of zombie flesh to perform the act.

**You say:** `healing`



>**Plur Etinu says:** If it is the power of the passion you require to bind your wounds, then lay down your tribute of 10 gold.
end

## Turn-Ins




if( **You turn in:** [Zombie Skin](/item/13074), [Zombie Skin](/item/13074)) then 


>**Plur Etinu says:** May the unbridled passion of Erollisi Marr flow through your body.


**Plur Etinu casts:** [Cure Disease](/spell/213) on target.

elseif( **You turn in:** [Bixie Stinger](/item/14029), [Bixie Stinger](/item/14029), [Bixie Stinger](/item/14029)) then 


>**Plur Etinu says:** May the unbridled passion of Erollisi Marr flow through your body.


**Plur Etinu casts:** [Cure Poison](/spell/203) on target.

elseif( **You turn in:** gold = 10) then


>**Plur Etinu says:** May the unbridled passion of Erollisi Marr flow through your body.


**Plur Etinu casts:** [Light Healing](/spell/17) on target.

**This NPC *should* return incorrect items given.**

end