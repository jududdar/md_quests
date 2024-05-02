# Shmendrik Lavawalker


## Dialog

**You say:** `hail`



>**Shmendrik Lavawalker says:** Hail, good Soandso!! Be wary near the waters of Lake Rathe! The Riptide goblin king, Lord Bergurgle, has been commanding his minions to murder and rob all who come near it! I am here seeking his death but I am afraid I am no match for all of his subjects. I shall reward you greatly for the death of Lord Bergurgle. I simply ask that you bring me his crown as proof.
end

## Turn-Ins




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_523.png" alt="" /> <a
                                href="/item/28044" data-url="28044" class="tooltip-link link">Lord Bergurgle's Crown</a>) then 


>*Shmendrik Lavawalker shoves the crown into a scorch marked leather satchel and cackles uncontrollably as madness twists his features and flames dance in his eyes. 'You, Soandso, have reduced the Riptides into chaos! Without a king to keep them in control they will ravage the settlements surrounding this lake! After the slaughter I shall return and easily burn the remainder of the villages and fishing shanties to the ground! None shall escape the fires of the Tyrant!!'*


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_697.png" alt="" /> <a
                                href="/item/28045" data-url="28045" class="tooltip-link link">Oil of Fennin Ro</a> 

 


**Spawn NPC:**  [\#Natasha Whitewater](/npc/51138) at (**y:** 3630.3, **x:** 160)

**This NPC *should* return incorrect items given.**

## Signals

if(e.signal == 1) then


>**Shmendrik Lavawalker says:** I'll slay you like I slaughtered your fellow missionaries! The Triumvirate can not decide the fate of a follower of the Tyrant!!


**Signaled to:**  [\#Natasha Whitewater](/npc/51138)

elseif(e.signal == 2) then


**Signaled to:**  [\#Natasha Whitewater](/npc/51138)
end

## On NPC Death

**Spawn NPC:**  [a spirit of flame](/npc/51145) at this location.





