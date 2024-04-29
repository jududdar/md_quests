# Behroe Dlexon
## Dialog

**You say:** `hail`



if **Faction** >= Dubious +300 then 



>**Behroe Dlexon says:** Ah, greetings, Soandso!  How are you this evening?  Hopefully, you are faring much better than I..  I'm stuck on the night watch here, and never get to see my lovely [Aenia].  Ah..  she is so sweet..  I wrote her this beautiful [ballad], but I fear she may never hear it.


else



>**Behroe Dlexon says:** The League of Antonican Bards is very displeased with your recent actions.   And I don't particularly care for you, or your stench, either!



**You say:** `aenia`



if **Faction** >= Indifferent +50 then



>**Behroe Dlexon says:** Aenia lives in North Qeynos in a little blue house near the Temple of Life with her overprotective father.  Last time he caught me there, he nearly killed me!


elseif **Faction** >= Indifferent then



>**Behroe Dlexon says:** The League of Antonican Bards recognizes your past deeds, and appreciates what you have done for them. But, you must prove your dedication some more... I will say this, you are on the right track to earning our trust, friend.


else



>**Behroe Dlexon says:** The League of Antonican Bards is very displeased with your recent actions.   And I don't particularly care for you, or your stench, either!



**You say:** `ballad`



if **Faction** >= Indifferent +50 then 




>**Behroe Dlexon says:** I wrote this little song for my dearest Aenia, but I can't sing it to her because I'm stuck here on watch duty.  You have a nice voice, Soandso, maybe you could go and sing my song to her for me, huh?  Just make sure you don't sing to Aenia when her father's around, 'cause like I said, he's already tried to kill me for seeing her.



**You receive:**  [The Thornless Rose](/item/18026)


elseif **Faction** >= Indifferent then



>**Behroe Dlexon says:** The League of Antonican Bards recognizes your past deeds, and appreciates what you have done for them. But, you must prove your dedication some more... I will say this, you are on the right track to earning our trust, friend.


else



>**Behroe Dlexon says:** The League of Antonican Bards is very displeased with your recent actions.   And I don't particularly care for you, or your stench, either!


end

## Turn-Ins




if **Faction** >= Indifferent +50 and  **You turn in:** [Letter to Behroe](/item/18027)) then


>**Behroe Dlexon says:** Ah, thank you, kind Soandso.  You've made two foolish lovebirds very happy.  Please, take this..  Though it is not much, it will help keep you warm on those chilly Karana nights.  It is very good to have a friend such as yourself, and I will one day repay you for your kindness and generosity.





* __Faction:__ [League of Antonican Bards](/faction/284) (8)


* __Faction:__ [Knights of Truth](/faction/281) (1)


* __Faction:__ [Guards of Qeynos](/faction/262) (1)


* __Faction:__ [Ring of Scale](/faction/304) (-1)


* __Faction:__ [Mayong Mistmoore](/faction/285) (-1)


 **You receive:**  [Shawl of the Wind Spirit](/item/1055) (+50 exp)

elseif **Faction** >= Indifferent +50 and  **You turn in:** [Jusean's Report Request](/item/18021)) then


>*Behroe Dlexon yawns and says, 'Oh, report time already again?  Yeah, here ya go, Soandso.  Be careful around here at night, I've been seeing some rough looking characters lurking about.*





* __Faction:__ [League of Antonican Bards](/faction/284) (10)


* __Faction:__ [Knights of Truth](/faction/281) (1)


* __Faction:__ [Guards of Qeynos](/faction/262) (1)


* __Faction:__ [Ring of Scale](/faction/304) (-1)


* __Faction:__ [Mayong Mistmoore](/faction/285) (-1)


 **You receive:**  [Behroe's Report](/item/18023) (+50 exp)

item_lib.return_items(e.self, e.other, e.trade, e.text)
## On NPC Death

>**Behroe Dlexon says:** Your actions will not go unnoticed! The League of Antonican Bards has many members all over this continent.