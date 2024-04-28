# Warder Elwysaie


## Dialog

**You say:** `Hail`



if(e.other:Race() == "Dark Elf" or e.other:Race() == "Iksar" or e.other:Race() == "Troll" or e.other:Race() == "Ogre" or e.other:Class() == "Shadowknight" or e.other:Class() == "Necromancer") then



e.self:DoAnim(48);



e.self:Emote("stands tall, eyeing Soandso before her with neither disdain nor favor as she delivers a proper nod of greetings. 'Greetings to you, dark one. You stand within the district of Tanaan 


else



e.self:DoAnim(70);



>*Warder Elwysaie gives a formal bow at the waist in an almost regal greeting toward Soandso. 'Good day to you , traveler, and may Tunare's gracious hand guide your fate with freedom.  I am Warder Elwysaie, a soldier and guardian of nature in my life upon Norrath. Here, I am a soldier still but one of faith and knowledge. I set my blades down long ago, and though I understand most gravely that the shadow of corruption that threatens this delicate and necessary balance still looms most deadly over us, I was no longer able to be nature's wrath adn vengeance. It was then that I heard the calling of New Tanaan and eagerly I followed to this place of neutrality. In the recent times where Norrath's travelers who have yet to appeal to the Plane of Knowledge grace us as visitors and students of our ways, I have volunteered my former status and knowledge to any young ranger who may need guidance in their skills as they grow in power.*

end

## Turn-Ins



local count =  **You turn in:**  { [Thorny Vine Helm](/item/4891),  [Thorny Vine Chestplate](/item/4892),  [Thorny Vine Vambraces](/item/4893),  [Thorny Vine Bracer](/item/4894),  [Thorny Vine Gauntlets](/item/4895),  [Thorny Vine Greaves](/item/4896),  [Thorny Vine Boots](/item/4897)}

if(count > 0) then


repeat



>**Warder Elwysaie says:** Thank you, Soandso.



 **You receive:** eq.ChooseRandom( [Peridot](/item/10028), 10037, 22503, 15981) (+300000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**
