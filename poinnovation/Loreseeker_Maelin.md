# Loreseeker Maelin



[Loreseeker Maelin](/npc/206209) is a level 75 Gnome Wizard that spawns in [Plane of Innovation](/zone/206).



## Dialog

local qglobals = eq.get_qglobals(e.other);



if ( qglobals.zebuxoruk == "2" and **You possess item:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1327.png" alt="" /> <a
                                href="/item/29165" data-url="29165" class="tooltip-link link">Quintessence of Elements</a> x 1




**You say:** `hail`




>*Loreseeker Maelin fidgets about with excitement, 'So here you are, this is quite impressive.  I cannot wait to see the results of this impressive machine!  I have coordinated with the clockworks here that have not gone mad.  We have set the machine to tear a point of time open that should be equal to that based on the cipher and history that we have [researched].'*






**You say:** `researched`




>**Loreseeker Maelin says:** Based on the findings from the information that you brought back to me I have determined the exact time to open.  I believe the machine will work.  Please step up and activate the machine!  Once you have formed a bond with the Plane of Time you will be able to access the Plane again through the Plane of Tranquility.  They have built a portal there, but no one was able to become attuned to that plane, until you that is.  Good luck!

end



## On NPC Spawn

**Set a timer** named *depop* for 900 seconds


## Timer(s)

**Loreseeker Maelin despawns.**