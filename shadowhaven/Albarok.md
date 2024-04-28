# Albarok
## Dialog

**You say:** `hail`



>**Albarok says:** Hey there Soandso, how are ya enj...


if(**spawned NPC:**  [Skiliar Hardbrick](/npc/150023)) then



eq.get_entity_list():GetMobByNpcTypeID( [Skiliar Hardbrick](/npc/150023)):Say("Hey Albarok, I dont recall allowing you to have visitors!");

end
