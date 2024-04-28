# Smith Tv-ysa




## Dialog

**You say:** `hail`



if **Faction** >= Indifferent then



>**Smith Tv-ysa says:** I am Tv\`ysa, guardian of the [Concordance of Research].


else



**Smith Tv-ysa says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!





**You say:** `Concordance of Research`



>**Smith Tv-ysa says:** The 'Concordance of Research' is an aid to those who follow the path of academia. It, and its sister books, 'Runes and Research', volumes I and II, help those who are [interested] in researching spells.

**You say:** `interested`



>**Smith Tv-ysa says:** I have several copies of each book. If you want a copy of 'Runes and Research', volume I or II, bring me a lightstone and I will give you whichever book I have more of at the moment. Bring me a greater lightstone, and I will give you a copy of the 'Concordance of Research.
end

## Turn-Ins



local gls =  **You turn in:**  { [Greater Lightstone](/item/10400)}

local ls =  **You turn in:**  { [Lightstone](/item/10300)}




if **Faction** >= Indifferent and (ls > 0)) then 


repeat



>**Smith Tv-ysa says:** A lightstone ? Thank you very much. Here is a copy of 'Runes and Research' for you.



* __Faction:__ [Dark Bargainers](/faction/236) (10)



* __Faction:__ [Dreadguard Outer](/faction/334) (1)



* __Faction:__ [Dreadguard Inner](/faction/370) (1)



 **You receive:** eq.ChooseRandom( [Runes and Research Volume I](/item/18175), 18176) (+10000 exp)



ls = ls - 1;


until ls == 0



if **Faction** >= Indifferent and (gls > 0)) then 


repeat



>**Smith Tv-ysa says:** A greater lightstone? Thank you very much. Here is a 'Concordance of Research' for you.



* __Faction:__ [Dark Bargainers](/faction/236) (10)



* __Faction:__ [Dreadguard Outer](/faction/334) (1)



* __Faction:__ [Dreadguard Inner](/faction/370) (1)



 **You receive:**  [Concordance of Research](/item/17504) (+10000 exp)



gls = gls - 1;


until gls == 0



**This NPC *should* return incorrect items given.**

end