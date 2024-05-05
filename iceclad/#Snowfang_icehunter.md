# Snowfang icehunter



[Snowfang icehunter](/npc/110007) is a level 27 Gnoll Monk that spawns in [Iceclad Ocean](/zone/110).



## On NPC Spawn

**Set a timer** named *fish* for 600 seconds


## Timer(s)

if(e.timer == "fish") then


walrus = eq.ChooseRandom("slaps its feet against the hard ice, making walrus-like sounds.","dips its club into the water and splashes it around just a little, imitating fish sounds.");


e.self:Emote(walrus);
end