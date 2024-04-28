# Kaiaren

## On NPC Spawn

**Set a timer** named *1* for 3600 seconds
## Dialog

if(**You possess item:**  [Book of Celestial Fists](/item/1689) x 1


**You say:** `lheao`




>**Kaiaren says:** Hmmm, never heard of him. Well, it doesn't matter, the book is here now. Curse that idiot for writing it in the first place. Not even sure why I let him stick around. If you ever see that clown monk Aradiel kick him in the shins for me! At any rate, I suppose you'd like to find the Fists and [have a nice chat with them], eh? Their master owes me much. I would reward you well if you were to bring me proof of the master's defeat.


**You say:** `have a nice chat with them`




>**Kaiaren says:** Yes, I suppose you would. All you children looking for fame and glory will eventually learn the poison of ambition. But how will you find them? They are able to meld with their elements seamlessly and they certainly have no interest in fooling with the likes of you. No, you will need to get their attention. Fortunately, I know [how you can do this].


**You say:** `how can i do this`




>**Kaiaren says:** My guess is that the weakest of the Fists will be the easiest to draw out. He is egotistical and arrogant. How he came to master the Discipline of Fire, I do not know. He will most likely be in another form, one of his element. When you find the one you believe to be the Fist, you must challenge him. If you use his true name, Eejag, in your formal challenge, he will respond. A flame can burn intensely but it cannot last for long. Know this when you battle him.

end

## Turn-Ins





if **You turn in:** [Celestial Fists](/item/1683)


>**Kaiaren says:** Now, then. Where did you find this, monk? This is not just some light reading to be borrowed from the town library. Who gave this to you?


 **You receive:**  [Book of Celestial Fists](/item/1689) 

elseif **You turn in:** [Charred Scale](/item/1684)


>**Kaiaren says:** Ahhh, impressive indeed! Now that you have broken the chain of the Fists, the others may come toppling down if you persevere. The Fist of Air is now the weakest, then Earth, and finally Water before the master of them all, Vorash. You must defeat them in order, proving the demise of the last to draw out the one you are after. The task before you now is to take this scale and show it to the Fist of Air wherever he may be. Good luck.


 **You receive:**  [Charred Scale](/item/1684) 

elseif **You turn in:** [Demon Fangs](/item/1688), [Book of Celestial Fists](/item/1689)


>*Kaiaren bows his head and breathes a long sigh as if relived of a great weight. He then looks up at you and says, 'I honestly did not believe you could have defeated Vorash. Even though he sought nothing but war and bloodshed, it is a life nonetheless and we must mourn him. I will sew these fangs into magical fist wraps and they shall be yours. Remember Xenevorash. A purpose can be found for every situation and individual. To achieve perfection is to perceive this truth.'*


 **You receive:**  [Celestial Fists](/item/10652) 

**This NPC *should* return incorrect items given.**

## Timer(s)

**Kaiaren despawns.**




