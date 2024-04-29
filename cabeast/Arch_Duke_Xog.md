# Arch Duke Xog
## Dialog

**You say:** `hail`



>**Arch Duke Xog says:** These are the sacred unholy grounds of the Crusaders of Greenmist and the Scaled Mystics. If you do not belong to us, you must leave this temple at once or learn great suffering in the name of Cazic-Thule.

**You say:** `greenmist`





>*Arch Duke Xog appears surprised at your words. 'You know of Greenmist? The Unholy Khukri of Rile? We once had knowledge of this weapon, but when our great cities were destroyed in 1056 A.G., so, too, were all the great libraries. We lost all records. An explorer named [Argest] claimed to have found one library still intact. Pure babble.'*

**You say:** `who is argest`






>**Arch Duke Xog says:** Once a Lord of Pain, Argest is now a great explorer. No lizard has seen more of Kunark than he. He returned one season ago to tell tales of an [ancient library]. He said that he believed that there he would find a tome which would reveal the location of the ancient crusader weapon, Greenmist.

**You say:** `ancient`



>**Arch Duke Xog says:** There are many ancient libraries yet to be discovered. Our once great cities have been decimated, if not by our foes, then by nature itself. Within the outlands are many ruins which have yet to reveal themselves. We look forward to the discovery of these ruins by such explorers as Lord Argest the Great. If only we knew [where] he was...

**You say:** `where is argest`






>*Arch Duke Xog becomes despondent at your question. 'Alas, our chance of locating Greenmist is lost as long as Argest remains missing. Reports have come in from the Legion's deep range patrols that he may be in the Frontier Mountain range. At least, that is where the patrol captain found Argest's walking staff. He might have been captured, killed or even digested!!'*

**You say:** `strange iksar`



>**Arch Duke Xog says:** Yes, he was dressed in rags and hadn't eaten in days. He rambled on about seemingly nothing, obviously he had lost his mind at some point. The guards brought him in because he told them he had valuable information concerning a captured Crusader. According to the mad man, our missing knight was captured by a group of cultists that follow a false god. The cultists intend on converting him apparently. Your [test] will concern Geanik.

**You say:** `test`



>**Arch Duke Xog says:** Learning Righteousness is learning to listen to one's own heart. At all times our Lord of Fear speaks to us. Our heart is through which he speaks. If we are pure in action and undistracted in mind we can hear the very words of our Father. Your test will be to find our lost Crusader. When you find him you must listen, and act based on what you hear. If your actions are Righteous, I will give you my reference. Bring me proof of your action and two sapphires.
end

## Turn-Ins



local text1 = "Where is the rest, maggot?! I said the traitor's head and two star rubies!";

local text2 = "Where is the rest, maggot?! I said proof of your action and two sapphires!";


local text3 = "A true crusader would have brought to me what I requested. The Hero Khukri and the Tome of Vok Na Zov.";




if( **You turn in:** [Guild Summons](/item/18205)) then 






>**Arch Duke Xog says:** Welcome into our brotherhood. Know you that our way is the way of pain. Do as we say and you shall climb the rungs of knighthood. Listen well to the Lords of Pain within this temple and follow the words of the hierophants, for Cazic-Thule speaks to us through them. Take this khukri. It is the chosen weapon of the Crusaders and can deliver great pain unto our foes. Go now and learn our ways. Seek out Lord Gikzic.


* __Faction:__ [Crusaders of Greenmist](/faction/442) (100)



* __Faction:__ [Legion of Cabilis](/faction/441) (25)






 **You receive:**  [Pawn's Khukri](/item/5120) (+200 exp)


elseif **Faction** >= Amiable and  **You turn in:** [Stupendous Tome](/item/18051), [Hero's Khukri](/item/5126)) then 


>**Arch Duke Xog says:** A legible tome of the scrolls of Vok Na Zov! What a find this is!! May the unholy curses of Cazic flow through you. Please accept the weapon of a Lord of Pain. To abandon it is to abandon our ways and earn yourself the hatred of our order.


* __Faction:__ [Crusaders of Greenmist](/faction/442) (10)


* __Faction:__ [Legion of Cabilis](/faction/441) (2)


 **You receive:**  [Lord of Pain's Khukri](/item/5128) (+25000 exp)

elseif( **You turn in:** [Illegible Note: Bracer](/item/14791)) then 






>*Arch Duke Xog  takes the note and glances at it briefly then lets out a heavy sigh and stares out over the city for several minutes. Finally he says quietly, 'Several months ago we lost contact with one of our crusaders. His name is, or was, Geanik. The last we heard from him he was furthering our cause against the loathsome Goblins that reside in Warsliks Wood. Just recently we were visited by a [strange Iksar].'*

elseif( **You turn in:** [Traitors Heart](/item/14807), [Sapphire](/item/10034), [Sapphire](/item/10034)) then


>**Arch Duke Xog says:** Thanks for resolving this issue. Here is your reward


 **You receive:**  [Xog's Reference: Bracer](/item/14808) (+10000 exp)

elseif( **You turn in:** [Illegible Note: Gauntlets](/item/14792)) then 


>*Arch Duke Xog  takes the note without even a glance in your direction and begins reading. After a long silence, he lets his arms drop to his sides and says quietly, 'We kill, Soandso. That is our job, our duty in life. Our targets are chosen for us. We merely listen. Right now I am being told there is a traitor not far from here, near the ocean. Go to him andhis life. Bring me his head, and two star rubies. As you do this, try hard to listen to our Lord's instruction. If you hear even a whisper, you will know more righteousness than most of this city.'*

elseif( **You turn in:** [Head of Blackhand](/item/14806), [Star Ruby](/item/10032), [Star Ruby](/item/10032)) then


>**Arch Duke Xog says:** Well done, Soandso.


 **You receive:**  [Xog's Reference: Gauntlet](/item/14809) (+10000 exp)

elseif( **You turn in:** [Greenmist Icon](/item/14814)) then


>*Arch Duke Xog takes the icon and stares at it. His face twists into a look of disdain and he suddenly throws the icon off the balcony. It lands in the water some distance away. Without even a glance at you he says in disgust, 'You're an idiot, Soandso. You fit your profession well. Leave my sight.'*


* __Faction:__ [Crusaders of Greenmist](/faction/442) (-25)


* __Faction:__ [Legion of Cabilis](/faction/441) (-6)

**This NPC *should* return incorrect items given.**





