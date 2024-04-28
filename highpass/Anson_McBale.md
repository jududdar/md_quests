# Anson McBale
## Dialog

**You say:** `hail`



if **Faction** >= Apprehensive then



>**Anson McBale says:** Beat it, Soandso,  unless you have something for me.





else



>**Anson McBale says:** Go away! We don't have time for the likes of you.


**You say:** `see stanos`



if **Faction** >= Apprehensive then



>**Anson McBale says:** This better be important.



**Spawn NPC:**  [Stanos Herkanor](/npc/5088) at (**y:** 10, **x:** 336)





else



>**Anson McBale says:** Go away! We don't have time for the likes of you.


**You say:** `stanos`



if **Faction** >= Apprehensive then



>**Anson McBale says:** Are you deaf, bladebait?  Unless you have something for me, you need to leave now, while I am still feeling mellow.  Don't much appreciate folks coming into my little kingdom here and snooping around.





else



>**Anson McBale says:** Go away! We don't have time for the likes of you.


**You say:** `you`



if **Faction** >= Apprehensive then



>**Anson McBale says:** Just who in the flip do you THINK I am?  Oh, you want my biography?  Soandso, you are standing on my last nerve.  Old men delight in telling tales about themselves.  Me, I'm busy living those tales at the moment.  If I am still here in thirty years, ask me then.


else



>**Anson McBale says:** Go away! We don't have time for the likes of you.

end

## Signals

if(e.signal == 1) then


>**Anson McBale says:** The boss might need some help!


local stanos = eq.get_entity_list():GetMobByNpcTypeID( [Stanos Herkanor](/npc/5088)); 


if ( stanos.valid ) then



e.self:MoveTo(stanos:GetX(), stanos:GetY(), stanos:GetZ(), -1, false);



elseif(e.signal == 2) then


>**Anson McBale says:** Vilnius has always had a good eye for talent.  I think we can trust this one.


**Signaled to:**  [Stanos Herkanor](/npc/5088)
end

## Turn-Ins




if **Faction** >= Apprehensive and  **You turn in:** [Stanos' Pouch](/item/28014)


>**Anson McBale says:** Ah, we have been expecting this. Let me get Stanos, he will want to inspect it first, but here are your coins.


* __Faction:__ [Highpass Guards](/faction/332) (50)


* __Faction:__ [Carson McCabe](/faction/329) (7)


* __Faction:__ [Merchants of Highpass](/faction/331) (7)


* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (2)


* __Faction:__ [The Freeport Militia](/faction/330) (2)


 **You receive:** 0 (+10000 exp)


**Spawn NPC:**  [Stanos Herkanor](/npc/5088) at (**y:** 10, **x:** 336)

**This NPC *should* return incorrect items given.**
