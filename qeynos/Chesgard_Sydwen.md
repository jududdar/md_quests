# Chesgard Sydwen



[Chesgard Sydwen](/npc/1044) is a level 61 Human GM Paladin that spawns in [South Qeynos](/zone/1).



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



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_790.png" alt="" /> <a
                                href="/item/12102" data-url="12102" class="tooltip-link link">Temple Blankets</a>


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




local sash =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_935.png" alt="" /> <a
                                href="/item/12100" data-url="12100" class="tooltip-link link">Bandit Sash</a>}


if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/18839" data-url="18839" class="tooltip-link link">A Sealed Letter</a>) then


>**Chesgard Sydwen says:** Hmmph!! My son is living in a fantasy world. Still, you have done well. Take this as a token of appreciation. It is not much, but it may come in handy.








Your faction standing with [Knights of Thunder](/faction/280) got better (<span class='text-success'>+10</span>)


Your faction standing with [Bloodsabers](/faction/221) got worse (<span class='text-danger'>-10</span>)


Your faction standing with [Priests of Life](/faction/341) got better (<span class='text-success'>+7</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+7</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_565.png" alt="" /> <a
                                href="/item/17005" data-url="17005" class="tooltip-link link">Backpack</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_567.png" alt="" /> <a
                                href="/item/6041" data-url="6041" class="tooltip-link link">Cast-Iron Warhammer</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_643.png" alt="" /> <a
                                href="/item/2139" data-url="2139" class="tooltip-link link">Raw-hide Gorget</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_771.png" alt="" /> <a
                                href="/item/2150" data-url="2150" class="tooltip-link link">Small Raw-hide Mask</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_759.png" alt="" /> <a
                                href="/item/9001" data-url="9001" class="tooltip-link link">Buckler</a>) (+1500 exp)

 


if(sash > 0) then


repeat


>**Chesgard Sydwen says:** Good work, knight! The Karana Bandits have been plaguing the Rainkeepers flock for some time.  Take this as a small reward for your devotion.  Continue the fight against the Karana Bandits.  Ahh... I wish [Cheslin] was equally as skilled.








Your faction standing with [Knights of Thunder](/faction/280) got better (<span class='text-success'>+20</span>)


Your faction standing with [Bloodsabers](/faction/221) got worse (<span class='text-danger'>-20</span>)


Your faction standing with [Priests of Life](/faction/341) got better (<span class='text-success'>+15</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+15</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_592.png" alt="" /> <a
                                href="/item/7012" data-url="7012" class="tooltip-link link">Bronze Dagger</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_762.png" alt="" /> <a
                                href="/item/7013" data-url="7013" class="tooltip-link link">Bronze Rapier</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_776.png" alt="" /> <a
                                href="/item/7014" data-url="7014" class="tooltip-link link">Bronze Spear</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_763.png" alt="" /> <a
                                href="/item/7015" data-url="7015" class="tooltip-link link">Bronze Main Gauche</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_740.png" alt="" /> <a
                                href="/item/7016" data-url="7016" class="tooltip-link link">Bronze Shortened Spear</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_580.png" alt="" /> <a
                                href="/item/5026" data-url="5026" class="tooltip-link link">Bronze Short Sword</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_590.png" alt="" /> <a
                                href="/item/5027" data-url="5027" class="tooltip-link link">Bronze Long Sword</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_569.png" alt="" /> <a
                                href="/item/5028" data-url="5028" class="tooltip-link link">Bronze Battle Axe</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_577.png" alt="" /> <a
                                href="/item/5029" data-url="5029" class="tooltip-link link">Bronze Bastard Sword</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_519.png" alt="" /> <a
                                href="/item/5030" data-url="5030" class="tooltip-link link">Bronze Two Handed Sword</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_736.png" alt="" /> <a
                                href="/item/5031" data-url="5031" class="tooltip-link link">Bronze Halberd</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_573.png" alt="" /> <a
                                href="/item/5032" data-url="5032" class="tooltip-link link">Bronze Axe</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_605.png" alt="" /> <a
                                href="/item/5033" data-url="5033" class="tooltip-link link">Bronze Broad Sword</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_604.png" alt="" /> <a
                                href="/item/5034" data-url="5034" class="tooltip-link link">Bronze Scimitar</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_579.png" alt="" /> <a
                                href="/item/5035" data-url="5035" class="tooltip-link link">Bronze Scythe</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_603.png" alt="" /> <a
                                href="/item/5036" data-url="5036" class="tooltip-link link">Bronze Claymore</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_568.png" alt="" /> <a
                                href="/item/5037" data-url="5037" class="tooltip-link link">Bronze Two Handed Battle Axe</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_578.png" alt="" /> <a
                                href="/item/6019" data-url="6019" class="tooltip-link link">Bronze Mace</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_567.png" alt="" /> <a
                                href="/item/6021" data-url="6021" class="tooltip-link link">Bronze Two Handed Hammer</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_567.png" alt="" /> <a
                                href="/item/6022" data-url="6022" class="tooltip-link link">Bronze Warhammer</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_741.png" alt="" /> <a
                                href="/item/6023" data-url="6023" class="tooltip-link link">Bronze Flail</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_741.png" alt="" /> <a
                                href="/item/6024" data-url="6024" class="tooltip-link link">Bronze Morning Star</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_542.png" alt="" /> <a
                                href="/item/9002" data-url="9002" class="tooltip-link link">Round Shield</a>) (+8100 exp)

**You receive coin:** 0-1 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-15 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_647.png' width='14' height='14'/> 



sash = sash - 1;


until sash == 0



**This NPC *should* return incorrect items given.**
