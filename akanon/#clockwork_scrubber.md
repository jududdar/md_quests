# clockwork scrubber
## On NPC Spawn

**Set a timer** named *pick_up* for 2 seconds
## Timer(s)

if ( e.timer == "pick_up" ) then




while ( e.self:CheckGround() ) do



>*clockwork scrubber clicks as a plate slides to the side revealing a hose that extends and sucks up an item from the ground*


## Dialog

**You say:** `628`



>*clockwork scrubber .wizz.click.628.*
end

## Turn-Ins



if ( **You turn in:** [Scrubber Key](/item/12164)) then 


>*clockwork scrubber .wizz.click.628.*





* __Faction:__ [Clockwork Gnome (Race)](/faction/695) (-5)


 **You receive:** eq.ChooseRandom( [Gnome Take](/item/12162), [Gnome Take](/item/12167)) 

**This NPC *should* return incorrect items given.**
