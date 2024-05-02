# Knargon Lanenda
## Arrive at Waypoint Script

if(e.wp == 2) then


>**Knargon Lanenda says:** Hey Pelshia, how's business?


**Signaled to:**  [Pelshia Thuxpire](/npc/2073)

elseif(e.wp == 7) then


>**Knargon Lanenda says:** And what about you, gorgeous? Looking as delightful as ever, I must say.

elseif(e.wp == 18) then


>**Knargon Lanenda says:** So, yeah, that Pelshia, she's all over me. And Renux, too. She was giving me the look, man. I'm telling ya. Zan, all the ladies want a piece of the Knargman.


**Signaled to:**  [Zannsin Resdinet](/npc/2085)
end

## Signals

if(e.signal == 1) then


>**Knargon Lanenda says:** How about you and I go take a stroll under the docks tonight?


**Signaled to:**  [Pelshia Thuxpire](/npc/2073)
end

## Dialog

**You say:** `hail`



if **Faction** >= Dubious then



>**Knargon Lanenda says:** Hey..  What's up? My name's Knargon Lanenda. I just came over here from [Freeport] a couple of months ago. I used to run a big business importing goods from [Faydwer]. If you've been to [Freeport]. I'm sure you've heard of me.


else



>**Knargon Lanenda says:** Heh...  With all you've done, I'm surprised you're still alive.


**You say:** `freeport`



>**Knargon Lanenda says:** It's a long way from here. . .which is a good thing for me.

**You say:** `jracol`



>**Knargon Lanenda says:** I don't know why [Carson] likes that guy ... he's certainly been nothing but trouble for me.

**You say:** `carson`



>**Knargon Lanenda says:** Carson McCabe? He runs that sham of a fortress called [Highpass Hold]. We've been dealing with him for a few years, now. But, lately he seems to be losing control of his business. [Hanns] will whip him into shape pretty soon though, I bet.

**You say:** `shipment`



if **Faction** >= Apprehensive then



>**Knargon Lanenda says:** We have a small shipment of goods coming in later tonight. The [courier] will be waiting outside the city gates. Casually tell the courier [Lovely night for a stroll], and give him this old card as proof that you work for us. Make certain that you are not followed, and return the shipment to me.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_648.png" alt="" /> <a
                                href="/item/13903" data-url="13903" class="tooltip-link link">Bent Playing Card</a>


else



>**Knargon Lanenda says:** Heh...  With all you've done, I'm surprised you're still alive.


**You say:** `courier`



>**Knargon Lanenda says:** The courier that usually runs [McCabe]'s shipment, is that good for nothing J'Racol. I don't trust his kind.

**You say:** `Hanns`



if **Faction** >= Amiable then



>**Knargon Lanenda says:** He is genuinely dangerous. If you think otherwise, you won't be thinking for long.


elseif **Faction** >= Indifferent then



>**Knargon Lanenda says:** The Circle has recognized your deeds and contributions, but I think you need to prove your worth to us a little more.


else



>**Knargon Lanenda says:** Heh...  With all you've done, I'm surprised you're still alive.


**You say:** `renux`



if **Faction** >= Amiable then



>**Knargon Lanenda says:** Ain't she a little vixen?! She wants me, I can tell.


elseif **Faction** >= Indifferent then



>**Knargon Lanenda says:** The Circle has recognized your deeds and contributions, but I think you need to prove your worth to us a little more.


else



>**Knargon Lanenda says:** Heh...  With all you've done, I'm surprised you're still alive.

end

## Turn-Ins




if **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18722" data-url="18722" class="tooltip-link link">Sealed Note For Knargon</a>) then 


>**Knargon Lanenda says:** Hmm. Carson better deal with his little 'problem' soon, it's costing us a lot of money. Hanns is gonna skin us all when he hears this. Go tell Hanns that [Carson has a mole in the Highpass] guards, and see what he wants us to do.


Your faction standing with [Circle of Unseen Hands](/faction/223) got better (<span class='text-success'>+5</span>)


Your faction standing with [Merchants of Qeynos](/faction/291) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Corrupt Qeynos Guards](/faction/230) got better (<span class='text-success'>+1</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Kane Bayle](/faction/273) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:** 0 (+0 exp)

 

local returned = item_lib.return_items(e.self, e.other, e.trade, false)

if ( returned ) then


>**Knargon Lanenda says:** I'm... erm, not quite sure what to do with this, but... thanks, I guess.
end


