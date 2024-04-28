# Toala Nehron
## Dialog

local fac = e.other:GetFaction(e.self);


**You say:** `hail`



>**Toala Nehron says:** I am Toala Nehron. You must be another young warrior aspiring to join the ranks of the Steel Warriors. We welcome all who would try. When you [have time] there is a friend of mine I would like you to check on.

**You say:** `opal`



>**Toala Nehron says:** Opal Darkbriar is a little plague rat.  She has used her knowledge of arcane arts to charm [Cain Darkmoore].  I know that is what happened.  Why else would he be in love with her?  He is a mighty warrior and she is nothing more than a sickly little librarian for the Academy of Arcane Science.  He must truly yearn for a bold hearted female warrior such as myself.  Not that I care, of course.

**You say:** `cain darkmoore`



>**Toala Nehron says:** Cain Darkmoore is only the most handsome of warriors!  He is also the strongest and most bold.  He has slain the mightiest of fiends.  He is truly the manliest man around.  It is no wonder he is the guildmaster of the Steel Warriors.

elseif(fac < 5) then


**You say:** `have time`




>**Toala Nehron says:** I have A friend by the name of [Lenka Stoutheart]. She reported to me that her ship was broken into and someone stole a pouch of hers. Could you go look into it for me? Just tell her Toala sent you. Oh, and pay no mind to the walking mountain by her. That will only be Bronto, her navigator. Thanks friend.


**You say:** `lenka stoutheart`




>**Toala Nehron says:** Lenka Stoutheart is an old friend of mine. I met her in my younger days when the Steel Warriors sent me to train in the ways of the Wolves of the North, the barbarian warriors of Halas. She is now an adventurer of great renown. She travels from continent to continent aboard her ship,the Blue Beast, her ship.


elseif(fac == 5) then


**You say:** `have time`




>**Toala Nehron says:** The Steel Warriors have no cause to dislike you, but you have yet to prove your worth to this guild.



elseif(fac > 5) then


**You say:** `have time`




>**Toala Nehron says:** Your head shall look grand mounted on the wall of the Steel Warriors Arena!!


end

## Turn-Ins



local fac = e.other:GetFaction(e.self);


if(fac < 5) then


if **You turn in:** [A Sealed Letter](/item/18814)



>**Toala Nehron says:** Why, that little trollop! What is she up to? Cain will never believe this! She must be in league with some faction of the dark elves, but why? Neither the Academy of Arcane Science nor Cain will believe this note. I will see what I can do. As for you, I command you to kill this Shintl and her dark elf courier Hollish!! Put their heads into this box and combine them. We shall cut the link. Bring me thier heads.



 **You receive:**  [Toalas Box for heads](/item/17971) (+500 exp)


elseif **You turn in:** [Box with Two Heads](/item/12246)



>**Toala Nehron says:** Good work!! We will soon catch Opal. I have started to formulate a plan to stop her. When I complete it, I shall notify you. Here. Take this small reward. I am sure killing Shintl was no trouble. She was just a halfling.



* __Faction:__ [Steel Warriors](/faction/311) (10)



* __Faction:__ [Guards of Qeynos](/faction/262) (2)



* __Faction:__ [Knights of Truth](/faction/281) (2)



* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (-1)



* __Faction:__ [The Freeport Militia](/faction/330) (-1)



 **You receive:** None 


elseif(fac == 5) then


if **You turn in:** [A Sealed Letter](/item/18814)



>**Toala Nehron says:** The Steel Warriors have no cause to dislike you, but you have yet to truly prove your worth to this guild.


elseif(fac > 5) then


if **You turn in:** [A Sealed Letter](/item/18814)



>**Toala Nehron says:** Your head shall look grand mounted on the wall of the Steel Warriors Arena!!


**This NPC *should* return incorrect items given.**
;

