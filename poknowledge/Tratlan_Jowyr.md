# Tratlan Jowyr

## Dialog

**You say:** `Hail`



>*Tratlan Jowyr looks deeply into the pool in front of him, 'Well darn it! I still can't see anything in this blasted [pool], can you Wicas?*





if(**spawned NPC:**  [Wicas Adaolath](/npc/202301)) then



eq.get_entity_list():GetMobByNpcTypeID( [Wicas Adaolath](/npc/202301)):Say("Nothing at all. Do you think that he led us astray?"); 


**You say:** `pool`



>*Tratlan Jowyr glances up at you like he just noticed your presence, 'This pool. There is supposed to be strong [magic] in it.'*

**You say:** `magic`



>**Tratlan Jowyr says:** Scrying magic. These pools can supposedly glance into all of the knowledge past, present, and future.





if(**spawned NPC:**  [Wicas Adaolath](/npc/202301)) then



eq.get_entity_list():GetMobByNpcTypeID( [Wicas Adaolath](/npc/202301)):Say("I think we should just do what [Tarerd] wants us to do."); 


**You say:** `tarerd`



if(**spawned NPC:**  [Wicas Adaolath](/npc/202301)) then



eq.get_entity_list():GetMobByNpcTypeID( [Wicas Adaolath](/npc/202301)):Say("Tarerd is the one who told us about these pools. He wanted us to kill some sort of lizards for him, but we have neither the time nor energy for such adventures. Perhaps you can get some information about the pools from him.");

end

## Turn-Ins



if **You turn in:** [The Reflecting Pools of Tanaan](/item/15960)


>*Tratlan Jowyr leafs quickly through the book. 'Thank you, it will take quite some time to go through all the information here. Here is a little something for your troubles.'*





 **You receive:** None 

**This NPC *should* return incorrect items given.**
