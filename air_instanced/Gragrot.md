# Gragrot
## On NPC Spawn

**Set a timer** named *depop* for 300 seconds
## Dialog

**You say:** `hail`



>**Gragrot says:** Hail! So you think you are a mighty Knight of Shadows? We must test these skills. Are you ready to begin the test?

**You say:** `ready`



>**Gragrot says:** Great, let us waste no more time! I offer to you three challenges: Bash, smash, or slash. What do you wish to be tested in?

**You say:** `bash`




>**Gragrot says:** Gragrot like bashin.  Gragrot say you like bashin too!  Give Gragrot an ebon tessera, a sphinx eye opal, and a finely crafted amulet.  Gragrot then give you amulet of the sphinx eye.

**You say:** `smash`




>**Gragrot says:** Gragrot wants you smashin.  Smash, smash, and return a copper disk, a small sapphire, and a silvery ring.  Then Gragrot give you crimson ring of the djinni.

**You say:** `slash`




>**Gragrot says:** Gragrot see you is powerful, but Gragrot wonders if you is good at Slashin. Gragrot says return with a Diaphanous Globe, a piece of dried leather, and a Finely Woven Cloth Belt. Gragrot then give you pegasus hide belt.
end

## Turn-Ins



if( **You turn in:** [Ebon Tessera](/item/20929), [Sphinx Eye Opal](/item/20997), [Finely Crafted Amulet](/item/20998)) then 



>**Gragrot says:** You is powerful! Take this!


 **You receive:**  [Amulet of the Sphinx Eye](/item/27705) (+100000 exp)


**Gragrot despawns.**

elseif( **You turn in:** [Copper Disc](/item/20936), [Small Sapphire](/item/20999), [Silvery Ring](/item/20700)) then 


>**Gragrot says:** You is powerful! Take this!


 **You receive:**  [Crimson Ring of the Djinni](/item/27706) (+100000 exp)


**Gragrot despawns.**

elseif( **You turn in:** [Diaphanous Globe](/item/20943), [Dried Leather](/item/20701), [Finely Woven Cloth Belt](/item/20702)) then 


>**Gragrot says:** Take this belt with the blessing of Veeshan, Soandso.


 **You receive:**  [Pegasus-Hide Belt](/item/2704) (+100000 exp)


**Gragrot despawns.**

**This NPC *should* return incorrect items given.**

## Timer(s)

**Stop timer** named *depop*

**Gragrot despawns.**



