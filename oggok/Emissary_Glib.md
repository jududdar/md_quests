# Emissary Glib
## On NPC Spawn

**Set a timer** named *depop* for 300 seconds
## Dialog

**You say:** `hail`



>**Emissary Glib says:** Gloop.. Are you the one? Who sent you?

**You say:** `marda`



>**Emissary Glib says:** <Gloop>.. Good. I am the secret emissary of the frogloks of Guk. I have come to help your community, provided, that is, that you help mine. Gloop.. I want you to track down and kill the troll hunters called 'slayers.' They are capturing our foragers in the swamps. Return their slayer necklaces to me and I shall pay you, but most important, find the slayer captain. Bring me his captain's necklace and I shall give you a secret. I must leave soon. If you need me, just ask Marda where I am.
end

## Turn-Ins



if( **You turn in:** [Frog Eye Necklace](/item/13369)) then


>**Emissary Glib says:** Good work. That is one less troll slayer. My people shall learn of your good deed. Please search for the slayer captain. He must be stopped.


* __Faction:__ [Oggok Citizen](/faction/143) (1)


 **You receive:** 0 (+500 exp)

elseif( **You turn in:** [Frog Eye Necklace](/item/13370)) then


>**Emissary Glib says:** 'Oooh!! .. You have dispatched the slayer captain. It will take them time to reorganize the slayers. During this time the froglok foragers can gather more provisions for Guk. Please take this as a token of my people's appreciation. Your standing with my brethren has grown. As for Marda's information.. within Grobb lies my aide, Groak. He was captured. Tell him Glib sent you.


* __Faction:__ [Oggok Citizen](/faction/143) (2)


 **You receive:** eq.ChooseRandom( [Forager Bag](/item/17928), [Hopper Spear](/item/13371)) (+500 exp)

**This NPC *should* return incorrect items given.**

## Timer(s)

**Emissary Glib despawns.**




