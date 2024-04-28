# Phenic Dionicas
## Dialog

**You say:** `hail`



>**Phenic Dionicas says:** Greetings adventurer. I am Phenic Dionicas, Magistrate of the Loyalist Combine Empire. I hope the [vampyres] did not cause you troubles on your journey here. 

**You say:** `vampyres`



>**Phenic Dionicas says:** Aye, the vampyres of the Coterie of the Eternal Night. I was among the first to ever [discover] the vampyre threat when I was just a young boy freshly initiated into the [Validus Custodus].

**You say:** `discover`



>**Phenic Dionicas says:** I was on a routine trade route patrol through the tenebrous mountains and the grimling forest when we were attacked by a pack of the vile undead. The creatures that attacked us wore the garments of Shadow Haven merchants and nearly my entire patrol was slain by their claws and fangs. Only [Heratius Grolden] and myself made it back to the safety of Katta Castellum alive and shortly after I was the only survivor of the attack.

**You say:** `Validus Custodus`



>**Phenic Dionicas says:** The Validus Custodus is the army of the Loyalist Empire. It was formerly known as the Tsaph Katta Militia when the city of Katta Castellum was still being erected upon the cliffs that it now stands. As the city grew and the duties of the militia expanded the governors and magistrates of the time met in council and the Validus Custodus was formed. My father Galin Dionicas was elected the first Commander and Chief of the Validus Custodus. Commander Galin was slain in his sleep the very same night that Heratius body was stolen from the graveyard by the vile Coterie of the Eternal Night. Their deeds shall not go unpunished.

**You say:** `Heratius Grolden`



>**Phenic Dionicas says:** Heratius Grolden was a boyhood friend of mine and a brave legionnaire in the Validus Custodus. He was buried with honor in the graveyard of Katta Castellum. Several nights after his burial Heratius' grave had been dug up and his body was missing. I suspect and fear that the Coterie of the Eternal Night returned for him to make him one of their own. I pray to whatever gods are listening that some day we are able to [track down the defilers]!

**You say:** `track down the defilers`



>**Phenic Dionicas says:** It has been several decades since the first group of vampyres that are responsible for the death of Heratius Grolden were encountered. I have been watching for signs of their origins since that time to little avail. What we do know is that they wore the apparel of merchants from Shadow Haven. How and why they were turned into the bloodsucking creatures they became is still a mystery and shrouded in many rumors. Take this official request form to the merchant records keeper in Shadow Haven and he may be able to provide you with records of any merchant caravans that departed for Katta Castellum within a reasonable time before the attacks and never returned.


**You receive:**  [Request Form](/item/31753)

**You say:** `track down the defilers`



**Phenic Dionicas says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!

**You say:** `Valdanov Zevfeer`



>**Phenic Dionicas says:** Valdanov Zevfeer was a traveling alchemist and magical reagent peddler that used to occasionally visit Katta Castellum. At one point before the initial vampyre attacks he decided to remain in Katta Castellum for a while with the wealthy Katta citizen Nathyn Illuminious. Apparently that decision saved his life as according to the records you have provided the caravan he arrived with never completed the return trip to Shadow Haven. That is as much as I know about the individual as he primarily kept to himself during his stay here.
end

## Turn-Ins



local qglobals = eq.get_qglobals(e.self,e.other);

local text = "I require the Ashes of Valdanov Zevfeer, the Magus Conlegium Token, and the Katta Castellum Badge of Service in order to reward you the honor you strive for.";

