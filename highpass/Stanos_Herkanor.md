# Stanos Herkanor


## On NPC Spawn

**Set a timer** named *depop* for 2000 seconds


## Timer(s)

if ( e.timer == "depop" ) then


**Stanos Herkanor despawns.**




elseif ( e.timer == "call_help" ) then


CallHelp();
end



## Dialog

**You say:** `hail`



>**Stanos Herkanor says:** Ah, the pouch.  This is the first step Anson.  The Circle has to be upset having this taken right out from under them.  That speaks well of the person who did the taking.  Hanns must be even more furious now <chuckle>.


**Signaled to:**  [Anson McBale](/npc/5037)

**You say:** `you`



e.self:DoAnim(63); 


>**Stanos Herkanor says:** <chuckle> You are young, aren't you? I ran [the Circle] out of Qeynos for well over 30 years, and did a right fine job of it. It's a long story, and isn't over yet. I have much to answer for.

**You say:** `circle`



e.self:DoAnim(64); 


>**Stanos Herkanor says:** The Circle of Unseen Hands, you oaf! The largest collection of thieves, murderers, con artists, and rogues in the world. No finer men can be found anywhere.

**You say:** `deal`



>**Stanos Herkanor says:** Aye, Soandso, we could make a deal. I have a blade I won't use anymore, and you have those fine looking daggers Vilnius gave you. Of course, you would have to do something for me first. Let me tell you my [story], then you decide.

**You say:** `story`



>**Stanos Herkanor says:** Johann Krieghor was the leader of the Circle and I was his second-in-command.  He made a dark bargain  with a  Teir'dal General.  The Circle was to assassinate Joren,  the high elf ambassador to Qeynos.  Had the plot worked, it would have weakened the alliance between high elves and humans, and possibly  caused a war between the two powers.  In either case, the Teir'Dal would have profited greatly by this event, and all others would have suffered.  I could not stand by and let this happen, but Johann would not be deterred, for the Teir'Dal had promised him much.  I had no choice but to kill Johann and the Teir'Dal agent.  I made it look like they offed each other, and then I hid the tools.

**You say:** `tools`



>**Stanos Herkanor says:** To allow the assassin to slay a prince, and fight his way back out, a fell blade was crafted. It was small enough to conceal under a garment and yet large enough to strike a mortal blow through armor. Aided by vile Teir'Dal enchantments, it is much more fearsome than it appears. I would gladly rid myself of it, but I fear I can not until I clear my name with Hanns.

**You say:** `general`



>**Stanos Herkanor says:** The General? I know not his true name, only that he is ranked high among the dark elves. He kept his identity secret, and it was only upon the death of his agent that I even learned the smallest amount about him, that of his Generalship. Knowing who he is would aid me greatly.

**You say:** `hanns`



>**Stanos Herkanor says:** Hanns Krieghor was a talented young man, in many ways much more of a man than his father. After the death of [Johann], I raised Hanns as my own son, and grew to love him as such. A few years back, to take revenge upon me for his [father's murder], Hanns seized control of the Circle. At the same time, he sent four of his best killers to finish me. The killers failed, I still live. Hanns still leads the Circle in Qeynos, and still seeks [my head].

**You say:** `murder`



>**Stanos Herkanor says:** Well, it's no great secret now that I was responsible for the death of Johann Krieghor, Hanns Krieghor's father. Johann used to lead the Circle. Hanns was but a pup when his father died at my hand, and became as a son to me. Hanns did not discover that I was the one who killed his father until many years later. For that, he wants [my head].

**You say:** `head`



>**Stanos Herkanor says:** Aye, Soandso, Hanns has wanted me dead for years. He's tried many times, though not personally. He's smart, that one, for not facing me, but foolish for wasting so many good men for naught.

**You say:** `clear.* name`



e.self:DoAnim(64); 


>**Stanos Herkanor says:** I need proof that what I say about Johann is truth, so that Hanns may forgive me. YOU can gather that proof for me. First, travel to Kaladim and Neriak, and there, upon the persons of the rogue guildmasters, you should find that which I seek, two parts of a document I recovered from the dead agent. I entrusted one to Founy, but that trust is gone, and Founy would betray me to Hanns were I to attempt to reclaim it. Tani N'mar has the other, which he should not possess, and keeps it only to spite me, not knowing its real importance. Steal them both, and bring them back to me. And don't let anyone follow you! If I am not around, tell Anson you want to see me.



**You say:** `Joren`



>**Stanos Herkanor says:** Joren was the boon companion to the King of Felwithe, a mighty paladin of great reknown, much loved by all the high elves. To slay him, certain. . .items. . .were crafted to make the job possible. With the death of the Teir'dal agent, and my theft of the [tools], the General was forced to abandon the plot.

**You say:** `help`



>**Stanos Herkanor says:** Well, then, I suppose you should hear my story.

**You say:** `lendel`



>**Stanos Herkanor says:** Lendel, eh?  About time.  Did he send you to help me?  Well, I need someone to follow up on a job for me, track down a fellow named Vilnius, near Qeynos, maybe in the Karanas, and tell him I am STILL waiting for my delivery.

**You say:** `I killed Renux`



>**Stanos Herkanor says:** You killed Renux?  You stupid git of a dog!  Renux was my best work, a killer without peer, without remorse.  All I did to her, I did for a reason, and it made her matchless.  Ravens take your eyes!  All you needed to do was gather evidence.  When Hanns' believed me, Renux would follow.  A hollow victory, it seems.  I suppose you had to do it, but I imagine it cost you in the process.  When this is over, perhaps you and I shall have a reckoning.


Your faction standing with [Highpass Guards](/faction/332) got worse (<span class='text-danger'>-500</span>)
end

function CallHelp()





local StanosFriends ={5019,5038,5107,5056,5055,5050,5051, [Anson McBale](/npc/5037),5009,5053,5060,5061,5054,5069,5134,5052};

for i = 1, #StanosFriends do


eq.signal(StanosFriends[i],1);
end



## Combat



if  Stanos Herkanor enters combat  then


CallHelp();


eq.pause_timer("depop");


**Set a timer** named *call_help* for 330 seconds

else


eq.resume_timer("depop");


**Stop timer** named *call_help*
end



## Signals

if(e.signal == 1) then


>**Stanos Herkanor says:** I tend to agree Anson.  We could make a deal.  I have a blade I won't use anymore, and you have those fine looking daggers Vilnius gave you.  Of course, you would have to do something for me first.  Let me tell you my story, then you decide.
end



## Turn-Ins



local text = "Did you forget something?";


if **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_864.png" alt="" /> <a
                                href="/item/28010" data-url="28010" class="tooltip-link link">Stained Parchment Top</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_864.png" alt="" /> <a
                                href="/item/28011" data-url="28011" class="tooltip-link link">Stained Parchment Bottom</a>) then


