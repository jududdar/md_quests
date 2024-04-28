# Jyle Windshot
## Dialog

local fac = e.other:GetFaction(e.self);



**You say:** `hail`



>**Jyle Windshot says:** Hello. Might I ask what you are looking for?

**You say:** `treant wood`



if(fac < 6) then



>**Jyle Windshot says:** You are a new courier from the Faydarks. I am sorry I did not stay closer to the docks. I hear that part of Freeport is dangerous and is filled with many rogues. I shall require a new Small Lantern in trade for the Treant Wood.


else



>**Jyle Windshot says:** Your ways are considered vile to Faydark's Champions. Leave before my rage overcomes my restraint.

end

## Turn-Ins




if **You turn in:** [Small Lantern](/item/13003)


>**Jyle Windshot says:** Thanks, friend. I have run a long way to get here in time. Mostly at night. I lost my lantern in a card game in Highkeep.


* __Faction:__ [Faydarks Champions](/faction/246) (1)


* __Faction:__ [King Tearis Thex](/faction/279) (1)


* __Faction:__ [Clerics of Tunare](/faction/226) (1)


* __Faction:__ [Soldiers of Tunare](/faction/310) (1)


* __Faction:__ [Crushbone Orcs](/faction/234) (-1)


 **You receive:** eq.ChooseRandom( [Wooden Shards](/item/13824),  [Wooden Shards](/item/13824),  [Wooden Shards](/item/13824),  [Wooden Shards](/item/13824),  [Wooden Shards](/item/13824),  [Wooden Shards](/item/13824),  [Wooden Shards](/item/13824),  [Wooden Shards](/item/13824),  [Wooden Shards](/item/13824), 12334) (+50 exp)

**This NPC *should* return incorrect items given.**


