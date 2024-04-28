# Treasurer Lynn
## On NPC Spawn

**Set a timer** named *pick_up* for 2 seconds
## Timer(s)

if ( e.timer == "pick_up" ) then




while ( e.self:CheckGround() ) do



>*Treasurer Lynn picks up something from the ground.*


## Dialog

**You say:** `hail`



>**Treasurer Lynn says:** Greetings!!  Welcome to Highkeep. home of the greatest casino in all of Norrath.  Please visit our fine casino on the second floor.

**You say:** `lottery`



>**Treasurer Lynn says:** Interested in the Highkeep lotter, are we?  I am afraid it as been put on hold.  We found last season's winner to be holding a counterfeit ticket.  We now await [last season's winner] to step foward with the winning ticket - ticket number 16568.  His prize is the key to the royal suite.

**You say:** `last season`



>**Treasurer Lynn says:** Last season's winner is not known.  I have heard from my sources that he was some sort of merchant of used goods.
end

## Turn-Ins




if **You turn in:** [Lottery Ticket \# 15600](/item/12261)


>**Treasurer Lynn says:** You have the runner up ticket from last season!! Here is your reward. Remember, a copper gambled is a plat earned!!


 **You receive:** None 

elseif **You turn in:** [Lottery Ticket \# 16568](/item/12266)


>**Treasurer Lynn says:** Congratulations!! You are the winner of last season's Highkeep lottery. Here is the key to the royal suite. You should find this room on the third floor.


 **You receive:**  [Highkeep Royal Suite](/item/12267) (+500 exp)

**This NPC *should* return incorrect items given.**

