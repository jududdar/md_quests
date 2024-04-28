# Assassin Daran

## Dialog

**You say:** `hail`



>*Assassin Daran grins wildly at Soandso. An uncomfortable presence washes over you in a split moment as you catch the halfling's narrowed eyes searching every inch of your person. 'Hail, greetings, and well met, friend! I am Daran, rogue extraordinaire! Rather, I am -the- rogue, I should say. A'course I dinnae boast, my friend! Aww. . . dinnae be offended or feel inferior, but be honored that ye stand in my presence. Well, enough of the introductions then, yes? Hrm. . . what have we here? Perhaps ye be a rogue, hrm? Ye seek my infinite and unsurpassed cunning and prowess perhaps to teach ye? Well then, if it is a master of the shadows that you wish to be, then I be the man who will most assuredly make a proper rogue out of you yet.'*
end

## Turn-Ins



local count =  **You turn in:**  { [Woven Shadow Helm](/item/4901),  [Woven Shadow Chestplate](/item/4902),  [Woven Shadow Vambraces](/item/4903),  [Woven Shadow Bracer](/item/4904),  [Woven Shadow Gauntlets](/item/4905),  [Woven Shadow Greaves](/item/4906),  [Woven Shadow Boots](/item/4907)}

if(count > 0) then


repeat



>**Assassin Daran says:** Thank you, Soandso.



 **You receive:** eq.ChooseRandom( [Peridot](/item/10028), 10037, 22503, 15981) (+300000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





