# Guard Dinamin



[Guard Dinamin](/npc/60053) is a level 38 Dwarf Warrior that spawns in [South Kaladim](/zone/60).



## Dialog

**You say:** `armor`



>**Guard Dinamin says:** If armor it is you're seeking, then go no further than Everhot Forge in North Kaladim.  The Everhots are the finest smiths to have walked Norrath.  Many have come from far and wide to be trained in their skills.

**You say:** `warrior guild`



>**Guard Dinamin says:** The warriors of Kaladim are the Stormguard.  The fiercest warriors on all Norrath.  Stormguard Hall is in South Kaladim and includes the white marble arena.

**You say:** `supplies`



>**Guard Dinamin says:** If you are looking for supplies, I can suggest Gurtha's Wares near the bridge in South Kaladim.

**You say:** `bank`



>**Guard Dinamin says:** You can find Ratsbone Treasury next to the mine entrance in North Kaladim.

**You say:** `stormguard`



>**Guard Dinamin says:** In South Kaladim you will find the Stormguard, the warrior guild.  They train on the arena grounds.

**You say:** `rogue guild`



>**Guard Dinamin says:** I have heard rumors of a rogue guild in Kaladim, but have seen none.

**You say:** `healer`



>**Guard Dinamin says:** If you are injured, I suggest you rush to North Kaladim and visit the Underfoot Cathedral.  Just go through tunnel behind Ratsbone Treasury.

**You say:** `mine`



>**Guard Dinamin says:** The mines of Kaladim can be entered in North Kaladim.  The opening is adjacent to the Ratsbone Treasury.

**You say:** `paladin guild`



>**Guard Dinamin says:** Our Paladins of Underfoot can be found to the rear of the Cathedral of Underfoot in North Kaladim.

**You say:** `cathedral`



>**Guard Dinamin says:** The Cathedral of Underfoot is the home of the clerics and paladins of Kaladim.  It is found in North Kaladim through a tunnel behind Ratsbone Treasury.

**You say:** `kiln`



>**Guard Dinamin says:** I know of one public kiln and pottery wheel and they are near the bridge in South Kaladim.

**You say:** `oven`



>**Guard Dinamin says:** There is a public oven in North Kaladim at Greybloom Farm.

**You say:** `leather`



>**Guard Dinamin says:** If you seek leather goods, stop by Tanned Assets in South Kaladim.  It is near the arena.

**You say:** `what.* bloodforge`



>**Guard Dinamin says:** The Bloodforge Brigade was created to take the place of the now defunct Irontoe Brigade.  I hear they are a much stronger force to reckon with.
end



## Arrive at Waypoint Script

if(e.wp == 6) then


e.self:DoAnim(36); 

elseif(e.wp == 21) then


e.self:DoAnim(36); 
end





