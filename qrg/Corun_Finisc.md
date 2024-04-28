# Corun Finisc
## Dialog

**You say:** `hail`



>**Corun Finisc says:** Hello. My name is Corun Finisc and I am one of the Jaggedpine Treefolk. It is our divine responsibility to watch over and protect Surefall Glade and its [inhabitants] from those who seek to [destroy] them.

**You say:** `inhabitants`



>**Corun Finisc says:** The bears of Surefall Glade are our brothers. We are all children of [Tunare]. We would gladly die in their defense.

**You say:** `tunare`



>**Corun Finisc says:** Tunare is the Mother of All. It is though Her will that we protect this land and its many creatures.

**You say:** `destroy`



>**Corun Finisc says:** Poachers in seach of bear skins and [gnolls] who attack us unprovoked. We are doing all we can to stop them. May [Tunare] give me the strength needed to smite them dead with my [crook].

**You say:** `crook`



if **Faction** >= Amiable then 



>**Corun Finisc says:** My crook? The Jaggedpine crook is an enchanted weapon of the Jaggedpine Treefolk. The [Sabertooths] take great pleasure in destroying the crooks of any Treefolk they manage to slay. If you were to recover the pieces of a broken crook, I would gladly mend it for you.


elseif **Faction** >= Indifferent then



>**Corun Finisc says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Corun Finisc says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `gnolls`



>**Corun Finisc says:** The Sabertooths are a vicious band of gnolls who live in Blackburrow, to the east of Surefall Glade. They constantly attack us when we only seek to share this land with them. They also send many patrols out into the Qeynos Hills to the south. We have even seen a Sabertooth skulking about in the caves behind Grizzly Falls. There is a [reward] for his hide.

**You say:** `reward`



if **Faction** >= Amiable then 



>**Corun Finisc says:** Yes. We are offering a small reward for slaying the skulking gnoll in the bear caves. Bring me his paw to claim your bounty. The Jaggedpine Treefolk remember well those who aid their cause.


elseif **Faction** >= Indifferent then



>**Corun Finisc says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Corun Finisc says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `sabertooths`



>**Corun Finisc says:** The gnolls of Blackburrow are called Sabertooths. They have been seen in force on a regular basis. They are surely up to something.



**You say:** `leader`



>**Corun Finisc says:** The land of Surefall Glade is ruled by no single hand other than Tunare, but if guidance is what you seek, I would suggest you speak with Te\`Anara.  She is the head of the Jaggedpine Treefolk.  Otherwise, you could speak with Hager Sureshot of the Protectors of the Pine.

**You say:** `poacher`



>**Corun Finisc says:** Poachers have been plaguing our land.  We do our best to stop them.  If you wish to join the fight, seek the masters of the Protectors of the Pine.

**You say:** `mammoth`



>**Corun Finisc says:** That information is best kept secret.

**You say:** `druid guild`



>**Corun Finisc says:** The Jaggedpine Treefolk are the local druids.  The masters can be found here within the great tree.

**You say:** `forge`



>**Corun Finisc says:** We have nothing like that here in Surefall Glade.  You must venture to Qeynos.

**You say:** `armor`



>**Corun Finisc says:** Oftentimes you can find a traveling merchant in one of the nearby houses.  Other than that you would have to travel to Qeynos.

**You say:** `qeynos`



>**Corun Finisc says:** The great city of Qeynos can be found by walking along the path outside of Surefall Glade.  Many of our rangers and druids serve alongside the Qeynos Guard when the need arises.

**You say:** `bank`



>**Corun Finisc says:** There is no need for a vault among our people.  You could try the Qeynos Hold in Qeynos.

**You say:** `talym`



>**Corun Finisc says:** Talym Shoontar is a wanted man.  He is a very infamous poacher.  Hager Sureshot has placed a bounty upon his head.

**You say:** `chanda`



>**Corun Finisc says:** The entire Miller family are nothing more than scum.  It is they who entice poachers to continue with their slaughter so they can profit from the skins of the wildlife.


**You say:** `tunarbos`



>**Corun Finisc says:** Long ago, centuries before the Combine Era even, there grew a great tree upon Norrath.  It stretched to the stars and was as wide as the span of Erud's Crossing.  From the roots of this tree sprung all the woodlands of Norrath.  An unknown force struck it down.  Some say it was the great dragon, Veeshan!  Whatever the force, the Great Tunarbos was shattered.  Lost forever.  Now the wood chips lie scattered across the face of Norrath.  To hold a shard of the Great Tunarbos is to hold the hand of Tunare.
end

## Turn-Ins



local text = "Look what you have found! It is tragic to know that for every broken crook that is recovered, one of the Treefolk has lost his life. Those gnolls will pay some day. If you have the other half of the crook I will repair it for you.";


if **Faction** >= Amiable and  **You turn in:** [Gnoll Paw](/item/13700)


>**Corun Finisc says:** Thank you for tracking down the filthy little poacher. Take this as your reward.


* __Faction:__ [Jaggedpine Treefolk](/faction/272) (10)


* __Faction:__ [Protectors of Pine](/faction/302) (2)


* __Faction:__ [QRG Protected Animals](/faction/343) (1)


* __Faction:__ [Unkempt Druids](/faction/324) (-2)


* __Faction:__ [Guards of Qeynos](/faction/262) (1)


 **You receive:** None 

elseif **Faction** >= Amiable and  **You turn in:** [Bottom of Broken Staff](/item/13231), [Top of Broken Staff](/item/13232)


>**Corun Finisc says:** Excellent! Here is a Jaggedpine Crook of your own. Please use it only to defend yourself and never to attack one of Tunare's creatures. You will find that while wielding the crook, Tunare grants you a boon of strength and the power to smite enemies who would otherwise be impervious to physical attacks.


* __Faction:__ [Jaggedpine Treefolk](/faction/272) (10)


* __Faction:__ [Protectors of Pine](/faction/302) (2)


* __Faction:__ [QRG Protected Animals](/faction/343) (1)


* __Faction:__ [Unkempt Druids](/faction/324) (-2)


* __Faction:__ [Guards of Qeynos](/faction/262) (1)


 **You receive:**  [Jaggedpine Crook](/item/13230) (+1500 exp)

**This NPC *should* return incorrect items given.**

## Arrive at Waypoint Script

if(e.wp == 3 or e.wp == 18 or e.wp == 29) then


**Corun Finisc shouts:** <span class="text-danger">Heed the wishes of Tunare and leave the bears of Surefall Glade undisturbed!</span>

elseif(e.wp == 11) then


>**Corun Finisc says:** By the will of Tunare, I serve this glade until I become one with it.
end
