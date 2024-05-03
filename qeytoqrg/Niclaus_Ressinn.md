# Niclaus Ressinn


## Dialog

**You say:** `hail`



>**Niclaus Ressinn says:** Hail, Soandso.  I am Niclaus Ressinn, loyal Paladin of Life. I am scouting the Qeynos Hills on orders from High Priestess Jahnda.  We have received reports of undead prowling these hills of late.

**You say:** `undead`



>**Niclaus Ressinn says:** I believe the undead prowl these hills at night. I have found the remains of several adventurers who obviously had the misfortune of running into some of Bertoxxulous' dark minions. One young human was still clutching this parchment in his cold, dead fist.

**You say:** `parchment`



if( **Faction is** > Indifferent) then



>**Niclaus Ressinn says:** I believe it is from a spell book of some kind and I do not have a working knowledge of things arcane. Perhaps you could help? Take it. I am sure someone in Qeynos could decipher it. I must remian here to gather more evidence but please return to me with anything you discover.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_864.png" alt="" /> <a
                                href="/item/13718" data-url="13718" class="tooltip-link link">Torn Parchment</a>

end



## Turn-Ins





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_869.png" alt="" /> <a
                                href="/item/18970" data-url="18970" class="tooltip-link link">Note to Niclaus</a>) then


>**Niclaus Ressinn says:** Oh, things are becoming dire here in Norrath. May Rodcet protect us! I have gathered most of the evidence I will need to present to Jahnda, but I could still use your assistance with one final piece. I need to recover a rib bone from of the undead beasts that wander these hills. Be sure the rib bone comes from one of the putrid skeletons. They are the spawn of Bertoxxulous.


eq.set_global("niclaus","1",1,"H12");

elseif(eq.get_qglobals(e.self,e.other)["niclaus"] == "1" and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_907.png" alt="" /> <a
                                href="/item/13722" data-url="13722" class="tooltip-link link">Putrid Rib Bone</a>) then


>**Niclaus Ressinn says:** Excellent! Rodcet smiles upon us this day! Here, please take this pouch of evidence to Jahnda in the Temple of Life. She will know what we must do. I will remain here to keep an eye out for the minions of Bertoxxlous. Also, accept this small reward as a token of my appreciation of your efforts to rid Norrath of the influence of the Plaguebringer.


eq.delete_global("niclaus");





Your faction standing with [Priests of Life](/faction/341) got better (<span class='text-success'>+50</span>)


Your faction standing with [Knights of Thunder](/faction/280) got better (<span class='text-success'>+15</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+25</span>)


Your faction standing with [Bloodsabers](/faction/221) got worse (<span class='text-danger'>-12</span>)


Your faction standing with [Antonius Bayle](/faction/219) got better (<span class='text-success'>+7</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_582.png" alt="" /> <a
                                href="/item/13724" data-url="13724" class="tooltip-link link">Pouch of Evidence</a> (+4000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0-10 <img src='/static/icons/item_647.png' width='14' height='14'/> 

local returned = item_lib.return_items(e.self, e.other, e.trade, false)

if(returned) then


>**Niclaus Ressinn says:** I'm... erm, not quite sure what to do with this, but... thanks, I guess.
end



## Arrive at Waypoint Script

if(e.wp == 4 or e.wp == 8) then


e.self:DoAnim(62);

elseif(e.wp == 5) then


e.self:SetRunning(true);

elseif(e.wp == 6) then


e.self:DoAnim(29);

elseif(e.wp == 7) then


>**Niclaus Ressinn says:** Guard! Come quick! The undead gather near the ruins of Geupal!


e.self:SetRunning(false);

elseif(e.wp == 9) then


e.self:DoAnim(7);

elseif(e.wp == 10) then


>**Niclaus Ressinn says:** Shh.. The fiends seems to dwell amongst the ruins. They wander off but eventually congregate back here. Shh.. OK NOW! RODCET PROTECT US!


e.self:SetRunning(true);

elseif(e.wp == 11) then


e.self:SetRunning(false);
end
