# Henna Treghost


## On NPC Spawn

**Set a timer** named *sing* for 1040 seconds


## Timer(s)

local song;



if (e.timer == "sing") then




if ( not **spawned NPC:**  [Trolon Lightleer](/npc/10141)





and not **spawned NPC:**  [Branis Noolright](/npc/10158)





and not **spawned NPC:**  [Palana Willin](/npc/10165)




) then





return;




song = math.random(1, 7);


if (song == 1) then



>**Henna Treghost says:** Let's hear some music.


elseif (song == 2) then



>**Henna Treghost says:** Music!! Music!!


elseif (song == 3) then



>**Henna Treghost says:** Play us some music bard!!


elseif (song == 4) then



>**Henna Treghost says:** Let's liven this pub up!


elseif (song == 5) then



>**Henna Treghost says:** Try to cheer this place up, bard.


elseif (song == 6) then



>**Henna Treghost says:** Where is the music? I don't pay you bards to drink all the grog!!


elseif (song == 7) then



>**Henna Treghost says:** Sing us a melody.









**Signaled to:**  [Trolon Lightleer](/npc/10141)


**Signaled to:**  [Branis Noolright](/npc/10158)


**Signaled to:**  [Palana Willin](/npc/10165)
end
