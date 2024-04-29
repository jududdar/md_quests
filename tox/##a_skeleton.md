# a skeleton
## On NPC Spawn

eq.set_timer("rant",math.random(180000,450000));
## Dialog

**You say:** `hail`



>**a skeleton says:** Can't you see we're busy here?!
end

## Turn-Ins



if( **You turn in:** [Useless Cloth Cap](/item/13894)) then


>**a skeleton says:** Aye.. You cut out the middleman..  I shall reward you.. hmm..  I have not found anything. how about..  <CRACK!! SNAP!! RIPP!!>  How about something off meself?


 **You receive:** eq.ChooseRandom( [Bone Shield](/item/9304), [Fractured Femur](/item/12195), [Bone Chips](/item/13073), [Zombie Skin](/item/13074)) (+500 exp)

**This NPC *should* return incorrect items given.**

## Timer(s)

if(e.timer == "rant") then


>**a skeleton says:** Yo ho. No sun!


eq.set_timer("rant",math.random(180000,450000));
end
