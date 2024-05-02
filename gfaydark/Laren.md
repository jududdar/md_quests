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



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_645.png" alt="" /> <a
                                href="/item/12185" data-url="12185" class="tooltip-link link">Useless Token</a>


elseif( **Faction is** == Indifferent) then



>**Laren says:** The Scouts of Tunare have no quarrel with you, but perhaps a few less Crushbone Orcs would prove your worth. Then we shall speak.


else



>**Laren says:** You dare to speak with a loyal member of the Scouts of Tunare?!  You are truly foolish!  Run away, while you still can.




end

## Turn-Ins





if **Faction** >= Amiable +300 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_982.png" alt="" /> <a
                                href="/item/12186" data-url="12186" class="tooltip-link link">Half Elf Head</a>) then 


>**Laren says:** You have proven yourself to be a worthy Scout of Tunare and as such you are worthy to hold the hilt of a scout blade. Remember, rogues in class are we, but in our chests beats the heart of the forest. Our skills are used in defense of Kelethin and her allies. Next you shall speak to Master Tylfon. He will inform you of the [scout silvermesh leggings].


Your faction standing with [Scouts of Tunare](/faction/316) got better (<span class='text-success'>+10</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_575.png" alt="" /> <a
                                href="/item/7321" data-url="7321" class="tooltip-link link">Scouts Blade</a> (+20000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-30 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**


