# Semkak Prophet of Vallon
## Dialog

if( **Faction is** > Indifferent) then


**You say:** `hail`




>**Semkak Prophet of Vallon says:** You have entered the sacred temple of Vallon Zek. This is the Temple of Strategy. We teach what must be done to be a great leader. Forethought is a powerful tool.


**You say:** `teach`




>**Semkak Prophet of Vallon says:** I cannot teach one of your kind the arts of war at this time. I must teach the other Kromzek and Kromrif that proper strategy will allow us to win the war against the dragons. If you were to serve the temple of Vallon, I might consider giving you a few words of advice about strategy.


**You say:** `serve the temple`




>**Semkak Prophet of Vallon says:** The dragons of Velious are ancient and wise beyond belief. They have ageless strategies to destroy their foes. The Temple of Strategy must gain the knowledge they hold. I have heard rumors of a great dragon burial ground. If this tomb indeed exists, find it and seek out the knowledge of the dragons who are now dead. Bring whatever you believe will teach us their strategies and tactics of the past.


elseif( **Faction is** > Apprehensive) then


>**Semkak Prophet of Vallon says:** You need to prove your dedication to our cause before I can discuss such matters with you.

else


**Semkak Prophet of Vallon says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.
end

## Turn-Ins





if( **Faction is** > Indifferent and  **You turn in:** [Golden Tablet of Draconic Strategy](/item/24986)


>**Semkak Prophet of Vallon says:** This tablet holds great knowledge. The Temple of Strategy thanks you, Soandso. Take this and know that your own strategies are wise indeed if you have acquired this tablet from the depths of the dragons' graveyard.


* __Faction:__ [Kromzek](/faction/448) (20)


* __Faction:__ [Kromrif](/faction/419) (5)


* __Faction:__ [King Tormax](/faction/429) (5)


* __Faction:__ [Claws of Veeshan](/faction/430) (-10)


 **You receive:** eq.ChooseRandom( [Steel Wristband  of Strategy](/item/25036), 25040, 25034, 25035) (+50000 exp)

**This NPC *should* return incorrect items given.**
