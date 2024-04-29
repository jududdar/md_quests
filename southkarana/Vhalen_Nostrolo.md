# Vhalen Nostrolo



## Dialog

**You say:** `hail`



>**Vhalen Nostrolo says:** Nice to meet you.  Do not the plains of Karana abound with life?  This land is truly blessed by the gods.  Would you like to [hear a tune] or will you pass up the opportunity?

**You say:** `hear a tune`



>**Vhalen Nostrolo says:** Inside this heart, I am trapped with the sight of beautiful colors, all memories of your love. They attack me with full might. You left me here in this garden of grey Never to see the true colors of the happiness of day Here in my heart I sit and I cry. You have left me alone and my colors have all died...  What do you think? Is it a [happy tune] or a [sad tune]?

**You say:** `happy tune`



>**Vhalen Nostrolo says:** It does need work. It should make the listener sad. I fear all my best tunes are behind me. That's why I am here. I am trying to write a [new composition].

**You say:** `new composition`



>**Vhalen Nostrolo says:** I have come here to create my greatest composition. I call it 'The Winds of Karana.' Alas, the song sheets have been taken from me. While I, ahem, attended to some personal business, a hermit came and stole two song sheets from my pack. It would be grand if, in your journeys, you were to come upon this hermit of the plains and return my song sheets to me. I would pay dearly. Now, I must get back to my thoughts. Please excuse me.

**You say:** `sad tune`



>**Vhalen Nostrolo says:** It takes a broken heart to truly appreciate that tune. I'm glad you enjoyed it. My dear [Metala] left me one year ago. The wound has healed, but the scar remains. I am presently trying to complete a [new composition]. Maybe that will turn me around.

**You say:** `Metala`



>**Vhalen Nostrolo says:** My dear sweet Metala Highflit. She was a bard I trained and fell in love with. We were perfect together. We composed many love ballads during those years. I just love the way she used to brush the hair away from her face and to see her in the moonlight brought daylight to my soul . We had such times ! I remember once, we had dinner at the Lion's Mane and we ordered a burrow pie for dessert. She got some whipped cream on her nose! Oh, it was so cute... am I [boring] you or should I tell you [where it went wrong]?



**You say:** `boring`



>**Vhalen Nostrolo says:** I understand. I must find a way to lift my spirits so that my audience will also be uplifted. I'm sure my new composition will help me overcome this sadness.

**You say:** `where it went wrong`



>**Vhalen Nostrolo says:** It was like that for years and then it all just ended. She began to hang around some man called Garuc Anehm. She started attending evening functions. She said it was choir practice for the Temple of Life. Do you want to know [what I found out], or am I [boring] you?

**You say:** `what I found out`



>**Vhalen Nostrolo says:** Feeling neglected, I also went to join the choir. To my shock, I learned from High Priestess Jahnda that Metala was never in the choir. When I mentioned that fellow Garuc's name, she gave me a dirty look and would say nothing further.  I must be boring you. You don't want to [hear the...


elseif(e.message:findi("hear the)) then


>**Vhalen Nostrolo says:** I went home to confront Metala.  All I found was an empty house and a note. 'Sorry to leave. Thank you for all you have taught me. My new friends have shown me new paths of pain. My music shall sing for a new generation of bard. Goodbye.' <sigh> I never saw her again . Whatever she has started is twisted and contorted. It is not the music of the soul. She must be stopped before it is too late. Please go! I cannot speak of this further.
end

## Turn-Ins




if( **You turn in:** [Lisera Lute](/item/13114)) then 


>**Vhalen Nostrolo says:** Oh, dear! I forgot to repair Cassius' lute. I shall fix and return it to him myself. Thank you for bringing this to me. Here, please return this note to Cassius. He shall be most happy. Thank you again, good citizen!


* __Faction:__ [League of Antonican Bards](/faction/284) (20)


* __Faction:__ [Knights of Truth](/faction/281) (3)


* __Faction:__ [Guards of Qeynos](/faction/262) (3)


* __Faction:__ [Ring of Scale](/faction/304) (-1)


* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (-1)


 **You receive:**  [Note To Cassius](/item/18803) (+5000 exp)

elseif( **You turn in:** [Winds of Karana sheet 1](/item/13116), [Winds of Karana sheet 2](/item/13119)) then 


>**Vhalen Nostrolo says:** Thank you, my friend. I have just completed the composition. It is a work of art. Here. Have a copy. I hope you have the musical talent required to play it. If not.. Practice, practice, practice!


* __Faction:__ [League of Antonican Bards](/faction/284) (30)


* __Faction:__ [Knights of Truth](/faction/281) (4)


* __Faction:__ [Guards of Qeynos](/faction/262) (4)


* __Faction:__ [Ring of Scale](/faction/304) (-1)


* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (-1)


 **You receive:** eq.ChooseRandom( [Song: Jaxan\`s Jig o\` Vigor](/item/15722), [Song: Selo\`s Accelerando](/item/15717), [Song: Chords of Dissonance](/item/15703), [Song: Chant of Battle](/item/15700)) (+5000 exp)

**This NPC *should* return incorrect items given.**


