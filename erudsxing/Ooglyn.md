# Ooglyn
## Dialog

**You say:** `hail`



>**Ooglyn says:** Ooooh, it you, Soandso. Me's been waitin for you cuz our frenz say you comin an need da test. So's I gib you da test. Hmm, now where me put it? Ooglyn been waiting for sign for so long dat me forget where me put test. Keep your eyes out for sign while me look for test. Oh, hey, Soandso, they gib you gem? I need dat gem, please, heheh.
end

## Turn-Ins




if **Faction** >= Indifferent and  **You turn in:** [Opaque Gem](/item/1666)) then 


>**Ooglyn says:** Ahhh, tank you, now me can...OH LOOK!! DA SIGN!!!! Oh, sorry you missed it. The sign show you where to wait for da test. Follow me...I like you so I take you there. We goin for a swim, Soandso!


* __Faction:__ [Truespirit](/faction/404) (100)


 **You receive:** 0 (+1000 exp)


>**Ooglyn says:** Ok shaman, let us be off.


eq.start(4);

**This NPC *should* return incorrect items given.**
;
## Arrive at Waypoint Script

if(e.wp == 17) then


>**Ooglyn says:** Ok, here is place for you to for waiting. Hab fun shaman!


**Set a timer** named *depop* for 60 seconds
end

## Timer(s)

**Spawn NPC:**  [Srafen the Soaked](/npc/98046) at (**y:** -1586, **x:** 4196)

**Ooglyn despawns.**

