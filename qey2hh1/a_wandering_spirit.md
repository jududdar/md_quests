# a wandering spirit
## Dialog

**You say:** `hail`



>*a wandering spirit stops and flashes brightly for a moment. It seems to be regarding you with interest.*


eq.pause(30);

elseif **Faction** >= Amiable +200 then


**You say:** `shield of falsehood`




e.self:Say(string.format("Yes, I have taken Marr's Promise along with Woe and Envy and fashioned them together to create the Shield of Falsehood. Wield this in defense of possession and the weakness that comes with hoarding treasure instead of using it to accomplish your goals. May it serve you well, %s.",e.other:Race()));



**You receive:**  [Shield of Falsehood](/item/1679)


**You say:** `last path`




>**a wandering spirit says:** You have trusted us along the paths we have set before you. You have been known to be patient and await the right moment. And now, you have learned the wisdom to act in our best interest. However, one last path awaits, to determine if you have the ability to act out what must be done. There are many troubles about the world we try to rub out but none is more serious than the curse on what the wasichu call the Emerald Jungle. Go there and find one of our spirits. Show them the gem you have been given and follow the path they set you on.



**You receive:**  [Sparkling Gem](/item/1668)

end

## Turn-Ins

local qglobals = eq.get_qglobals(e.self,e.other);



local text = "You are close to passing the test, keep up the good work.";


if **Faction** >= Amiable and  **You turn in:** [A Small Gem](/item/1667)) then 


>**a wandering spirit says:** Oh, it is you, shaman! Good! You must hurry before it's too late. Go now to the Mountains they call Rathe and find them! They need your help quickly! They will know you when they see you and instruct you on how you can help, but you must hurry!


* __Faction:__ [Truespirit](/faction/404) (100)


 **You receive:** 0 (+1000 exp)

elseif **Faction** >= Amiable +100 and  **You turn in:** [Marrs Promise](/item/1675), [Woe](/item/1676), [Envy](/item/1677)) then 


>*a wandering spirit nods somberly and takes the items. After a moment, he says, 'It is unfortunate that it came to this, but nothing else was to be done. Both paragons had lost sight of their virtures to protect the items given to them. The mere protection of these material belongings was not as important to Mithaniel Marr or Bertoxulous as it was that they act with righteousness in their minds and purpose in their hearts. You saw this and acted accordingly. For that, we will reward you with the three treasures made into one to ward off the falsehood of possession, the [Shield of Falsehood]. You have walked the path and now, as your final test, we must set you along one [last path].'*


* __Faction:__ [Truespirit](/faction/404) (100)


 **You receive:** 0 (+1000 exp)

elseif( **You turn in:** [Obsidian Pebble](/item/1669), [Marble Pebble](/item/1670)) then 


>**a wandering spirit says:** This is a sad day. You have failed and strayed from the path set before you. Please try to live as close to the spirits as you are able, though this is the closest you will ever get.


**a wandering spirit despawns.**

elseif( **You turn in:** [Obsidian Pebble](/item/1669)) then 


>**a wandering spirit says:** This is a sad day. You have failed and strayed from the path set before you. Please try to live as close to the spirits as you are able, though this is the closest you will ever get.


**a wandering spirit despawns.**

elseif( **You turn in:** [Marble Pebble](/item/1670)) then 


>**a wandering spirit says:** This is a sad day. You have failed and strayed from the path set before you. Please try to live as close to the spirits as you are able, though this is the closest you will ever get.

**This NPC *should* return incorrect items given.**



