# Geeda
## Dialog

**You say:** `hail`



>**Geeda says:** Are not the woods of the Faydarks a lovely sight? Tunare has truly blessed us. It is unfortunate that the orcs of [Crushbone Citadel] have chosen to invade our lands.

**You say:** `crushbone citadel`



>**Geeda says:** Within the Greater Faydarks can be found the entrance to Crushbone Citadel, home of the orcs. They have increased their raids on our lands. We do not know why. The High Elder of Kelethin has instructed us to keep tabs on the orcs' movements. Hmmm.. How would you like to [assist the scouts]?

**You say:** `assist the scouts`



if **Faction** >= Amiable then



>**Geeda says:** We trust this operation to high standing rogues of the Scouts of Tunare. Easy it may be, but the reward is a scout cape. The scout cape is meant for Scouts of Tunare only. Have you [contributed to the Scouts' cause]?


elseif( **Faction is** == Indifferent) then



>**Geeda says:** The Scouts of Tunare have no quarrel with you, but perhaps a few less Crushbone Orcs would prove your worth. Then we shall speak.


else



>**Geeda says:** You dare to speak with a loyal member of the Scouts of Tunare?!  You are truly foolish!  Run away, while you still can.





**You say:** `contributed`



if **Faction** >= Amiable then 



>**Geeda says:** So we have heard. Here, then. Take this coin. Venture into Crushbone and find our scout, Kelynn. He is posing as a slave to gain information. He tries to work very close to an opening in a cave near the moats. Find this point and wait for him to appear. Give him the coin and he shall give you the information you are to return to me.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_647.png" alt="" /> <a
                                href="/item/12184" data-url="12184" class="tooltip-link link">Useless Token</a>


elseif( **Faction is** == Indifferent) then



>**Geeda says:** The Scouts of Tunare have no quarrel with you, but perhaps a few less Crushbone Orcs would prove your worth. Then we shall speak.


else



>**Geeda says:** You dare to speak with a loyal member of the Scouts of Tunare?!  You are truly foolish!  Run away, while you still can.




end

## Turn-Ins





if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/12183" data-url="12183" class="tooltip-link link">Crushbone Information</a>) then


>**Geeda says:** Fine work. We are very grateful. Take this Scout Cape. May you use it to serve Kelethin.


Your faction standing with [Scouts of Tunare](/faction/316) got better (<span class='text-success'>+20</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_840.png" alt="" /> <a
                                href="/item/2914" data-url="2914" class="tooltip-link link">Scouts Cape</a> (+5000 exp)

 

**This NPC *should* return incorrect items given.**
