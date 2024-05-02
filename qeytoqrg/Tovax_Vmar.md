# Tovax Vmar
## Dialog

**You say:** `hail`



if **Faction** >= Apprehensive then



>**Tovax Vmar says:** What?  Who the heck are you and how do you know my name?!  Never mind...  Just leave me alone!



else



**Tovax Vmar says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

>Oh look, a talking lump of refuse.  How novel!

end

## On NPC Spawn

e.self:SetRunning(true);
## Arrive at Waypoint Script

local ZoneTime = eq.get_zone_time()["zone_hour"];

if(e.self:GetGrid() == 13) then


if(e.wp > 0 and e.wp < 3) then



e.self:SetRunning(false);


elseif( e.wp == 3) then



e.self:SetRunning(true);



if(ZoneTime > 18 and ZoneTime < 24) then




e.self:RemoveWaypoints();




e.self:AssignWaypoints(math.random(21,25));




e.self:SetRunning(false);



elseif(ZoneTime > 6 or math.random(100) < 20) then




**Tovax Vmar despawns.**




elseif(e.self:GetGrid() > 20 and e.self:GetGrid() < 26) then 


if(e.wp == 1 or e.wp == 3) then



e.self:SetRunning(true);


else



e.self:SetRunning(false);




if(e.self:GetGrid() > 20 and e.self:GetGrid() < 26) then


if(e.wp == 2 or e.wp == 3) then



>**Tovax Vmar says:** S'ragg is going to have my head for losing that letter...


elseif(e.wp == 4) then



e.self:RemoveWaypoints();



e.self:AssignWaypoints(13);



e.self:SetRunning(false);

end

## Depart from Waypoint Script

if(e.self:GetGrid() > 20 and e.self:GetGrid() < 26 and e.wp == 1) then


**Spawns on ground:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/18802" data-url="18802" class="tooltip-link link">A Sealed Letter</a> at location.
end
