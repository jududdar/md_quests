# Fahlia Shadyglade



[Fahlia Shadyglade](/npc/203372) is a level 55 Half Elf Warrior that spawns in [Plane of Tranquility](/zone/203).

local REFUSE_TXT = "Fahlia Shadyglade tells you, 'I can see that you may be passionate to help others but now I must ask you to be about your own business. I sense that if you were to try to help you may befall the same fate as poor Tylis.  Perhaps you should become more experienced in traveling through the planes before you learn more of his condition.'";



## Dialog

local qglobals = eq.get_qglobals(e.other);



**You say:** `hail`



if ( qglobals.tylis and qglobals.tylis == "2" ) then



**Message:** <span class="text-warning">*Fahlia Shadyglade tells you, 'This is wonderful! I am so happy that you could help to free Tylis from Saryrn's grasp!  Please try not to bother him too much. He will need time to recover.'*</span>


else



**Message:** <span class="text-warning">*Fahlia Shadyglade tells you, 'Greetings travelers. Please excuse me but I must attend to Tylis for his condition does not improve.'*</span>





**You say:** `condition`





if ( (qglobals.thelin and qglobals.thelin == "4") and (not qglobals.fuirstel or qglobals.fuirstel ~= "5") ) then



**Message:** <span class="text-warning">*Fahlia Shadyglade tells you, 'I understand that you are passionate to our cause, I have heard that you have recovered Thelin's sanity. You may be powerful enough to enter into the domain of Saryrn, but before I can ask you to help Tylis perhaps you should help one that is in more dire need. Go talk to Adler Fuirstel. His brother has fallen under the curse of a god just like Thelin.'*</span>


elseif ( qglobals.thelin and qglobals.thelin == "4" and qglobals.fuirstel and qglobals.fuirstel == "5" ) then



**Message:** <span class="text-warning">*Fahlia Shadyglade tells you, 'It all goes back to when I found him. I had just purchased a new fishing pole in the hopes of finding some time to relax on the shores of the island. As I was walking out of the shop, I heard a distant moan. I walked toward the source and found Tylis lying by the reflecting pool. The pool was different, though. It now had a small [black cube] floating over it. I tried to wake Tylis but was not successful. I then brought him here and have been caring for him since.'*</span>


else



e.other:Message(0, REFUSE_TXT);





**You say:** `black cube`





if ( qglobals.thelin and qglobals.thelin == "4" and qglobals.fuirstel and qglobals.fuirstel == "5" ) then



**Message:** <span class="text-warning">*Fahlia Shadyglade tells you, 'I do not like that cube at all. Just thinking of it brings pain to my mind. Gazing upon it gives the sensation of being slowly rent apart at each limb. I believe that whatever has fallen over Tylis is related to this cursed cube. Other elders claim that it is a portal that will lead into the [Plane of Torment].'*</span>


else



e.other:Message(0, REFUSE_TXT);





**You say:** `plane of torment`





if ( qglobals.thelin and qglobals.thelin == "4" and qglobals.fuirstel and qglobals.fuirstel == "5" ) then



**Message:** <span class="text-warning">*Fahlia Shadyglade tells you, 'It is not a plane that was originally sought to be reached by our elders. It is their belief though that Saryrn, the Mistress of Torment, intends to breed her suffering even into this protected plane of Quellious. I wish I had the strength to go into the Plane of Torment and find out exactly the nature of the current circumstances to have afflicted Tylis, but I cannot leave his side in good conscience.'*</span>


else



e.other:Message(0, REFUSE_TXT);





**You say:** `will go`





if ( qglobals.thelin and qglobals.thelin == "4" and qglobals.fuirstel and qglobals.fuirstel == "5" ) then



**Message:** <span class="text-warning">*Fahlia Shadyglade tells you, 'Wonderful. I did not think that an outsider was one that I could trust to aid me in this. One name that Tylis has mentioned in agony is that of Maareq. I do not know whom this is, but he must be instrumental in Tylis' suffering. You must find Maareq and do what you must to release Tylis from this torture.'*</span>



if ( not qglobals.tylis ) then




eq.set_global("tylis", "1", 5, "F");





**Message:** <span class="text-warning">*You have received a character flag!*</span>


else



e.other:Message(0, REFUSE_TXT);

end
