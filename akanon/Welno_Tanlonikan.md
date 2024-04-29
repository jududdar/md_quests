# Welno Tanlonikan


## Dialog

local expansion_flag = eq.get_current_expansion();

if(eq.get_current_expansion() >= 4.0) then


**You say:** `hail`




>**Welno Tanlonikan says:** Greetings there Soandso! I am Welno Tanlonikan Assassin of Akanon. I pride myself on being one of the few to train our younger prospects in the ways of the rogue. If you are a young gnome rogue in training then I might have some [tasks] for you.


**You say:** `tasks`




>**Welno Tanlonikan says:** Well I should hope you are truly a Rogue of Akanon or else I dont have any work for ya! However if you are then I have some things for you to do. I will present you with a magical box that you will use to craft together certain components that will make an armor material. You will then take the material that you have fashioned with the proper pattern to the forge to create your own armor. I will provide you with whatever patterns are necessary along with the armor [recipes] should you so ask.


**You say:** `recipes`




>**Welno Tanlonikan says:** I have the armor recipes for all pieces of Chainmail of the Shadowwalker all you must do is simply ask for whichever piece you want to craft. I can provide you with the recipe for Shadowwalker [Coifs], [Bracers], [Sleeves], [Boots], [Leggings], [Gloves] and [Tunic]. Once you have collected the necessary components for each recipe combine them in this box to fashion the correct material.



**You receive:**  [Welnos Assembly Kit](/item/17254)



**You say:** `boots`




>**Welno Tanlonikan says:** There are many things in the Steamfont Mountains that I am sure you don't want to step in Soandso. To create your boot material you will need to combine 3 Bricks of Crude Bronze, 1 Yellow Reculse Silk, 2 Spiderling Eyes and 1 Mead in your assembly kit. Once you have created the proper material take it to a forge along with this mold to fashion your very own Shadowwalkers Chainmail Boots.



**You receive:**  [Crude Boot Mold](/item/19634)



**You say:** `bracer`




>**Welno Tanlonikan says:** A pair of these here bracers will be a great addition to your armor set there Soandso. To create your bracer material you will need to combine 1 Brick of Crude Bronze, 1 Runaway Clockwork Motor, 1 Infected Rat Liver and 1 Bandage in your assembly kit. Once you have created the proper material take it to a forge along with this mold to fashion your very own Shadowwalkers Chainmail Bracer.



**You receive:**  [Crude Bracer Mold](/item/19632)



**You say:** `coif`




>**Welno Tanlonikan says:** While you should usually be using the shadows to your advantage should you need to face your opponent having a good coif will greatly increase your chances of survival. To create your coif material you will need to combine 2 Bricks of Crude Bronze, 1 Rat Meat, 1 Grikbar Kobold Fur and 1 Throwing Knife in your assembly kit. Once you have created the proper material take it to a forge along with this mold to fashion your very own Shadowwalkers Chainmail Coif.



**You receive:**  [Crude Helm Mold](/item/19631)



**You say:** `gloves`




>**Welno Tanlonikan says:** Well you sure cant pick someones pocket with a broken hand now can you? I agree that gloves would be a great armor piece for you to craft. To create your glove material you will need to combine 3 Bricks of Crude Bronze, 1 Yellow Reculse Silk, 1 Brownie Leg , and 2 Spider Legs in your assembly kit. Once you have created the proper material take it to a forge along with this mold to fashion your very own Shadowwalkers Chainmail Gloves.



**You receive:**  [Crude Gauntlets Mold](/item/19633)



**You say:** `leggings`




>**Welno Tanlonikan says:** What do you think you are doing running around here with no pants on! To create your leggings material you will need to combine 4 Bricks of Crude Bronze, 1 Kobold Tooth, 1 Plague Rat Tail , 1 Bottle and the Torn Cloak of Faerron in your assembly kit. Once you have created the proper material take it to a forge along with this mold to fashion your very own Shadowwalkers Chainmail Leggings.



**You receive:**  [Crude Greaves Mold](/item/19636)



**You say:** `sleeves`




>**Welno Tanlonikan says:** Having the proper sleeves will definitely be to your advantage when in a heated battle. To create your sleeves material you will need to combine 2 Bricks of Crude Bronze, 2 Brownie Brains and 1 Young Ebon Drake Wing in your assembly kit. Once you have created the proper material take it to a forge along with this mold to fashion your very own Shadowwalkers Chainmail Sleeves.



**You receive:**  [Crude Vambrace Mold](/item/19635)



**You say:** `tunic`




>**Welno Tanlonikan says:** I'm glad to see that you have progressed this far in your training and that you are ready to craft your final armor piece. To create your tunic material you will need to combine 5 Bricks of Crude Bronze, 1 Minotaur Scalp, 1 Brownie Parts, 1 Runaway Clockwork Motor, 1 Swirling Mist and the evil Dirolensab\`s Bracer in your assembly kit. Once you have created the proper material take it to a forge along with this mold to fashion your very own Shadowwalkers Chainmail Tunic. When you are finished with your tunic please come back to see me as I have a [favor] to ask of you.



**You receive:**  [Crude Breastplate Mold](/item/19637)



**You say:** `favor`




>**Welno Tanlonikan says:** Well you see I have been working on constructing some new daggers for all new rogues but I am in need of a few items to make my first prototype. If you were able to collect the rare items I am in need of to make this dagger I would be happy to give you the first I make should I be able to create it. Will you [collect] these rare items for me?


**You say:** `collect`




>**Welno Tanlonikan says:** Excellent please seek out 2 Minotaur Scalps and 2 Mountain Lion Jawbones and return to me with them when you are done.


else


**You say:** `hail`




>**Welno Tanlonikan says:** Greetings there Soandso! I am Welno Tanlonikan Assassin of Akanon. I pride myself on being one of the few to train our younger prospects in the ways of the rogue.

end

## Turn-Ins

local expansion_flag = eq.get_current_expansion();



if( **You turn in:** [A note](/item/18776)) then 


>**Welno Tanlonikan says:** Yes, I just knew you'd see it my way, Soandso. Anyway, welcome to our little part of Ak'Anon's underworld. We have to pay a high price to keep our small orgainzation hidden, which keeps us all busy around here. Now throw this on, and let's put you to work.


* __Faction:__ [Deepmuses](/faction/240) (100)



* __Faction:__ [Merchants of Ak`Anon](/faction/288) (15)



* __Faction:__ [Gem Choppers](/faction/255) (15)



* __Faction:__ [Dark Reflection](/faction/238) (-15)



 **You receive:**  [Scuffed Tunic*](/item/13519) (+20 exp)


elseif(expansion_flag >= 4.0 and  **You turn in:** [Minotaur Scalp](/item/9108), [Minotaur Scalp](/item/9108), [Mountain Lion Jawbone](/item/9109), [Mountain Lion Jawbone](/item/9109)) then 


>**Welno Tanlonikan says:** Here is that dagger I promised you Soandso!


 **You receive:**  [Gemmed Shadowwalkers Dagger](/item/9110) 


**This NPC *should* return incorrect items given.**
