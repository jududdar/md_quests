# Kogna
## Dialog

**You say:** `Hail`



>**Kogna says:** You be tinking you be [real tuff Craknek]?

**You say:** `real tuff craknek`



if **Faction** >= Indifferent +50 then



>**Kogna says:** Me not tinking so. but maybe me wrongs.. no.. me neber wrongs.  You no tuff. only liddle Craknek is you.  You tink you be tuff Craknek. you bringed me four lizard meats.  Me like lizard meats.  You no tuff.  You bringed me lizard [meats].  I make you tuffer Craknek.  Me bestest Craknek.


elseif **Faction** >= Indifferent then




>**Kogna says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Kogna says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `meats`



>**Kogna says:** Yup, meats.  You brings me four, me gives you sumting.
end

## Turn-Ins



if **Faction** >= Indifferent +50 and  **You turn in:** [Lizard Meat](/item/13410), [Lizard Meat](/item/13410), [Lizard Meat](/item/13410), [Lizard Meat](/item/13410)


>**Kogna says:** No, I donut tink so. Who gived you? Bah, me most tuffest Craknek, but me no lier. Me help you be tuffer Craknek. Who gived you dese? Maybe you finded dead lizards, yes, dat it. Bah, taking dis and kills more tings. You learned much, com see me, I teaches you best Craknek ways. Keep eye on dem Greenbloods, dey nasty and not so tuff.


* __Faction:__ [Craknek Warriors](/faction/232) (5)


* __Faction:__ [Clurg](/faction/228) (1)


* __Faction:__ [Green Blood Knights](/faction/261) (-1)


 **You receive:** eq.ChooseRandom( [Rusty Two Handed Battle Axe](/item/5025), [Rusty Two Handed Sword](/item/5023)) (+550 exp)

**This NPC *should* return incorrect items given.**





