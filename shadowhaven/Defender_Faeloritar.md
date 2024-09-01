# Defender Faeloritar

[Defender Faeloritar](/npc/150140) is a level 55 Human Warrior that spawns in [Shadow Haven](/zone/150).

Their primary faction is [Haven Defenders](/faction/1509).



## Dialog

**You say:** `hail`


>**Defender Faeloritar says:** Welcome to the Knights Table Soandso, I am Faeloritar and I watch the bar here. There have been some pretty rowdy brawls here in the past, so we always have a guard near by in case things get out of hand. It's not often that a fight breaks out here, but it sure is fun when one does.









## Combat

if Defender Faeloritar enters combat  then

**Set a timer** named *combatsay* for 300 seconds

else

**Stop timer** named *combatsay*









## Timer(s)

>**Defender Faeloritar says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!







## On NPC Death

**Stop timer** named *combatsay*

