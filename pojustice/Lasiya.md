# Lasiya



[Lasiya](/npc/201362) is a level 46 Dark Elf Magician that spawns in [Plane of Justice](/zone/201).








## Dialog

if(e.language == 23 and e.other:GetLanguageSkill(23) >= 100) then


**You say:** `Hail`




e.self:Say("" .. e.other:Race() .. "...'  She tucks her long, beautiful hair behind her ears and meets your gaze.  In her eyes you see...  desire?  'The Dark Tower always has need for new...  blood.   Come closer, little " .. e.other:Race() .. ".  Lasiya won't hurt you, not a bit.  Come and lose yourself in my arms...   I can guarantee you an eternity from which you will never wish to escape...",23);


else


>*Lasiya 'does not appear to understand you.'*
end
