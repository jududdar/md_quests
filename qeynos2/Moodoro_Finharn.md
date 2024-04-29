# Moodoro Finharn
## Dialog

**You say:** `hail`



if **Faction** >= Indifferent then 




>**Moodoro Finharn says:** Greetings, fellow traveler! I gotta tell ya. I love this town. Especially Crow's. Although the crowd seems a bit shadier than other places of the sort.


else



**Moodoro Finharn says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.




**You say:** `testament of vanear`



>**Moodoro Finharn says:** So you have heard that good old Moodoro has knowledge of the Testament of Vanear. I care little for that book. Of course I have it!! If you want it, I will sell it to you for two gold pieces.

**You say:** `ran`



>**Moodoro Finharn says:** Ran Flamespinner is a librarian in Highpass Hold.

**You say:** `page 34`



>**Moodoro Finharn says:** So, you know I have page 34. Pretty smart of me to tear the most important page out before someone else tried, eh? If you really want it, then sit down and deal in. Ante is 4 gold. I will give you one card. If it is a jester, then I will give you the page. Let's do it.

**You say:** `tonic`



>**Moodoro Finharn says:** I need some of Erud's tonic water. There is a merchant in Erudin who sells it.
end

## Arrive at Waypoint Script

if(e.wp == 6) then


>**Moodoro Finharn says:** <urp>.. I don't feel so well.


**Signaled to:**  [Flynn Merrington](/npc/2091)

elseif(e.wp == 14) then


eq.set_anim(2040,1);


>**Moodoro Finharn says:** Ooooh.. Bllaughhh.. Ooh.. I need some tonic.
end

## Signals


if(e.signal == 1) then


>**Moodoro Finharn says:** HA! HA! HA! Oh...  <burp> HA!  HA!  HA! How pitiful! HA! HA!




## Turn-Ins




if( **You turn in:** [Eruds Tonic](/item/13118)) then


>**Moodoro Finharn says:** Oh thank the maker you have returned. Here is a little something in return





* __Faction:__ [Crimson Hands](/faction/233) (20)


* __Faction:__ [High Council of Erudin](/faction/266) (2)


* __Faction:__ [Heretics](/faction/265) (-3)


* __Faction:__ [High Guard of Erudin](/faction/267) (2)


e.other:QuestReward(0,0,0,0,0,0);

elseif( **You turn in:** [Jester](/item/13994)) then


>**Moodoro Finharn says:** Lucky you. We were hoping to really clean you out. Here you go. Take the page. Even together, the book is nothing more than fiction.


 **You receive:**  [Page 34 of a Book](/item/13836) 

elseif( **You turn in:** gold = 4) then


>**Moodoro Finharn says:** Well, what do you have?!!


 **You receive:** eq.ChooseRandom( [Jester](/item/13994), [Queen](/item/13993), [King](/item/13992), [Knight](/item/13995)) 

elseif( **You turn in:** gold = 2) then


>**Moodoro Finharn says:** HA!! I hope you enjoy the book. It is missing pages 30 and 34. It is nothing more than garbage without them. A rogue ripped them from their bindings and sold them to [Ran].


 **You receive:**  [Testament of Vanear](/item/17918) 

**This NPC *should* return incorrect items given.**

## On NPC Death

e.self:Emote(string.format("'s corpse says 'I'll get you back %s!'",e.other:GetCleanName()));