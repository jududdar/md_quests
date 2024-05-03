# Rueppy Kutpurse


## Dialog

**You say:** `hail`



>**Rueppy Kutpurse says:** Hello, Soandso. Rueppy's my name. Why don't you buy us something to [drink] and we can talk?

**You say:** `drink`



>**Rueppy Kutpurse says:** How about a short beer? That sounds good.

**You say:** `blackburrow stout`



>**Rueppy Kutpurse says:** Oh, well we can't get that here. However, you can always [smuggle] it in...

**You say:** `smuggle`



if **Faction** >= Amiable +200 then 



>**Rueppy Kutpurse says:** You interested in a little job? I need you to meet someone who is bringing me some stout. He was supposed to meet me in the ruins on the other side of the Great Wall, but I have other business to attend to. His name is Gunrich. You might have to wait for a while for him to show up, as he will be skittish at the sight of a stranger. Payment has already been made. Just tell him, 'Dark rivers flow east,' and he will know to trust you. Make sure you don't say anything else to him or the deal will sour. Meet me back here with the stout.


elseif **Faction** >= Indifferent then



>**Rueppy Kutpurse says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Rueppy Kutpurse says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

>Oh look, a talking lump of refuse.  How novel!


end



## Turn-Ins




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_828.png" alt="" /> <a
                                href="/item/13032" data-url="13032" class="tooltip-link link">Short Beer</a>) then 


>**Rueppy Kutpurse says:** Oh, thank you.  AH! That sure is good. Not as good as a [Blackburrow stout], but what is?


 &#127873; **You receive:** 0 (+10 exp)

 



elseif **Faction** >= Amiable +200 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_836.png" alt="" /> <a
                                href="/item/13131" data-url="13131" class="tooltip-link link">Case of Blackburrow Stout</a>) then 


>**Rueppy Kutpurse says:** Heh heh! You did it! I thought the deputies would get you for sure! I mean... You did it! Heh! Here buy yourself a drink on me.


Your faction standing with [Deeppockets](/faction/241) got better (<span class='text-success'>+10</span>)


Your faction standing with [Circle of Unseen Hands](/faction/223) got better (<span class='text-success'>+1</span>)


Your faction standing with [Merchants of Rivervale](/faction/292) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Coalition of Tradefolk Underground](/faction/336) got better (<span class='text-success'>+1</span>)


Your faction standing with [Carson McCabe](/faction/329) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:** 0 (+10 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0-5 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**
