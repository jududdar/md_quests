# Korrigain


## Dialog

**You say:** `hail`



>**Korrigain says:** Who dares disturb my rest? If ye be a friend of the mighty Coldain, then show me proof and I shall tell you of my plight. If not, then be on your way.
end

## Turn-Ins





if( **You turn in:** [Obsidian Coldain Insignia Ring](/item/30268)) then


>**Korrigain says:** Many seasons ago I stood here in life with my comrades, the best warriors Thurgadin had to offer. Along with our faithful wolven army we were poised to eliminate the Kromrif presence in the region. Somehow, the enemy was made aware of our plans and just before our attack, a group of Ry'Gorr oracles charmed our wolves, forcing them to tear down their own masters. We were caught by surprise and died a savage death.


eq.get_entity_list():GetMobByNpcTypeID(116534):CastToNPC():AssignWaypoints(16);


 **You receive:**  [Obsidian Coldain Insignia Ring](/item/30268) 

**This NPC *should* return incorrect items given.**

end