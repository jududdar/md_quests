# Hanns Krieghor
## Signals

if(e.signal == 1) then


>**Hanns Krieghor says:** Yes, I just got some new information from Prak this evening. He says they found out the spy is working for some bandit in the Karanas named Rujahn Tahslek. You used to work out there. do you recognize the name?


**Signaled to:**  [Zannsin Resdinet](/npc/2085)

elseif(e.signal == 2) then


>**Hanns Krieghor says:** Hmmff.. Anyway, send someone to Prak. I want this job done quickly. Let's show these pathetic bandits that they've been nosing around in the wrong places.


**Signaled to:**  [Zannsin Resdinet](/npc/2085)

elseif(e.signal == 3) then


>**Hanns Krieghor says:** Lomarc is already back. He sent word that the guards are on to him, so he's laying low for a bit. He also said the cost for delivery just went up, because he had to pay off the owner of the Mermaid's Lure.


**Signaled to:**  [Renux Herkanor](/npc/2033)

elseif(e.signal == 4) then


>**Hanns Krieghor says:** Finally, the rat comes out of his hole! Send some men, no no, go yourself, and track him down. Then kill him. I don't care who sees you, or who gets in your way. Finish the job. And bring me whatever you find on his carcass. I'm sure he took some valuables from us when he escaped. And don't worry about Malka, she will keep until you finish Stanos, then she is yours. Shame to waste such talent, but you don't steal from the Circle and live.


**Signaled to:**  [Renux Herkanor](/npc/2033)
end

## Dialog

**You say:** `hail`



>**Hanns Krieghor says:** My name is Hanns..  Do as I say, and we shall get along just fine.

**You say:** `knargon`



>**Hanns Krieghor says:** That little weasel is scurrying around here somewhere, I suppose.

**You say:** `carson has a mole in the highpass`



>**Hanns Krieghor says:** Arrgg, that Carson can't control anything. Sometimes he's practically useless. Go tell Zannsin that [I want him to send some of his men to Prak in Highpass], to help Carson get back on track.

**You say:** `stanos`



>**Hanns Krieghor says:** Stanos Herkanor? <he roars in frustration> That bastard should be long dead by now. if you see him, you hightail it back and let me know at once. Do I make myself clear, Soandso? Do not speak to him, do not attack him, just return here and inform me. And that is ALL you need to know about Stanos.


e.self:DoAnim(60); 
end

## Turn-Ins




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_864.png" alt="" /> <a
                                href="/item/18708" data-url="18708" class="tooltip-link link">Napkin From Crows</a>) then 


>**Hanns Krieghor says:** Lucky thing you weren't followed. or you'd be breathing through holes in your back right now. Go find Knargon, maybe you can help run the next [shipment]. Remember, we keep our business quiet, so watch yourself, sewer crawler.


Your faction standing with [Circle of Unseen Hands](/faction/223) got better (<span class='text-success'>+100</span>)


Your faction standing with [Merchants of Qeynos](/faction/291) got worse (<span class='text-danger'>-15</span>)


Your faction standing with [Corrupt Qeynos Guards](/faction/230) got better (<span class='text-success'>+15</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got worse (<span class='text-danger'>-15</span>)


Your faction standing with [Kane Bayle](/faction/273) got better (<span class='text-success'>+10</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_678.png" alt="" /> <a
                                href="/item/13501" data-url="13501" class="tooltip-link link">Second Hand Tunic*</a> (+20 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_982.png" alt="" /> <a
                                href="/item/28058" data-url="28058" class="tooltip-link link">Head of Stanos</a>) then


>**Hanns Krieghor says:** YES! The bastard is dead, finally. I would have loved to do the work myself, but this will suffice. Here, take this, you have proven yourself a true friend of the Circle!





Your faction standing with [Circle of Unseen Hands](/faction/223) got better (<span class='text-success'>+200</span>)


Your faction standing with [Merchants of Qeynos](/faction/291) got worse (<span class='text-danger'>-30</span>)


Your faction standing with [Corrupt Qeynos Guards](/faction/230) got better (<span class='text-success'>+30</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got worse (<span class='text-danger'>-30</span>)


Your faction standing with [Kane Bayle](/faction/273) got better (<span class='text-success'>+20</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_575.png" alt="" /> <a
                                href="/item/7501" data-url="7501" class="tooltip-link link">Fanged Skull Stiletto</a> (+0 exp)

 

**This NPC *should* return incorrect items given.**
;

