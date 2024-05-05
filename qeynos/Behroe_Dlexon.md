# Behroe Dlexon



[Behroe Dlexon](/npc/1000) is a level 18 Human Bard that spawns in [South Qeynos](/zone/1).



## Dialog

**You say:** `hail`



if **Faction** >= Dubious +300 then 



>**Behroe Dlexon says:** Ah, greetings, Soandso!  How are you this evening?  Hopefully, you are faring much better than I..  I'm stuck on the night watch here, and never get to see my lovely [Aenia].  Ah..  she is so sweet..  I wrote her this beautiful [ballad], but I fear she may never hear it.


else



>**Behroe Dlexon says:** The League of Antonican Bards is very displeased with your recent actions.   And I don't particularly care for you, or your stench, either!



**You say:** `aenia`



if **Faction** >= Indifferent +50 then



>**Behroe Dlexon says:** Aenia lives in North Qeynos in a little blue house near the Temple of Life with her overprotective father.  Last time he caught me there, he nearly killed me!


elseif **Faction** >= Indifferent then



>**Behroe Dlexon says:** The League of Antonican Bards recognizes your past deeds, and appreciates what you have done for them. But, you must prove your dedication some more... I will say this, you are on the right track to earning our trust, friend.


else



>**Behroe Dlexon says:** The League of Antonican Bards is very displeased with your recent actions.   And I don't particularly care for you, or your stench, either!



**You say:** `ballad`



if **Faction** >= Indifferent +50 then 




>**Behroe Dlexon says:** I wrote this little song for my dearest Aenia, but I can't sing it to her because I'm stuck here on watch duty.  You have a nice voice, Soandso, maybe you could go and sing my song to her for me, huh?  Just make sure you don't sing to Aenia when her father's around, 'cause like I said, he's already tried to kill me for seeing her.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18026" data-url="18026" class="tooltip-link link">The Thornless Rose</a>


elseif **Faction** >= Indifferent then



>**Behroe Dlexon says:** The League of Antonican Bards recognizes your past deeds, and appreciates what you have done for them. But, you must prove your dedication some more... I will say this, you are on the right track to earning our trust, friend.


else



>**Behroe Dlexon says:** The League of Antonican Bards is very displeased with your recent actions.   And I don't particularly care for you, or your stench, either!


end



## Turn-Ins




if **Faction** >= Indifferent +50 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/18027" data-url="18027" class="tooltip-link link">Letter to Behroe</a>) then


>**Behroe Dlexon says:** Ah, thank you, kind Soandso.  You've made two foolish lovebirds very happy.  Please, take this..  Though it is not much, it will help keep you warm on those chilly Karana nights.  It is very good to have a friend such as yourself, and I will one day repay you for your kindness and generosity.





Your faction standing with [League of Antonican Bards](/faction/284) got better (<span class='text-success'>+8</span>)


Your faction standing with [Knights of Truth](/faction/281) got better (<span class='text-success'>+1</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+1</span>)


Your faction standing with [Ring of Scale](/faction/304) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Mayong Mistmoore](/faction/285) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_665.png" alt="" /> <a
                                href="/item/1055" data-url="1055" class="tooltip-link link">Shawl of the Wind Spirit</a> (+50 exp)

 

elseif **Faction** >= Indifferent +50 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18021" data-url="18021" class="tooltip-link link">Jusean's Report Request</a>) then


>*Behroe Dlexon yawns and says, 'Oh, report time already again?  Yeah, here ya go, Soandso.  Be careful around here at night, I've been seeing some rough looking characters lurking about.*





Your faction standing with [League of Antonican Bards](/faction/284) got better (<span class='text-success'>+10</span>)


Your faction standing with [Knights of Truth](/faction/281) got better (<span class='text-success'>+1</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+1</span>)


Your faction standing with [Ring of Scale](/faction/304) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Mayong Mistmoore](/faction/285) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18023" data-url="18023" class="tooltip-link link">Behroe's Report</a> (+50 exp)

 

**This NPC *should* return incorrect items given.**



## On NPC Death

>**Behroe Dlexon says:** Your actions will not go unnoticed! The League of Antonican Bards has many members all over this continent.