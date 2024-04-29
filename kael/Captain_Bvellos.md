# Captain Bvellos



## Dialog

**You say:** `hail`



if **Faction** >= Apprehensive then



>**Captain Bvellos says:** Greetings, Soandso. I am the captain of the Kael militia. I will be watching those of your kind who have come to Kael Drakkel as mercenaries and bounty hunters. You may have come here to serve king Tormax but Kael is my home and I intend to keep it a safe place for the Kromzek. Keep yourself out of trouble or you willup in a world of pain.


else



**Captain Bvellos says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `work`



if **Faction** >= Amiable then



>**Captain Bvellos says:** Are you looking for work, Soandso? I may have a use for one of your kind. I believe that several nobles in this fine city are not all they appear to be. I have suspicions about that filthy Wenglawks. He will do whatever it takes to amass his own wealth. My sources tell me that he may very well be trading with the Coldain, or worse yet, the dragons. If you could find me proof of his underhanded dealings, I would be most pleased.


elseif **Faction** >= Indifferent then



>**Captain Bvellos says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Captain Bvellos says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `proof`



if **Faction** >= Amiable then



>**Captain Bvellos says:** The more convincing the proof is, the better. There must be a record of his actions somewhere.


elseif **Faction** >= Indifferent then



>**Captain Bvellos says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Captain Bvellos says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `safe`



if **Faction** >= Amiable then



>**Captain Bvellos says:** With the influx of mercenaries into Kael Drakkel, I have seen minor crimes increase. I have had to increase my militia patrols. A majority of my militia work longer hours than they did before. There was a time when we only had to watch for the dragons from the sky and the Coldain from the outside. Now we must watch within.


elseif **Faction** >= Indifferent then



>**Captain Bvellos says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Captain Bvellos says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `mercenaries`



if **Faction** >= Amiable then



>**Captain Bvellos says:** I have several bounties open if you are interested. Bring me the head of a Coldain and I will reward you with a small sum of money and spread the word of your good work. There is also a bounty upon the nefarious Icepaw kobolds who serve the outcast Velketor. I require four of the paws of those little beasts.


elseif **Faction** >= Indifferent then



>**Captain Bvellos says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Captain Bvellos says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

end

## Turn-Ins





local head =  **You turn in:**  { [Coldain Head](/item/30081)}



if **Faction** >= Amiable and  **You turn in:** [Icepaw Kobold's Paw](/item/25301), [Icepaw Kobold's Paw](/item/25301), [Icepaw Kobold's Paw](/item/25301), [Icepaw Kobold's Paw](/item/25301)) then


>**Captain Bvellos says:** You have done well to hunt down these foul dogs.


>*Captain Bvellos reaches into a large bag and pulls something shiny from within its depths 'Take this as a reward.*


* __Faction:__ [Kromzek](/faction/448) (40)


* __Faction:__ [Kromrif](/faction/419) (10)


* __Faction:__ [King Tormax](/faction/429) (10)


* __Faction:__ [Claws of Veeshan](/faction/430) (-20)


 **You receive:** eq.ChooseRandom( [Silvery Mask](/item/25077), [Antlered Mask](/item/25084), [Giant Scalemail Tunic](/item/25018)) 

elseif **Faction** >= Amiable and  **You turn in:** [Wurmscale Scroll](/item/1718)) then 


>**Captain Bvellos says:** This indeed points to Wenglawks being a traitor. If only there were more proof I could take this to the king. Thank you, Soandso, you have done a great service for Kael. Take this mask as a reward for your service to this city.


* __Faction:__ [Kromzek](/faction/448) (50)


* __Faction:__ [Kromrif](/faction/419) (12)


* __Faction:__ [King Tormax](/faction/429) (12)


* __Faction:__ [Claws of Veeshan](/faction/430) (-25)


 **You receive:**  [Mask of War](/item/25024) (+1000 exp)


if(head > 0) then



repeat



>**Captain Bvellos says:** Excellent, Soandso. Here is the bounty as promised.



* __Faction:__ [Kromzek](/faction/448) (40)



* __Faction:__ [Kromrif](/faction/419) (10)



* __Faction:__ [King Tormax](/faction/429) (10)



* __Faction:__ [Claws of Veeshan](/faction/430) (-20)



 **You receive:** 0 (+1000 exp)



head = head - 1;


until head == 0


**This NPC *should* return incorrect items given.**
