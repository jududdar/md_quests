# Gkrean Prophet of Tallon
## Dialog

if( **Faction is** > Indifferent) then


**You say:** `hail`




>**Gkrean Prophet of Tallon says:** You have entered the sacred temple of Tallon Zek. This is the Temple of Tactics, where we teach what must be done to achieve goals in the most efficient manner.


**You say:** `teach`




>**Gkrean Prophet of Tallon says:** I cannot teach one of your kind the arts of war. I must teach the other Kromzek at this time. If you were to serve the Temple of Tactics I might consider giving you a few words of wisdom.


**You say:** `serve the temple`




>**Gkrean Prophet of Tallon says:** The great father of war, Rallos Zek, wishes the destruction of the inferior race known as the Coldain. As the high priest of Tallon Zek, I see that they use great tactics to evade destruction. Find the ones who teach these tactics to the other Coldain and bring back the books that contain the ancient Coldain tactics and strategies. Do not waste my time without a scroll or book that those tiny beasts hold.


elseif( **Faction is** > Apprehensive) then


>**Gkrean Prophet of Tallon says:** You need to prove your dedication to our cause before I can discuss such matters with you.

else


**Gkrean Prophet of Tallon says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.
end

## Turn-Ins





if( **Faction is** > Indifferent and  **You turn in:** [Brells Divine Strategy](/item/24987)


>**Gkrean Prophet of Tallon says:** You are a brave little beast to gain this tome. Let me impart a bit of wisdom to you. Tactics must change - if you do not ever adapt to new surroundings, environments and rules, you will surely perish.


* __Faction:__ [Kromzek](/faction/448) (20)


* __Faction:__ [Kromrif](/faction/419) (5)


* __Faction:__ [King Tormax](/faction/429) (5)


* __Faction:__ [Claws of Veeshan](/faction/430) (-10)


 **You receive:** eq.ChooseRandom( [Circlet of Tallon](/item/25037), [Book of Tactics](/item/25038), [Gauntlets of Iron Tactics](/item/25039), [Bracelet of Sacrifice](/item/25042)) (+50000 exp)

**This NPC *should* return incorrect items given.**

