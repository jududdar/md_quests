# Vicus Nonad



[Vicus Nonad](/npc/1047) is a level 26 Human Rogue that spawns in [South Qeynos](/zone/1).



## On NPC Spawn

**Set a timer** named *cough* for 350 seconds


## Timer(s)

if(e.timer == "cough") then


>*Vicus Nonad coughs and wheezes.*
end



## Dialog

**You say:** `hail`



>**Vicus Nonad says:** Greetings, Soandso.  My name is Vicus Nonad. <cough>  I am the official tax collector for the fine city of Qeynos. <cough>  I serve the will of Antonius Bayle, our glorious leader.  <cough>  <cough>  Please excuse my [cough].  <cough>

**You say:** `cough`



>**Vicus Nonad says:** Oh, <cough> I am sorry, but it seems I have fallen a bit ill.  I was caught out in the rain the other day and my chills have gotten the best of me. <cough>  If only someone would [help] me with today's [collections]..  <cough>

**You say:** `help.* collection`



if **Faction** >= Apprehensive then



>**Vicus Nonad says:** Oh thank <cough> you so <cough> <cough> much <cough>..  Here is the official collection box.  Please collect from each merchant on the <cough> [list].  Then bring me back the combined total of all your collections.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_609.png" alt="" /> <a
                                href="/item/17012" data-url="17012" class="tooltip-link link">Tax Collection Box</a>


else



**Vicus Nonad says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `list`



if **Faction** >= Apprehensive then



>**Vicus Nonad says:** Oh.  <cough>  I am sorry..  I forgot to give it to you.  Here you go.  Be sure to give that back when your job is finished.  <cough>



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18009" data-url="18009" class="tooltip-link link">List of Debtors</a>


else



**Vicus Nonad says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

end



## Turn-Ins



local text = "Very good <cough> work. But I need both the full tax collection box and the list of debtors. You did get the [list] from me before you left, right? <cough>";



if **Faction** >= Apprehensive and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_609.png" alt="" /> <a
                                href="/item/13181" data-url="13181" class="tooltip-link link">Full Tax Collection Box</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18009" data-url="18009" class="tooltip-link link">List of Debtors</a>) then


>**Vicus Nonad says:** <cough> Great! Thank you so much. Here is a small gratuity for a job well done. Thank you again. <cough> Antonius Bayle and the People of Qeynos appreciate all yo have done.





Your faction standing with [Antonius Bayle](/faction/219) got better (<span class='text-success'>+10</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+10</span>)


Your faction standing with [Ring of Scale](/faction/304) got worse (<span class='text-danger'>-5</span>)


Your faction standing with [Kane Bayle](/faction/273) got worse (<span class='text-danger'>-10</span>)


Your faction standing with [Merchants of Qeynos](/faction/291) got better (<span class='text-success'>+10</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_615.png" alt="" /> <a
                                href="/item/13053" data-url="13053" class="tooltip-link link">Brass Ring</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_754.png" alt="" /> <a
                                href="/item/10010" data-url="10010" class="tooltip-link link">Copper Amulet</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_767.png" alt="" /> <a
                                href="/item/10018" data-url="10018" class="tooltip-link link">Hematite</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_946.png" alt="" /> <a
                                href="/item/10017" data-url="10017" class="tooltip-link link">Turquoise</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_944.png" alt="" /> <a
                                href="/item/10015" data-url="10015" class="tooltip-link link">Malachite</a>) (+1000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0-2 <img src='/static/icons/item_645.png' width='14' height='14'/> 0-5 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**
