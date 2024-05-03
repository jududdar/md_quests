# a thunder spirit princess




## Dialog

**You say:** `hail`



>**a thunder spirit princess says:** Greetings, travelers, welcome to the Plane of Sky! We are thunder spirits - this first island is our home. You are welcome to stay here as long as you like. If you wish to go to other islands you may purchase keys from the Key Master.

**You say:** `gkzzallk`



>**a thunder spirit princess says:** Gkzzallk lives far above here. We often take him tea because he's so nice to us fairies! He likes to chat with the others who live here and can often be found in the temple up above. If you give me a bit of money, I can go make sure he is home.
end



## Turn-Ins



if( **You turn in:** gold = 10) then


>**a thunder spirit princess says:** Thank you, Soandso. I will tell him to expect visitors.


**Spawn NPC:**  [Gkzzallk](/npc/71073) at (**y:** 662.5, **x:** 287.9)
end



## On NPC Death

local sirranName = "sirran";

sirranName = sirranName .. eq.get_zone_guild_id();

eq.set_global(sirranName,"1",3,"M20");

**Spawn NPC:**  [Sirran the Lunatic](/npc/71058) at (**y:** 1381, **x:** 688)




