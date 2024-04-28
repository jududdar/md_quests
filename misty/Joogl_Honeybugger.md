# Joogl Honeybugger
## Dialog

**You say:** `hail`



>**Joogl Honeybugger says:** Hello. I would shake your hand, but it would [hurt]. Ooooh! Owwy!

**You say:** `hurt`






>**Joogl Honeybugger says:** I was attacked by the bixies. They swarmed on me!! I think I got too near their queen. I need that honey to make a living! Get me a bandage and I will tell you where all their worker bee's buzz around.

**You say:** `I need the honeycomb`



>**Joogl Honeybugger says:** If you're looking for the honeycombs, I don't have any right now. I have been unable to get any since I was attacked by the little [buggers]. I will tell you where to get some if you will only get me a bandage for my bites.

**You say:** `what buggers`



>**Joogl Honeybugger says:** I was attacked by the bixies. They swarmed on me!! I think I got too near their queen. I need that honey to make a living! Get me a bandage and I will tell you where all their worker bees buzz around.
end

## Turn-Ins



local bandage = 0;



if **You turn in:** [Bandages](/item/13009), [Bandages](/item/13009), [Bandages](/item/13009), [Bandages](/item/13009)


bandage=4;

if **You turn in:** [Bandages](/item/13009), [Bandages](/item/13009), [Bandages](/item/13009)


bandage=3;

if **You turn in:** [Bandages](/item/13009), [Bandages](/item/13009)


bandage=2;

if **You turn in:** [Bandages](/item/13009)


bandage=1;

if(bandage > 0) then


for i = 1, bandage do







>**Joogl Honeybugger says:** Oh thank you, Soandso. If you are ever going to gather bixie honeycomb's pray you do not run into the queen. The only way I know of collecting the honey is by intercepting the drone's and taking the honeycomb's they sometime's carry. Good luck!!







* __Faction:__ [Merchants of Rivervale](/faction/292) (1)



* __Faction:__ [Deeppockets](/faction/241) (1)



* __Faction:__ [Guardians of the Vale](/faction/263) (1)



* __Faction:__ [Mayor Gubbin](/faction/286) (1)



* __Faction:__ [Coalition of Tradefolk Underground](/faction/336) (-1)



**This NPC *should* return incorrect items given.**
