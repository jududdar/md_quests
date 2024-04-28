# Zenita DRin
## Dialog

**You say:** `hail`



>**Zenita DRin says:** Greetings. I would love to chat with you, but I just realized something.. I do not waste time with whelps.

**You say:** `lens`



>**Zenita DRin says:** So you seek the Spare Lens. Yes. I have it. There are only two ways you can obtain it, [fight] the great Zenita or [play a game of chance].

**You say:** `play a game of chance`



>**Zenita DRin says:** Great. It is rather simple. I have five cards and only one is King Naythox. Find it. In order to get one card all you need to do is buy me a bottle of Innoruuks Kiss of Death from the barkeep in Chops N Hops. One bottle for one card. Return the King Naythox card to me and you shall get the Spare Lens.

**You say:** `fight`



>**Zenita DRin says:** Darn!! I was hoping not to hear that word, fight. Oh well.


**Zenita DRin attacks you.**
end

## Turn-Ins




if **You turn in:** [King Card](/item/22298)


>**Zenita DRin says:** Why I will be.. You got it!! I thought I took it out of the deck. Very well. You win the Spare Lens fair and square. Here you are. Now get out of my sight.


 **You receive:**  [A Telescope Lens](/item/13279) (+500 exp)

elseif **You turn in:** [Innoruuk's Kiss of Death](/item/13121)


>**Zenita DRin says:** Let see what card you pulled.


 **You receive:** eq.ChooseRandom( [Castle Card](/item/22293), [Beggar Card](/item/22294), [Joker Card](/item/22295), [Wild Card](/item/22296), [Queen Card](/item/22297), [King Card](/item/22298), [Knight Card](/item/22299)) 

elseif **You turn in:** [Knight Card](/item/22299)


e.self:Say(string.format("Bad luck must be one of your strong suits. You should have been a beggar because you sure aren't a very good %s. You lose!",e.other:Class()));

elseif **You turn in:** [Joker Card](/item/22295)


e.self:Say(string.format("I see you have drawn the card that best represents a %s such as yourself. You lose!",e.other:Race()));

**This NPC *should* return incorrect items given.**


