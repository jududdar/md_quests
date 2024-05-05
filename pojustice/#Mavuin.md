# Mavuin



[Mavuin](/npc/201081) is a level 60 High Elf Enchanter that spawns in [Plane of Justice](/zone/201).



## Dialog

local qglobals = eq.get_qglobals(e.self, e.other);

local mavuinFlag = tonumber(qglobals["mavuin"]) or 0;



**You say:** `hail`





if ( mavuinFlag >= 2 ) then



**Message:** <span class="text-warning">*Mavuin tells you, 'So you have pleaded my case to the Tribunal, I am most thankful.  I hope that they will listen to my case soon and release me.  The knowledge that I promised you is this.  The followers in the Plane of Tranquility are trying to find information on what has happened to Zebuxoruk.  What I know is that he has been captured for a second time.  If you want to find out more information I believe you should seek an audience with Karana and Mithaniel Marr.  I can only assume that they were present at the time of his capture and know why this has taken place.  Also seek from Marr a way to translate the divine language.  Only with it can you understand the writing of the gods.  There is no more that I can tell you, but thank you once again for your attempt in returning my freedom.'*</span>



if ( mavuinFlag == 2 ) then




eq.set_global("mavuin", "3", 5, "F");





**Message:** <span class="text-warning">*You have received a character flag!*</span>






elseif ( mavuinFlag == 0 ) then



**Message:** <span class="text-warning">*Mavuin strains his eyes to look up at you in disbelief, then reaches down into a rusted vent and pulls out a journal.  'Please I implore you, take word to the Tribunal.  I have done nothing wrong, yet I have been sentenced to eternity in this cell.  I wish to present all of the [information] about my case to them.  They must listen to my plea if they are truly the gods of justice.'*</span>






elseif ( mavuinFlag == 1 ) then



**Message:** <span class="text-warning">*Mavuin tells you, 'Please it is the only hope that I live for.  Deliever me from this horrid fate.  Take word of my desire to plead my case before the Tribunal!'*</span>






**You say:** `information`



**Message:** <span class="text-warning">*Mavuin tells you, 'I know it has been said for years before me, and will be said for years after me, but I was truly framed for my crime.  You see the gods feared the knowledge that I carry with me.  So to prevent me passing this knowledge to others, it was set up to show that I had plotted to murder one of the other elders.  Please go before the tribunal and plead my case.  If you do this I will share what I know with you, I apologize for holding it against you, but I am desperate to be released.'*</span>


if ( mavuinFlag == 0 ) then



eq.set_global("mavuin", "1", 5, "F");



**Message:** <span class="text-warning">*You have received a character flag!*</span>
