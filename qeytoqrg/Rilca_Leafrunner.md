# Rilca Leafrunner
## On NPC Spawn

eq.set_timer("depop",math.random(1200000,3600000));
## Timer(s)

if(e.timer == "depop") then


**Rilca Leafrunner despawns.**
end

## Dialog

**You say:** `hail`



>**Rilca Leafrunner says:** Well, it seems that you have something of importance that you wish to speak to me about? No? Then perhaps you can do something [for me].

**You say:** `for you`



>**Rilca Leafrunner says:** Well I need some information. It appears that some gnolls are planning an [invasion] of Surefall. I believe there are some gnoll couriers that are running information. If you could bring me their marching orders, invasion plans, area maps, and their encryption key. Your best chance to catch a courier is probably inside Blackburrow.

**You say:** `invasion`



>**Rilca Leafrunner says:** Apparently they've heard of our plans to reopen the entrance to Jaggedpine inside Surefall. It seems they believe the think they have a chance to stop us. While most of us have little concern about a gnoll invasion force the information you provide would be of great assistance.
end

## Turn-Ins




if **You turn in:** [Marching Orders](/item/15931), [Invasion Plans](/item/15932), [Area Maps of Qeynos Hills](/item/15933), [Encryption Key](/item/15934)


>*Rilca Leafrunner takes a look at the documents you handed her and smiles, 'This is exactly what we needed. We'll be better prepared if the gnolls are foolish enough to actually attack. I hope you are willing to assist us in the defense of Surefall. Should you choose to aid us, this club will serve you well.'*


 **You receive:**  [Club of Gnoll Bashing](/item/15935) (+15000 exp)

**This NPC *should* return incorrect items given.**
