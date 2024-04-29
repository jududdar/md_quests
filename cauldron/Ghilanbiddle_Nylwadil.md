# Ghilanbiddle Nylwadil
## Dialog

if( **Faction is** > Dubious) then


**You say:** `hail`




>**Ghilanbiddle Nylwadil says:** What business do you have here?!! Trying to keep safe? Expecting us to fight your battles? Bah!!


**You say:** `chalice of conquest`




>**Ghilanbiddle Nylwadil says:** Looking for the chalice, are you? Ha!! I don't know where it is, but I know a [lost soul] who does and he could lead you right to it. He had a taste of it and now he can't get enough. He is sort of under the weather, or do I mean under the ground? Ha!!


**You say:** `lost soul`




>**Ghilanbiddle Nylwadil says:** The orc named Captain Klunga knows where it's buried. Unfortunately, his time on Norrath has passed. I happen to know two things... one, he is buried somewhere in this territory and two, I can [raise Klunga] and he can show you where the chalice is.


**You say:** `raise klunga`




>**Ghilanbiddle Nylwadil says:** I can raise Captain Klunga if I have a portion of his blood, an item he once owned and the most important part, 100 gold coins!! Hehe!! A gnome's got to make a living, you know?


else


>**Ghilanbiddle Nylwadil says:** You dare to speak to a member of the Eldritch Collective!! You had best leave before you find your soul displaced from your body.
end

## Turn-Ins



local text = "The deal was - an article of Klunga's and his blood along with my fee of 100 gold coins and you will have his resurrection."


if( **You turn in:** [Klunga's Bracelet](/item/12280), [Blood Stained Note](/item/18946),gold = 100) then


>**Ghilanbiddle Nylwadil says:** Biggily boo, biggily borc.. Raise that stinky orc!! Bamm!! Okay!! It's done. Now all you have to do is find him in the spot where his soul left him and give him an orc shovel. Oh!! I didn't mention that? Oh, well. I'm sure you can find one.. somewhere. Now, get lost before I turn you into a toad!





* __Faction:__ [Eldritch Collective](/faction/245) (5)


* __Faction:__ [Dark Reflection](/faction/238) (-1)


* __Faction:__ [The Dead](/faction/239) (-1)


* __Faction:__ [Gem Choppers](/faction/255) (1)


* __Faction:__ [King Ak`Anon](/faction/333) (1)


 **You receive:** 0 (+18000 exp)


**Spawn NPC:**  [Captain Klunga](/npc/70072) at (**y:** -726, **x:** -2133)

**This NPC *should* return incorrect items given.**
;
## Signals

>**Ghilanbiddle Nylwadil says:** Ha!! One like that one stands no chance within this realm. The goblins shall skin him alive!!

**Signaled to:**  [Elmion Hendrys](/npc/70005)

