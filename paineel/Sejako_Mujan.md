# Sejako Mujan
## Dialog

**You say:** `Hail`



>**Sejako Mujan says:** Shhhh....keep your voice down lest you wake Alaria. We can [speak elsewhere] if you wish.

**You say:** `speak elsewhere`



>**Sejako Mujan says:** Follow me and we shall discuss how you may assist me with my [current research].


eq.start(16);

**You say:** `current research`



>**Sejako Mujan says:** Recently patrols have been sent to the Stonebrunt Mountains to investigate rumors of an alliance between the Kejekans and Erudin. There is much spiritual activity in that region of Odus and the patrols have reported encountering massive beasts called Titans. These titans exhibit abilities that lead me to believe they are powerful animal spirits that have somehow taken on a physical form in order to enter and manipulate the realm of the living. I require [samples] of the Titans physiology in order to further my research.

**You say:** `samples`



>**Sejako Mujan says:** There have been sightings of Titans in many forms. The samples I require are the fangs of the leopard, sabretooth, and gorilla titans, and the rattle of the snake titan.
end

## Turn-Ins



local text = "I require all four titan samples in order to pursue the research I desire.";



if **You turn in:** [Gigantic Gorilla Fang](/item/6957), [Giant Sabertooth Fang](/item/6943), [Giant Leopard Fang](/item/6959), [Ancient Snake Rattle](/item/6948)


>**Sejako Mujan says:** Excellent!! These shall provide valuable information to my research on the spirit realm.


 **You receive:**  [Staff of the Moribund Spirits](/item/2568) (+250 exp)

**This NPC *should* return incorrect items given.**




