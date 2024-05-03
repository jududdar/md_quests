# Raffel Minnmorn


## On NPC Spawn

**Set a timer** named *talk* for 600 seconds


## Dialog

**You say:** `hail`



>**Raffel Minnmorn says:** Hello, friend. I am visiting from the plains. I hope to make a FORTUNE here in Qeynos.

**You say:** `Flockwalker`



>**Raffel Minnmorn says:** Gash Flockwalker is a druid from Surefall Glade. I have a special delivery for him.

**You say:** `special delivery`



>**Raffel Minnmorn says:** I shall chop you down as your people chopped down the beauty of the forests!!


**Raffel Minnmorn attacks you.**
end



## Timer(s)

if(e.timer == "talk") then


>**Raffel Minnmorn says:** Pardon me.  Have you seen a man named Gash Flockwalker?  He hails from Surefall Glade.


**Stop timer** named *talk*


**Signaled to:**  [Tasya Huntlan](/npc/1104)
end
