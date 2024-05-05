# Adler Fuirstel



[Adler Fuirstel](/npc/203394) is a level 46 Human Warrior that spawns in [Plane of Tranquility](/zone/203).



## Dialog

local qglobals = eq.get_qglobals(e.other);



**You say:** `hail`





if ( not qglobals.fuirstel or qglobals.fuirstel == "1" ) then



**Message:** <span class="text-warning">*Adler Fuirstel tells you, 'Can you smell it?   It is the musk of death and pestilence.  It is a smell that I have welcomed for so long, but now it turns my stomach.  My brother Milyk and I have come here from Qeynos.  We were members of the Bloodsabers but sought higher enlightenment.  Upon arriving here Milyk began to channel all of his energy into opening the portal to the Plane of Disease.'*</span>






elseif ( qglobals.fuirstel == "2" ) then



**Message:** <span class="text-warning">*Adler Fuirstel tells you, 'Please you must hurry!  Take the ward that surrounds you back to my brother and lift the sickness that has come over him!'*</span>






elseif ( qglobals.fuirstel == "3" ) then



**Message:** <span class="text-warning">*Adler Fuirstel tells you, 'Did you learn how to get into Bertoxxulous lair when you retrieved the ward?  In my brothers vision he spoke of a huge metal pipe, that would only be affected by one that carries the knowledge of what lies behind it.  Go now into disease and move the rotted pipe that is behind Grummus.  There you will find the Lord of Pestilience.  I beg of you for the mercy of my brother, and myself, weaken Bertoxxulous to a point that his curse on us can be lifted.'*</span>






elseif ( qglobals.fuirstel == "4" or qglobals.fuirstel == "5" ) then



**Message:** <span class="text-warning">*Adler Fuirstel tells you, 'Your service to me and my brother will never be forgotten.  We are concentrating on how to close this portal now.  The Lord of Pestilience has made it abundantly clear that he cares not for his followers.  Thank you again, and good luck to you in your travels.'*</span>





**You say:** `plane of disease`



**Message:** <span class="text-warning">*Adler Fuirstel tells you, 'We sought only the wisdom of Bertoxxulous.  When Milyk finished his chant and the portal opened, it began to spew out this vile pestilence you see before you.  Milyk caught the brunt of the plague, and his condition worsens.  I have been infected as well, and am weak but I will go into the plane to save my brother if I must.  The weavers have seen in their tapestries that one holds a ward that will halt the effects of the toxins that the touch of Bertoxxulous brings.'*</span>





**You say:** `ward`



**Message:** <span class="text-warning">*Adler Fuirstel tells you, 'The ward is carried by the one that Bertoxxulous has created to protect the entrance into his den.  If you dare travel into this pungent plane and find the ward bring it back.  If we can halt the advancing toxins in Milyk's system maybe we can save him.'*</span>


if ( not qglobals.fuirstel ) then



eq.set_global("fuirstel", "1", 5, "F");



**Message:** <span class="text-warning">*You have received a character flag!*</span>

