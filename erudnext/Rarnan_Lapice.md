# Rarnan Lapice
## Dialog

**You say:** `hail`



>**Rarnan Lapice says:** It is good to meet you. Soandso.  To enter the Temple of Divine Light is to invite Quellious into your body and soul.  Tranquility is our way and. as such. we do all we can to uphold it.  Are you a [cleric of Quellious]. or am I mistaken?

**You say:** `cleric of Quellious`



if **Faction** >= Amiable then



>**Rarnan Lapice says:** I have a small task for you then. Go to the city library and ask the librarian for the book 'The Testament of Vanear'. I shall require it for further studies. Do not return empty-handed or you shall know my rage.


elseif **Faction** >= Indifferent then



>**Rarnan Lapice says:** You have not done much to upset the Peacekeepers of this temple. but we must ask you to prove yourself to us before we may discuss things such as this.


else



>**Rarnan Lapice says:** Leave my sight at once! You are no friend to the Peacekeepers of the Temple of Divine Light.

end

## Turn-Ins




if **Faction** >= Amiable and  **You turn in:** [Testament of Vanear](/item/13991)


>**Rarnan Lapice says:** I sent you after that book ages ago! What took you so long? I have already completed my studies. Luckily I found the original manuscript under my bedroll. I forgot I had kept it there. Take this as a token of my apology. Maybe it will aid you in your next book hunt. I know how cunning those books can be.


* __Faction:__ [Peace Keepers](/faction/298) (50)


* __Faction:__ [Heretics](/faction/265) (12)


* __Faction:__ [High Council of Erudin](/faction/266) (-12)


 **You receive:**  [Spell: Languid Pace](/item/15302) (+12500 exp)

**This NPC *should* return incorrect items given.**
;
