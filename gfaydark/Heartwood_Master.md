# Heartwood Master
## Dialog

**You say:** `hail`



if **Faction** >= Amiable then



>**Heartwood Master says:** Greetings, child of Tunare. As druids of the Mother of all, we may only use blunt weapons and the scimitar, all other blades are forbidden. Prove your devotion by bringing me a [rusty short sword], a [rusty long sword], a [rusty broad sword], and a [rusty bastard sword]. I will destroy them and reward your faith.


elseif **Faction** >= Indifferent then



>**Heartwood Master says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Heartwood Master says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!

end

## Turn-Ins



local text = "Tunare be praised! Do you have the rest I requested?";



if **You turn in:** [A tattered note](/item/18786)


>**Heartwood Master says:** Welcome! We are the Soldiers of Tunare, the sworn protectors of Faydark. I thank you for joining our cause, we can always use the help. Here, put on this tunic, and let's get started.. you have much to learn.


* __Faction:__ [Soldiers of Tunare](/faction/310) (100)


* __Faction:__ [King Tearis Thex](/faction/279) (15)


* __Faction:__ [Faydarks Champions](/faction/246) (15)


 **You receive:**  [Green and Tan Tunic*](/item/13537) (+20 exp)

elseif **Faction** >= Amiable and  **You turn in:** [Rusty Short Sword](/item/5013), [Rusty Broad Sword](/item/5016), [Rusty Long Sword](/item/5019), [Rusty Bastard Sword](/item/5022)


>**Heartwood Master says:** You have done well, child! Take this as a blessing from Tunare for doing her will.


* __Faction:__ [Soldiers of Tunare](/faction/310) (1)


* __Faction:__ [King Tearis Thex](/faction/279) (1)


* __Faction:__ [Faydarks Champions](/faction/246) (1)


 **You receive:** None 

**This NPC *should* return incorrect items given.**


