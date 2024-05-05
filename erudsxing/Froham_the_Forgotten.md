# Froham the Forgotten



[Froham the Forgotten](/npc/98047) is a level 20 Skeleton Warrior that spawns in [Erud's Crossing](/zone/98).

local counting;



## On NPC Spawn

**Set a timer** named *FrohamDepart* for 140 seconds

counting = 0;


## Dialog

**You say:** `hail`



>*Froham the Forgotten looks up at you and mumbles a brief greeting. He appears uncomfortable around others.*

**You say:** `who are you`



>*Froham the Forgotten glances up at you, fiddling with his bony fingers and mumbles, 'Mmmm me name's Froham..I'm 'ere [waitin].*

**You say:** `waitin`



>**Froham the Forgotten says:** Just waitin' . . . it'll [be ere soon], I s'pose.

**You say:** `be here soon`



>*Froham the Forgotten obviously has trouble communicating. He shifts uncomfortably and says, 'Well I'm not sure, but it's real important. I been 'ere fer a [long time], a real long time. So I'll keep waitin' til it comes.*

**You say:** `long time`



>**Froham the Forgotten says:** Been 'ere since Erud sailed over with his friends. They let me catch a ride on their ship after I told them I needed to come 'ere to wait. He was a nice fella, real smart. Though I'm thinkin' he's dead by now. Maybe [Abe] knows fer sure. Abe's been here longer'n me, even.

**You say:** `abe`



>**Froham the Forgotten says:** Yeah, Abe's an old guy. Well, he's kinda beyond bein' old if ye know what I mean. Not all together either. His mind floats all over like the sea around us. But he's got enough sense to wait here like he's done fer, well, fer dang near ever. If ye see him, and he ain't much fer talkin' straight, ask him about [a broken arrow]. Not sure what it means to him but it seems to bring him around.
end



## Timer(s)



if (e.timer == "FrohamDepart") then


counting = counting + 1;

if(counting == 2) then


>*Froham the Forgotten sighs heavily and says, 'Looks like it's not comin'. You know, Abe told me of a great treasure a ways away from here, guarded by one o' them girls with fish tails. I always wanted to go but those two jokers, Dillon and the other young one, never had the guts. Why don't ye come with me, shaman? We'll split the treasure fifty-fifty, fair and square.*


eq.start(34);

elseif (counting == 5) then


**Spawn NPC:**  [Abe the Abandoned](/npc/98050) at (**y:** -1585, **x:** 4169)


**Froham the Forgotten despawns.**


**Stop timer** named *FrohamDepart*
end

