# Legionnaire Marais
## On NPC Spawn

**Set a timer** named *depop* for 600 seconds
## Timer(s)

if(e.timer == "depop") then


**Legionnaire Marais despawns.**

elseif(e.timer == "die") then


**Legionnaire Marais despawns.**
end

## Dialog

**You say:** `hail`



>*Legionnaire Marais looks up at you wearily, 'Corporal Donfeld?'*
end

## Turn-Ins





if **You turn in:** [torn half of a note](/item/18332)


>*Legionnaire Marais shows relief in his eyes, 'I knew someone would come if I... just held out... long enough... Take these... be careful... ' And with that, Marais allows himself to finally die.*


 **You receive:** None 


**Set a timer** named *die* for 10 seconds

**This NPC *should* return incorrect items given.**
