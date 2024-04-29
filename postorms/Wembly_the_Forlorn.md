# Wembly the Forlorn


## Dialog

if (  **Faction is** >= Amiable ) then


**You say:** `hail`




>*Wembly the Forlorn grumbles under his breath, 'Yes, yes, I see you there. No need for you to shout I can see you just fine! Now, what was I saying? Yes that's right... let me know when you are [done].*


**You say:** `done`




>**Wembly the Forlorn says:** Yes done! Weren't you paying attention? Once you've gathered all the pieces of the [key] bring it to me and I'll put them back together for you.


**You say:** `key`




>**Wembly the Forlorn says:** THE Key, you really are as thick skulled as you look. You [agree to help] me and you aren't even paying attention.


**You say:** `agree to help`




>**Wembly the Forlorn says:** You agree to help? Great! I haven't even told you what I needed yet, or why. It is very noble of you to offer me your assistance. I've been trapped here for a little too long, I washed up on the shore still [tied to the mast] of my ship. Wonder that I even survived the storm.


**You say:** `tied to the mast`




>**Wembly the Forlorn says:** The Diaku Raiders, filthy sort if you ask me. I was out on a shipping run, when Diaku attacked, they pillaged all of my goods, then tied me to the mast and left me floating a sea. Then the storm came and ate my ship, and I woke up here, I swear that I saw some [Diaku] washed up on the shore with me.


**You say:** `Diaku`




>**Wembly the Forlorn says:** The Diaku that attacked me! Pay attention for Karana's sake! You appear to be the fighting sort. You can help me kill the Diaku at their source in [Drunder].


**You say:** `Drunder`




>**Wembly the Forlorn says:** Drunder! The Fortress of Zek, the Zeks don't trust any one mortal to have free access to the fortress. The Diaku come and go in fours, and four parts are needed for entry. Of course they won't part with them easily. If you find four, and bring me four, I can make the four into one, and with one, you can get into Drunder without three more. Then, with your one, you can kill all of them. I would do it myself, but with my bad knee and all. . .


else


>**Wembly the Forlorn says:** You need to prove your dedication to our cause before I can discuss such matters with you.
end

## Turn-Ins




if( **You turn in:** [Quarter of a Diaku Emblem](/item/29216), [Quarter of a Diaku Emblem](/item/29217), [Quarter of a Diaku Emblem](/item/29218), [Quarter of a Diaku Emblem](/item/29219)) then




if (  **Faction is** >= Amiable ) then




>**Wembly the Forlorn says:** What's this? Four pieces of a Diaku Emblem? Why ever would you give these to me? Well I think I can get them to fit back together. You know, while you have this, I would be quite happy if you would avenge the loss of my dear ship and kill every Diaku you find? Yes that would be very good indeed. Here is your key, and a key for all your companions as well.



* __Faction:__ [Askr the Lost](/faction/1609) (5)



* __Faction:__ [Storm Guardians](/faction/1618) (5)



 **You receive:**  [Completed Diaku Emblem](/item/29215) (+150000 exp)





else



>**Wembly the Forlorn says:** You need to prove your dedication to our cause before I can discuss such matters with you.


**This NPC *should* return incorrect items given.**
;