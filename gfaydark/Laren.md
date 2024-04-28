# Laren
## Dialog

**You say:** `hail`



>**Laren says:** Welcome, my friend! What is it you seek from Laren and the Scouts of Tunare?

**You say:** `scouts blade`



if **Faction** >= Amiable then



>**Laren says:** So you have heard of the dagger created especially for the rogues of Kelethin! The creator of these blades has since passed away. We mourn his death. And, I am sorry to say, we have no more to offer our new scouts. There is a way though.. A way to gain a blade and a way to [avenge the craftsman].


elseif( **Faction is** == Indifferent) then



>**Laren says:** The Scouts of Tunare have no quarrel with you, but perhaps a few less Crushbone Orcs would prove your worth. Then we shall speak.


else



>**Laren says:** You dare to speak with a loyal member of the Scouts of Tunare?!  You are truly foolish!  Run away, while you still can.





**You say:** `avenge the craftsman`



if **Faction** >= Amiable +300 then 



>**Laren says:** You must journey to Antonica. Seek out a castle high in the Serpent's Spine. A castle called Highkeep. Search for a man named Fenn Kaedrick. Give him this token and he shall know why you were sent. Perhaps the merchants will know of his whereabouts. Go at once. I have faith in you. Good luck, Soandso.



**You receive:**  [Useless Token](/item/12185)


elseif( **Faction is** == Indifferent) then



>**Laren says:** The Scouts of Tunare have no quarrel with you, but perhaps a few less Crushbone Orcs would prove your worth. Then we shall speak.


else



>**Laren says:** You dare to speak with a loyal member of the Scouts of Tunare?!  You are truly foolish!  Run away, while you still can.




end

## Turn-Ins





if **Faction** >= Amiable +300 and  **You turn in:** [Half Elf Head](/item/12186)


>**Laren says:** You have proven yourself to be a worthy Scout of Tunare and as such you are worthy to hold the hilt of a scout blade. Remember, rogues in class are we, but in our chests beats the heart of the forest. Our skills are used in defense of Kelethin and her allies. Next you shall speak to Master Tylfon. He will inform you of the [scout silvermesh leggings].


* __Faction:__ [Scouts of Tunare](/faction/316) (10)


 **You receive:** None 

**This NPC *should* return incorrect items given.**


