# Baobob Miller
## Arrive at Waypoint Script

if(e.wp == 3) then


>**Baobob Miller says:** Greetings, sister! I just wanted to make sure no harm had befallen you.


**Signaled to:**  [Chanda Miller](/npc/4052)


e.self:SetRunning(true);

elseif(e.wp == 4) then


e.self:SetRunning(false);

elseif(e.wp == 7) then


eq.set_anim(4055,1);
end

## Signals

>**Baobob Miller says:** But, you will always be my little sister. Fare well, Chanda! See you soon!
## Dialog

**You say:** `hail`



>**Baobob Miller says:** Hello, there. My name is Baobob Miller. My [sister] and I are the best tanners in all of Norath. Wolves are my specialty. A nice wolf skin [garment] would be the perfect accessory to your stylish ensemble.

**You say:** `sister`



>**Baobob Miller says:** My little sister Chanda is the second best tanner around!. Seriously though, she is a very skilled artisan and people travel far and wide to acquire one of her fine bear skin cloaks. I am proud of her. She doesn't really like to meet new people, but if you tell her [Baobob sent you], I am sure she can help get you into some nice bear skin boots.

**You say:** `garment`



>**Baobob Miller says:** I make the finest wolf skin [boots],[cloaks] and [belts] in all of Antonica.

**You say:** `boot`



>**Baobob Miller says:** If you can bring me a wolf skin of medium quality and pay me a fee of say.. hmmmm.. for you.. 15 gold pieces, I think I can make you a pair of boots that will make all of Qeynos envy you.

**You say:** `cloak`



if **Faction** >= Indifferent then



>**Baobob Miller says:** Yes! One of my wold skin cloaks would go very well with your.. eeerr.. style.. Ahem! Let's see.. I think I can get you into one for 21 gold pieces, but, you have to provide the skin, and I make my cloaks with only the highest quality wolf skins.


else



>**Baobob Miller says:** Hmm.. I really would not feel comfortable helping you in that way. You need to prove yourself to me by aiding my friends and family in the Plains of Karana before I will help you.


**You say:** `belt`



>**Baobob Miller says:** Belts are far more forgiving than cloaks or boots. A lesser quality pelt and 5 gold pieces would get you a nice wolf-hide belt.

**You say:** `talym`



>**Baobob Miller says:** Talym Shoontar. He is a fine hunter. He sure can skin a bear faster than any man alive. Last I heard, he was hunting in the Plains of Karana.


**You say:** `mammoth`



>**Baobob Miller says:** Mammoth! That beast is the oldest living bear I have ever heard of. Ten feet tall and full of muscles. If you ever find yourself in the caves of Surefall Glade, make sure to hunt that beast down and send him to his death. We Millers would pay a lot of platinum for a hide like that.
end

## Turn-Ins



local text = "Good work! Now have you the rest of what I require?";





if **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_553.png" alt="" /> <a
                                href="/item/13755" data-url="13755" class="tooltip-link link">High Quality Wolf Skin</a>, gold = 21) then


>**Baobob Miller says:** Here ya go! That should keep ya nice and warm! Be sure to tell all the friends you're going to impress where you got this fine cloak. Although I am sure they probably have heard of me already.


Your faction standing with [Karana Residents](/faction/345) got better (<span class='text-success'>+2</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+1</span>)


Your faction standing with [Priests of Life](/faction/341) got better (<span class='text-success'>+1</span>)


Your faction standing with [Knights of Thunder](/faction/280) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_840.png" alt="" /> <a
                                href="/item/2905" data-url="2905" class="tooltip-link link">Wolf-hide Cape</a> (+50 exp)

 



elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_553.png" alt="" /> <a
                                href="/item/13754" data-url="13754" class="tooltip-link link">Medium Quality Wolf Skin</a>, gold = 15) then


>**Baobob Miller says:** They are exquisite, if I do say so myself. Hope they fit.


Your faction standing with [Karana Residents](/faction/345) got better (<span class='text-success'>+2</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+1</span>)


Your faction standing with [Priests of Life](/faction/341) got better (<span class='text-success'>+1</span>)


Your faction standing with [Knights of Thunder](/faction/280) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_525.png" alt="" /> <a
                                href="/item/2906" data-url="2906" class="tooltip-link link">Wolf-hide Boots</a> (+50 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_553.png" alt="" /> <a
                                href="/item/13753" data-url="13753" class="tooltip-link link">Low Quality Wolf Skin</a>, gold = 5) then


>**Baobob Miller says:** I hate working with such low quality hides. They lack the sheen that makes a high quality pelt look so fine! Anyhow, here's your belt.


Your faction standing with [Karana Residents](/faction/345) got better (<span class='text-success'>+2</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+1</span>)


Your faction standing with [Priests of Life](/faction/341) got better (<span class='text-success'>+1</span>)


Your faction standing with [Knights of Thunder](/faction/280) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_564.png" alt="" /> <a
                                href="/item/2907" data-url="2907" class="tooltip-link link">Wolf-hide Belt</a> (+50 exp)

 

**This NPC *should* return incorrect items given.**
