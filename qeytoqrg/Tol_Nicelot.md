# Tol Nicelot
## Dialog

**You say:** `hail`



>**Tol Nicelot says:** I have no time to waste with strangers!

**You say:** `moodoro`



>**Tol Nicelot says:** Yes, I knew Moodoro Finharn. He used to be a good friend until he started visiting Qeynos and indulging in human vices. He was executed for crimes against the state. Not even his sister Nolusia could get the charge dropped. There have been some who say he escaped execution and lives in Qeynos. That is insane babbling.

**You say:** `nolusia`



>**Tol Nicelot says:** Nolusia is a member of the Craftkeepers. She lives as a guildmaster in Erudin Palace.
end

## Arrive at Waypoint Script

if(e.wp == 1 or e.wp == 6) then


e.self:SetRunning(true);

elseif(e.wp == 4 or e.wp == 7) then


e.self:SetRunning(false);
end
