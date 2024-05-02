# Loveal S-Nez



## Dialog

**You say:** `Hail`



>**Loveal S-Nez says:** What is this I see before me? A would-be hero of the Dead? You reek of false bravado. I have seen others much stronger than you meet their fate at theof a blade. I see no reason to continue our conversation. How can one such as you assist with my [delegated duties]?

**You say:** `delegated duties`



>**Loveal S-Nez says:** Why do you ask? I know why. Glory has captured your affections. Those who seek glory find death. Still, you may be of some use. Before I assign you a task, I must be assured of your power. I require you to [perform a test].

**You say:** `perform a test`



if **Faction** >= Amiable then



>**Loveal S-Nez says:** In the Lavastorm Mountain Range there have been sightings of a paladin, one Sir Lindeal. He has compromised our routes between.. well, that is none of your concern. All you need to know is that this paladin of the Temple of Marr must be sent to his everlasting life. Do so and prove your worth to us. I await your proof. Use no assistance. If you are truly his equal then I shall know. I know all.


elseif **Faction** >= Indifferent then



>**Loveal S-Nez says:** When you learn to serve the Dead, then I will find the time to speak of such things.


else



>**Loveal S-Nez says:** How dare you enter my presence?!  In the name of the Dead I should strike you down!




**You say:** `appointed tasks`



if **Faction** >= Amiable then



>**Loveal S-Nez says:** Very well. You have gained the appropriate power. I require you to journey to the Commonlands and seek out Kizdean Gix. He is a member of a very important force. Tell him 'Utalk Adarev Otcin'. Remember this password.


elseif **Faction** >= Indifferent then



>**Loveal S-Nez says:** When you learn to serve the Dead, then I will find the time to speak of such things.


else



>**Loveal S-Nez says:** How dare you enter my presence?!  In the name of the Dead I should strike you down!




**You say:** `Thex Mallet`



if **Faction** >= Amiable then



>**Loveal S-Nez says:** All you can know is that the Thex Mallet is desired by our Queen. If we are not successful in its retrieval, it will be our heads which adorn her trophy room. We have learned its location and believe it to be broken into three separate pieces.


elseif **Faction** >= Indifferent then



>**Loveal S-Nez says:** When you learn to serve the Dead, then I will find the time to speak of such things.


else



>**Loveal S-Nez says:** How dare you enter my presence?!  In the name of the Dead I should strike you down!




**You say:** `queen`



if **Faction** >= Amiable then



>**Loveal S-Nez says:** The Queen of the Teir'Dal is the most powerful of all. It is she who should sit on the throne and not King Naythox. The Dead are her humble servants. We await the day when she shall finally take her rightful position as ruler of Neriak.


elseif **Faction** >= Indifferent then



>**Loveal S-Nez says:** When you learn to serve the Dead, then I will find the time to speak of such things.


else



>**Loveal S-Nez says:** How dare you enter my presence?!  In the name of the Dead I should strike you down!




**You say:** `king`



if **Faction** >= Amiable then



>**Loveal S-Nez says:** A competent and powerful warrior, but a warrior nonetheless. He has suppressed the true glory of the Teir'Dal. Perhaps it is time for a new ruler of Neriak.


elseif **Faction** >= Indifferent then



>**Loveal S-Nez says:** When you learn to serve the Dead, then I will find the time to speak of such things.


else



>**Loveal S-Nez says:** How dare you enter my presence?!  In the name of the Dead I should strike you down!




**You say:** `innoruuk`



>**Loveal S-Nez says:** He is the Prince of Hate. We are His vessels of destruction. There are no greater servants of Innoruuk than the Dead. His word is law. Once the Teir'Dal obtain the second half of the [scroll of G'han], all Norrath shall be enveloped by His glorious hate.

**You say:** `scroll`



>**Loveal S-Nez says:** The scroll of G'han was scribed long ago by the great necromancer G'han. With it, we can commune directly with Innoruuk. Unfortunately, one portion of the scroll was taken from us by a rogue who was hired by the Koada'Dal. In Felwithe, it doth lie. The Indigo Brotherhood now attempts to reclaim it.

**You say:** `koada`



>**Loveal S-Nez says:** Have you not been educated in the ancient elven language? The three races of elvenkind are designated thus: Teir'Dal are dark elves, Koada'Dal are high elves and Feir'Dal are wood elves.
end
## Turn-Ins



local expansion_flag = eq.get_current_expansion();

local item_awarded = eq.ChooseRandom(5374, 13394);

if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18828" data-url="18828" class="tooltip-link link">Testimony</a>) then


>**Loveal S-Nez says:** So you have succeeded where others have failed. You show promise. Take this then. You shall be a valuable asset to the Dead and soon this shall be of value to one so great. This will help you on your way. Are you still interested in my [appointed tasks]?


Your faction standing with [The Dead](/faction/239) got better (<span class='text-success'>+25</span>)


Your faction standing with [Queen Cristanos Thex](/faction/303) got better (<span class='text-success'>+3</span>)


Your faction standing with [King Naythox Thex](/faction/278) got worse (<span class='text-danger'>-3</span>)


Your faction standing with [Keepers of the Art](/faction/275) got worse (<span class='text-danger'>-3</span>)


Your faction standing with [Eldritch Collective](/faction/245) got worse (<span class='text-danger'>-3</span>)


Your faction standing with [Primordial Malice](/faction/1522) got worse (<span class='text-danger'>-50</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_842.png" alt="" /> <a
                                href="/item/2317" data-url="2317" class="tooltip-link link">Cloak of the Undead Eye</a> (+33750 exp)

**You receive coin:** 1 <img src='/static/icons/item_644.png' width='14' height='14'/> 5 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_567.png" alt="" /> <a
                                href="/item/13390" data-url="13390" class="tooltip-link link">Thex Mallet</a>) then


>**Loveal S-Nez says:** Oh how grand it is!! Look at it!! I feel the power trembling within. Who would have thought such an item would be abandoned? You have performed supremely. Queen Cristanos shall reward me greatly and I shall reward you greatly. Here is my weapon from years past.. the Reaper of the Dead. I believe it has one soul still trapped within.


Your faction standing with [The Dead](/faction/239) got better (<span class='text-success'>+100</span>)


Your faction standing with [Queen Cristanos Thex](/faction/303) got better (<span class='text-success'>+15</span>)


Your faction standing with [King Naythox Thex](/faction/278) got worse (<span class='text-danger'>-15</span>)


Your faction standing with [Keepers of the Art](/faction/275) got worse (<span class='text-danger'>-15</span>)


Your faction standing with [Eldritch Collective](/faction/245) got worse (<span class='text-danger'>-15</span>)


Your faction standing with [Primordial Malice](/faction/1522) got worse (<span class='text-danger'>-200</span>)








 &#127873; **You receive:** None 

 

**This NPC *should* return incorrect items given.**






