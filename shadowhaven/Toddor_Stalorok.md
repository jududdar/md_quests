# Toddor Stalorok
## Dialog

**You say:** `hail`



>**Toddor Stalorok says:** Lo dere Soandso. It's nice to see you have made it to our armor shop. We got all the finest selections that could suit your taste.  If ye got any questions I'm Toddor and dis is me wife Melina.


e.self:DoAnim(66); 


if(**spawned NPC:**  [\#Melina Stalorok](/npc/150271)) then



eq.get_entity_list():GetMobByNpcTypeID( [\#Melina Stalorok](/npc/150271)):Say("Hello there!");

end
