# Evynd Firestorm
## Combat

if  Evynd Firestorm enters combat  then


**Zone Wide Emote:** <span class="text-warning">*Evynd Firestorm says 'I will see that my flames consume you.'*</span>


**Set a timer** named *portals* for 120 seconds

else


**Stop timer** named *portals*
end

## On NPC Death

**Spawn NPC:**  [\#Askr the Lost](/npc/209156) at (**y:** -1732, **x:** -1123)
## Timer(s)

if ( e.timer == "portals" ) then


**Zone Wide Emote:** <span class="text-warning">*Evynd waves his hands in the air, calling the power of the firestorm through the blazing portals.*</span>


**Signaled to:**  [A firestorm portal](/npc/209122)
end
