# Defender Raldson




## Dialog

**You say:** `hail`



>**Defender Raldson says:** Good day to you Soandso. A fine day it is today in the Haven. I hear the bazaar is full of great deals today. I'd love to go and check them out for myself unfortunately I'm stuck here worrying about my friend [Daksins].

**You say:** `daksin`



>**Defender Raldson says:** Well I know that he told me he was going to the Tenebrous Mountains to try to acquire the blood of one of the cursed vampyres there. A very brave gnome he is, but also sometimes not very aware of what he is getting himself into. He told me that he needed to bring it to Zimloro so that a potion could be made to cure his sick sister.  She was attacked by one of the cursed not too long ago. Perhaps you could go [lend him a hand] so that he could return sooner.  His family is very worried about him.

**You say:** `lend him a hand`



>**Defender Raldson says:** That is very nice of you, Soandso. I'm sure his family will be very grateful. He should not be there alone and we fear the worst for him. If you are to go search for him, please bring him this note from Zimloro that contains further instructions Please seek him out and do your best to convince him to come home.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_864.png" alt="" /> <a
                                href="/item/4764" data-url="4764" class="tooltip-link link">A List of Potion Components</a>
end



## Combat

if Defender Raldson enters combat  then


**Set a timer** named *combatsay* for 300 seconds

else


**Stop timer** named *combatsay*
end



## Timer(s)

>**Defender Raldson says:** A fool you are indeed to test your fighting skills to mine!  You shall now die by my blade!


## On NPC Death

**Stop timer** named *combatsay*