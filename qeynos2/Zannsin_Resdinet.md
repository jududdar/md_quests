# Zannsin Resdinet


## Arrive at Waypoint Script

if(e.wp == 10) then


>**Zannsin Resdinet says:** Hey Hanns.. Have you gotten word from Prak about the spy in Carson's guards?


**Signaled to:**  [Hanns Krieghor](/npc/2074)
end



## Signals

if(e.signal == 1 and e.self:GetX() == 163 and e.self:GetY() == 144) then


>**Zannsin Resdinet says:** Yeah, whatever, Knarg. If I were you, I wouldn't mess around with [Renux]. She's in tight with [Hanns], and you know how he is.

elseif(e.signal == 2) then


>**Zannsin Resdinet says:** [Rujahn] Tahslek, huh? I've never heard of him, but those bandits seem to have a new leader every month or so.

elseif(e.signal == 3) then


>**Zannsin Resdinet says:** I'll send one of our best men to Highpass and eliminate [Rujahn]'s spy.
end



## Dialog

**You say:** `hail`



>**Zannsin Resdinet says:** Hey..  My name's Zannsin, but you can call me [Zan].

**You say:** `zan`



>**Zannsin Resdinet says:** That's what they call me. Now quit bugging me, I have work to do.

**You say:** `renux`



>**Zannsin Resdinet says:** She is second in command around here. She and [Hanns] go way back, from what I hear...  Renux is probably the only person Hanns trusts.

**You say:** `hanns`



>**Zannsin Resdinet says:** Hanns, he runs things around here. Years ago, Hanns took over Ghil's old ring and started up the Circle of Unseen Hands. The Circle quickly took any market opposition out of Qeynos. We currently have connections in Erudin, Highpass and even Freeport.

**You say:** `prak`



>**Zannsin Resdinet says:** Prak owns a small casino out in Highpass.  He helps us keep tabs on what Carson and his men are up to.

**You say:** `knargon`



>**Zannsin Resdinet says:** That kid's just looking for trouble. He better get it together and start proving that he's worth something.

**You say:** `kane`



>**Zannsin Resdinet says:** You sure are nosey...  [Crow] will tell you everything you need to know about Kane.

**You say:** `crow`



>**Zannsin Resdinet says:** Crow owns the bar upstairs...let's just say he's really close friends with [Hanns], so do whatever he asks you...got it?

**You say:** `rujahn`



if( **Faction is** > Amiable) then



>**Zannsin Resdinet says:** Hmm, I see. Maybe you can help us out with this, Soandso, huh? I think it'd be a perfect opportunity for you to prove just how valuable you are to our little organization. Take this letter to Prak at Golden Rooster in Highpass, and see what you can do to help him out.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18795" data-url="18795" class="tooltip-link link">Letter for Prak</a>


else



>**Zannsin Resdinet says:** The Circle has recognized your deeds and contributions, but I think you need to prove your worth to us a little more.

end



## Turn-Ins




if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18028" data-url="18028" class="tooltip-link link">Message to Zannsin</a>) then


>**Zannsin Resdinet says:** Great work, Soandso... The Circle is very pleased with your performance of late, and as a small reward for our more trusted members, I give you this... the cloak of the Unseen Hands. It's good to know that we can count on you to get the job done... here, Soandso, go relax and have some wine, on me.


Your faction standing with [Circle of Unseen Hands](/faction/223) got better (<span class='text-success'>+125</span>)


Your faction standing with [Merchants of Qeynos](/faction/291) got worse (<span class='text-danger'>-18</span>)


Your faction standing with [Corrupt Qeynos Guards](/faction/230) got better (<span class='text-success'>+18</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got worse (<span class='text-danger'>-18</span>)


Your faction standing with [Kane Bayle](/faction/273) got better (<span class='text-success'>+12</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_656.png" alt="" /> <a
                                href="/item/1048" data-url="1048" class="tooltip-link link">Black Leather Cloak</a> (+0 exp)

**You receive coin:** 2 <img src='/static/icons/item_644.png' width='14' height='14'/> 3 <img src='/static/icons/item_645.png' width='14' height='14'/> 6 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**

