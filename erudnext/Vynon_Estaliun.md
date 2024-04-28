# Vynon Estaliun
## Dialog

**You say:** `hail`



>**Vynon Estaliun says:** I welcome you to the temple of the Peacekeepers. The ways of peace and tranquility are ours to uphold. May you find a place among us. We have much work to do. If you are a paladin of this temple. you must [desire to face fear].

**You say:** `desire to face fear`



if **Faction** >= Amiable then 



>**Vynon Estaliun says:** Very well. You shall face it. In Toxxulia Forest. you shall seek out Kerra Ridge. Once found. you will bring me the tail of a catfisher. Somehow. you shall find a way. They are weak. but they only work near the opposite side of the bridge. along the water's edge.


elseif **Faction** >= Indifferent then



>**Vynon Estaliun says:** You have not done much to upset the Peacekeepers of this temple, but we must ask you to prove yourself to us before we may discuss things such as this.


else



>**Vynon Estaliun says:** Leave my sight at once! You are no friend to the Peacekeepers of the Temple of Divine Light.


end

## Turn-Ins




if **Faction** >= Amiable and  **You turn in:** [Fishy Cat Tail](/item/13884)


>**Vynon Estaliun says:** Good work. I knew you could do it. Take this as reward.





* __Faction:__ [Peace Keepers](/faction/298) (5)


* __Faction:__ [High Council of Erudin](/faction/266) (1)


* __Faction:__ [Heretics](/faction/265) (-1)


 **You receive:** eq.ChooseRandom( [Torch](/item/13002), [Brass Ring](/item/13053)) (+2000 exp)

**This NPC *should* return incorrect items given.**
;

