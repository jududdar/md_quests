# a confused castaway
## On NPC Spawn

**Set a timer** named *lie* for 1 seconds
## Timer(s)

if ( e.timer == "lie" ) then


eq.stop_timer(e.timer);


e.self:SetAppearance(3);
end

## Dialog


**You say:** `hail`



>**a confused castaway says:** Wha... what happened? Where am I? This isn't the cave... And you, who are you? Why are you standing over me with that peculiar look on your face? I didn't do anything regrettable did I?


e.self:SetAppearance(0);




**You say:** `yes`



>**a confused castaway says:** Oh no, I thought it was just a dream, a nightmare. All I saw was myself as a Srerendi Storm giant, dealing punishment to all interlopers of my domain. Deep down, I couldn't believe that it was me, but on the surface, I could feel the power, feel a force guiding me to be... to be evil. What did you say they called me?



**You say:** `jeplak`



>**a confused castaway says:** Right, Jeplak. Obviously I wasn't really him, but he's not far from here. I was merely a distraction for anyone who tried to push he and his tribe out of this place. There is another building behind this one that you might want to check for the real Jeplak. I apologize if I've caused any harm to anyone. Farewell, and good luck.


**a confused castaway despawns.**
end
