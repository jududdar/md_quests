# Carprin Deatharn



[Carprin Deatharn](/npc/200232) is a level 70 Knight of Pestilence Warrior that spawns in [The Crypt of Decay](/zone/200).



## On NPC Spawn

**Set a timer** named *depop* for 12300 seconds

e.self:SetGuardSpot(384, -112, -53.9, 197);


## Combat

if  Carprin Deatharn enters combat  then


eq.pause_timer("depop");


**Set a timer** named *drophate* for 1 seconds

else


eq.resume_timer("depop");


**Stop timer** named *drophate*
end



## On NPC Death

**Zone Wide Emote:** <span class="text-warning">*Dark laughter sounds from deeper within the chapel as a menacing voice is heard saying, 'Come great corrupter of entropy and decay. Stop these foolish mortals from violating our masters chapel.*</span>

**Spawn NPC:**  [\#Avhi Escron](/npc/200225) at (**y:** 135, **x:** 405)


## Timer(s)


if ( e.timer == "drophate") then




if ( math.random() < 0.01666 ) then 



local target = e.self:GetTarget();



if ( target and target.valid ) then




e.self:RemoveFromHateList(target);





eq.debug(e.self:GetName().." dropped target from hate list ("..target:GetName()..")", 2);





elseif ( e.timer == "depop" ) then


**Carprin Deatharn despawns.**
end
