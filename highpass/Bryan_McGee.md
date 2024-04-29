# Bryan McGee
## Dialog

**You say:** `hail`



>**Bryan McGee says:** I do not know what you are doing up here, but I am a busy man. Please return to the bar downstairs and enjoy the atmosphere.


**Signaled to:**  [Beef](/npc/5055)

**You say:** `oblong bottle`



>**Bryan McGee says:** The oblong bottle is a legend. They say one drink and you're off to oblivion, but just before that you feel the best you've ever felt and relive all your finest memories in the blink of an eye. The last I heard, some guy by the name of Turgin Swillfod turned up in Freeport spouting that he had found it. He was never heard from again.

**You say:** `never stop chopping`



>**Bryan McGee says:** Hey!! You must be the one I traded my axe to. Funny.. I thought you were much shorter. If you have my axe I will return your gem to you. Well..? Let's have it!


end

## Signals

if(e.signal == 1) then


>**Bryan McGee says:** The boss might need some help!


local stanos = eq.get_entity_list():GetMobByNpcTypeID(5088); 


if ( stanos.valid ) then



e.self:MoveTo(stanos:GetX(), stanos:GetY(), stanos:GetZ(), -1, false);

end

## Turn-Ins




if( **You turn in:** [never stop chopping](/item/12366)) then 


>**Bryan McGee says:** On second thought.. You can do a little favor for me first. An associate of mine has asked me to acquire a case of spirits for him. Take this box and seek out what is needed to fill it. Inside you will combine the spirits of Lendel's Grand Lager, Gator Gulp Ale, Blackburrow Swig, Tunare's Finest, Underfoot Triple Bock, Frozen Toe Rum, Blood Spirit, Vasty Deep Ale, Clockwork Oil Stout and the legendary..[Oblong Bottle].





* __Faction:__ [Coalition of Tradefolk Underground](/faction/336) (10)


* __Faction:__ [Coalition of Tradefolk](/faction/229) (10)


* __Faction:__ [Carson McCabe](/faction/329) (1)


* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (1)


* __Faction:__ [The Freeport Militia](/faction/330) (1)


 **You receive:**  [Bottle Crate](/item/17984) (+15000 exp)


**Signaled to:**  [Beef](/npc/5055)

elseif( **You turn in:** [Case of Spirits](/item/12365)) then


>**Bryan McGee says:** I cannot believe you actually acquired all those drinks!! You do good work, kid. Here is the gem as I promised. And a few plat for good measure. Don't let it be said that the Axe doesn't treat his friends right.


* __Faction:__ [Coalition of Tradefolk Underground](/faction/336) (25)


* __Faction:__ [Coalition of Tradefolk](/faction/229) (25)


* __Faction:__ [Carson McCabe](/faction/329) (2)


* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (1)


* __Faction:__ [The Freeport Militia](/faction/330) (3)


 **You receive:**  [Gem of Stamina](/item/12348) (+15000 exp)

**This NPC *should* return incorrect items given.**
