# Arch Mage Narik


## Dialog

**You say:** `Hail`



if(e.other:Race() == "Dark Elf" or e.other:Race() == "Iksar" or e.other:Race() == "Troll" or e.other:Race() == "Ogre" or e.other:Class() == "Shadowknight" or e.other:Class() == "Necromancer") then



e.self:DoAnim(26);



e.self:Emote("raises a brow and gives an emotionless stare of objective study toward Soandso, 'You seem out of place 


else



e.self:DoAnim(48);



>*Arch Mage Narik gives a gentle smile and polite bow of respect to Soandso, 'Greetings and welcome to the district of Tanaan, traveler. This place of neutrality is quite content to have you among us, learning from us what we humbly can teach you. Many adepts who were adventurers not too different from yourself have stepped forward and offered their memories as present lessons to those willing to learn of them. I myself was a master of the elements in my time, though I do not make this declaration as one that craves due respect for the title. Rather, I hope that you may perhaps be of the same path and if you need tutoring in the way of skills, then I would be more than pleased to oblige your needs.'*


**You say:** `jewel`



>*Arch Mage Narik slams his book shut. 'So, the snake has legs after all! Tell Onirelin if he wants this back, he can come here himself and kiss my. . ., no wait. I have a better idea.' He draws closer and whispers, 'Did Onirelin tell you why I took this jewel? I did it in response to him taking my lady love, Elisha Dirtyshoes. We were to be married until she ran off with him. However, she also ran off with my engagement ring I gave to her. It is quite valuable to me, and I would be most happy to have it back. If you can procure it from her, I'll give Onirelin his jewel back. He's suffered long enough, I think.'*
end

## Turn-Ins



local count =  **You turn in:**  { [Apothic Crown](/item/1239),  [Apothic Robe](/item/1240),  [Apothic Sleeves](/item/1241),  [Apothic Warband](/item/1242),  [Apothic Gloves](/item/1243),  [Apothic Kilt](/item/1244),  [Apothic Boots](/item/1245)}

if **You turn in:** [Nariks Ring](/item/28087)


>**Arch Mage Narik says:** This is truly excellent. You have done well recovering this for me. You may take Onirelin's jewel and also tell him never to set foot near me again. Leave me now, I have much work to do.





 **You receive:**  [Onirelins Jewel](/item/28088) (+100 exp)



if(count > 0) then


repeat



>**Arch Mage Narik says:** Thank you, Soandso.



 **You receive:** eq.ChooseRandom( [Peridot](/item/10028), 10037, 22503, 15981) (+300000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**
