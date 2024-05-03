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



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_709.png" alt="" /> <a
                                href="/item/12103" data-url="12103" class="tooltip-link link">A Full Chalice</a>


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



if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_709.png" alt="" /> <a
                                href="/item/12104" data-url="12104" class="tooltip-link link">An Empty Chalice</a>) then


>**Gehna Solbenya says:** You have done a good service for the flock of Karana. Study the words upon this scroll and soon Karana shall keep you from thirst.





Your faction standing with [Knights of Thunder](/faction/280) got better (<span class='text-success'>+10</span>)


Your faction standing with [Bloodsabers](/faction/221) got worse (<span class='text-danger'>-10</span>)


Your faction standing with [Priests of Life](/faction/341) got better (<span class='text-success'>+7</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+7</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15210" data-url="15210" class="tooltip-link link">Spell: Yaulp</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15207" data-url="15207" class="tooltip-link link">Spell: Divine Aura</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15201" data-url="15201" class="tooltip-link link">Spell: Flash of Light</a>) (+2000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-20 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-20 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif **Faction** >= Amiable +150 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_644.png" alt="" /> <a
                                href="/item/12101" data-url="12101" class="tooltip-link link">A Spectacle</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_644.png" alt="" /> <a
                                href="/item/12101" data-url="12101" class="tooltip-link link">A Spectacle</a>) then 


>**Gehna Solbenya says:** Excellent work. These foul men have no right to be proficient in the ways of healing. Here then is your bounty. Use it in your continued war against the Karana bandits.





Your faction standing with [Knights of Thunder](/faction/280) got better (<span class='text-success'>+20</span>)


Your faction standing with [Bloodsabers](/faction/221) got worse (<span class='text-danger'>-20</span>)


Your faction standing with [Priests of Life](/faction/341) got better (<span class='text-success'>+15</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+15</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15226" data-url="15226" class="tooltip-link link">Spell: Endure Disease</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15219" data-url="15219" class="tooltip-link link">Spell: Center</a>) (+20000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-20 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**
