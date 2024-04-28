# an investigator
## Dialog

local qglobals = eq.get_qglobals(e.self);


**You say:** `hail`



>*an investigator raises one eyebrow and looks at you with suspicion before returning his watchful eye to the many people going about their business in the city.*

**You say:** `first suspect`



>**an investigator says:** The first suspect was last seen near the shop called Fireprides.

**You say:** `follow me`



>**an investigator says:** Right, let's get going.


eq.follow(e.other:GetID());

**You say:** `confession`



>**an investigator says:** Here you are.


**You receive:**  [Confession Document](/item/2344)

**You say:** `summon a guard`



>**an investigator says:** Guards!  Take this man away.


**Spawn NPC:**  [Guard Sylus](/npc/1314) at (**y:** 50, **x:** -413)

**You say:** `summon a guard`



>**an investigator says:** Guards!  Take this man away.


**Spawn NPC:**  [\#Guard Sylus](/npc/1182) at (**y:** 145, **x:** -246)

**You say:** `summon a guard`



>**an investigator says:** Let us interrogate the suspects before summoning any guards.

**You say:** `second suspect`



>**an investigator says:** The second suspect was sighted below the Grounds of Fate.

**You say:** `third suspect`



>**an investigator says:** The last suspect has been known to hang around that low life known as Raz the Rat.
end

## Turn-Ins



if **You turn in:** [Investigators Briefing](/item/18289)


>**an investigator says:** Very well, let's get to work. I assume you have read the briefing and committed it to memory. This is how you will be tested. I shall play the part of student and you shall play the master who directs me. I promise I won't make it easy on you either, we want only the best. We'll see how you do and then I'll decide if you are worthy to wear the badge or not.


eq.follow(e.other:GetID());


**Set a timer** named *depop* for 1800 seconds


**Spawn NPC:**  [\#Riley Shplots](/npc/1183) at (**y:** 200, **x:** -324)


eq.set_global("invest_badge","first_suspect",3,"F");

elseif **You turn in:** [Rileys Confession](/item/2369), [Willies Confession](/item/2394), [Head of Donally Stultz](/item/2279)


eq.stop_follow();


>**an investigator says:** You have done our city a great service and helped to bring several criminals to justice this day! Wear this Investigator's Badge with pride! Speak again with Vegalys Keldrane, he may have information about [advancing further] in rank.


* __Faction:__ [Antonius Bayle](/faction/219) (5)


* __Faction:__ [Guards of Qeynos](/faction/262) (5)


* __Faction:__ [Ring of Scale](/faction/304) (-2)


* __Faction:__ [Kane Bayle](/faction/273) (-5)


* __Faction:__ [Merchants of Qeynos](/faction/291) (5)


 **You receive:**  [Investigator's Badge](/item/2386) (+2000 exp)


eq.delete_global("invest_badge");


**an investigator despawns.**

item_lib.return_items(e.self, e.other, e.trade, e.text)
## Timer(s)

if(e.timer == "depop") then


>**an investigator says:** Our time has run out. You have failed.


**an investigator despawns.**


eq.delete_global("invest_badge");
end

## Signals

if(e.signal == 1) then


>**an investigator says:** We have several witnesses that have signed affidavits swearing to the fact that they had witnessed you raising an undead servant in the hills outside the city several nights past. Do you deny this?


**Signaled to:**  [\#Willie Garrote](/npc/1201)

elseif(e.signal == 2) then


>**an investigator says:** I find that difficult to believe. We have further statements that say you were seen drawing the life force from a rat before this undead servant of yours tore it apart. The evidence against you is irrefutable. I suggest you cooperate now. It will be better for you in the long run.


**Signaled to:**  [\#Willie Garrote](/npc/1201)

elseif(e.signal == 3) then


>**an investigator says:** We are deadly serious, sir. We know who you are and where your allegiances lie. We are also aware that you are simply a misguided pawn in this terrible plot. I suggest you take advantage of this offer, sign the confession document and allow yourself to be taken into custody. The court may not be so lenient should it come to a trial.


**Signaled to:**  [\#Willie Garrote](/npc/1201)
end

## On NPC Death

eq.delete_global("invest_badge");