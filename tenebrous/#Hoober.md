# Hoober
local elixer = 0;

## On NPC Spawn

**Set a timer** named *feign* for 1 seconds

**Set a timer** named *depop* for 300 seconds
## Timer(s)

if(e.timer == "feign") then


e.self:SetAppearance(3);


**Stop timer** named *feign*

elseif(e.timer == "depop") then


**Stop timer** named *depop*


**Hoober despawns.**
end

## Turn-Ins





if( **You turn in:** [Elixir of Obsession](/item/5994)) then


>*Hoober coughs a bit as you feed him the elixir. With a bit o a start he comes around to full consciousness with a calm in his eyes. 'Do I know you?' he asks.*


elixer = 1;

**This NPC *should* return incorrect items given.**

## Dialog

**You say:** `happened to behari`



>*Hoober sobs into his hands, 'horrible tings... such horrible things... I remember this man named Behari, take this, it belonged to him before... before I... 'suddenly, Hoober begins to shake uncontrollably. He starts to look at you, something between fear and dementia behind his eyes, 'Go! GO NOW! It's starting again, I shouldn't be around decent people! LEAVE ME ALONE! Stop treating me like a fool, I will leave the money in a sack under the seventy-third pillar from the giant froglok just as I agreed with your master NOW GET AWAY FROM ME!' His shouts echo throughout the mountains as he tears off at a full sprint.*


 **You receive:**  [Aisha'a Locket](/item/5996) (+500 exp)


elixer = 0;


**Hoober despawns.**
end


## On NPC Death

elixer = 0;

**Spawn NPC:**  [\#Hoober](/npc/172012) at this location.
end