# Bunu Stoutheart


## On NPC Spawn

**Set a timer** named *follow* for 1 seconds


## Timer(s)

if(e.timer == "follow") then


local mobtypeID =  eq.get_entity_list():GetMobByNpcTypeID(13065);





if(mobtypeID) then



local follow_mob = mobtypeID:GetID();



eq.follow(follow_mob,15);



**Stop timer** named *follow*

end



## Dialog

**You say:** `hail`



>**Bunu Stoutheart says:** Hail, Soandso!  I am Bunu Stoutheart of the [Fangbreakers].  I am a loyal shaman who serves the will of the Tribunal.

**You say:** `fangbreaker`



>**Bunu Stoutheart says:** The Fangbreakers are Norrath's foremost [lycanthrope] hunters.  We bring those bloodthirsty beasts to justice.

**You say:** `werewolves`



>**Bunu Stoutheart says:** Lycanthropes, or werewolves, are victims of a horrible curse that transforms them into vicious murdering beasts.  But the fact that they are not in control of themselves does not excuse them from responsibility! They must be punished for the atrocities they commit!

**You say:** `halas`



>**Bunu Stoutheart says:** I hail from Halas, nestled deep in the Everfrost Peaks, but the Plains of Karana have been my home for many years now.

end