>**Stanos Herkanor says:** Excellent!  With this document I can..' <He pauses for a moment>. 'Damnation!  Curse my tired old mind, I forgot that I could not read the document.  It is written in some obscure code or language.  I can't decipher it, but I know someone who can.  Seek out one called Eldreth, an Erudite who used to do work for me.  I know not where he may be found these days, only that he will not be found in Erudin, as they want his head for some misdeed in the past.  Give him the complete parchment, and tell him I sent you.  He owes me.


Your faction standing with [Highpass Guards](/faction/332) got better (<span class='text-success'>+100</span>)


Your faction standing with [Carson McCabe](/faction/329) got better (<span class='text-success'>+15</span>)


Your faction standing with [Merchants of Highpass](/faction/331) got better (<span class='text-success'>+15</span>)


Your faction standing with [Corrupt Qeynos Guards](/faction/230) got better (<span class='text-success'>+5</span>)


Your faction standing with [The Freeport Militia](/faction/330) got better (<span class='text-success'>+5</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_868.png" alt="" /> <a
                                href="/item/28012" data-url="28012" class="tooltip-link link">Combined Parchment</a> (+500 exp)

 


**Stanos Herkanor despawns.**

elseif **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_722.png" alt="" /> <a
                                href="/item/28013" data-url="28013" class="tooltip-link link">Generals Pouch</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_574.png" alt="" /> <a
                                href="/item/7506" data-url="7506" class="tooltip-link link">Jagged Diamond Dagger</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_574.png" alt="" /> <a
                                href="/item/7505" data-url="7505" class="tooltip-link link">Cazic Quill</a>) then


e.self:Say("Very well done.  I leave now to confront Hanns with this evidence.  Even so, it will not be easy to regain his trust.  That is why I need those daggers, in case all else fails.<chuckle>   Bristlebane grant me luck - I can no longer live like a hunted dog.  In any case, I am grateful for your aid.  Take this wretched blade, I can bear it no longer.
I must warn you, I feel it carries Innoruuk's curse; all who are near it learn the meaning of hate. <chuckle>  Ironic, isn't it?  You went to all that work to redeem yourself for a rapier, yet the true reward came when you redeemed another. <chuckle>.  Good luck, Soandso, for much as I, you will need it.");


Your faction standing with [Highpass Guards](/faction/332) got better (<span class='text-success'>+100</span>)


Your faction standing with [Carson McCabe](/faction/329) got better (<span class='text-success'>+15</span>)


Your faction standing with [Merchants of Highpass](/faction/331) got better (<span class='text-success'>+15</span>)


Your faction standing with [Corrupt Qeynos Guards](/faction/230) got better (<span class='text-success'>+5</span>)


Your faction standing with [The Freeport Militia](/faction/330) got better (<span class='text-success'>+5</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1183.png" alt="" /> <a
                                href="/item/11057" data-url="11057" class="tooltip-link link">Ragebringer</a> (+10000 exp)

 


**Stanos Herkanor despawns.**

elseif **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_682.png" alt="" /> <a
                                href="/item/18961" data-url="18961" class="tooltip-link link">Translated Parchment</a>) then


>**Stanos Herkanor says:** Let me see what you have here. Aha, so that's who.. yes, yes! There is one more thing I need you to do. This document tells me who the originator of the plot really was. His name is General V'ghera, which is interesting, as Anson's men have spotted him in Kithicor recently. He will not be easy to get to, but if you give this box to one of his many aides, the General will HAVE to come to investigate. You see, this box used to contain the tools crafted for the assassination. When he arrives, kill him! I need any documents you find on him - with luck it will be enough evidence to convince Hanns that what I say is true. Bring any documents or dispatch cases you find, along with those blades Vilnius made you work so hard for, and we will make a trade.


Your faction standing with [Highpass Guards](/faction/332) got better (<span class='text-success'>+100</span>)


Your faction standing with [Carson McCabe](/faction/329) got better (<span class='text-success'>+15</span>)


Your faction standing with [Merchants of Highpass](/faction/331) got better (<span class='text-success'>+15</span>)


Your faction standing with [Corrupt Qeynos Guards](/faction/230) got better (<span class='text-success'>+5</span>)


Your faction standing with [The Freeport Militia](/faction/330) got better (<span class='text-success'>+5</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_836.png" alt="" /> <a
                                href="/item/28057" data-url="28057" class="tooltip-link link">Sealed Box</a> (+500 exp)

 


**Stanos Herkanor despawns.**

**This NPC *should* return incorrect items given.**
