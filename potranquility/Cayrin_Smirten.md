# Cayrin Smirten
## On NPC Spawn

e.self:CastToNPC():SetNoQuestPause(true);

eq.set_timer("inifish",math.random(32000));
## Dialog

**You say:** `hail`



>**Cayrin Smirten says:** Aye, can I help you with something? I'm trying to concentrate on my fishing, so if you don't mind...
end

## Timer(s)

if(e.timer == "inifish") then


**Stop timer** named *inifish*


**Set a timer** named *fish* for 32 seconds


e.self:DoAnim(5);

elseif(e.timer == "fish") then


e.self:DoAnim(5);
end