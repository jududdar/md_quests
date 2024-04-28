# Tymoz


## Dialog

**You say:** `hail`



if **Faction** >= Dubious then



>**Tymoz says:** So " .. e.other:Race() .. ", you dare to stand before the mighty Tymoz?  I am the Governor of this village of the Coterie of the Eternal Night.  Do you wish to assist the Coterie, or will you better serve us as sustenance for our eternal lives?


else



**Tymoz says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `assist the coterie`



if **Faction** >= Dubious then



>**Tymoz says:** You have made an intelligent decision my friend.  Our primary foe is the meddling Validus Custodus, the militia of Katta Castellum.  I will reward you for every two damaged custodus legionnaire helms or two damaged custodus centurion helms that you present to me as proof that you have slain members of our enemies ranks.


else



**Tymoz says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

end

## Turn-Ins



local text = "I require two damaged custodus helms as proof of your deeds.";



if **Faction** >= Dubious and  **You turn in:** [Damaged Custodus Legionnaire Helm](/item/31748), [Damaged Custodus Legionnaire Helm](/item/31748)


>**Tymoz says:** Excellent! Two less of those self righteous Validus Custodus goons to worry about!


* __Faction:__ [Coterie of the Eternal Night](/faction/1506) (1)


* __Faction:__ [Validus Custodus](/faction/1503) (-1)


* __Faction:__ [Nathyn Illuminious](/faction/1505) (-1)


* __Faction:__ [Valdanov Zevfeer](/faction/1507) (1)


 **You receive:** None 

elseif **Faction** >= Dubious and  **You turn in:** [Damaged Custodus Centurion Helm](/item/31749), [Damaged Custodus Centurion Helm](/item/31749)


>**Tymoz says:** Excellent! Two less of those self righteous Validus Custodus goons to worry about!


* __Faction:__ [Coterie of the Eternal Night](/faction/1506) (1)


* __Faction:__ [Validus Custodus](/faction/1503) (-1)


* __Faction:__ [Nathyn Illuminious](/faction/1505) (-1)


* __Faction:__ [Valdanov Zevfeer](/faction/1507) (1)


 **You receive:**  [Potent Vitae](/item/31833) (+5000 exp)

**This NPC *should* return incorrect items given.**
