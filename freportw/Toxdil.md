# Toxdil
## Dialog

**You say:** `hail`



>**Toxdil says:** Correct. Toxdil is my name. No last name. I swear allegiance to no house nor guild. What brings you down here? Perhaps you seek my [deadly liquid], perhaps not. Whatever your reasons, I warn you to keep an eye out for the militia. They have begun to patrol the sewers.

**You say:** `deadly liquid`



>**Toxdil says:** The deadly liquid I offer to rogues is called snake venom. I will be glad to make it for you, but first you must supply me with two snake venom sacs and my fee of 20 gold pieces. You may find the sacs upon the giant snakes of the Commonlands.

**You say:** `gem of righteousness`



>**Toxdil says:** That gem is worthless!! If you want it, you can have it. Oh, but I forgot! I sold it to some gem merchant. I can't seem to remember her name, but she paid highly for it. Ha!! Imagine that. Worthless hunk of crystal. Do not bother looking for it.
end

## Turn-Ins



local text = "I require two snake venom sacs and my fee of 20 gold coins before I shall create the snake venom."


if( **You turn in:** [A Sparkling Sapphire](/item/12353)) then


>**Toxdil says:** The gem!! I would notice it's sparkle anywhere!! I cannot believe you are handing it back to me!! What a fool. Here you are fool. You can have this worthless key now.


 **You receive:**  [A Tiny Key](/item/12351) (+15000 exp)

elseif( **You turn in:** [A Snake Venom Sac](/item/14017), [A Snake Venom Sac](/item/14017),gold = 20) then


>**Toxdil says:** Here is your snake venom. May you... shall we say... apply it to good use.


 **You receive:**  [Snake Venom](/item/14016) (+1000 exp)

**This NPC *should* return incorrect items given.**
