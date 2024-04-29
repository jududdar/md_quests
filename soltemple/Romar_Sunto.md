# Romar Sunto
## Dialog

if **Faction** >= Indifferent then


**You say:** `hail`




>**Romar Sunto says:** I am Romar Sunto, servant of Solusek Ro.  I am searching for the [coin] of the mighty enchanter [Tash] - if you are interested in helping me acquire it, I will [reward] you with a powerful spell.  I am also a dispenser of the Staff of Ro, sometimes also called [darkwood staves].


**You say:** `darkwood stave`




>**Romar Sunto says:** Bring me a lambent stone from a hill giant, a sand giant or a griffon and I will give you a darkwood staff.


**You say:** `tash`




>**Romar Sunto says:** Tash was a mighty enchanter and a master jewelcrafter.


**You say:** `reward`




>**Romar Sunto says:** I will reward you with a scroll for the spell Tashania. For personal use, of course.


**You say:** `coin pouch`




>**Romar Sunto says:** I will gladly lend you this coin pouch - put all 10 antique silver coins into it and combine them into the Coin of Tash.



**You receive:**  [A coin pouch](/item/17511)


**You say:** `what.* coin`




>**Romar Sunto says:** Tash had a collection of ten antique silver coins that were left in different cities around the world.  If you were to collect all 10 coins, I would give you a [coin pouch] that would let you combine them into the master coin of Tash.  If you are interested, I will sell you a copy of the Tome of Tash, detailing where the coins were reportedly left, for a mere 50 gold.


else


**Romar Sunto says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!
end

## Turn-Ins




if **Faction** >= Indifferent and  **You turn in:** [Lambent Stone](/item/10000)) then


>**Romar Sunto says:** A stone for a staff - very well.


* __Faction:__ [Temple of Solusek Ro](/faction/415) (1)


* __Faction:__ [Shadowed Men](/faction/416) (-1)


 **You receive:**  [Darkwood Staff](/item/6048) (+1000 exp)

elseif **Faction** >= Indifferent and  **You turn in:** [Radiant Coin of Tash](/item/10793)) then 


>**Romar Sunto says:** The Coin of Tash - fully enchanted! I am in your debt. Here is the scroll of Tashania that was promised to you.


 **You receive:**  [Spell: Tashania](/item/15678) (+20000 exp)

elseif **Faction** >= Indifferent and  **You turn in:** [Coin of Tash](/item/10790)) then 


>**Romar Sunto says:** The Coin of Tash. It is of no use to me like this. You must take the coin to Tarn Visilin in High Keep to get it enchanted.


 **You receive:**  [Coin of Tash](/item/10790) 

elseif **Faction** >= Indifferent and  **You turn in:** gold = 50) then 


e.other:Say("Once you combine the coins within the pouch, you must take the Coin of Tash to Tarn Vislin in the HighKeep library to get it enchanted.  Give him the coin and he will enchant it for you.");





* __Faction:__ [Temple of Solusek Ro](/faction/415) (1)


* __Faction:__ [Shadowed Men](/faction/416) (-1)


 **You receive:**  [Tome of Tesh](/item/18032) (+500 exp)

**This NPC *should* return incorrect items given.**
