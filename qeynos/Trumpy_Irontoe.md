# Trumpy Irontoe


## Dialog

local fac = e.other:GetFaction(e.self);

**You say:** `hail`



>**Trumpy Irontoe says:** Heh? What's yer name? Soandso? Never heard of ya. Now quit breathin' on me and buy us some [drinks]!

**You say:** `drink`



>**Trumpy Irontoe says:** <BURP!> Yeah. Gimme a.. <BURP!> er.. honey mead.

**You say:** `dragon`



>**Trumpy Irontoe says:** What?  Dragon?  That was a joke, ya zombie!  Sheesh!   I miss [Kaladim]..

**You say:** `kaladim`



>**Trumpy Irontoe says:** Heh? Kaladim, you say? It's a long way from here, I tell you.. Home to us dwarves it is. I miss it sometimes though.. Its tough being a swashbuckling dwarf with my rugged good looks when all the other dwarves are so envious. Cripes, Soandso... You got me all misty-eyed now.. <BURP> Peh! Buy me a honey mead, will ya?

**You say:** `skippy`



>**Trumpy Irontoe says:** Skippy? You mean that fish farmer? Heh heh heh. What a moron. And his brother [Beren] has the nerve to actually threaten ME!?.. Burp.. Bah. Remind me to tell [Kane] about that steaming pile of gnoll dung.

**You say:** `beren`



if **Faction** >= Apprehensive then



>**Trumpy Irontoe says:** Don't even mention that weakling's name. He.. burp.. Keeps threatening me. ME! Trumpy IRONTOE!!! Peh! That useless son of a goblin had better wise up and realize that in this burg if you ain't with [Kane], you are against him. And if you are against him.. burp.. you ain't nothing but a corpse.




else



>**Trumpy Irontoe says:** Heh.  Well, well, what have we here?  Seems you don't want to be part of Kane's new Qeynos huh?  Well...  You keep bugging me and the only thing you'll be a part of is the bottom of my boot!



**You say:** `kane`



if **Faction** >= Apprehensive then



>**Trumpy Irontoe says:** Ah.. burp.. that piece of cr.. eh? Oh its you.. Kane runs this burg.. or at least he will.. if [Sragg] can get his act together.




else



>**Trumpy Irontoe says:** Heh.  Well, well, what have we here?  Seems you don't want to be part of Kane's new Qeynos huh?  Well...  You keep bugging me and the only thing you'll be a part of is the bottom of my boot!


**You say:** `sragg`



if **Faction** >= Apprehensive then



>**Trumpy Irontoe says:** Where did you hear that name?!? Not from me! I didn't say nothing about Sragg or those Bloodsabers or their dang temple in the sewers! Get away from me ya hobgoblins! I don't wants no trouble!


else



>**Trumpy Irontoe says:** Heh.  Well, well, what have we here?  Seems you don't want to be part of Kane's new Qeynos huh?  Well...  You keep bugging me and the only thing you'll be a part of is the bottom of my boot!


else


>**Trumpy Irontoe says:** You had better just be... <BURP!>...  minding your own business if you know what is good for you.  Gnollbreath.  We Irontoes are a proud and strong bunch of dwarves from [Kaladim].  We crush weaklings like you.  <BURP!>
end



## Turn-Ins




local text = "Beh! Thanks, Skippy. Why don't ya buy yourself one? And.. <gulp>.. <burp>.. get me another!";



if **Faction** >= Dubious and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_702.png" alt="" /> <a
                                href="/item/13033" data-url="13033" class="tooltip-link link">Honey Mead</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_702.png" alt="" /> <a
                                href="/item/13033" data-url="13033" class="tooltip-link link">Honey Mead</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_702.png" alt="" /> <a
                                href="/item/13033" data-url="13033" class="tooltip-link link">Honey Mead</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_702.png" alt="" /> <a
                                href="/item/13033" data-url="13033" class="tooltip-link link">Honey Mead</a>) then


>**Trumpy Irontoe says:** BWAH hah hah! I knew you wasn't the loser you.. <gulp>.. <gulp>.. appear to be! I will have to tell [Kane].. <burp>.. all about you. Maybe get you in the gang!





Your faction standing with [Circle of Unseen Hands](/faction/223) got better (<span class='text-success'>+1</span>)


Your faction standing with [Merchants of Qeynos](/faction/291) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Corrupt Qeynos Guards](/faction/230) got better (<span class='text-success'>+1</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Kane Bayle](/faction/273) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:** 0 (+200 exp)

 

**This NPC *should* return incorrect items given.**
