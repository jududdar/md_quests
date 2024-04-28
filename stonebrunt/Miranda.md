# Miranda
## Dialog

**You say:** `hail`



if **Faction** >= Dubious +300 then



>**Miranda says:** I'm not supposed to talk to strangers but if my parents let you in here I guess it's ok. Do you like [candy]? I could give you some candy to play a game with me but my [dice] are gone now.


else



>**Miranda says:** You have done much to anger the spirits thus you are not accepted by our people.


**You say:** `candy`



if **Faction** >= Dubious +300 then



>**Miranda says:** Khonza Ayssla went away one time and came back with chocolate covered cherries and pixie powder cinnesticks for my sister and I. I like the chocolates the best.


else



>**Miranda says:** You have done much to anger the spirits thus you are not accepted by our people.


**You say:** `dice`



if **Faction** >= Dubious +300 then



>**Miranda says:** I had my dice in a little bag and lost it outside the walls of the village. I think the kobolds must have found it.


else



>**Miranda says:** You have done much to anger the spirits thus you are not accepted by our people.

end

## Turn-Ins





if **Faction** >= Dubious +300 and  **You turn in:** [Chocolate Marr Cherries](/item/19992)


>*Miranda claps her hands with excitement 'Chocolate cherries! My favorite! Here try some of this!'*


* __Faction:__ [Kejek Village](/faction/5011) (1)


* __Faction:__ [Peace Keepers](/faction/298) (1)


 **You receive:**  [Pouch of Kejek Catnip](/item/20115) (+1000 exp)

elseif **Faction** >= Dubious +300 and  **You turn in:** [Tiny Pouch of Bone Dice](/item/2088)


>**Miranda says:** You found my dice!!! Thank you Soandso!!


* __Faction:__ [Kejek Village](/faction/5011) (2)


* __Faction:__ [Peace Keepers](/faction/298) (1)


 **You receive:**  [Ball of Burlap Yarn](/item/20116) (+1000 exp)


**This NPC *should* return incorrect items given.**
