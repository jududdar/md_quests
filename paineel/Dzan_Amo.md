# Dzan Amo
## Dialog

if **Faction** >= Apprehensive then 


**You say:** `hail`




>**Dzan Amo says:** Welcome to the Tabernacle of Terror. Perhaps you can control your fear long enough to be of [service] to us.


**You say:** `service`




>**Dzan Amo says:** I need some things fetched from the creatures just outside our city for some ritual experimentation. Bring me two tufts of bat fur and two fire beetle legs and I will school you in the ways of terror.


else


>**Dzan Amo says:** Begone from this place! Infidels like you have no place among the faithful of Cazic-Thule!

end

## Turn-Ins



local text = "I need no fewer than four infected rat livers!! Now, go get me what I require!!"; 



if( **You turn in:** [Bat Fur](/item/13069), [Bat Fur](/item/13069), [Fire Beetle Leg](/item/13250), [Fire Beetle Leg](/item/13250)) then 


>**Dzan Amo says:** Very good young one. Here is something to assist in your studies of the principles of terror.


* __Faction:__ [Heretics](/faction/265) (5)


* __Faction:__ [Deepwater Knights](/faction/242) (-5)


* __Faction:__ [Gate Callers](/faction/254) (-5)


* __Faction:__ [Craftkeepers](/faction/231) (-5)


* __Faction:__ [Crimson Hands](/faction/233) (-5)


 **You receive:**  [Spell: Spook the Dead](/item/15209) (+1000 exp)

**This NPC *should* return incorrect items given.**






