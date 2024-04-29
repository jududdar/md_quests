# Gehna Solbenya
## Dialog

**You say:** `hail`



>**Gehna Solbenya says:** Greetings and blessings to you, Soandso. Karana offers you his protection and guidance. All who accept the offer shall find safe haven within our Temple of Thunder, If you are a cleric of Karana, you must have a [desire to serve Karana]'s flock.

**You say:** `serve karana`



if **Faction** >= Indifferent then



>**Gehna Solbenya says:** If you are a young acolyte, you may [deliver blessings to the flock] and if you are a skilled cleric, we need you to [hunt bandit binders].



else



>**Gehna Solbenya says:** You have proven yourself not only an enemy of the Knights of Thunder, but an enemy of Karana himself. Now leave, sewer rat!


**You say:** `deliver.* flock`








if **Faction** >= Amiable then



>**Gehna Solbenya says:** Then go to the Plains of Karana. It is there that the blessings are needed. Ask every resident of the plains if they are followers of Karana. If they are, then ask them if they [require Karana's blessings]. Let them drink from this temple chalice. Return the empty chalice to me and you shall never go thirsty again.



**You receive:**  [A Full Chalice](/item/12103)


elseif **Faction** >= Indifferent then



>**Gehna Solbenya says:** Well, friend, the Temple of Thunder has recognized and appreciates your past deeds for us.  But this matter is of vital importance to us and we need more proof of your devotion to our cause.


else



>**Gehna Solbenya says:** You have proven yourself not only an enemy of the Knights of Thunder, but an enemy of Karana himself. Now leave, sewer rat!


**You say:** `hunt.* binders`



if **Faction** >= Amiable +150 then




>**Gehna Solbenya says:** Go to the Plains of Karana and seek out the Karana Bandits. Among them can be found their bandit binders. They are healers of sorts. Which evil deity granted them this power is unknown to us. Each carries a binder spectacle. I shall reward clerics for every two returned spectacles. Perhaps a new power may even be bestowed.






elseif **Faction** >= Indifferent then



>**Gehna Solbenya says:** Well, friend, the Temple of Thunder has recognized and appreciates your past deeds for us.  But this matter is of vital importance to us and we need more proof of your devotion to our cause.


else



>**Gehna Solbenya says:** You have proven yourself not only an enemy of the Knights of Thunder, but an enemy of Karana himself. Now leave, sewer rat!


**You say:** `karana`



>**Gehna Solbenya says:** Karana, the Rainkeeper, is the provider of the storms. If it were not for the storms of Karana, life would not flourish. All should pay tribute to the Rainkeeper.








**You say:** `bertoxxulous`



>**Gehna Solbenya says:** Bertoxxulous, the Plaguebringer, is the Lord of Disease. It is he who smites Norrath with his diseases and imperfections. Those who follow him are called [Bloodsabers].

**You say:** `bloodsaber`



>**Gehna Solbenya says:** It is rumored that there is a shrine in the great city of Qeynos which pays homage to the Plaguebringer, Bertoxxulous. The members of this vile church of the damned are called the Bloodsabers. They are dreaded shadowknights, necromancers and evil clerics. It is our duty to destroy all who dare to pray to such a deity. Join our fight. Speak more of this matter with Chesgard Sydwend.

**You say:** `heal`



>**Gehna Solbenya says:** If you need to be healed, I suggest you speak with the Priests of Life. You can find them in the Temple of Life on the other side of Qeynos. The only service you can pay for here is holy armor. Daedet Losaren charges followers of Karana for that blessing.
end

## Turn-Ins



local text = "The bounty will not be paid until two spectacles are received.";



if **Faction** >= Amiable and  **You turn in:** [An Empty Chalice](/item/12104)) then


>**Gehna Solbenya says:** You have done a good service for the flock of Karana. Study the words upon this scroll and soon Karana shall keep you from thirst.





* __Faction:__ [Knights of Thunder](/faction/280) (10)


* __Faction:__ [Bloodsabers](/faction/221) (-10)


* __Faction:__ [Priests of Life](/faction/341) (7)


* __Faction:__ [Guards of Qeynos](/faction/262) (7)


 **You receive:** eq.ChooseRandom( [Spell: Yaulp](/item/15210), [Spell: Divine Aura](/item/15207), [Spell: Flash of Light](/item/15201)) (+2000 exp)

elseif **Faction** >= Amiable +150 and  **You turn in:** [A Spectacle](/item/12101), [A Spectacle](/item/12101)) then 


>**Gehna Solbenya says:** Excellent work. These foul men have no right to be proficient in the ways of healing. Here then is your bounty. Use it in your continued war against the Karana bandits.





* __Faction:__ [Knights of Thunder](/faction/280) (20)


* __Faction:__ [Bloodsabers](/faction/221) (-20)


* __Faction:__ [Priests of Life](/faction/341) (15)


* __Faction:__ [Guards of Qeynos](/faction/262) (15)


 **You receive:** eq.ChooseRandom( [Spell: Endure Disease](/item/15226), [Spell: Center](/item/15219)) (+20000 exp)

**This NPC *should* return incorrect items given.**
