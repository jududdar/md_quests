# Ruru the Cook
## Dialog

**You say:** `hail`



>**Ruru the Cook says:** A stranger? Hmm. Well since you are new to these parts, I will introduce myself. I am Ruru, I do the cooking around here. Best cook in all the lands I would say.


if(**spawned NPC:**  [Grudash the Baker](/npc/114467)) then



eq.get_entity_list():GetMobByNpcTypeID( [Grudash the Baker](/npc/114467)):Emote("laughs, 'I'm sure they'd prefer my Boysenberry pie to your Roasted Walrus with Plum Sauce any day.'");



>*Ruru the Cook laughs, 'Don't get me started. You know that my cuisine Is prefered over yours two to one.'*


elseif(**spawned NPC:**  [\#Grudash the Baker](/npc/114639)) then



eq.get_entity_list():GetMobByNpcTypeID( [\#Grudash the Baker](/npc/114639)):Emote("laughs, 'I'm sure they'd prefer my Boysenberry pie to your Roasted Walrus with Plum Sauce any day.'");



>*Ruru the Cook laughs, 'Don't get me started. You know that my cuisine Is prefered over yours two to one.'*

end
