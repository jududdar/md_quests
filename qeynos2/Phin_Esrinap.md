# Phin Esrinap



[Phin Esrinap](/npc/2075) is a level 61 Human GM Monk that spawns in [North Qeynos](/zone/2).



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



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18921" data-url="18921" class="tooltip-link link">Message to Konem</a>


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




if **Faction** >= Apprehensive and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18922" data-url="18922" class="tooltip-link link">Grathins Invoice</a>) then


>**Phin Esrinap says:** Oh this is not good. Too many innocent traders have been getting robbed lately by those vile bandits out in the Karanas. Something must be done soon. Anyway, thank you for delivering the message... you did very well, young Soandso. Here's a little something to quench your thirst from all that running around.





Your faction standing with [Silent Fist Clan](/faction/309) got better (<span class='text-success'>+5</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+1</span>)


Your faction standing with [Ashen Order](/faction/361) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_584.png" alt="" /> <a
                                href="/item/13006" data-url="13006" class="tooltip-link link">Water Flask</a> (+1500 exp)

 



elseif **Faction** >= Amiable +50 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_555.png" alt="" /> <a
                                href="/item/13789" data-url="13789" class="tooltip-link link">Gnoll Pup Scalp</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_555.png" alt="" /> <a
                                href="/item/13789" data-url="13789" class="tooltip-link link">Gnoll Pup Scalp</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_555.png" alt="" /> <a
                                href="/item/13789" data-url="13789" class="tooltip-link link">Gnoll Pup Scalp</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_555.png" alt="" /> <a
                                href="/item/13789" data-url="13789" class="tooltip-link link">Gnoll Pup Scalp</a>) then 


>**Phin Esrinap says:** Good job, Soandso, keep up the good work! Here is your white training headband. Wear it with honor, and make Lu'Sun proud.


Your faction standing with [Silent Fist Clan](/faction/309) got better (<span class='text-success'>+25</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+3</span>)


Your faction standing with [Ashen Order](/faction/361) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_932.png" alt="" /> <a
                                href="/item/10110" data-url="10110" class="tooltip-link link">White Headband</a> (+200 exp)

 



elseif **Faction** >= Amiable +75 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_907.png" alt="" /> <a
                                href="/item/13722" data-url="13722" class="tooltip-link link">Putrid Rib Bone</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_907.png" alt="" /> <a
                                href="/item/13722" data-url="13722" class="tooltip-link link">Putrid Rib Bone</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_907.png" alt="" /> <a
                                href="/item/13722" data-url="13722" class="tooltip-link link">Putrid Rib Bone</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_932.png" alt="" /> <a
                                href="/item/10110" data-url="10110" class="tooltip-link link">White Headband</a>) then 


>**Phin Esrinap says:** Good work.. and, as promised, here is your reward. It is an honor to present this yellow headband to Soandso, for recent acts of courage and heroism, on behalf of the Silent Fist Clan.


Your faction standing with [Silent Fist Clan](/faction/309) got better (<span class='text-success'>+50</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+7</span>)


Your faction standing with [Ashen Order](/faction/361) got better (<span class='text-success'>+2</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_933.png" alt="" /> <a
                                href="/item/10111" data-url="10111" class="tooltip-link link">Yellow Headband</a> (+400 exp)

 



elseif **Faction** >= Amiable +125 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_556.png" alt="" /> <a
                                href="/item/13027" data-url="13027" class="tooltip-link link">Blackburrow Gnoll Pelt</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_556.png" alt="" /> <a
                                href="/item/13027" data-url="13027" class="tooltip-link link">Blackburrow Gnoll Pelt</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_556.png" alt="" /> <a
                                href="/item/13028" data-url="13028" class="tooltip-link link">Blackburrow Gnoll Skin</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_933.png" alt="" /> <a
                                href="/item/10111" data-url="10111" class="tooltip-link link">Yellow Headband</a>) then 


>**Phin Esrinap says:** It is an honor to present the orange headband of the Silent Fist Clan to one of our finest members, Soandso the mighty!


Your faction standing with [Silent Fist Clan](/faction/309) got better (<span class='text-success'>+50</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+7</span>)


Your faction standing with [Ashen Order](/faction/361) got better (<span class='text-success'>+2</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_934.png" alt="" /> <a
                                href="/item/10112" data-url="10112" class="tooltip-link link">Orange Headband</a> (+800 exp)

 

**This NPC *should* return incorrect items given.**



