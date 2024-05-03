# Elder Poxbourne


## Dialog

local qglobals = eq.get_qglobals(e.other);

local thelinFlag = tonumber(qglobals.thelin) or 0;


**You say:** `hail`



if ( thelinFlag >= 3 ) then



**Message:** <span class="text-warning">*Thelin tells you, 'I apologize but I cannot stand to greet you. I am still quite weak and recovery will be a long and painful road, though it is a most welcome venture. I want you to know how much I appreciate your bravery in helping me. I am forever in your debt.'*</span>



if ( thelinFlag == 3 ) then




eq.set_global("thelin", "4", 5, "F");





**Message:** <span class="text-warning">*You receive a character flag!*</span>


else



**Message:** <span class="text-warning">*Adroha gives a soft sigh of woe, 'You won't be getting any response from Thelin.  Ever since his injury he has been in a deep [coma] with no sign of ever recovering.'*</span>



**Message:** <span class="text-warning">*Thelin tosses and turns violently on the floor, then is still.*</span>

end
