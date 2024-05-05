# Tani N\`Mar



[Tani N\`Mar](/npc/42000) is a level 45 Dark Elf GM Rogue that spawns in [Neriak - 3rd Gate](/zone/42).





## On NPC Spawn

**Set a timer** named *pick_up* for 2 seconds


## Timer(s)

if ( e.timer == "pick_up" ) then




while ( e.self:CheckGround() ) do



>*Tani N-Mar picks up something from the ground.*




## Dialog

**You say:** `hail`



>**Tani N-Mar says:** Greetings!  You must be a stranger or [new to the Hall].  If you are a stranger. be warned that these halls are intended for the Ebon Mask only. If you are found to be a member of another house. you just may feel the sting of a blade in your back.

**You say:** `new to the hall`



if **Faction** >= Amiable then



>**Tani N-Mar says:** Then I am glad to make your acquaintance. Have you ever been to Freeport?  If not. how would you like to go?  It is a test of your cunning we wish.  Are you prepared to risk your young life?  Are you [ready to venture to Freeport]?


elseif **Faction** >= Indifferent then



>**Tani N-Mar says:** You have done nothing to upset the Ebon Mask, but there is much more which you must do before we do business.  Perhaps a task from Master Hekzin shall set things right.


else



>**Tani N-Mar says:** You are quite bold to approach a member of the Ebon Mask. Now be smart and run away.




**You say:** `venture to freeport`



if **Faction** >= Amiable then






>**Tani N-Mar says:** Find a way to the port of Freeport.  Seek out Giz Dinree.  She is usually near the shores at night.  She is your contact. Tell her you were [sent by Tani].  She will fill you in on your mission.  Good luck.  Do not waste time practicing your skills. Go as you are.


elseif **Faction** >= Indifferent then



>**Tani N-Mar says:** You have done nothing to upset the Ebon Mask, but there is much more which you must do before we do business.  Perhaps a task from Master Hekzin shall set things right.


else



>**Tani N-Mar says:** You are quite bold to approach a member of the Ebon Mask. Now be smart and run away.




**You say:** `book of souls`




>**Tani N-Mar says:** The Book of Souls chronicles all the lives Innoruuk has tainted over the years. It is in the care of the Maestro of Rancor. I can use this tome as a basis for my translation, if you return it and the note to me. An experienced practitioner in the art of non-detection should be able to snatch it from its resting place, don't you think, " .. e.other:Race() .. "?

**You say:** `note`




>**Tani N-Mar says:** Oh, you want that piece of paper Stanos was so hot after? Well it's mine now, though it looks like ogre scratch to me. You're not getting it, Stanos is not getting it, and Hanns is not getting it. It is MINE! Now, " .. e.other:Race() .. ", scamper off like the dog you are, before I decide I need more practice with these short swords!

**You say:** `stanos`




>**Tani N-Mar says:** Stanos? Hahahaha! That old fool crossed my path a few times in the past, but he is not able to trouble me now. If you see him, tell him Tani sends his..love. Hahahaha!
end



## Turn-Ins





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_983.png" alt="" /> <a
                                href="/item/13892" data-url="13892" class="tooltip-link link">Human Head</a>) then


>**Tani N-Mar says:** Good work! I knew you could prove your worth. Most waste time training. I do not reward those who waste my time. Please take this. It is from our horde, from countless robberies. I hope you can use it to advance yourself. Remember to always stay faithful to Neriak.


Your faction standing with [Ebon Mask](/faction/244) got better (<span class='text-success'>+20</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Wolves of the North](/faction/320) got worse (<span class='text-danger'>-5</span>)


Your faction standing with [Guardians of the Vale](/faction/263) got worse (<span class='text-danger'>-2</span>)


Your faction standing with [Carson McCabe](/faction/329) got worse (<span class='text-danger'>-5</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_596.png" alt="" /> <a
                                href="/item/5066" data-url="5066" class="tooltip-link link">Cinctured Whip</a> (+5000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 9 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**






