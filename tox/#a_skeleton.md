# a skeleton
## On NPC Spawn

eq.set_timer("rant",math.random(180000,450000));
## Dialog

**You say:** `hail`



>**a skeleton says:** Grab a pick. Give us a hand!
end

## Turn-Ins



if **You turn in:** [Useless Cloth Cap](/item/13894)


>**a skeleton says:** Good work, you should be running this operation instead of that Talrigar fellow. Have a small reward. A little bit of the gems I found while tunneling through this rock.


 **You receive:** eq.ChooseRandom( [Malachite](/item/10015), [Lapis Lazuli](/item/10016), [Turquoise](/item/10017), [Hematite](/item/10018)) (+500 exp)

**This NPC *should* return incorrect items given.**

## Timer(s)

if(e.timer == "rant") then


>**a skeleton says:** A skeleton's day is never done.


eq.set_timer("rant",math.random(180000,450000));
end
