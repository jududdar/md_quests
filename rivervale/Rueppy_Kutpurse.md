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




if( **You turn in:** [Short Beer](/item/13032)) then 


>**Rueppy Kutpurse says:** Oh, thank you.  AH! That sure is good. Not as good as a [Blackburrow stout], but what is?


 **You receive:** 0 (+10 exp)



elseif **Faction** >= Amiable +200 and  **You turn in:** [Case of Blackburrow Stout](/item/13131)) then 


>**Rueppy Kutpurse says:** Heh heh! You did it! I thought the deputies would get you for sure! I mean... You did it! Heh! Here buy yourself a drink on me.


* __Faction:__ [Deeppockets](/faction/241) (10)


* __Faction:__ [Circle of Unseen Hands](/faction/223) (1)


* __Faction:__ [Merchants of Rivervale](/faction/292) (-1)


* __Faction:__ [Coalition of Tradefolk Underground](/faction/336) (1)


* __Faction:__ [Carson McCabe](/faction/329) (1)


 **You receive:** 0 (+10 exp)

**This NPC *should* return incorrect items given.**
