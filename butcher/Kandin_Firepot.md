# Kandin Firepot
## Dialog

**You say:** `hail`



>**Kandin Firepot says:** Hello, there! Don't have time to talk. I'm workin', workin', workin'! Careful! Don't slip in the oil!

**You say:** `what oil`



if **Faction** >= Apprehensive +40 then



>**Kandin Firepot says:** Ah the oil! I recently sent a specially crafted golem to explore through a huge portal to another plane. It's instructions were to collect special oil that I suspect existed in the plane. What I think is the golem broke down. This looks like a good task for one like you. Go see what's wrong with the golem. Here is spare gears of mine incase it's broken. Be careful though, if you put it in wrong it could explode or worse!



**You receive:**  [Golem Sprocket](/item/14319)


else



**Kandin Firepot says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!

end

## Turn-Ins





if **You turn in:** [Note from Arantir](/item/18169)


>**Kandin Firepot says:** Brother! I have one of those. He's great, but he's dead. His name was Gabstik and he was a really powerful wizard. I still have one of his greatest possesions! You look like you could use it. I've added another thing to my shopping list. I require a dry brittle skin that I can mold or a rare oil found in the planes that I can soak the fuse in. Get me one of these things and I'll trade it for my bother's stick.


* __Faction:__ [Truespirit](/faction/404) (10)

elseif **You turn in:** [Green Oil](/item/14349)


if **Faction** >= Apprehensive +40 then



>**Kandin Firepot says:** Oh wow! You found the oil! Where is the golem? You didn't hurt him did you? I am very fond of him. Anyways, here is your reward a note and staff to give to that guy you were asking me about.



* __Faction:__ [Truespirit](/faction/404) (10)



 **You receive:**  [Staff of Gabstik](/item/14339) 



 **You receive:**  [Note to Arantir](/item/18168) 


else



>**Kandin Firepot says:** I have no need for this item Soandso. You can have it back.



 **You receive:**  [Green Oil](/item/14349) 


**This NPC *should* return incorrect items given.**





