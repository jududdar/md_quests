# Master Vhezar



[Master Vhezar](/npc/201378) is a level 46 Iksar Monk that spawns in [Plane of Justice](/zone/201).








## Dialog

if(e.language == 18 and e.other:GetLanguageSkill(18) >= 100) then


**You say:** `Hail`




e.self:Say("Hail.'  He holds your gaze.  'Peace be with you, Soandso.  You appear unrestful, this is good.  Unrest makes one attentive.  Focused.  Alert.  You will need the sum total of your wits at your command if you are to not fall to the [forces] at work in this place of imprisonment.",18);


**You say:** `forces`




e.self:Say("There are many.  The representatives of True Justice hold sway here, and the task of dispensing judgments falls upon them.  I have heard that the Warden...'  He looks out to see if he is being overheard.  'I have heard that the Warden has his own thoughts on justice, however.  Then, there are we [prisoners].",18);


**You say:** `prisoners`




e.self:Say("From those with whom I have talked, it seems that we have little in common save that we have all been accused of the most serious of crimes.  The definition of serious seems to vary according to the background of the prisoner, though.  I overheard a conversation of a dwarf claiming that she was sent here for overcharging on goods that she sold, for example.'  He shakes his head and looks resigned to a long fate.  I have [faith].",18);


**You say:** `faith`




e.self:Say("As a Grandmaster, my life is one of pure worship.  In the worship of the Great Fearsome, so I go about my days.  My faith shall not let me down, of this I have no doubt.  Even in the face of great accusation, I shall remain true to the one, real god.'  He adjusts his wristband and glances at you from the corner of one eye.  'That god is Cazic-Thule, mark you, " .. e.other:Race() .. ".",18);


else


>*Master Vhezar 'does not appear to understand you.'*
end
