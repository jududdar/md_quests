# Tylis Newleaf
local FLAG_LIMIT = 72;



## On NPC Spawn

flags = 0;

**Set a timer** named *depop* for 600 seconds


## Timer(s)

if ( e.timer == "depop" ) then


**Tylis Newleaf despawns.**
end



## Dialog

local qglobals = eq.get_qglobals(e.other);


**You say:** `hail`





if ( qglobals.tylis ) then






**Message:** <span class="text-warning">*Tylis Newleaf tells you, 'I must thank you for your kind efforts friends.  This place has laid claim to me for far too long.  Please take care and offer the dark wench my best.  I am off... and I suggest you not stray to far from that route yourselves.  Please tell me when you are ready to return and may your blades strike true!'*</span>







if ( qglobals.tylis == "1" and flags <= FLAG_LIMIT ) then




eq.set_global("tylis", "2", 5, "F");




**Message:** <span class="text-warning">*You have received a character flag!*</span>




flags = flags + 1;









if ( qglobals.cl_keeper ) then




eq.delete_global("cl_keeper");









elseif ( not qglobals.cl_keeper ) then






if ( flags <= FLAG_LIMIT ) then




**Message:** <span class="text-warning">*Tylis Newleaf tells you, 'I don't recognize you, stranger. Thank you so much for your kind efforts.  This place has claimed me for far too long.  I will leave now that I have been freed of my torment. However, before I go, please tell me when you're [ready to return] and I will send you out first.'*</span>




eq.set_global("cl_keeper", "1", 5, "F");




**Message:** <span class="text-warning">*You have received a new checklist flag!*</span>




flags = flags + 1;







**You say:** `ready to return`



**Tylis Newleaf casts:** [Torment's Beckon](/spell/1136) on target.
end
