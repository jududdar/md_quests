# Tundra Jack


## On NPC Spawn

e.self:SetRunning(true);


## Dialog

**You say:** `hail`



>**Tundra Jack says:** Good mining to you, kid! What are you doing way out here? You're gonna catch frostbite. The name's Tundra Jack, prospector supreme. Trained by the finest miners in Kaladim!! Me 'n [Iceberg] have been out here for three years now, searchin' fer fortune.

**You say:** `iceberg`



>**Tundra Jack says:** Iceberg used to be a beast.  He terrorized Halas for some time, then he met me.  I tamed the beast and now he watches my back.  You never know when the ice giants may go for a stroll from [Permafrost].

**You say:** `permafrost`



>**Tundra Jack says:** If I knew that, I would be swinging my picks inside it already!  The entrance is said to be somewhere out here in Everfrost Peaks.

**You say:** `sweaty shirt`



>**Tundra Jack says:** Looking fer that blasted shirt, huh?  Well, as you can smell, I didn't get to washing it, but I wrapped it onto Iceberg's collar. I'd say you can have it, but Iceberg kind of likes it now.  The only way you're gonna be able to grab it from him is to feed him his [favorite meal].

**You say:** `favorite meal`



>**Tundra Jack says:** Iceberg has some picky eating habits.  If he can't catch any goblins, he prefers [Lion Delight].  Lion Delight is his favorite.

**You say:** `lion delight`



>**Tundra Jack says:** I usually get Lion Delight from Teria O'Danos in Halas.
end



## Signals

if(e.signal == 1) then


>**Tundra Jack says:** On my way, Iceberg!!


local mobtypeID =  eq.get_entity_list():GetMobByNpcTypeID(30062);



if(mobtypeID) then



local follow_mob = mobtypeID:GetID();



eq.follow(follow_mob);



**Stop timer** named *follow*


elseif(e.signal == 2) then


>**Tundra Jack says:** Ha!!  Looks like old Iceberg likes you.  Either that or he's tasting you.

elseif(e.signal == 3) then


eq.stop_follow();
end



## Arrive at Waypoint Script

if(e.wp == 14 or e.wp == 45) then


>**Tundra Jack says:** Come on, Iceberg! Time to do a little mining.

elseif(e.wp == 16 or e.wp == 17 or e.wp == 18 or e.wp == 47 or e.wp == 48) then


>**Tundra Jack says:** Silver and Gold!!.. Silver and Gold!!

elseif(e.wp == 19 or e.wp == 49) then


>**Tundra Jack says:** Nothin'!!
end