if( **Faction is** > Apprehensive and  **You turn in:** [Water-stained note](/item/18330)


>**Phenic Dionicas says:** I was afraid of this. I do not know how much Halle managed to tell you, but we have had our suspicions about one of the Legionnaires ever since she overheard him talking in his sleep. She was meant to get close to him, I guess she found something out... I should have been more careful!  Take this to Governor Markil, it concerns his men and I've no doubt he can handle it. Thank you much for your help.


* __Faction:__ [Concilium Universus](/faction/1561) (2)


* __Faction:__ [Seru](/faction/1483) (-1)


* __Faction:__ [Heart of Seru](/faction/1486) (-1)


 **You receive:**  [Sealed Message](/item/18331) (+1000 exp)

elseif **You turn in:** [Old Merchant Records](/item/18352)


>**Phenic Dionicas says:** Most interesting. One of the names on this list I recognize. The alchemist [Valdanov Zevfeer]. Nathyn Illuminious would know more of Valdanov. Present this badge to Nathyn so that he knows you have been sent by the Magistrates to inquire about this issue and question him about the alchemist.


* __Faction:__ [Concilium Universus](/faction/1561) (2)


* __Faction:__ [Seru](/faction/1483) (-1)


* __Faction:__ [Heart of Seru](/faction/1486) (-1)


 **You receive:**  [Katta Castellum Badge of Service](/item/31752) (+1000 exp)

elseif **You turn in:** [Report of Nathyns Questioning](/item/31755)


>**Phenic Dionicas says:** So Valdanov had an interest in a Vah Shir vampyre?!! Perhaps we should seek out this Vah Shir and find more clues. Take these orders to Legionnaire Falion during his next shift at the Tenebrous Mountains Gate, he will question any travelers that pass by about this mysterious Vah Shir.  Should you locate the Vah Shir Vampyre attempt to present him with your Badge of Service for questioning, he just may agree to cooperate rather than anger the Validus Custodus.


* __Faction:__ [Concilium Universus](/faction/1561) (2)


* __Faction:__ [Seru](/faction/1483) (-1)


* __Faction:__ [Heart of Seru](/faction/1486) (-1)


 **You receive:**  [Orders for Legionnaire Falion](/item/31756) (+1000 exp)

elseif **You turn in:** [A Worn Research Book](/item/18449)


>*Phenic Dionicas  listens to your account of the events that have occurred since last you spoke and reads through the journal. 'This investigation is getting more and more baffling the further we delve. Among other things, I am wondering if the shade that was imprisoned in the chest is the same that was providing Valdanov with the blood for his research. Take the belt that the shade was wearing with these instructions to Governor Lathin at the Magus Conlegium. In the meantime I will pay a visit to Nathyn Illuminious.*


* __Faction:__ [Concilium Universus](/faction/1561) (4)


* __Faction:__ [Seru](/faction/1483) (-1)


* __Faction:__ [Heart of Seru](/faction/1486) (-2)


 **You receive:**  [Instructions for Lathin Firetree](/item/7270) 

elseif **You turn in:** [Enchanted Record of Events](/item/7361)


>**Phenic Dionicas says:** There is much that is disturbing about these revelations. I will make sure the Validus Custodus is alert than they already are to the presence of powerful vampyre among our citizens. If you can find this Valdanov Zevfeer slay him and bring me his ashes your Katta Castellum Badge of Service, and your Magus Conlegium Token I will bestow upon you an honorable reward.


* __Faction:__ [Concilium Universus](/faction/1561) (25)


* __Faction:__ [Seru](/faction/1483) (-2)


* __Faction:__ [Heart of Seru](/faction/1486) (-12)

elseif **You turn in:** [Arbogasts Holy Water](/item/29899)


>*Phenic Dionicas looks at you and smiles despite the fact that you have splashed water all over him- he does not appear to be burning at all.  'Oh, excuse me.  You seem to have spilled your water, here have some of mine my friend.  Good day to you, Soandso,' he says.*


 **You receive:**  [Phenics Water](/item/29898) 

elseif **You turn in:** [Vampyre Volatilis Ashes](/item/7397), [Katta Castellum Badge of Service](/item/31757), [Magus Conlegium Token](/item/7394)


>**Phenic Dionicas says:** You have done a great service for Katta Castellum and the Loyalist Empire. I award you for your honorable Services. Know that you will be remembered for your deeds.


* __Faction:__ [Concilium Universus](/faction/1561) (50)


* __Faction:__ [Seru](/faction/1483) (-5)


* __Faction:__ [Heart of Seru](/faction/1486) (-25)


 **You receive:**  [Loyalist Shield of Honor](/item/7398) (+100000 exp)

**This NPC *should* return incorrect items given.**
