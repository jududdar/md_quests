# Elder Fuirstel
## Dialog

local qglobals = eq.get_qglobals(e.other);



**You say:** `hail`




if ( not qglobals.fuirstel or qglobals.fuirstel == "1" ) then



**Message:** <span class="text-warning">*Elder Fuirstel groans in agony.  His tainted breath surrounds your face.*</span>






elseif ( qglobals.fuirstel == "2" or qglobals.fuirstel == "3" ) then



**Message:** <span class="text-warning">*Elder Fuirstel slowly turns towards you.   You can feel the heat radiating from his face.  The warding that envelopes your body reaches out and begins to surround him. You immediately see improvement in his condition.  The pus filled sores covering his face and his burning fever start to vanish.  'Thank you friend.  I no longer feel the touch of death on my soul.  However I do feel the grasp on Bertoxxulous, his plague is still upon me but not spreading throughout my body.  I fear the only way to remove this pox would be to weaken Bertoxxulous enough that his curse would be lifted.  I now renounce my faith in Bertoxxulous, please fell this god so that I may continue and learn from my mistakes.'*</span>



if ( qglobals.fuirstel == "2" ) then




eq.set_global("fuirstel", "3", 5, "F");





**Message:** <span class="text-warning">*You have received a character flag!*</span>






elseif ( qglobals.fuirstel == "4" or qglobals.fuirstel == "5" ) then



**Message:** <span class="text-warning">*Elder Fuirstel tells you, 'Welcome back friend.  I must tell you that my brother and I shall never forget what you have done for us.  We have since renounced our following of Bertoxxulous, for in him we only found suffering.  We have joined a new following, learning from the gods without their direct influence over us.  I shall not keep you though, thank you once again!'*</span>



if ( qglobals.fuirstel == "4" ) then




eq.set_global("fuirstel", "5", 5, "F");





**Message:** <span class="text-warning">*You have received a character flag!*</span>

end
