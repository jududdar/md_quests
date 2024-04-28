# Emmerik Skyfury
## Combat

if  Emmerik Skyfury enters combat  then


**Zone Wide Emote:** <span class="text-warning">*Emmerik gestures toward the sky calling meteors to his aid.*</span>


**Set a timer** named *portals* for 120 seconds

else


**Stop timer** named *portals*
end

## On NPC Death

**Spawn NPC:**  [\#\#Askr the Lost](/npc/209157) at (**y:** -1733, **x:** -1065)

**Despawn all instances of:**  [\#Askr the Lost](/npc/209156)
## Timer(s)

if ( e.timer == "portals" ) then


**Zone Wide Emote:** <span class="text-warning">*Emmerik raises his arm high above his head.  Great bolts of energy surge through him and strike the portals.*</span>


**Signaled to:**  [A celestial portal](/npc/209102)





if ( e.self:GetHPRatio() < 25 ) then



**Set a timer** named *portals* for 60 seconds






elseif ( e.self:GetHPRatio() < 50 ) then



**Set a timer** named *portals* for 90 seconds

end
