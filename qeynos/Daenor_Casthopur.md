# Daenor Casthopur
## Dialog

local fac = e.other:GetFaction(e.self);

**You say:** `hail`



>**Daenor Casthopur says:** Ah, hello there, Soandso, and welcome to the Hall of Sorcery! I'm Daenor, a wizard of the Order of Three. I can help you practice your skills and learn some new ones.

**You say:** `neclo`



if(fac < 6) then 



>**Daenor Casthopur says:** Neclo Rheslar is an old friend of mine. Right now, he's out working in the Qeynos Hills. In fact, if you have some free time, you should go out and meet him. Here, if you go, take this note to him for me. Thanks, friend.



**You receive:**  [Note to Neclo](/item/18823)


else



>**Daenor Casthopur says:** The Order of Three has been monitoring your recent activities, and we are appalled by you and your actions! Now, begone!

end

## Turn-Ins



**This NPC *should* return incorrect items given.**
