# Hemia Skemner


## Dialog

**You say:** `hail`



>**Hemia Skemner says:** How are you? Welcome to the Academy of Arcane Science. Please feel free to roam. May knowledge be your goal. Be you a [fellow scientist] or visitor, I am sure you will find whatever you seek.

**You say:** `fellow scientist`



if **Faction** >= Amiable then



>**Hemia Skemner says:** That is good. I hope you can handle the knowledge of arcane science. Some have gone mad conducting research. Such a person is [Lydl Mastat].


elseif **Faction** >= Indifferent then



>**Hemia Skemner says:** The word of mouth in the Academy of Arcane Science is that you are no foe, but you have yet to prove your worth to us. Perform more tasks for the great Tara Neklene.


else



>**Hemia Skemner says:** You had best leave my sight. I am a faithful member of the Academy of Arcane Science and you are no ally of ours.


**You say:** `lydl mastat`



>**Hemia Skemner says:** Lydl Mastat is nothing more than a young apprentice of mine. He went mad working on a formula for deep water breathing. He now roams the outskirts of Freeport boasting of power he does not have. Someone should [teach Lydl a lesson].

**You say:** `teach lydl a lesson`



>**Hemia Skemner says:** Then go. He appears near the gates of Freeport from time to time. He is not powerful, but he has a secret. Nothing save magic can harm him. This was the result of an experimental potion he drank. Slay him and return his locked spellbook to me.
end



## Turn-Ins




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/13863" data-url="13863" class="tooltip-link link">A Locked Book</a>) then 


>**Hemia Skemner says:** You have done the world of magic a great justice, Soandso.


Your faction standing with [Arcane Scientists](/faction/220) got better (<span class='text-success'>+10</span>)


Your faction standing with [Knights of Truth](/faction/281) got better (<span class='text-success'>+2</span>)


Your faction standing with [Opal Darkbriar](/faction/296) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [The Freeport Militia](/faction/330) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:** 0 (+500 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-5 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**


