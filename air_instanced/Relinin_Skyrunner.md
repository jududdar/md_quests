# Relinin Skyrunner
## On NPC Spawn

**Set a timer** named *depop* for 300 seconds
## Dialog

**You say:** `hail`



>**Relinin Skyrunner says:** Greetings Soandso. I can only assume my reasons for being summoned is that you wish to take the tests. Would you like to be tested in the body, in defense, or in the element of earth?

**You say:** `body`



>**Relinin Skyrunner says:** Very well. You must scour this plane and bring back to me these components: an auburn tessera, a ysgaril root, and a griffon talon. Make haste, and good luck.

**You say:** `defense`



>**Relinin Skyrunner says:** Defense it is. You must prove yourself worthy enough for the Spiroc spirits to guard you. Bring back to me a mithril disc, a harpy tongue, and a fine velvet cloak. Good luck to you Soandso.

**You say:** `element of earth`



>**Relinin Skyrunner says:** Elemental earth you say? When honed, the elements can be among our best allies. Retrieve a gridelin globe, a dragon hide mantle, and a spiroc earth totem. Only with these items can you master the element of earth.
end

## Turn-Ins



if( **You turn in:** [Auburn Tessera](/item/20934), [Griffon Talon](/item/20850), [Ysgaril Root](/item/20849)) then 


>**Relinin Skyrunner says:** Good work, ranger.


 **You receive:**  [Griffon Talon Necklace](/item/14567) (+100000 exp)


**Relinin Skyrunner despawns.**

elseif( **You turn in:** [Fine Velvet Cloak](/item/20853), [Harpy Tongue](/item/20852), [Mithril Disc](/item/20851)) then 


>**Relinin Skyrunner says:** You should find this cloak useful.


 **You receive:**  [Dark Cloak of the Sky](/item/27731) (+100000 exp)


**Relinin Skyrunner despawns.**

elseif( **You turn in:** [Dragon-hide Mantle](/item/20854), [Gridelin Globe](/item/20948), [Spiroc Earth totem](/item/20855)) then 


>**Relinin Skyrunner says:** The mantle I give you to wear houses a powerful enchantment. Use it with care.


 **You receive:**  [Earthshaker's Mantle](/item/2714) (+100000 exp)


**Relinin Skyrunner despawns.**

**This NPC *should* return incorrect items given.**

## Timer(s)

**Stop timer** named *depop*

**Relinin Skyrunner despawns.**




