# Squire Fuzzmin
## On NPC Spawn

 e.self:SetRunning(true);
## Arrive at Waypoint Script

if(e.wp == 9) then


e.self:SetRunning(false);


eq.stop();


local mobtypeID =  eq.get_entity_list():GetMobByNpcTypeID(84005);


local follow_hobble = mobtypeID:GetID();


eq.follow(follow_hobble);
end

## Dialog

**You say:** `hail`



>*Squire Fuzzmin awakens from a quick shuteye.*


>**Squire Fuzzmin says:** Yawn.. Oh!! Hello. Don't mind the rusty old tin can. Sir Hobble is on a [quest] of sorts. I tell you, I would leave if he did not pay good wages to carry his equipment.

**You say:** `quest`



>**Squire Fuzzmin says:** Sir Hobble is searching for [three special dragons]. For all I know they are not even dragons. He can't see or hear very well. He still thinks I am the only troll squire around.

**You say:** `three special dragon`



>**Squire Fuzzmin says:** Apparently he is after three dragons which are supposedly named Azdalin, Gylton, and Xyfl. He will not rest until he holds their scales. I wish you could [find the dragons].

**You say:** `find the dragon`



>**Squire Fuzzmin says:** If you bring me the three scales I will be able to place them upon the next three victims of Sir Hobble. Then we can part from this accursed isle. He would never know the difference. Do this and I will give you a warrior weapon out of the old knight's armory.
end

## Turn-Ins



local text = "I need the three dragon scales of Azdalin, Gylton and Xyfyl.";


if( **You turn in:** [Dragon Scales](/item/12950), [Dragon Scales](/item/12951), [Dragon Scales](/item/12952)) then



e.self:DoAnim(20);


>*Squire Fuzzmin tumbles around and stands on his hands. With his feet he pulls a long polearm from a nearby weapons cache!! 'Woohoo!! I can taste the brew in Freeport already. Here you are my friend. A real Wurmslayer!!'*


* __Faction:__ [Inhabitants of Firiona Vie](/faction/248) (10)


* __Faction:__ [Emerald Warriors](/faction/326) (7)



* __Faction:__ [Storm Guard](/faction/312) (7)


* __Faction:__ [Legion of Cabilis](/faction/441) (-1)


* __Faction:__ [Pirates of Gunthak](/faction/313) (-1)


 **You receive:**  [Wurmslayer](/item/5057) (+700000 exp)

**This NPC *should* return incorrect items given.**












