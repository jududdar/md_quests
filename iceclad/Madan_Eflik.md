# Madan Eflik



[Madan Eflik](/npc/110040) is a level 30 Gnome Rogue that spawns in [Iceclad Ocean](/zone/110).



## On NPC Spawn

**Set a timer** named *rub* for 3000 seconds


## Timer(s)

e.self:Emote(eq.ChooseRandom("rubs her arms to warm herself up. 'Did you find me something other than biscuits yet? What? No? Stay on your side of the igloo, then, Sojan!","shivers violently.  'I hate this place.  My sister always told me I shouldn't be a pirate and that you were nothing but a clockwork grease pouring imbecile!'"));

if(**spawned NPC:**  [Sojan the Sleepless](/npc/110066)) then


eq.get_entity_list():GetMobByNpcTypeID( [Sojan the Sleepless](/npc/110066)):Emote("sighs and stares at the ground solemnly"); 
end
