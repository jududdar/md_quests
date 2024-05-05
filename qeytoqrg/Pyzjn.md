# Pyzjn



[Pyzjn](/npc/4015) is a level 13 Gnome Necromancer that spawns in [Qeynos Hills](/zone/4).

local despawntime;



## On NPC Spawn

if(e.self:GetSpawnPointID() == 365105 or e.self:GetSpawnPointID() == 365106) then


despawntime = 0;


**Set a timer** named *depop* for 8640 seconds
end



## Timer(s)

if(e.timer == "depop") then


**Stop timer** named *depop*


despawntime = 1;
end



## Arrive at Waypoint Script

local ZoneTime = eq.get_zone_time()["zone_hour"];

if(e.self:GetGrid() == 26 and despawntime == 1) then


if(e.wp == 0 and ZoneTime > 7 and ZoneTime < 20) then



despawntime = 0;



**Pyzjn despawns.**

end



## Dialog

**You say:** `hail`



if **Faction** >= Apprehensive then



>**Pyzjn says:** Hail, Soandso.  Pyzjn is working for Master Varsoon.  If Pyzjn do good work maybe Master Varsoon tell Master Bruax he is worthy.  Pyzjn must go now.  All glory to the Plaguebringer!  May you die a painful, oozing death.


else



**Pyzjn says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

>Oh look, a talking lump of refuse.  How novel!

end

