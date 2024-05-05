# Tylis Newleaf



[Tylis Newleaf](/npc/203373) is a level 55 Wood Elf Warrior that spawns in [Plane of Tranquility](/zone/203).



## Dialog

local qglobals = eq.get_qglobals(e.other);


**You say:** `hail`





if ( qglobals.saryrn or qglobals.cipher ) then



**Message:** <span class="text-warning">*Tylis Newleaf tells you, 'You took on and destroyed the Mistress of Torment? Truly impressive! Now that you have found the knowledge that is the cipher, I recall that there was one that I had met once in New Tanaan. He might be able to use it properly. I believe he is now the Grand Librarian of the city.  Good luck with all that you seek friends.'*</span>






elseif ( qglobals.tylis and qglobals.tylis == "2" ) then



**Message:** <span class="text-warning">*Tylis Newleaf tells you, 'I wanted to thank you once again for your kind efforts, friend. That place had laid claim to me for far too long. So long that I have seen what Saryrn carries. I believe it to be a cipher between the language of the gods and common tongue. If it is real ultimate power that you seek, you should obtain it from her.'*</span>






else



**Message:** <span class="text-warning">*Tylis Newleaf lies on the floor still quivering in pain.  You notice the concern that Fahlia is showing for him.*</span>

end
