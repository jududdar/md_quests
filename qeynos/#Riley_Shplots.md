# Riley Shplots
## On NPC Spawn

**Set a timer** named *depop* for 1800 seconds
## Dialog

**You say:** `bloodsaber`



>*Riley Shplots shakes visibly and says, 'Oh, no. I knew this would happen one day. Please don't hurt me! I had very little to do with this plague, though it is quite a nice one, you must admit. I was just a courier. I'll come quietly. I don't want any trouble. My small contribution to the glory of Bertoxxulous has already been given but I certainly don't want to go to meet him just yet!'*
end

## Turn-Ins



if **You turn in:** [Confession Document](/item/2344)


 **You receive:** None 


eq.set_global("invest_badge","second_suspect",3,"F");


**Spawn NPC:**  [\#Willie Garrote](/npc/1201) at (**y:** -11, **x:** -414)

item_lib.return_items(e.self, e.other, e.trade, e.text)
## Signals

if(e.signal == 1) then


eq.start(65);
end

## Timer(s)

if(e.timer == "depop") then


**Riley Shplots despawns.**
end
