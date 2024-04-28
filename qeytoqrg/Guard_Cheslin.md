# Guard Cheslin
## Dialog

**You say:** `hail`



>**Guard Cheslin says:** Hail, mighty adventurer! I am Guard Cheslin Sydwend and I am here to serve and protect. Feel safe when we Qeynos guards are on watch. We are the best!

**You say:** `father sent me`



>**Guard Cheslin says:** My father has no need to worry and I do not need a baby sitter. I may be in training still, but a Qeynos guard in training is still a formidable opponent. EVIL, BEWARE!!   HAIL ANTONIUS BAYLE! 

**You say:** `donation.* temple.* thunder`





>**Guard Cheslin says:** Of course I shall donate to that esteemed order. Here you are, my good friend. Now run along before you are injured by some nasty creature. By the way, you should speak with my fellow guard, Leopold. He also would donate.


**You receive:**  [A Donation](/item/13295)

**You say:** `drop`



>**Guard Cheslin says:** Yes!! I seem to have dropped some of my [Illusion] cards.

**You say:** `illusion`



>**Guard Cheslin says:** Oh!! Do you play Illusion, too? I love that game. I have some very rare cards in my deck. I seem to have dropped four of them somewhere during my last patrol. Darn it! They probably blew away the minute I dropped them! I will never find those cards again.
end

## Turn-Ins




if **You turn in:** [Ebon Lotus](/item/13904), [Library of Erudin](/item/13905), [Chrono Cyclone](/item/13906), [Diamond Vale](/item/13907)


>**Guard Cheslin says:** Oh great! I have all my cards back. Here is a little something for assisting a Qeynos guard. And any time you are in trouble, just call on Cheslin, master swordsman. Take it to my father, Master Chesgard of the Knights of Thunder in Qeynos. No doubt he sent you to follow me on my watch.


* __Faction:__ [Guards of Qeynos](/faction/262) (20)


* __Faction:__ [Antonius Bayle](/faction/219) (3)


* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (-3)


* __Faction:__ [Circle of Unseen Hands](/faction/223) (-5)


* __Faction:__ [Merchants of Qeynos](/faction/291) (2)


 **You receive:** None 

elseif **You turn in:** [Ebon Lotus](/item/13904)


>**Guard Cheslin says:** Wow!! I thought I lost this for good. All together I lost the [illusion] cards: Ebon Lotus, Library of Erudin, Chrono Cyclone and Diamond Vale. Man!! Those are rare cards!


**This NPC *should* return incorrect items given.**

## Arrive at Waypoint Script

local xloc = e.self:GetX();

local yloc = e.self:GetY();

local zloc = e.self:GetZ();

if(e.wp == 1) then


>**Guard Cheslin says:** Hail, fellow guards! I am off to protect the travelers of the hills from evil. I shall return!


**Signaled to:**  [Hefax Tinmar](/npc/4142)


**Signaled to:**  [Mogan Delfin](/npc/4001)

elseif(e.wp == 3) then


>**Guard Cheslin says:** Fear not, simple travelers. Cheslin the masterful is here to protect you.


eq.create_ground_object( [Library of Erudin](/item/13905),xloc,yloc,zloc,0,300000); 


>**Guard Cheslin says:** Hey! Did I just drop something?

elseif(e.wp == 4) then


>**Guard Cheslin says:** Fear not, simple travelers. Cheslin the masterful is here to protect you.


eq.create_ground_object( [Ebon Lotus](/item/13904),xloc,yloc,zloc,0,300000); 


>**Guard Cheslin says:** Hey! Did I just drop something?

elseif(e.wp == 7) then


>**Guard Cheslin says:** Fear not, simple travelers. Cheslin the masterful is here to protect you.


eq.create_ground_object( [Diamond Vale](/item/13907),xloc,yloc,zloc,0,300000); 


>**Guard Cheslin says:** Hey! Did I just drop something?

elseif(e.wp == 9) then


>**Guard Cheslin says:** Fear not, simple travelers. Cheslin the masterful is here to protect you.


eq.create_ground_object( [Chrono Cyclone](/item/13906),xloc,yloc,zloc,0,300000); 


>**Guard Cheslin says:** Hey! Did I just drop something?

elseif(e.wp == 11) then


>**Guard Cheslin says:** I lost some of my [illusion] playing cards. And they were the rare ones too! Darn it! If anyone finds them, please return them to me.
end
