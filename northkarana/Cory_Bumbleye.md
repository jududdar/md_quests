# Cory Bumbleye


## On NPC Spawn

**Set a timer** named *follow* for 1 seconds


## Timer(s)

if(e.timer == "follow") then


local mobtypeID =  eq.get_entity_list():GetMobByNpcTypeID(13065);





if(mobtypeID) then



local follow_mob = mobtypeID:GetID();



eq.follow(follow_mob,25);



**Stop timer** named *follow*

end




## Dialog

**You say:** `hail`



>**Cory Bumbleye says:** Hey, Soandso!  I am Cory Bumbleye, expert [lycanthrope] tracker.  You had better be careful out here.  There are [werewolves] in these hills.  Heck, if it weren't for us [Fangbreakers], this whole area would be overrun with the flea-bitten beasts.

**You say:** `fangbreaker`



>**Cory Bumbleye says:** I am a Fangbreaker.  We hunt werewolves.  We are the best in all of Antonica.

**You say:** `werewolves`



>**Cory Bumbleye says:** Peh!  Werewolves are just overgrown dogs that need to be put down.  And let me tell you this, if a friend of yours ever survives a werewolf attack, I would watch him VERY closely.  If he is infected, you will have no choice but to slay him before he eats you.

**You say:** `rivervale`



>**Cory Bumbleye says:** Rivervale?  I am from Rivervale.  I joined up with the Fangbreakers when they tracked a [werewolf] into the Misty Thicket.

end
