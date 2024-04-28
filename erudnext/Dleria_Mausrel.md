# Dleria Mausrel
## Dialog

**You say:** `Hail`



>**Dleria Mausrel says:** Hail! You appear to be a [new priest]. Ah, I so enjoy the presence of youth within Deepwater Temple. I am sure Prexus is smiling upon us as we speak.

**You say:** `new priest`



if **Faction** >= Amiable then 



**You say:** `new priest`





>**Dleria Mausrel says:** As I suspected. I shall assist you with your training and you shall assist the temple with your service. A young priest can help out by asking to [convert fishermen in Qeynos] or maybe even something truly great such as requesting to [protect the depths].



**You say:** `protect the depth`





>**Dleria Mausrel says:** We have heard of zombies inhabiting the depths of Erud's Crossing. Go and seek them out. Destroy them. This evil should not exist within the realm of the Ocean Lord. Take this bag. Fill it with their rotting flesh. combine it and return it to me. May Prexus guide you.




**You receive:**  [Empty Bag](/item/17939)



**You say:** `convert fishermen in qeynos`





>**Dleria Mausrel says:** So you wish to journey to Qeynos? So be it. Go to Qeynos and find me a willing convert. Ask them if they wish the blessing of Prexus. If so, they should snap their pole in two and you will return it to me. Do this and be rewarded.




elseif **Faction** >= Indifferent then



>**Dleria Mausrel says:** There is no reason to dislike you, but we of the Deepwater Knights must see more done for our cause before we truly accept you.


else



>**Dleria Mausrel says:** We, the Deepwater Knights, know of your vile ways. You had best leave while you can.

end

## Turn-Ins




if **Faction** >= Amiable and  **You turn in:** [Snapped Pole](/item/13922)


>**Dleria Mausrel says:** Good work, young priest. Soon you shall carry the word of the Ocean Lord to distant lands. For now, continue your training. As for your reward, I have this which has been sitting in our vault. I hope it can be of use to a young priest such as yourself.





* __Faction:__ [Deepwater Knights](/faction/242) (5)


* __Faction:__ [High Council of Erudin](/faction/266) (1)


* __Faction:__ [Heretics](/faction/265) (-1)


 **You receive:** eq.ChooseRandom( [Raw-hide Sleeves](/item/2144), [Raw-hide Gloves](/item/2146), [Raw-hide Leggings](/item/2147), [Backpack](/item/17005)) (+4000 exp)

elseif **Faction** >= Amiable and  **You turn in:** [Bag of Zombie Flesh](/item/13880)


>**Dleria Mausrel says:** Peeuww!! That most certainly is zombie flesh!! Here is your reward. You have done a fine service in the name of Prexus. Soon you shall advance and we may tell you of greater dangers lurking in the depths.





* __Faction:__ [Deepwater Knights](/faction/242) (10)


* __Faction:__ [High Council of Erudin](/faction/266) (1)


* __Faction:__ [Heretics](/faction/265) (-1)


 **You receive:** eq.ChooseRandom( [Raw-hide Sleeves](/item/2144), [Raw-hide Gloves](/item/2146), [Raw-hide Leggings](/item/2147), [Backpack](/item/17005), [Spell: True North](/item/15205), [Spell: Cure Poison](/item/15203), [Spell: Divine Aura](/item/15207), [Spell: Flash of Light](/item/15201), [Spell: Lull](/item/15208), [Spell: Spook the Dead](/item/15209)) (+4000 exp)

**This NPC *should* return incorrect items given.**
;

