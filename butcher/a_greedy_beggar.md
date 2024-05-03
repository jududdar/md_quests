# a greedy beggar
local followtarget;
local skip;



## On NPC Spawn

followtarget = nil;

skip = 0;


## Dialog

**You say:** `hail`



>**a greedy beggar says:** Hello there Soandso. I don't suppose you can spare some coins? I'm just a poor halfling that is far away from home. I can't afford anything to eat or drink. Anything you can offer me will be of help.


if(followtarget == nil) then



followtarget = e.other:GetID();



e.self:SetAppearance(0); 



**Set a timer** named *follow* for 3 seconds

end



## Timer(s)

if(e.timer == "follow" and eq.get_entity_list():GetClientByID(followtarget).valid and skip == 0) then


eq.follow(followtarget); 

else


if(skip == 0) then



skip = 1;



eq.stop_follow();



e.self:SetAppearance(3); 


elseif(skip == 1) then



skip = 0;



**Stop timer** named *follow*



followtarget = nil;



e.self:MoveTo(2407,1482,0,168,true);

end



## Turn-Ins 





if(followtarget == nil or e.other:GetID() == followtarget) then


>**a greedy beggar says:** Oh thank you. You are too kind to this poor halfling. Do you have anything else to give me?


e.self:SetAppearance(0); 


followtarget = e.other:GetID();


**Set a timer** named *follow* for 3 seconds

else


**This NPC *should* return incorrect items given.**

end
