# Lysbith McNaff
## Dialog

**You say:** `hail`



>**Lysbith McNaff says:** Hail! Ye've come to [serve Halas]. have ye not? We're the Wolves o' the North and it is our task to defend our city from harm.

**You say:** `serve halas`



if( **Faction is** > Indifferent) then 



**You say:** `serve halas`





>**Lysbith McNaff says:** Halas is surrounded by barren arctic tundra. We've many foes. Among them are the [orc troopers]. [ice goblins] and the ever-present polar bears.



**You say:** `orc troopers`





>**Lysbith McNaff says:** So. Ye think yerself strong enough to battle the snow orc troopers? I pray to the Tribunal that ye are. If ye can return to me four wrath orc wristbands from the troopers' bodies. I'll reward ye with the [Seax].



**You say:** `protect the pass`





>**Lysbith McNaff says:** Then travel to the Everfrost Peaks and take this pack with you.  I want you to return this pack to me when it is filled with the beaded ice necklaces of the Ice Goblins.  When it is filled, combine the items and return it to me and I shall decide if you deserve a reward for your deed.




**You receive:**  [Empty Bag](/item/17944)










elseif( **Faction is** == Indifferent) then



>**Lysbith McNaff says:** The Wolves o' the North show ye no ill will, but there's much ye must do to earn our trust. Perhaps ye should inquire o' the [gnoll bounty].


elseif( **Faction is** < Indifferent) then



>**Lysbith McNaff says:** Run while ye still can!! The Wolves o' the North will not tolerate yer presence!





**You say:** `ice goblins`



>**Lysbith McNaff says:** The ice goblins have plagued our community fer some time now. At times. they even manage to get inside our walls. Fer the most part. they prey on travelers who pass through Everfrost Peaks. Since they're a weak race. we employ our youngest warriors to [protect the pass].

**You say:** `seax`



>**Lysbith McNaff says:** The Seax is a Northman warrior's piercing weapon. Dinnae confuse this with another [weapon] related to the Seax called the Langseax. The local rogues have also learned to master the Seax. I'll only offer it to those who battle the [orc troopers].

**You say:** `gnoll bounty`



>**Lysbith McNaff says:** I've placed a bounty on the gnolls o'Blackburrow. Their whelps have invaded our land and we must carry the fight into their dens. Join the fight and return three gnoll fangs as proof of yer victory in Blackburrow. Do so, and earn the respect o' the Wolves o' the North.

**You say:** `weapon`



>**Lysbith McNaff says:** The Langseax is a one-handed slashing weapon crafted fer a warrior. Tis the brother to the [Seax].


end

## Turn-Ins



if( **Faction is** > Indifferent and  **You turn in:** [Wrath Orc Wristbands](/item/12223), [Wrath Orc Wristbands](/item/12223), [Wrath Orc Wristbands](/item/12223), [Wrath Orc Wristbands](/item/12223)


>**Lysbith McNaff says:** Ye're becoming a fine champion o' Halas. Take th' Seax. May ye always defend Halas!





* __Faction:__ [Wolves of the North](/faction/320) (20)





* __Faction:__ [Shamen of Justice](/faction/327) (4)





* __Faction:__ [Merchants of Halas](/faction/328) (5)





* __Faction:__ [Steel Warriors](/faction/311) (1)





 **You receive:**  [Seax](/item/7322) (+3000 exp)

elseif( **Faction is** > Indifferent and  **You turn in:** [Bag of Ice Necklaces](/item/13898)


>**Lysbith McNaff says:** Ye've done well, me young " .. e.other:Class() .. " .  We've gathered these to add to yer provisions.  While in the Everfrost Peaks, be on the watch fer any gnolls ye may find.  I declare there to be a [gnoll bounty].





* __Faction:__ [Wolves of the North](/faction/320) (10)





* __Faction:__ [Shamen of Justice](/faction/327) (2)





* __Faction:__ [Merchants of Halas](/faction/328) (2)





* __Faction:__ [Steel Warriors](/faction/311) (1)





 **You receive:** eq.ChooseRandom( [Iron Ration](/item/13005), [Ration](/item/13007), [Water Flask](/item/13006), [Torch](/item/13002), [Small Lantern](/item/13003)) (+3800 exp)

elseif **You turn in:** [Gnoll Fang](/item/13915), [Gnoll Fang](/item/13915), [Gnoll Fang](/item/13915)



>**Lysbith McNaff says:** Fine work, fine work!  The gnoll threat must be extinguished before it can ever fully grow.  Ye've done yer part to aid our cause.  Please allow me to repay ye with a few provisions and a wee bit o' coin.  Then, continue with yer good deeds.





* __Faction:__ [Wolves of the North](/faction/320) (15)




* __Faction:__ [Shamen of Justice](/faction/327) (3)




* __Faction:__ [Merchants of Halas](/faction/328) (3)




* __Faction:__ [Steel Warriors](/faction/311) (1)




 **You receive:** eq.ChooseRandom( [Iron Ration](/item/13005), [Ration](/item/13007), [Water Flask](/item/13006), [Torch](/item/13002)) (+8000 exp)
**This NPC *should* return incorrect items given.**
