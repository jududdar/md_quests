# Phin Esrinap
## On NPC Spawn

**Set a timer** named *konem* for 4100 seconds
## Timer(s)

>**Phin Esrinap says:** I can't believe that lazy [Konem] has been gone for over two days.  That's the last time I send that guy out for me.
## Dialog

**You say:** `hail`



>**Phin Esrinap says:** Hello, my name is Phin. Practice, practice, practice.. That's my motto. It is my responsibility to train our members, and help them to advance their skills and abilities. I also reward our members with colored [Headbands] for completing certain tasks.

**You say:** `white headband`



if **Faction** >= Amiable +50 then



>**Phin Esrinap says:** That is our training headband.. Beginning students can earn this by slaying four [gnoll] pups, and bringing their scalps back to me.


elseif **Faction** >= Indifferent then



>**Phin Esrinap says:** I have been watching you, and appreciate the help you've given to the brothers and sisters of the Silent Fist. But, I feel that such a vital matter should be left to one of our more trusted members.


else



>**Phin Esrinap says:** Your previous actions disgust me. Our guild will have nothing to do with the likes of you. Now, please, leave us be!


**You say:** `yellow headband`



if **Faction** >= Amiable +75 then



>**Phin Esrinap says:** This is awarded to our students for helping clear out the evil that inhabits the old ruins of the Qeynos Hills. Just bring me back three putrid rib bones as proof of your good deeds and turn in your [training headband], and then I will give you the yellow headband.


elseif **Faction** >= Indifferent then



>**Phin Esrinap says:** I have been watching you, and appreciate the help you've given to the brothers and sisters of the Silent Fist. But, I feel that such a vital matter should be left to one of our more trusted members.


else



>**Phin Esrinap says:** Your previous actions disgust me. Our guild will have nothing to do with the likes of you. Now, please, leave us be!


**You say:** `orange headband`



if **Faction** >= Amiable +125 then



>**Phin Esrinap says:** This is a difficult award to obtain. The city of Qeynos is, as you know, under constant attack by the gnolls of Blackburrow. The Silent Fist Clan rewards its members who venture deep into this gnoll stronghold and bring swift justice to these vile creatures. Please return two Blackburrow gnoll pelts - make sure they aren't ruined - and a Blackburrow gnoll skin as proof of your noble actions. Also, turn in your [yellow headband], and then I shall give you the orange one. Good luck.


elseif **Faction** >= Indifferent then



>**Phin Esrinap says:** I have been watching you, and appreciate the help you've given to the brothers and sisters of the Silent Fist. But, I feel that such a vital matter should be left to one of our more trusted members.


else



>**Phin Esrinap says:** Your previous actions disgust me. Our guild will have nothing to do with the likes of you. Now, please, leave us be!


**You say:** `Headband`



>**Phin Esrinap says:** Yes, I give the [White, Yellow, and Orange Headbands] to our newer members, and Togahn gives out [Red, Purple, and Blue Headbands] to our elder members.

**You say:** `Tomer Instogle`



>**Phin Esrinap says:** Tomer? I think Seta needs someone to go find him... Go ask her.

**You say:** `Konem`



if **Faction** >= Apprehensive then



>**Phin Esrinap says:** Ah yes, Konem. I had him run an errand out to Surefall Glade over two days ago, and he still hasn't returned. Knowing Konem, he probably found a nice shady tree to take a nap under. If you happen to pass by him, could you please take him this note?  Thanks, Soandso, and be safe.



**You receive:**  [Message to Konem](/item/18921)


else



>**Phin Esrinap says:** Your previous actions disgust me. Our guild will have nothing to do with the likes of you. Now, please, leave us be!


**You say:** `gnoll`



>**Phin Esrinap says:** Those vile creatures are constantly attacking our city.. and often killing innocent citizens. It is our duty to help defend Qeynos from their vicious raids.

**You say:** `black headband`



>**Phin Esrinap says:** The black headband is one of the highest honors of the Silent Fist Clan.  Only [Lu'Sun] gives those out.

**You say:** `lusun`



>**Phin Esrinap says:** Ahhh, Lu'Sun is a master of many skills.  He has traveled all of Norrath, studying various techniques and disciplines.  Now, he runs this small guild and passes on his knowledge to those willing to devote their lives to our cause.

**You say:** `red`



>**Phin Esrinap says:** Togahn gives out the red, purple, and blue headbands...  go ask him what you need to do to earn one.
end

## Turn-Ins



local text1 = "Good.. the more of these vile dogs we slay, the safer the citizens of Qeynos will be.";

local text2 = "Ahh.. Good. I feel that your hard work and training will soon be rewarded.. and the yellow headband shall soon be yours.";

local text3 = "Good work, Soandso. You are well on your way toward earning the orange headband.";




if **Faction** >= Apprehensive and  **You turn in:** [Grathins Invoice](/item/18922)) then


>**Phin Esrinap says:** Oh this is not good. Too many innocent traders have been getting robbed lately by those vile bandits out in the Karanas. Something must be done soon. Anyway, thank you for delivering the message... you did very well, young Soandso. Here's a little something to quench your thirst from all that running around.





* __Faction:__ [Silent Fist Clan](/faction/309) (5)


* __Faction:__ [Guards of Qeynos](/faction/262) (1)


* __Faction:__ [Ashen Order](/faction/361) (1)


 **You receive:**  [Water Flask](/item/13006) (+1500 exp)



elseif **Faction** >= Amiable +50 and  **You turn in:** [Gnoll Pup Scalp](/item/13789), [Gnoll Pup Scalp](/item/13789), [Gnoll Pup Scalp](/item/13789), [Gnoll Pup Scalp](/item/13789)) then 


>**Phin Esrinap says:** Good job, Soandso, keep up the good work! Here is your white training headband. Wear it with honor, and make Lu'Sun proud.


* __Faction:__ [Silent Fist Clan](/faction/309) (25)


* __Faction:__ [Guards of Qeynos](/faction/262) (3)


* __Faction:__ [Ashen Order](/faction/361) (1)


 **You receive:**  [White Headband](/item/10110) (+200 exp)



elseif **Faction** >= Amiable +75 and  **You turn in:** [Putrid Rib Bone](/item/13722), [Putrid Rib Bone](/item/13722), [Putrid Rib Bone](/item/13722), [White Headband](/item/10110)) then 


>**Phin Esrinap says:** Good work.. and, as promised, here is your reward. It is an honor to present this yellow headband to Soandso, for recent acts of courage and heroism, on behalf of the Silent Fist Clan.


* __Faction:__ [Silent Fist Clan](/faction/309) (50)


* __Faction:__ [Guards of Qeynos](/faction/262) (7)


* __Faction:__ [Ashen Order](/faction/361) (2)


 **You receive:**  [Yellow Headband](/item/10111) (+400 exp)



elseif **Faction** >= Amiable +125 and  **You turn in:** [Blackburrow Gnoll Pelt](/item/13027), [Blackburrow Gnoll Pelt](/item/13027), [Blackburrow Gnoll Skin](/item/13028), [Yellow Headband](/item/10111)) then 


>**Phin Esrinap says:** It is an honor to present the orange headband of the Silent Fist Clan to one of our finest members, Soandso the mighty!


* __Faction:__ [Silent Fist Clan](/faction/309) (50)


* __Faction:__ [Guards of Qeynos](/faction/262) (7)


* __Faction:__ [Ashen Order](/faction/361) (2)


 **You receive:**  [Orange Headband](/item/10112) (+800 exp)

**This NPC *should* return incorrect items given.**



