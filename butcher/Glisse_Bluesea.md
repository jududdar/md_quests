# Glisse Bluesea


## On NPC Spawn



eq.spawn_condition("butcher",3,1);

eq.spawn_condition("butcher",4,1);

eq.spawn_condition("butcher",5,1);

eq.spawn_condition("butcher",6,1);


## Signals

if(e.signal == 1) then


**Glisse Bluesea shouts:** <span class="text-danger">The Maiden's Voyage has departed the outpost at Firiona Vie. Please be ready to board the shuttles shortly, if you desire to make the journey to Kunark.</span>


if(e.signal == 2) then


**Glisse Bluesea shouts:** <span class="text-danger">The Maiden's Voyage is now ready to be boarded. Please form an orderly line to the shuttles, and remember, no pushing!</span>


**Signaled to:**  [Shuttle I](/npc/846)


**Signaled to:**  [Shuttle II](/npc/847)


**Signaled to:**  [Shuttle III](/npc/848)


**Signaled to:**  [Shuttle IV](/npc/849)
end