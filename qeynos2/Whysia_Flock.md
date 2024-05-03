# Whysia Flock


## Dialog

**You say:** `hail`



>**Whysia Flock says:** Good evening, Soandso. Feel free to take your time browsing. The temple shop is open night and day for your convenience. Most clerics need access to their [scroll strongbox] at all times.

**You say:** `scroll strongbox`



if( **Faction is** < Indifferent) then 



>**Whysia Flock says:** Your mere presence disgusts me. Please remove yourself from my sight. Until you change yourself and your ways, you are unwelcome in the Temple of Life.


else



>**Whysia Flock says:** The scroll strongboxes are kept here. They are used by the temple clerics to hold their valuable scrolls. I tend to the 30 and 40 numbered boxes and [Tyokan] deals with the 20s. Presently all are taken and the waiting list is quite long. If you are here to turn in your key, then please do so. I shall get your scroll for you.


**You say:** `tyokan`



>**Whysia Flock says:** Tyokan Mekase is the day merchant here at the temple shop. He usually arrives around eight in the morning or so.


**You say:** `recharge the Shining Star of Life`



>**Whysia Flock says:** Are you interested in recharging your Shining Star of Life? I can do it for you, but I require the Shining Star of Life and 20 gold.

end



## Turn-Ins






if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_741.png" alt="" /> <a
                                href="/item/6356" data-url="6356" class="tooltip-link link">Shining Star of Light</a>, gold=20) then 


>**Whysia Flock says:** Here you are, then.  May the power of the Prime Healer guide you through life and keep you healthy.




 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_741.png" alt="" /> <a
                                href="/item/6356" data-url="6356" class="tooltip-link link">Shining Star of Light</a> 

 

**This NPC *should* return incorrect items given.**



end