# Loremaster Sarl
## On NPC Spawn

if(**spawned NPC:**  [\#\#Loremaster Sarl](/npc/115000)) then


**Despawn NPC:**  [\#\#Loremaster Sarl](/npc/115000)
end

## Dialog

**You say:** `hail`



>**Loremaster Sarl says:** Ahhh, hello there. What can I do for you, Soandso

**You say:** `name.* slain`



>**Loremaster Sarl says:** The name of Dragon, you say? One that was slain? Hmmm, sounds interesting. Like I said, we've had little contact with Dragons, but I vaguely recall an ancient legend about a slain dragon and one of our people meeting. Follow me to the Library and we'll talk along the way.


e.self:CastToNPC():AssignWaypoints(31);

**You say:** `dragon`



>**Loremaster Sarl says:** Dragons, ye say? Well, you might just be in luck. I'm the resident Lore Keeper on the subject of dragons, though we don't know very much about them as a community. We've had very little contact with the majestic beasts. Only the Bravest of our kin have ever found the guts to stand their ground when facing a Dragon, let alone speak with them. What are you looking for exactly?

**You say:** `black`



>**Loremaster Sarl says:** Excellent, I know what we're lookin fer now.


**Spawn NPC:**  [\#\#Loremaster Sarl](/npc/115000) at this location.


**Loremaster Sarl despawns.**

## Arrive at Waypoint Script

if(e.self:GetGrid() == 31) then


if(e.wp == 10) then



>**Loremaster Sarl says:** There are only a few myths we've recorded havin to do with Dragons, many less legends. There's a story of an ancestor of the Dain ridin a 'Wurm' into battle against Giants. A Wurm be a lesser form of a Dragon, not able to use magic or fly, but still just as mean. There's another story, more recent, about a pair a Coldain that rampaged through the countryside along side a magical sea turtle, undoing evil and saving this and that. Heheh, more likely a drunken wive's tale.


elseif(e.wp == 18) then



>**Loremaster Sarl says:** 'Ye may not know this, but we didn't always make our home here in Thurgadin. Centuries ago we lived deep down in the ground, close to Brell. That was our first home after we became stranded on this chunk of ice. We lived there peacefully for a while, until the Giant kin found us. They drove us out, though we didn't leave without a fight. This statue coming up here is of a hero that sacrificed his life in that battle to bring a great cavern down on the heads of many o those giants.


elseif(e.wp == 25) then



>**Loremaster Sarl says:** I brung up our old home o Froststone because we had many books and tablets that were lost when we were forced to flee. We had a long history during our peaceful time there, much of it is lost to us now. Still, we were able to save a few slim volumes. I'm thinkin we may find yer answer in o those old recordings. We'll see...Ahhh, here we are. Remember to keep yer voice down, it is a library ye know.


elseif(e.wp == 27) then



>**Loremaster Sarl says:** If we Coldain just work together, obeying Brell's teachings, nothing can stop us from overcoming our enemies. Even the Kromrif will fall before us if we are undivided. It is only when we stray from our fundamental knowledge that we are vulnerable.


elseif(e.wp == 29) then



e.self:SetAppearance(4);


elseif(e.wp == 33) then



>**Loremaster Sarl says:** Ok, here we are. Let me see.' Sarl runs a finger along the book labels searching for a particular volume...


elseif(e.wp == 34) then



>**Loremaster Sarl says:** Do ye know anythin about this dragon? Ye need his name right? Some o these older ones are organized in strange ways. I love me fore fathers, but they made some funny kinda rules. Do you know what color this dragon was?

end