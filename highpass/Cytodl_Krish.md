# Cytodl Krish



[Cytodl Krish](/npc/5005) is a level 25 Dark Elf Shadow Knight that spawns in [Highpass Hold](/zone/5).



## Dialog



**You say:** `hail`



>**Cytodl Krish says:** What do you want? I have no reason to waste my time with the likes of you!

**You say:** `where`



>**Cytodl Krish says:** There have been reports of murders within Highpass, murders in which the victims were drained of every iota of blood. I was sent here by my [guild master] to investigate.

**You say:** `guild master`



if( **Faction is** >= Amiable) then 



>**Cytodl Krish says:** I was sent here by Noxhil V'Sek of the Dead. We are the necromancers and shadowknights of Neriak.


elseif( **Faction is** == Indifferent) then



>**Cytodl Krish says:** When you learn to serve the Dead, then I will find the time to speak of such things.


else



>**Cytodl Krish says:** How dare you enter my presence?!  In the name of the Dead I should strike you down!


end



## On NPC Spawn

**Set a timer** named *timecheck* for 60 seconds


## Timer(s)

if ( e.timer == "timecheck" and not e.self:IsEngaged() ) then




local zoneTime = eq.get_zone_time()["zone_hour"];



if ( zoneTime > 18 or zoneTime < 8 ) then



**Cytodl Krish despawns.**

end



## On NPC Death

**Spawn NPC from spawn group:** [Cytodl Krish](/npc/336269) after 1200 second(s)