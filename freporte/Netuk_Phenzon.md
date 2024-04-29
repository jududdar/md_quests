# Netuk Phenzon
## Dialog

**You say:** `hail`



>**Netuk Phenzon says:** Welcome Soandso. Let us fill your heart with hate. May you carry that hate unto your fellow citizens. Innoruuk has need of your services. We have A [mission] for you.

**You say:** `mission`



if **Faction** >= Amiable then



>**Netuk Phenzon says:** There is a man called Groflah Steadirt. He frequents a bar here in Freeport during the early evening hours. Our sources tell us he was given a piece of parchment taken from one of our allies. Who that is, is none of your business. We only require you to recover the parchment, which he no doubt has on him. End his life and return the note to me. Do not let me see your miserable face again until you have the parchment.


elseif( **Faction is** == Indifferent) then



>**Netuk Phenzon says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Netuk Phenzon says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!

end

## Turn-Ins




if **Faction** >= Amiable and  **You turn in:** [A tattered flier](/item/18818)) then 


>**Netuk Phenzon says:** It is about time you returned! Innoruuk would be proud of the red you have spread upon the land.


* __Faction:__ [Dismal Rage](/faction/271) (30)


* __Faction:__ [Knights of Truth](/faction/281) (-4)


* __Faction:__ [Opal Darkbriar](/faction/296) (6)


 **You receive:**  [Spell: Siphon Strength](/item/15343) (+500 exp)

**This NPC *should* return incorrect items given.**
;

