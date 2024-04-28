# Captain Ryglot Cupperhide
## Dialog


local questState = tonumber(eq.get_qglobals(e.other).pov_orb_quest or 0);



if ( questState == 6 ) then



**You say:** `hail`




e.self:Say("I am very [busy] at the moment. Perhaps you should come back at another time "..e.other:GetName());






**You say:** `busy`




>**Captain Ryglot Cupperhide says:** I can't go into any great detail, but the Crystalline Globe was taken from our command structure. Its believed to have been separated into three pieces. Unfortunately, we're having a lot of trouble relocating it. Perhaps you'd like to [help].






**You say:** `help`




>**Captain Ryglot Cupperhide says:** That's good to hear Soandso. I wish we had more soldiers like yourself willing to help. I'm going to need you to locate the missing pieces of the globe and bring them back to me. After you've acquired the pieces perhaps you'd be able to rally enough people to lend us a hand with another [mission] objective we've been unable to fulfill do to our diminished numbers.






**You say:** `mission`




>**Captain Ryglot Cupperhide says:** Well, I can't go into any details as to our main purpose is, but one of our missions was to exterminate the crystalline dragon. However, due to our company being split we are unable to go forward with this part of the operation. It has been placed on hold, pending the outcome of the [war].






**You say:** `war`




>**Captain Ryglot Cupperhide says:** Unfortunately, that is one of the things that I'm unable to speak of at this time. However, if you are [willing] to help rally some people together I may be able to release some more information to you.






**You say:** `willing`




>**Captain Ryglot Cupperhide says:** Well, that's good to hear. Bring me back what I've requested and we'll talk then.


else


**You say:** `hail`




>**Captain Ryglot Cupperhide says:** Please leave. I am extremely busy at the moment.

end

## Turn-Ins

local questState = tonumber(eq.get_qglobals(e.other).pov_orb_quest or 0);





if (  **You turn in:** [A piece of the crystalline globe](/item/25796), [A piece of the crystalline globe](/item/25797), [A piece of the crystalline globe](/item/25798) 




if ( questState == 6 ) then



>*Captain Ryglot Cupperhide looks up at you in surprise. 'I can't believe you brought the missing pieces back to me so quickly. I have a team of men who have been looking for these pieces for weeks now. That's quite a feat. Unfortunately, I will be unable to make use of the Crystalline Globe at this time. A message has been dispatched to my platoon asking us to return to the Halls of Honor. It looks as if we'll be joining up with the rest of our company fairly soon. Keep the globe. If you're able to rally enough people together to take on Aerin\`Dar then perhaps you'll be able accomplish an objective that our platoon was unable to do. I must go now. Good luck to you Soandso.'*







 **You receive:** None 


else



>**Captain Ryglot Cupperhide says:** Thanks for the gift.



**This NPC *should* return incorrect items given.**
;