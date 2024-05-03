# Jaled Dar-s shade
local SHOUTS = {

"Trakanon, my friend, you BETRAYED me!",

"Harla!  Phara!  It is cold here, and dark, so very dark.",

"Somebody is there, I can tell!  Listen to me!  We were WRONG, he must be awakened!",

"Zlandicar, I know you are here, you are always here!  Do not ignore me, you must listen....we must talk.",

"Release him..............release him.....release...ME!",
};
local nextShout = 1;



## On NPC Spawn

**Set a timer** named *zoneshout* for 2400 seconds

eq.set_timer("depop", 48 * 60 * 60 * 1000);




## Timer(s)


if ( e.timer == "zoneshout" ) then


if ( not e.self:IsEngaged() and SHOUTS[nextShout] ) then



e.self:Shout(SHOUTS[nextShout]);




nextShout = nextShout + 1;


if ( not SHOUTS[nextShout] ) then



nextShout = 1;


elseif ( e.timer == "depop" ) then


**Jaled Dar-s shade despawns.**
end



## Dialog

**You say:** `hail`



>**Jaled Dar-s shade says:** Mortal! You MUST aid me! I will have my revenge, and my rest!

**You say:** `aid you`



>**Jaled Dar-s shade says:** You must wake The Sleeper. He is our salvation, he will restore a new golden age to Norrath. It was a terrible mistake to subdue him, jealousy and envy led us to do it. I see all of this clearly now.

**You say:** `sleeper`



>**Jaled Dar-s shade says:** Kerafyrm, the best of us, what we should be. We imprisoned him in a timeless slumber aeons ago. I know how to release him, but I am no longer of the flesh, so I cannot do it myself. But you can accomplish this task!

**You say:** `task`



>**Jaled Dar-s shade says:** When the tomb was closed and the entry sealed, many dragons participated in the ceremony. They invested portions of their essence into the seal. The seal is part of them now. With the right talismans, I can show you how to make a key that will allow one to pass, as if they were of the First Brood. If you do not wish to do this for the good of all, perhaps you will be willing to do it for material riches. Priceless treasures are stored in the tomb, yours for the taking, once you are inside and have released The Sleeper.

**You say:** `talisman`



>**Jaled Dar-s shade says:** Sontalak, Lendiniara, Klandicar, Yelinak, and Zlandicar are all that are left alive of those who were involved in the sealing of the tomb. Each has a talisman. Bring me any one of these items, or a large enough piece from one of the talismans from a dead first brood, and I shall unlock its power, which will allow you entry into the tomb.

**You say:** `treasure`



>**Jaled Dar-s shade says:** Weapons, armor, tomes of great power, and more, are held inside. The barrier that keeps The Sleeper in his state of slumber also wards the treasure. You must first remove this barrier.

**You say:** `barrier`



>**Jaled Dar-s shade says:** Four dragons maintain the barrier around The Sleeper. These four dragons channel their energies into the barrier. For the barrier to drop, you must slay all four. This will be no easy task, for they are powerful and learned, the best and brightest of that era. But once this is done, The Sleeper shall awake, and the treasures there shall be yours for the taking. The Sleeper will travel to the Skyshrine to resume his rightful position among wurmkind.
end



## Turn-Ins





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1067.png" alt="" /> <a
                                href="/item/9296" data-url="9296" class="tooltip-link link">Shard of Hsagra's Talisman</a> or


 **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_510.png" alt="" /> <a
                                href="/item/27255" data-url="27255" class="tooltip-link link">Klandicar's Talisman</a> or


 **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_510.png" alt="" /> <a
                                href="/item/27256" data-url="27256" class="tooltip-link link">Sontalak's Talisman</a> or


 **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_510.png" alt="" /> <a
                                href="/item/27258" data-url="27258" class="tooltip-link link">Zlandicar's Talisman</a> or


 **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_510.png" alt="" /> <a
                                href="/item/27259" data-url="27259" class="tooltip-link link">Lendiniara's Talisman</a> or


 **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_510.png" alt="" /> <a
                                href="/item/27266" data-url="27266" class="tooltip-link link">Yelinak's Talisman</a>) then


>**Jaled Dar-s shade says:** Very well done. Here is how you unlock the entry. Seek out a great dragon statue in the Eastern Wastes, and use this key there. Not very different from how you entered my old domain, Veeshan's Peak, now, is it? Haha, yes, I know many things, even dead.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1080.png" alt="" /> <a
                                href="/item/27265" data-url="27265" class="tooltip-link link">Sleeper's Key</a> (+50000 exp)

 

**This NPC *should* return incorrect items given.**
