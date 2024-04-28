# Nivold Predd
## Dialog

**You say:** `hail`



if **Faction** >= Amiable then



>**Nivold Predd says:** What do you want? Do not disturb me lest you plan to assist in my [summoning of Dread].


elseif **Faction** >= Indifferent then



>**Nivold Predd says:** I sense the potential to learn the ways of fear within you. Continue striving to master your fear and one day perhaps you can be of service to our Lord Cazic-Thule.




else



>**Nivold Predd says:** Begone from this place! Infidels like you have no place among the faithful of Cazic-Thule!





**You say:** `summoning of dread`



if **Faction** >= Amiable then



>**Nivold Predd says:** There are some components essential to the summoning of the avatar of Dread. I require the eye of a griffon. some [powder of reanimation]. the brain of the Ishva Mal. and the toes of an ice giant. Fetch me these reagents so that we may summon the avatar to forge a shield worn only by the mightiest apostles of Cazic-Thule.


elseif **Faction** >= Indifferent then



>**Nivold Predd says:** I sense the potential to learn the ways of fear within you. Continue striving to master your fear and one day perhaps you can be of service to our Lord Cazic-Thule.




else



>**Nivold Predd says:** Begone from this place! Infidels like you have no place among the faithful of Cazic-Thule!





**You say:** `powder of reanimation`



if **Faction** >= Amiable then



>**Nivold Predd says:** There is a gnome necromancer who has been experimenting with a powder used in reanimating long dead organic tissue. He is known to frequent places populated by undead in order to pursue his research. Seek him out and procure a bit of his powder.


elseif **Faction** >= Indifferent then



>**Nivold Predd says:** I sense the potential to learn the ways of fear within you. Continue striving to master your fear and one day perhaps you can be of service to our Lord Cazic-Thule.




else



>**Nivold Predd says:** Begone from this place! Infidels like you have no place among the faithful of Cazic-Thule!




end

## Turn-Ins



local text = "I require all four reagents, anything less is useless. Incompetence will get you nowhere amongst the faithful of Cazic-Thule!";



if **Faction** >= Amiable and  **You turn in:** [Ice Giant Toes](/item/16540), [Griffon Eye](/item/13739), [Brain of the Ishva Mal](/item/14111), [Powder of Reanimation](/item/14112)


>**Nivold Predd says:** Commendable work, you have proven yourself a valuable member of our order. Our chanters have summoned the avatar of Dread. Hurry and take him this mundane shield so that he may forge it into a truly valuable symbol of your devotion to the lord of Fear!


* __Faction:__ [Heretics](/faction/265) (400)


* __Faction:__ [Deepwater Knights](/faction/242) (-400)


* __Faction:__ [Gate Callers](/faction/254) (-400)


* __Faction:__ [Craftkeepers](/faction/231) (-400)


* __Faction:__ [Crimson Hands](/faction/233) (-400)


 **You receive:** None 


**Spawn NPC:**  [avatar of dread](/npc/75194) at (**y:** 1230, **x:** 474)

**This NPC *should* return incorrect items given.**
;

