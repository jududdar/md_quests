# Rugurt Grubdigger


## On NPC Spawn

e.self:CastToNPC():SetNoQuestPause(true);

eq.set_timer("inifish",math.random(32000));


## Dialog

**You say:** `hail`



>**Rugurt Grubdigger says:** Huh. what you want? Don' scare off da fishes. less you want me to toss you in with dem.
end



## Timer(s)

if(e.timer == "inifish") then


**Stop timer** named *inifish*


**Set a timer** named *fish* for 32 seconds


e.self:DoAnim(5);

elseif(e.timer == "fish") then


e.self:DoAnim(5);
end