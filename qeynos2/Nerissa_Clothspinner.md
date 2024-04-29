# Nerissa Clothspinner
## Arrive at Waypoint Script

if(e.wp == 17) then


>**Nerissa Clothspinner says:** When will my sister show up? I need her!

elseif(e.wp == 27) then


e.self:MerchantOpenShop();

elseif(e.wp == 28) then


e.self:MerchantCloseShop();

elseif(e.wp == 43) then


>**Nerissa Clothspinner says:** Bartender! Some water, please.
end

## Dialog

**You say:** `hail`



>**Nerissa Clothspinner says:** Good day to you! Be careful in the city of Qeynos. [Rumors] of corruption may be true. Believe me. I wish my [sister] were here to help.

**You say:** `sister`



if **Faction** >= Indifferent then



>**Nerissa Clothspinner says:** My sister is in the Karanas. She is a warrior. Her name is Milea. I really need her. Would you please deliver a note to her? You look able-bodied enough for the job.


else



>**Nerissa Clothspinner says:** I do not trust you. I heard word that you are not a good person. Mend your ways and then I may trust you with such talk.




**You say:** `deliver a note`



if **Faction** >= Indifferent then



>**Nerissa Clothspinner says:** Here you go then, brave adventurer. Godspeed to you.



**You receive:**  [A Tattered Note](/item/18801)


else



>**Nerissa Clothspinner says:** I do not trust you. I heard word that you are not a good person. Mend your ways and then I may trust you with such talk.




**You say:** `rumors`



if **Faction** >= Indifferent then



>**Nerissa Clothspinner says:** I have heard that a few of the Qeynos merchants and guards are not very happy with the current state of the city. Taxes are too high and many of the guards have been sent to the outlands, leaving Qeynos vulnerable to attack. I do not feel the same way, but I fear these few may become many. I [fear for my life].


else



>**Nerissa Clothspinner says:** I do not trust you. I heard word that you are not a good person. Mend your ways and then I may trust you with such talk.




**You say:** `fear`



if **Faction** >= Indifferent then



>**Nerissa Clothspinner says:** During a late night stroll by the pond in north Qeynos I spied a guard carrying a very large carpet on his shoulders. He approached the pond's edge and unrolled the carpet, the body of another guard rolled out and began to moan. The other guard grabbed for a long spear like weapon from his back. He drove the weapon into the man and pushed him into the pond. I screamed. He turned to me and I ran. I do not think he gave chase, too bad, he would not like to run into my [guardian] at home. I told my guardian and we both went to the pond and saw no body. He believes I was drinking too much wine. I do not drink. Now I fear for my life when I am in the streets of Qeynos.


else



>**Nerissa Clothspinner says:** I do not trust you. I heard word that you are not a good person. Mend your ways and then I may trust you with such talk.




**You say:** `guardian`



if **Faction** >= Indifferent then



>**Nerissa Clothspinner says:** When my big sister left Qeynos for adventure, she left me in the hands of her old time friend Kane Bayle. Yes, the commander of the Qeynos Guards is my guardian. You would think I would be safe. Every time I tell him the rumors I hear he just ignores me. He is too busy I guess.


else



>**Nerissa Clothspinner says:** I do not trust you. I heard word that you are not a good person. Mend your ways and then I may trust you with such talk.



end

## Turn-Ins





if( **You turn in:** [Monogrammed Cloth](/item/13302)) then 


>**Nerissa Clothspinner says:** Thank you my friend. I understand that Astaed Wemor of the Temple of Life has been concerned for my well being. Take him this note. I am sure he will reward you for easing my troubled mind.. If you are a respected member.


* __Faction:__ [Merchants of Qeynos](/faction/291) (15)


* __Faction:__ [Circle of Unseen Hands](/faction/223) (-3)


* __Faction:__ [Antonius Bayle](/faction/219) (2)


* __Faction:__ [Coalition of Tradefolk](/faction/229) (1)


* __Faction:__ [Guards of Qeynos](/faction/262) (3)


 **You receive:**  [A tattered note](/item/18862) (+1000 exp)

**This NPC *should* return incorrect items given.**
