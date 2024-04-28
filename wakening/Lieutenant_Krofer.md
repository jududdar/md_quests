# Lieutenant Krofer
## Dialog

**You say:** `hail`




>**Lieutenant Krofer says:** Unless you're the new mercenary reinforcements I suggest you remove yourself from my presence before I decorate the bottom of my boot with your intestines.

elseif( **Faction is** > Indifferent) then


**You say:** `next assignment`




>**Lieutenant Krofer says:** Well, ready or not, this must be done now. Out there in the forest are our enemies. For us to be successful, we must know what they are doing and how they are going about it. Our probing attacks have revealed little so we've decided to send you out to gather any info you can. There must be some sort of messenger out there, bring any info you might find.


**You say:** `prepared`




>**Lieutenant Krofer says:** Very well. We've decided to attack the small Sifaye village northeast of here and I want you to coordinate the attack. I will send you into Kael Drakkel with a request for troop assistance. After the squad is assembled you will lead them to the staging point where you will oversee the battle. Here is the request. Take it to Drioc in the city and return here with the troops.



**You receive:**  [Krofers Requisition](/item/1706)


**You say:** `reinforcement`




>**Lieutenant Krofer says:** Oh? Well then show me your assignment, " .. e.other:Race() .. ".


elseif( **Faction is** == Indifferent) then


**You say:** `next assignment`




>**Lieutenant Krofer says:** You need to prove your dedication to our cause before I can discuss such matters with you.


elseif( **Faction is** < Indifferent) then


**Lieutenant Krofer says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.
end

## Turn-Ins



local text = "Where is the rest, manling?";



if( **Faction is** >= Indifferent and  **You turn in:** [Mercenary Assignment](/item/1702)


>**Lieutenant Krofer says:** Drioc sent you? I suppose one can't expect much from a mercenary. Well then, Soandso, your first assignment will be to clear out some of this forest's annoying populace. Bring me the meat of one of the raptors, the meat of two panthers, and the remains of one of those living puddles of black sludge found in the caves. You will then have your payment.


* __Faction:__ [Kromzek](/faction/448) (10)


* __Faction:__ [Kromrif](/faction/419) (2)


* __Faction:__ [King Tormax](/faction/429) (2)


* __Faction:__ [Claws of Veeshan](/faction/430) (-5)


 **You receive:** 0 (+1000 exp)

elseif( **Faction is** >= Indifferent and  **You turn in:** [Panther Meat](/item/22851), [Panther Meat](/item/22851), [Raptor Meat](/item/22852), [Tar goo strands](/item/1703)


>**Lieutenant Krofer says:** Well, I suppose you may be worth something more than fodder after all. Here is your payment. Speak to me again when you are ready for your next assignment. For now, get some rest, you will need it.


* __Faction:__ [Kromzek](/faction/448) (10)


* __Faction:__ [Kromrif](/faction/419) (2)


* __Faction:__ [King Tormax](/faction/429) (2)


* __Faction:__ [Claws of Veeshan](/faction/430) (-5)


 **You receive:** 0 (+1000 exp)

elseif( **Faction is** > Indifferent and  **You turn in:** [Sifaye messengers report](/item/1704)


>**Lieutenant Krofer says:** Excellent, Soandso. With this we can plan an attack that might actually accomplish something. Here is your payment. You have also earned this cloak, it should help protect you from the clawing undergrowth of this savage land. Your next mission will be more complex and dangerous, however we may be able to spare a laborer or two to assist you. Rest now, and tell me when you are prepared.


* __Faction:__ [Kromzek](/faction/448) (13)


* __Faction:__ [Kromrif](/faction/419) (3)


* __Faction:__ [King Tormax](/faction/429) (3)


* __Faction:__ [Claws of Veeshan](/faction/430) (-6)


 **You receive:**  [Velium Studded Cloak](/item/1705) (+1000 exp)

elseif **You turn in:** [Signed Requisition](/item/1707)


>*Lieutenant Krofer takes the note and looks it over, then sighs and says, 'This will have to be enough. The squad should be here shortly. When they arrive you will march with them to the staging area near the village of those insect Sifaye. When you are satisfied with the formation, give the corporal the order to attack and observe the battle. After the village is destroyed return this report to me and we'll plan our next move.'*


 **You receive:**  [Mission Report](/item/1708) (+1000 exp)


**Spawn NPC:**  [Corporal Hlash](/npc/119022) at (**y:** -699, **x:** -4975)


**Spawn NPC:**  [Berzerker Dolvad](/npc/119025) at (**y:** -697, **x:** -4954)


**Spawn NPC:**  [Berzerker Voldak](/npc/119027) at (**y:** -671, **x:** -4954)


**Spawn NPC:**  [Disciple Atharm](/npc/119028) at (**y:** -672, **x:** -4976)

**This NPC *should* return incorrect items given.**
