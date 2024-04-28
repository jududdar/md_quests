# Tovan Tenlah
## Dialog

if(eq.get_current_expansion() >= 4.0) then


**You say:** `hail`




>**Tovan Tenlah says:** I suppose you're one of Nestrals new employees, eh? Well if that's the case I can help get you outfitted with some [gear] necessary for people in this [line of work].


**You say:** `gear`




>**Tovan Tenlah says:** The first thing you need is a suit of sturdy traders clothing. Take this note to Verona Rankin and she'll help you with a suit tailored to your needs. Once you have been outfitted in your traders clothing return to me and I will inform you of your [next task].



**You receive:**  [Note to Verona Rankin](/item/19846)


**You say:** `next task`




>**Tovan Tenlah says:** Ready to get to work are you? Listen carefully. Outside Freeports South gate you will find one of our employees, Rigg Nostra, who is acting as an intermediary between the Coalition of Tradefolk and some recently acquired business associates. Give him this card so he knows I've sent you and he will give you further instructions. Do not mention any of our names in public. The Freeport Militia would likely impose high taxes on the Coalition if they found out about the goods being exchanged to us by our new associates.



**You receive:**  [Bent Playing Card](/item/19917)

end

## Turn-Ins



local expansion_flag = eq.get_current_expansion();



if(expansion_flag >= 4.0 and  **You turn in:** [Rough Blue Gem](/item/19918)


>**Tovan Tenlah says:** Sharpen this dagger and take it with this gem and a rattlesnake skin to Verona Rankin.


* __Faction:__ [Coalition of Tradefolk Underground](/faction/336) (5)


* __Faction:__ [Coalition of Tradefolk](/faction/229) (5)


* __Faction:__ [Carson McCabe](/faction/329) (1)


* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (1)


* __Faction:__ [The Freeport Militia](/faction/330) (1)


 **You receive:**  [Faceted Blue Gem](/item/19919) (+100 exp)


 **You receive:**  [Dull Coalition Dirk](/item/19920) 

**This NPC *should* return incorrect items given.**
;

