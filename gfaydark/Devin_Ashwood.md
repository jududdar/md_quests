# Devin Ashwood
## Dialog

**You say:** `hail`



>**Devin Ashwood says:** Good day to you. Soandso!  I am Devin Ashwood.  Pleased to make your acquaintance.

**You say:** `Ganelorn Oast`



>**Devin Ashwood says:** Ganelorn Oast! For he has single-handedly caught more poachers than any other ranger. He is credited for helping numerous endangered species recover from certain extinction. I suppose I am lucky he is fond of my sister, as I am soon to train under him as an apprentice. Perhaps one day I will even [call upon the flames] in the way that he does.


**Signaled to:**  [Lily Ashwood](/npc/54086)

**You say:** `call upon the flames`



if(**Your level** >= 50) then



>**Devin Ashwood says:** Aye, Ganelorn is renowned not only for his abilities as an archer and a master of melee combat, but also for his use of powerful magics. Never before have I seen a forester evoke a fireball of such great force. It would be any ranger's dream to become his pupil just to study that one spell. Ganelorn doesn't train just anyone, though. If you want to learn from him, I'm certain you would have to prove yourself as a forester.


else



**Devin Ashwood says one of the following:**

>Someone with your skills is more suited to beetle slaying.  Run along, now.

>This matter is far too advanced for you to handle.  Come back after you've killed a few more large rats.

>It's much safer for you to spend time fishing than on a dangerous issue like this.

>I think I saw a gnoll pup you could probably defeat, a few miles back.


**You say:** `want to learn`



if(**Your level** >= 50) then



>**Devin Ashwood says:** He is a very busy individual. I believe he is currently in the eastern part of the Karanas trying to track down a poacher. Even if you can track him down, don't get your hopes up.' Lily Ashwood says 'Oh! If you're going to see him, would you please take this letter to him? I trust you, since you're a ranger and all.



**Signaled to:**  [Lily Ashwood](/npc/54086)


else



**Devin Ashwood says one of the following:**

>Someone with your skills is more suited to beetle slaying.  Run along, now.

>This matter is far too advanced for you to handle.  Come back after you've killed a few more large rats.

>It's much safer for you to spend time fishing than on a dangerous issue like this.

>I think I saw a gnoll pup you could probably defeat, a few miles back.



end

## Signals

if(e.signal == 1) then


>**Devin Ashwood says:** Bah! Why would the greatest forester in all of Norrath ask you to marry him? Between his time spent protecting wildlife, hunting poachers and training me, I doubt he has any spare time for a foolish girl like you, sister.


**Signaled to:**  [Lily Ashwood](/npc/54086)
end

