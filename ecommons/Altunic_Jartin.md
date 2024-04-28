# Altunic Jartin
## Arrive at Waypoint Script

if(e.wp == 2) then


e.self:SetRunning(true);

elseif(e.wp == 3) then


e.self:SetRunning(false);
end

## Dialog

**You say:** `hail`



>**Altunic Jartin says:** Greetings, traveler! Have you need of provisions or perhaps other wares? I sell what I find upon the battlegrounds of the Commonlands.

**You say:** `Where is your house`



>**Altunic Jartin says:** Follow me.


eq.move_to(4791.06,-83.55,-51.47);


**Spawn NPC:**  [Squire Narl](/npc/22196) at (**y:** -105.49, **x:** 4707.63)
end

## Turn-Ins




if **You turn in:** [A note](/item/18896)


>**Altunic Jartin says:** You are the one they have sent? A squire?!! I hope you can help me. I gather items strewn upon the grounds of the Commonlands. I sell them at good prices. Lately, I have been terrorized by a human rogue named Narl. He will no doubt appear at my [house] soon. Bring his head to me.

elseif **You turn in:** [A Human Head](/item/13867)


>**Altunic Jartin says:** You have performed a great service to me, but I fear others will attack me while I stroll the countryside. It would be very noble of you to fetch me a cloth shirt for protection from wicked creatures. It is not much, but it will help.


* __Faction:__ [Knights of Truth](/faction/281) (5)


* __Faction:__ [Dismal Rage](/faction/271) (-1)


* __Faction:__ [The Freeport Militia](/faction/330) (-1)


* __Faction:__ [Priests of Marr](/faction/362) (1)


* __Faction:__ [Steel Warriors](/faction/311) (1)


 **You receive:** 0 (+500 exp)

elseif **You turn in:** [Cloth Shirt](/item/1004)


>**Altunic Jartin says:** Thank you. You are very noble for a squire. I can see you becoming a very valuable asset to the Hall of Truth. Take this token. Tell Merko that you have [earned the Token of Generosity].


* __Faction:__ [Knights of Truth](/faction/281) (5)


* __Faction:__ [Dismal Rage](/faction/271) (-1)


* __Faction:__ [The Freeport Militia](/faction/330) (-1)


* __Faction:__ [Priests of Marr](/faction/362) (1)


* __Faction:__ [Steel Warriors](/faction/311) (1)


 **You receive:**  [Token of Generosity](/item/13865) (+500 exp)
end


