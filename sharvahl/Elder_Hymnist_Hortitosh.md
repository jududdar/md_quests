# Elder Hymnist Hortitosh
## Dialog

local qglobals = eq.get_qglobals(e.self,e.other);

**You say:** `hail`



>**Elder Hymnist Hortitosh says:** Hail. Are you here to assist with something specific or just looking for something to do?

**You say:** `application`



>**Elder Hymnist Hortitosh says:** Luckily for you someone found it.


**You receive:**  [Application for Citizenship](/item/2873)

**You say:** `cloak`



>**Elder Hymnist Hortitosh says:** Someone found this under a table at the one of the pubs. Try not to lose it this time.


**You receive:**  [Initiate's Cloak of Shar Vahl](/item/2878)

**You say:** `essence of sonnet`



>*Elder Hymnist Hortitosh stops what he is doing and looks at you, most surprised, 'An essence of sonnet? I have never produced such a thing my friend, though the fact that you would even request one from me is very flattering.' His eyes leave your face and settle off in the distance somewhere as he continues, 'I was present once when one was created... it was beautiful. I was only a child, but there was no mistaking the significance. Oh how I would love to produce such a thing myself- an accomplishment without peer for one of my art. They say that the inspiration must be genuine, should you know of something that could inspire me so then by all means, I will see if I have an essence of sonnet within me.'*
end

## Turn-Ins



local text = "This item, by itself, means nothing to me.";



if( **You turn in:** [Kalila'a Diary](/item/18324)) then


>*Elder Hymnist Hortitosh opens the diary and reads. Before long he is utterly engrossed in the story of purest love that you have given him, and it begins. You are something less than fully aware of what happens next, the wind whistles and you could swear that the room fills with light though you could not prove it. A moment later, a sense of completeness has filled you. All you know for sure is that Hortitosh stands before you, fully spent, and you hold in your hand what could only be an essence of sonnet.*


 **You receive:**  [Essence of Sonnet](/item/5991) 

elseif( **You turn in:** [A Hymnist Guild Summons](/item/18552)) then 


>**Elder Hymnist Hortitosh says:** Our newest instrumentalist arrives! You have grown strong in the safety of our city and it is time now for you to repay our society. The Jharin, keepers of our history, accept you and deem you to be worthy of our training. Take this application to Registrar Bindarah and return to me with proof of your citizenship.


>**Elder Hymnist Hortitosh says:** I know that you may be nervous right now... after all, this should be a very exciting first step for you.  If you happen to get lost while looking for the registrar, just ask one of the other citizens or guards for directions.  They will most likely know where to find the place or person that you are looking for.


eq.set_global("Shar_Vahl_Cit","1",5,"F");





 **You receive:**  [Application for Citizenship](/item/2873) (+20 exp)

elseif( **You turn in:** [Notarized Application](/item/2897), [Acrylia Slate of Shar Vahl](/item/2877)) then


>**Elder Hymnist Hortitosh says:** Soandso, citizen of Shar Vahl, accept this cloak as a symbol of your loyalty and service to our noble people. It will grow with you, young initiate, and like you it has incredible potential. Present your slate of citizenship to Gherik and he will guide you through your early training. May your songs inspire us all!


eq.set_global("Shar_Vahl_Cit","7",5,"F");


 **You receive:** GiveAll( [Acrylia Slate of Shar Vahl](/item/2877), [Initiate's Cloak of Shar Vahl](/item/2878)) (+450 exp)

elseif( **You turn in:** [Case of Guard Uniforms](/item/3920)) then


>**Elder Hymnist Hortitosh says:** These are finely crafted indeed, Soandso. Merchant Fahaar told me you were quite the prodigy, but don't tell him I told you that. Take this receipt and show it to Fahaar and tell him the king is quite pleased with both your work, and his teaching!


 **You receive:**  [Order Receipt](/item/3921) (+1000 exp)

**This NPC *should* return incorrect items given.**





