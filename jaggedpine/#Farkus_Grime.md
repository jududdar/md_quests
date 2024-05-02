# Farkus Grime
## On NPC Spawn

tellpause = 0;

already_tell = 0;
## Dialog

**You say:** `hail`



>**Farkus Grime says:** Hmm? What do you want?

**You say:** `diseased bear liver`



>*Farkus Grime clenches his teeth and speaks in a quiet but deadly tone, 'Keep your voice down you fool, mention of such a thing around here is dangerous! I'm always willing to help someone who shares the same... philosophy... as myself though. Are you [truly serious] about this?'*

**You say:** `truly serious`



>**Farkus Grime says:** Very well, follow me and we'll have a little chat then.


if(e.self:GetX() == 1830 and e.self:GetY() == 1316) then



eq.move_to(1390,1360,19,0,true);


elseif(e.self:GetX() == 1390 and e.self:GetY() == 1360 and already_tell == 0) then



already_tell = 1;



**Set a timer** named *Secrets* for 2 seconds

end

## Timer(s)

if(e.timer == "Secrets") then


**Set a timer** named *Secrets* for 7 seconds


tellpause = tellpause + 1;


if(tellpause == 1) then



>**Farkus Grime says:** I had not pegged you as one allied with the Plaguebringer, may his blessing once again spread across the land.


elseif(tellpause == 2) then



>**Farkus Grime says:** So you wish for me to defile one of these so-called 'sacred' bears for you? I'm not sure what vile ritual you would need this liver for but I'd be delighted to assist you.


elseif(tellpause == 3) then



>**Farkus Grime says:** However, before I do this thing for you there's something I need for you to do for me to show your loyalty. And to help me to settle an outstanding score of course.


elseif(tellpause == 4) then



>**Farkus Grime says:** I want you to assassinate a Qeynos guard by the name of Nash. He has been a thorn in our side for some time. Bring me his head and I shall defile one of these bears for you.


elseif(tellpause == 5) then



eq.move_to(1830,1316,-12,220,true);



**Stop timer** named *Secrets*



already_tell = 0;



tellpause = 0;

end

## Turn-Ins





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_982.png" alt="" /> <a
                                href="/item/8276" data-url="8276" class="tooltip-link link">Head of Guard Nash</a>) then 


>**Farkus Grime says:** You've done well, I see we are of a like mind. I'll lure the bear outside so you can do your work.


eq.start(41);

**This NPC *should* return incorrect items given.**

## Arrive at Waypoint Script

if(e.wp == 3) then


>*Farkus Grime holds a bit of food out to the bear cub, 'Want it?'*


**Signaled to:**  [a docile bear](/npc/181102)

elseif(e.wp == 4) then


>**Farkus Grime says:** Follow me then little bear

elseif(e.wp == 5) then


>*Farkus Grime gives the bear the tainted food.*

elseif(e.wp == 6) then


>**Farkus Grime says:** The diseased within this food acts very quickly.  The bear should be maddened by the illness shortly and his liver suitable for harvest.


**Signaled to:**  [a docile bear](/npc/181102)
end
