# Chesgard Sydwen
## Dialog

local fac = e.other:GetFaction(e.self);



**You say:** `hail`



>**Chesgard Sydwen says:** May [Karana] guide you. Are you a [citizen of Qeynos] or a [visitor]?

**You say:** `citizen of qeynos`



>**Chesgard Sydwen says:** Then I would urge you to attend daily services in the Temple of Thunder.  You are a [member of Thunder] are you not?  Or maybe I am mistaken and you are just [lost].

**You say:** `lost`



>**Chesgard Sydwen says:** Then study and spread the words of Karana the Rainkeeper.  May all the storms in your heart be controlled by the Rainkeeper.  You are young to the world just as [Cheslin] is.

**You say:** `member of thunder`


 
if(fac <= 4) then



>**Chesgard Sydwen says:** I welcome you. Karana cares for all of His flock. He bestows a touch of His power upon the souls of the Clerics and Paladins of our temple. We look after His flock. Speaking of which, I require the assistance of a young paladin to [deliver provisions to needy members].


elseif(fac == 5) then



>**Chesgard Sydwen says:** Well, friend, the Temple of Thunder has recognized and appreciates your past deeds for us.  But this matter is of vital importance to us and we need more proof of your devotion to our cause.


else



>**Chesgard Sydwen says:** You have proven yourself not only an enemy of the Knights of Thunder, but an enemy of Karana himself. Now leave, sewer rat!





**You say:** `karana bandit`



>**Chesgard Sydwen says:** In the Plains of Karana can be found the [Karana Bandits]. They plague our followers and dare to use the name of the Rainkeeper as title.  For this, Karana commands their deaths. I have a bounty for every returned Bandit Sash, collectible by members only. For clerics, Gehna has a bounty on Binder Spectacles.

**You say:** `cheslin`



>**Chesgard Sydwen says:** My son, Cheslin, is currently in training to be a Qeynos Guard.  I fear it was not his calling.  He is not quite in our realm of reality.  He spent too many years of playing games of warriors and dragons.  He will be doing his first patrols in Qeynos Hills this week.  If you are near there, I would appreciate it if you would watch and see him safely through his first patrols.  Tell him I sent you.

**You say:** `deliver provisions to needy members`



if(fac <= 4) then




>**Chesgard Sydwen says:** Good show!! Here you are, young knight. Take these blankets to any resident who desires warmth. Ask them if they are followers of Karana, then ask if they require temple blankets. Be careful, the plains are quite dangerous for a young knight.



**You receive:**  [Temple Blankets](/item/12102)


elseif(fac == 5) then



>**Chesgard Sydwen says:** Well, friend, the Temple of Thunder has recognized and appreciates your past deeds for us.  But this matter is of vital importance to us and we need more proof of your devotion to our cause.


else



>**Chesgard Sydwen says:** You have proven yourself not only an enemy of the Knights of Thunder, but an enemy of Karana himself. Now leave, sewer rat!







**You say:** `Karana`



>**Chesgard Sydwen says:** Karana, the Rainkeeper, is the provider of the storms. If it were not for the storms of Karana, life would not flourish. All should pay tribute to the Rainkeeper.







**You say:** `Bertoxxulous`



>**Chesgard Sydwen says:** Bertoxxulous, the Plaguebringer, is the Lord of Disease. It is he who smites Norrath with his diseases and imperfections. Those who follow him are called [Bloodsabers].





**You say:** `Bloodsabers`



>**Chesgard Sydwen says:** It is rumored that there is a shrine in the great city of Qeynos which pays homage to the Plaguebringer, Bertoxxulous. The members of this vile church of the damned are called the Bloodsabers. They are dreaded shadowknights, necromancers and evil clerics. It is our duty to destroy all who dare to pray to such a deity. Join our fight. Speak more of this matter with Chesgard Sydwend.

**You say:** `heal`



>**Chesgard Sydwen says:** If you need to be healed, I suggest you speak with the Priests of Life. You can find them in the Temple of Life on the other side of Qeynos. The only service you can pay for here is holy armor. Daedet Losaren charges followers of Karana for that blessing.







end

## Turn-Ins




local sash =  **You turn in:**  { [Bandit Sash](/item/12100)}


if **You turn in:** [A Sealed Letter](/item/18839)


>**Chesgard Sydwen says:** Hmmph!! My son is living in a fantasy world. Still, you have done well. Take this as a token of appreciation. It is not much, but it may come in handy.








* __Faction:__ [Knights of Thunder](/faction/280) (10)


* __Faction:__ [Bloodsabers](/faction/221) (-10)


* __Faction:__ [Priests of Life](/faction/341) (7)


* __Faction:__ [Guards of Qeynos](/faction/262) (7)


 **You receive:** eq.ChooseRandom( [Backpack](/item/17005), [Cast-Iron Warhammer](/item/6041), [Raw-hide Gorget](/item/2139), [Small Raw-hide Mask](/item/2150), [Buckler](/item/9001)) (+1500 exp)


if(sash > 0) then


repeat


>**Chesgard Sydwen says:** Good work, knight! The Karana Bandits have been plaguing the Rainkeepers flock for some time.  Take this as a small reward for your devotion.  Continue the fight against the Karana Bandits.  Ahh... I wish [Cheslin] was equally as skilled.








* __Faction:__ [Knights of Thunder](/faction/280) (20)


* __Faction:__ [Bloodsabers](/faction/221) (-20)


* __Faction:__ [Priests of Life](/faction/341) (15)


* __Faction:__ [Guards of Qeynos](/faction/262) (15)


 **You receive:** None 



sash = sash - 1;


until sash == 0



**This NPC *should* return incorrect items given.**
