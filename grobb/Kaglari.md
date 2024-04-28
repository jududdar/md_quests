# Kaglari

## Dialog

**You say:** `hail`



>**Kaglari says:** SNORT!  HHUUUUCCCSSH..  Peh!  You speak at Kaglari, High Priestess of Dark Ones.  Children of Hate.  Spawn of Innoruuk.  Soandso . speak or be gone!  <SNORT!>  You [wish majik power]?

**You say:** `wish majik power`



if **Faction** >= Amiable then




>**Kaglari says:** GOOD! SNORT!! Innoruuk needs more childrens.  You show majik skill or I give you to Innoruuk.  You bring two snake scales and two bone chips ..<SNORT>..  from old bones.  I teach you majik.  GO!  <SNORT!!>


elseif **Faction** >= Indifferent then



>**Kaglari says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Kaglari says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!

end

## Turn-Ins



if  **Faction** >= Amiable and  **You turn in:** [Bone Chips](/item/13073), [Bone Chips](/item/13073), [Snake Scales](/item/13070), [Snake Scales](/item/13070)


>**Kaglari says:** SNORT!! Good. Innoruuk get special gift. Not you, dis time. Here. Learning majik wid dis. You more want to help Innoruuk?


* __Faction:__ [Dark Ones](/faction/237) (5)


* __Faction:__ [Shadowknights of Night Keep](/faction/308) (1)


* __Faction:__ [Frogloks of Guk](/faction/251) (-1)


 **You receive:**  [Spell: Burst of Flame](/item/15093) (+1000 exp)

elseif  **You turn in:** [A tattered note](/item/18791)


>**Kaglari says:** Good.. Kaglari need you help.. Kaglari teach you majik now.


* __Faction:__ [Dark Ones](/faction/237) (100)


* __Faction:__ [Shadowknights of Night Keep](/faction/308) (25)


* __Faction:__ [Frogloks of Guk](/faction/251) (-15)


 **You receive:**  [Muck Stained Tunic*](/item/13529) (+20 exp)

**This NPC *should* return incorrect items given.**
