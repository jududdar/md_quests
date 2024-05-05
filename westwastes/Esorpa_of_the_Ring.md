# Esorpa of the Ring



[Esorpa of the Ring](/npc/120086) is a level 53 Dragon Wizard that spawns in [Western Wastes](/zone/120).



## Dialog

**You say:** `hail`



if **Faction** >= Kindly then



>**Esorpa of the Ring says:** You are truly a blight upon the planet.  Here you are in this, the most holy of lands, and you DARE speak to me as if you were some sort of equal!  We need to wipe the world clean, it  is for the children of Veeshan, no others! I do not know what the Claws are thinking, our Mother would not approve of your kind, this much I know.


elseif **Faction** >= Indifferent then



>**Esorpa of the Ring says:** You do not smell foul as I would have expected, but I still want nothing to do with you, Soandso


else



>**Esorpa of the Ring says:** The Ring of Scale shall fly forth and destroy all of you one day.  Perhaps I shall start now.


**You say:** `claws of veeshan`



if **Faction** >= Kindly then



>**Esorpa of the Ring says:** The Claws of Veeshan, the 'wise ones'  as my sire and dam refer to them.  Sent me here to 'learn' from this tired old collection of fools and dreamers.  I have been here ages, and I am still not allowed in the Temple.  What is there to learn from those that will not teach?  I cannot even get a message to the fools, I think they have forgotten I am here.


elseif **Faction** >= Indifferent then



>**Esorpa of the Ring says:** You do not smell foul as I would have expected, but I still want nothing to do with you, Soandso


else



>**Esorpa of the Ring says:** The Ring of Scale shall fly forth and destroy all of you one day.  Perhaps I shall start now.

end
