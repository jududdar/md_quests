# a visiting priestess


## Dialog

**You say:** `hail`



>**a visiting priestess says:** Hail, Soandso! Are you the champion Najena sent for?

**You say:** `willing`



>**a visiting priestess says:** Very well then, Soandso.  I am Aerthane D'Zitherak, Priestess of Innoruk, seeker of the fabled and ancient staff of Ankexfen.  Have you ever heard of this relic?

**You say:** `no`



>**a visiting priestess says:** No? Why am I not surprised? You look too weak and frail to be of any use. You probably could not even best one of those intoxicated, weak-minded goblins controlled by that pathetic eye called Xxorb. Away with you, useless creature!

**You say:** `yes i have`



>**a visiting priestess says:** So you have heard of it?  Tell me what you know.  I would be most amused to hear what a feeble creature such as yourself might know of the staff of Ankexfen.

**You say:** `what.* ankexfen`



>**a visiting priestess says:** The wrath of the unnamed gods was grim. Thousands of ogres were instantly slain - their empire left to crumble under the hand of retribution. The giants were flung across the face of Norrath like seeds to the wind. The Ankexfen's fates were more severe. The entire race was exterminated, but from the ashes were born the four goblin races. What is known is that each goblin clan was stripped of any knowledge and was neither informed of the other clans nor of their own origins. Each clan was then transported to a separate environment to help preserve the gods' will. However, the gods were not without mercy and each clan was granted a section of the staff. Upon each staff, a crystal was placed. These staves served to aid the goblin clans in understanding their environments. These remnants of the staff of Ankexfen are what I desire. Bring them to me and the Priests of Innoruuk shall reward you.
end

## Turn-Ins



local text = "grins evilly as she disassembles the staff and holds forth a runed wooden rod.";




if **You turn in:** [Ice Crystal Staff](/item/6323), [Fire Crystal Staff](/item/6324), [Slime Crystal Staff](/item/6335), [Water Crystal Staff](/item/6336)


>*a visiting priestess cackles with glee as she slowly assembles the runed rods, and with a muttered incantation and a flash of light, disappears, leaving only a note that slowly drifts to the ground.*


* __Faction:__ [Priests of Innoruuk](/faction/340) (100)


* __Faction:__ [King Naythox Thex](/faction/278) (15)


* __Faction:__ [Priests of Marr](/faction/362) (-34)


* __Faction:__ [Clerics of Tunare](/faction/226) (-25)


* __Faction:__ [Priests of Life](/faction/341) (-15)


* __Faction:__ [Primordial Malice](/faction/1522) (-400)


 **You receive:**  [Scroll of Flayed Goblin Skin](/item/18401) (+132775 exp)


**a visiting priestess despawns.**

local returned = item_lib.return_items(e.self, e.other, e.trade, false);


if(returned) then



>**a visiting priestess says:** This is not part of the bargain. Bring me the pieces of the Staff of Ankexfen!

end


