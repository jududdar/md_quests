# Miner Perrin



[Miner Perrin](/npc/153063) is a level 30 Dwarf Warrior that spawns in [Echo Caverns](/zone/153).



## Dialog

**You say:** `hail`



>**Miner Perrin says:** You know I think they set us goals they know we can't meet just so we'd work harder.


if(**spawned NPC:**  [Crew Chief Grinn](/npc/153070)) then



eq.get_entity_list():GetMobByNpcTypeID( [Crew Chief Grinn](/npc/153070)):Say("What's that Perrin?  Need more work do ye?");

end
