# Kendrick
## On NPC Spawn

**Set a timer** named *depop* for 300 seconds
## Dialog

**You say:** `hail`



>**Kendrick says:** Great, let us waste no more time! Do you wish to begin your test of Thievery, Silence, or Trickery?

**You say:** `thievery`




>**Kendrick says:** Thievery is absolute. Travel beyond and bring forth an Ivory Tessera, a gem of invigoration, and an inlaid choker to complete the test of thievery and earn the wispy choker of vigor!

**You say:** `silence`




>**Kendrick says:** Silence makes us deadly. Proceed upward and bring to me a spiroc sky totem, a pearlescent globe, and a black griffon feather. Griffon Wing Spauldors shall be yours if you complete this.

**You say:** `trickery`




>**Kendrick says:** Trickery, ahh how Fizzlethorpe blesses us! Adventure and return a mottled spiroc feather, a cracked leather belt, and a sphinxian circlet to complete the test of trickery and earn Renards Belt of Quickness.
end

## Turn-Ins



if( **You turn in:** [Ivory Tessera](/item/20928), [Gem of Invigoration](/item/20984), [Inlaid Choker](/item/20985)) then 



>**Kendrick says:** Excellent! Fizzlethorpe blesses you with this gift.


 **You receive:**  [Wispy Choker of Vigor](/item/14552) (+100000 exp)



**Kendrick despawns.**

elseif( **You turn in:** [Spiroc Sky Totem](/item/20989), [Pearlescent Globe](/item/20942), [Black Griffon Feather](/item/20988)) then 


>**Kendrick says:** These spauldors made from griffon wings will aid you in your ascent to greatness, Soandso.


 **You receive:**  [Griffon Wing Spauldors](/item/2703) (+100000 exp)



**Kendrick despawns.**

elseif( **You turn in:** [Mottled Spiroc Feather](/item/20956), [Cracked Leather Belt](/item/20992), [Sphinxian Circlet](/item/20993)) then 


>**Kendrick says:** If one is slow, he dies a quick death. With this belt, you can avoid all that with nary a breath.


 **You receive:**  [Renard's Belt of Quickness](/item/11676) (+100000 exp)



**Kendrick despawns.**

**This NPC *should* return incorrect items given.**

## Timer(s)

**Stop timer** named *depop*

**Kendrick despawns.**




