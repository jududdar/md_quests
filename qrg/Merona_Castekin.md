# Merona Castekin
## Dialog

**You say:** `hail`



>**Merona Castekin says:** Oh, hello! Welcome to Surefall Glade. Are you planning a trip to Qeynos? If you are, I could use some help finding my [brother].

**You say:** `brother`



if **Faction** >= Amiable then 



>**Merona Castekin says:** My brother Ronn went to Qeynos several days ago for supplies. He was just going to Sneed's and back. But he hasn't been seen since. I can't leave the Glade because the Sabertooths could attack at any minute. Could you please find out what happened to my brother? Ask Sneed about [Ronn Castekin].


elseif **Faction** >= Indifferent then



>**Merona Castekin says:** Well, I, and the Protectors of Jaggedpine, have noticed your helpful deeds so far...  just keep up the good work, and you will soon be trusted enough to handle such important matters.




else



>**Merona Castekin says:** You dare show your face around here, as bad as your reputation is with the Protectors of Jaggedpine? Begone, enemy of the forest!




**You say:** `leader`



>**Merona Castekin says:** The land of Surefall Glade is ruled by no single hand other than Tunare, but if guidance is what you seek, I would suggest you speak with Te\`Anara.  She is the head of the Jaggedpine Treefolk.  Otherwise, you could speak with Hager Sureshot of the Protectors of the Pine.

**You say:** `poacher`



>**Merona Castekin says:** Poachers have been plaguing our land.  We do our best to stop them.  If you wish to join the fight, seek the masters of the Protectors of the Pine.

**You say:** `mammoth`



>**Merona Castekin says:** That information is best kept secret.

**You say:** `druid guild`



>**Merona Castekin says:** The Jaggedpine Treefolk are the local druids.  The masters can be found here within the great tree.

**You say:** `forge`



>**Merona Castekin says:** We have nothing like that here in Surefall Glade.  You must venture to Qeynos.

**You say:** `armor`



>**Merona Castekin says:** Oftentimes you can find a traveling merchant in one of the nearby houses.  Other than that you would have to travel to Qeynos.

**You say:** `qeynos`



>**Merona Castekin says:** The great city of Qeynos can be found by walking along the path outside of Surefall Glade.  Many of our rangers and druids serve alongside the Qeynos Guard when the need arises.

**You say:** `bank`



>**Merona Castekin says:** There is no need for a vault among our people.  You could try the Qeynos Hold in Qeynos.

**You say:** `talym`



>**Merona Castekin says:** Talym Shoontar is a wanted man.  He is a very infamous poacher.  Hager Sureshot has placed a bounty upon his head.

**You say:** `chanda`



>**Merona Castekin says:** The entire Miller family are nothing more than scum.  It is they who entice poachers to continue with their slaughter so they can profit from the skins of the wildlife.


**You say:** `tunarbos`



>**Merona Castekin says:** Long ago, centuries before the Combine Era even, there grew a great tree upon Norrath.  It stretched to the stars and was as wide as the span of Erud's Crossing.  From the roots of this tree sprung all the woodlands of Norrath.  An unknown force struck it down.  Some say it was the great dragon, Veeshan!  Whatever the force, the Great Tunarbos was shattered.  Lost forever.  Now the wood chips lie scattered across the face of Norrath.  To hold a shard of the Great Tunarbos is to hold the hand of Tunare.
end

## Turn-Ins




if **Faction** >= Amiable and  **You turn in:** [Torn Parchment](/item/18014)


>**Merona Castekin says:** Oh Tunare why!?!? Those foul Bloodsabers will pay for my brother's death!! Here. You have given us valuable information about a new threat to our homes. Take this a token of our appreciation.


* __Faction:__ [Protectors of Pine](/faction/302) (5)


* __Faction:__ [Jaggedpine Treefolk](/faction/272) (1)


* __Faction:__ [Sabertooths of Blackburrow](/faction/306) (-1)


* __Faction:__ [Guards of Qeynos](/faction/262) (1)


 **You receive:** eq.ChooseRandom( [Band of Tunare](/item/13184), [Ring of Pine](/item/13185), [Water Flask](/item/13006), [Ration](/item/13007), [Hunting Bow](/item/8011), [Large Lantern](/item/13004), [Loaf of Bread](/item/13015), [Bandages](/item/13009)) (+1000 exp)

**This NPC *should* return incorrect items given.**
;