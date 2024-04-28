# Jras Solsier
## Dialog

**You say:** `hail`



>**Jras Solsier says:** Welcome to the Temple of Divine Light.  We are the Peacekeepers. followers of Quellious.  If you are a paladin of this temple. you can assist us by showing a desire to [protect the peace].

**You say:** `protect the peace`



if **Faction** >= Amiable then 



**You say:** `protect the peace`





>**Jras Solsier says:** It was a fine decision. We are in need of your services.  It seems there is a disturbance in Toxxulia Forest.  There are poachers from other nations who have sought to cause turbulence among the creatures there.  Will you help us [catch the poachers] or are you skeptical about this mission?



**You say:** `catch the poachers`







>**Jras Solsier says:** The infidels are in Toxxulia Forest. They have begun hunting the kobolds. We have no love of the kobolds. but cannot allow the lands of Odus to be overrun by outsiders. The ways of tranquility are balanced with harmony. We will not allow chaos to take hold of our land.  Go and find these poachers. Bring me their heads!!




elseif **Faction** >= Indifferent then




>**Jras Solsier says:** You have not done much to upset the Peacekeepers of this temple, but we must ask you to prove yourself to us before we may discuss things such as this.


else




>**Jras Solsier says:** Leave my sight at once! You are no friend to the Peacekeepers of the Temple of Divine Light.


end

## Turn-Ins




if **Faction** >= Amiable and  **You turn in:** [Poacher's Head](/item/13825)


>**Jras Solsier says:** You have served us well. The harmony of the forest shall be preserved. I have word that theses infidels were all working for one man. Find me evidence pertaining to this man. Surely one of these poachers has something which could aid in finding this man. We must stop him to stop the poachers. Go in peace.





* __Faction:__ [Peace Keepers](/faction/298) (5)


* __Faction:__ [High Council of Erudin](/faction/266) (1)


* __Faction:__ [Heretics](/faction/265) (-1)


 **You receive:** eq.ChooseRandom( [Copper Band](/item/10004), [Small Lantern](/item/13003), [Malachite](/item/10015), [Rusty Spear](/item/7009)) (+3000 exp)

elseif **Faction** >= Amiable and  **You turn in:** [Barbarian Head](/item/13913)


>**Jras Solsier says:** It is done! Quellious will look favorably upon our church and we will look favorably upon you. Go in peace.





* __Faction:__ [Peace Keepers](/faction/298) (10)


* __Faction:__ [High Council of Erudin](/faction/266) (2)


* __Faction:__ [Heretics](/faction/265) (-2)


 **You receive:** eq.ChooseRandom( [Spell: Courage](/item/15202), [Spell: Holy Armor](/item/15011)) (+5000 exp)

**This NPC *should* return incorrect items given.**
;

