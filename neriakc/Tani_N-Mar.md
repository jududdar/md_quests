# Tani N-Mar


## On NPC Spawn

**Set a timer** named *pick_up* for 2 seconds
## Timer(s)

if ( e.timer == "pick_up" ) then




while ( e.self:CheckGround() ) do



>*Tani N-Mar picks up something from the ground.*


## Dialog

**You say:** `hail`



>**Tani N-Mar says:** Greetings!  You must be a stranger or [new to the Hall].  If you are a stranger. be warned that these halls are intended for the Ebon Mask only. If you are found to be a member of another house. you just may feel the sting of a blade in your back.

**You say:** `new to the hall`



if **Faction** >= Amiable then



>**Tani N-Mar says:** Then I am glad to make your acquaintance. Have you ever been to Freeport?  If not. how would you like to go?  It is a test of your cunning we wish.  Are you prepared to risk your young life?  Are you [ready to venture to Freeport]?


elseif **Faction** >= Indifferent then



>**Tani N-Mar says:** You have done nothing to upset the Ebon Mask, but there is much more which you must do before we do business.  Perhaps a task from Master Hekzin shall set things right.


else



>**Tani N-Mar says:** You are quite bold to approach a member of the Ebon Mask. Now be smart and run away.




**You say:** `venture to freeport`



if **Faction** >= Amiable then






>**Tani N-Mar says:** Find a way to the port of Freeport.  Seek out Giz Dinree.  She is usually near the shores at night.  She is your contact. Tell her you were [sent by Tani].  She will fill you in on your mission.  Good luck.  Do not waste time practicing your skills. Go as you are.


elseif **Faction** >= Indifferent then



>**Tani N-Mar says:** You have done nothing to upset the Ebon Mask, but there is much more which you must do before we do business.  Perhaps a task from Master Hekzin shall set things right.


else



>**Tani N-Mar says:** You are quite bold to approach a member of the Ebon Mask. Now be smart and run away.




**You say:** `book of souls`




>**Tani N-Mar says:** The Book of Souls chronicles all the lives Innoruuk has tainted over the years. It is in the care of the Maestro of Rancor. I can use this tome as a basis for my translation, if you return it and the note to me. An experienced practitioner in the art of non-detection should be able to snatch it from its resting place, don't you think, " .. e.other:Race() .. "?

**You say:** `note`




>**Tani N-Mar says:** Oh, you want that piece of paper Stanos was so hot after? Well it's mine now, though it looks like ogre scratch to me. You're not getting it, Stanos is not getting it, and Hanns is not getting it. It is MINE! Now, " .. e.other:Race() .. ", scamper off like the dog you are, before I decide I need more practice with these short swords!

**You say:** `stanos`




>**Tani N-Mar says:** Stanos? Hahahaha! That old fool crossed my path a few times in the past, but he is not able to trouble me now. If you see him, tell him Tani sends his..love. Hahahaha!
end

## Turn-Ins





if **You turn in:** [Human Head](/item/13892)


>**Tani N-Mar says:** Good work! I knew you could prove your worth. Most waste time training. I do not reward those who waste my time. Please take this. It is from our horde, from countless robberies. I hope you can use it to advance yourself. Remember to always stay faithful to Neriak.


* __Faction:__ [Ebon Mask](/faction/244) (20)


* __Faction:__ [Guards of Qeynos](/faction/262) (-1)


* __Faction:__ [Wolves of the North](/faction/320) (-5)


* __Faction:__ [Guardians of the Vale](/faction/263) (-2)


* __Faction:__ [Carson McCabe](/faction/329) (-5)


 **You receive:**  [Cinctured Whip](/item/5066) (+5000 exp)

**This NPC *should* return incorrect items given.**






