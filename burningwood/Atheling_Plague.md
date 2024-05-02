# Atheling Plague



## Dialog

**You say:** `hail`



>**Atheling Plague says:** Ahh!! A conversationalist. How good to meet you, Soandso. Yes. I have heard of you. Go ahead and ask for that which has brought you to my tower and emboldened you to slay my weaker minions.

**You say:** `sisters of scale`



>**Atheling Plague says:** What a coincidence! I, too, seek a skull. Perhaps you might help me [obtain the skull]. Perhaps then you shall have the skull you desire.

**You say:** `obtain the skull`



>**Atheling Plague says:** I am sure you would not mind removing the head of a scaled mystic. I hope not. There is an old Iksar who once called me slave. Now he shall adorn my wall, mounted on a fine plaque. His name is Digalis. Find him. Do not return until your task is complete.
end

## Turn-Ins




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1070.png" alt="" /> <a
                                href="/item/12764" data-url="12764" class="tooltip-link link">Iksar Skull</a>) then


**Atheling Plague shouts:** <span class="text-danger">Excellent. You show signs of a true Iksar slayer. Too, bad I have already given the skull of the Sister of Scale to another. Perhaps you would like to meet him before he departs. Say hello, Doval.</span>


**Spawn NPC:**  [Clerk Doval](/npc/87154) at this location.


**Set a timer** named *heal* for 20 seconds

**This NPC *should* return incorrect items given.**
;
## Timer(s)

if(e.timer == "heal") then


**Atheling Plague casts:** [Healing](/spell/12) on **NPC:**  [Clerk Doval](/npc/87154)
end

## Signals

if(e.signal == 1) then


**Stop timer** named *heal*
end

## On NPC Death

**Stop timer** named *heal*




