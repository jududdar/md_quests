# Eldreth


## Dialog

**You say:** `hail`



>**Eldreth says:** Go away! I'm busy! I don't have time for scoundrels like you! Leave me alone or I shall, um..turn you into, er, a fish or something! That is what us powerful wizards do to those who annoy us! Yes, that is it. A fish! Did that sound scary enough?

**You say:** `that was scary`



>**Eldreth says:** Ha! I knew it. I could see you trembling! Everyone fears an angry wizard and nobody wants to be a fish. I know I detest fish, it is always fish fish fish around here. Fish cakes, fish stew, fish wine, I am sick of fish. But alas, while I am a powerful wizard, I am also a poor one. Oh well, good things come to those who wait. So, why are you here, " .. e.other:Race() .. "?

**You say:** `stanos sent me`



>**Eldreth says:** Stanos? Stanos Herkanor? I thought he was long dead. He nearly got me killed, in any case. What does the old fool want of me now?

**You say:** `translate`



>**Eldreth says:** Ah, codes are my specialty! It's what I did for the Circle before Hanns took over. But the Fox is wrong. I owe him nothing! As a fact, he owes me! He wants this translated - he will have to pay!

**You say:** `pay`



>**Eldreth says:** Aye, pay, and pay you must. I need 100 platinum pieces to begin my work. This tower is old and drafty and it will take that much to make it bearable. And while you're at it, I need something else. I am very busy here and have no time to shop, so bring me back a couple bottles of milk along with your very large bag of platinum, and I will translate anything you wish at that time.
end

## Turn-Ins



local text = "looks at you, obviously expecting more. Did you forget the milk?";





if( **You turn in:** [Bottle of Milk](/item/13087), [Bottle of Milk](/item/13087), [Combined Parchment](/item/28012), platinum = 100) then



>**Eldreth says:** Hmm, interesting. This document is not only encoded, but written in a very obscure language. From what I can gather, it's a variant of elder Teir'Dal, but not one I've encountered. I can not fully translate this, but I know one who can. Find Yendar and give him this.



* __Faction:__ [Order of Three](/faction/342) (400)



* __Faction:__ [Bloodsabers](/faction/221) (-100)



* __Faction:__ [Guards of Qeynos](/faction/262) (60)



* __Faction:__ [Opal Darkbriar](/faction/296) (-60)



 **You receive:**  [Scribbled Parchment](/item/28053) (+500 exp)



**Eldreth despawns.**


**This NPC *should* return incorrect items given.**






