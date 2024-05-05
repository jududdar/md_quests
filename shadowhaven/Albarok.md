# Albarok



[Albarok](/npc/150045) is a level 55 Dwarf Warrior that spawns in [Shadow Haven](/zone/150).



## Dialog

**You say:** `hail`



>**Albarok says:** Hey there Soandso, how are ya enj...


if(**spawned NPC:**  [Skiliar Hardbrick](/npc/150023)) then



eq.get_entity_list():GetMobByNpcTypeID( [Skiliar Hardbrick](/npc/150023)):Say("Hey Albarok, I dont recall allowing you to have visitors!");

end
