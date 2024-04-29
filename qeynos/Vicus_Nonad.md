# Vicus Nonad
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



**You receive:**  [Tax Collection Box](/item/17012)


else



**Vicus Nonad says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `list`



if **Faction** >= Apprehensive then



>**Vicus Nonad says:** Oh.  <cough>  I am sorry..  I forgot to give it to you.  Here you go.  Be sure to give that back when your job is finished.  <cough>



**You receive:**  [List of Debtors](/item/18009)


else



**Vicus Nonad says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

end

## Turn-Ins



local text = "Very good <cough> work. But I need both the full tax collection box and the list of debtors. You did get the [list] from me before you left, right? <cough>";



if **Faction** >= Apprehensive and  **You turn in:** [Full Tax Collection Box](/item/13181), [List of Debtors](/item/18009)) then


>**Vicus Nonad says:** <cough> Great! Thank you so much. Here is a small gratuity for a job well done. Thank you again. <cough> Antonius Bayle and the People of Qeynos appreciate all yo have done.





* __Faction:__ [Antonius Bayle](/faction/219) (10)


* __Faction:__ [Guards of Qeynos](/faction/262) (10)


* __Faction:__ [Ring of Scale](/faction/304) (-5)


* __Faction:__ [Kane Bayle](/faction/273) (-10)


* __Faction:__ [Merchants of Qeynos](/faction/291) (10)


 **You receive:** eq.ChooseRandom( [Brass Ring](/item/13053), [Copper Amulet](/item/10010), [Hematite](/item/10018), [Turquoise](/item/10017), [Malachite](/item/10015)) (+1000 exp)

**This NPC *should* return incorrect items given.**
