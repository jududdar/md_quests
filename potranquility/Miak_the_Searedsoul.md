# Miak the Searedsoul


## Dialog

local qglobals = eq.get_qglobals(e.other);



**You say:** `hail`



if ( qglobals.pofire and qglobals.pofire == "2" ) then



>**Miak the Searedsoul says:** Greetings again. I sense that you have the correct path for the portal to the Plane of Fire. If you simply touch the portal, I will channel it to open to the location in your mind.


else



>**Miak the Searedsoul says:** Greetings traveler.  I am Miak, guardian of the portal to the greater elemental [Plane of Fire.]





**You say:** `plane of fire`



if ( qglobals.pofire and qglobals.pofire == "2" ) then



**Message:** <span class="text-warning">*Miak the Searedsoul smiles oddly at you, 'I will not say that the Plane of Fire is safe, but entering it will no longer mean your immediate demise... well it may not.'*</span>


else



>**Miak the Searedsoul says:** The Plane of Fire is no place for a mortal to go frolicking about.  Regardless, to use the portal now would surely mean [your demise.]





**You say:** `demise`



if ( qglobals.pofire and qglobals.pofire == "2" ) then



>**Miak the Searedsoul says:** You are the one that discovered the portal's destination.  All you need to do is concentrate on the correct path, the rest will be done by the foci and myself.


else



>**Miak the Searedsoul says:** Yes, theof your mortal existence.  Recently the portal seems to have lost its direction.  The location the portal sends you to is not safe; the [portal's destination] seems to have moved somehow.





**You say:** `portal's destination`



if ( qglobals.pofire and qglobals.pofire == "2" ) then



>**Miak the Searedsoul says:** You are the one that discovered the portal's destination.  All you need to do is concentrate on the correct path, the rest will be done by the foci and myself.


else



>**Miak the Searedsoul says:** I do not know if I will ever be able to correct the portal's destination, but if you have the true route for the portal in your mind I will be able to channel the portal to the correct location.



if ( not qglobals.pofire ) then




eq.set_global("pofire", "1", 5, "F");





**Message:** <span class="text-warning">*You have received a character flag!*</span>

end
