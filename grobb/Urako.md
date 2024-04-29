# Urako


## Dialog

**You say:** `Hail`



>**Urako says:** Me says hi to you.  What you want from me?  Oh!!  Me shaman trainer.  You must be shaman.  Are you [shaman Darkone]?

**You say:** `i.* shaman darkone`



if **Faction** >= Amiable then 



>**Urako says:** You choose rite if you bes a shaman.  Wes da best.  You remember ta not get in Kaglari way.  He get mad berry easy.  He gets berry mad at Urako if he finds out me make [big mistake].


elseif **Faction** >= Indifferent then



>**Urako says:** Darkones no hates you, buts you not helps us enuff.


else



>**Urako says:** You die! Me Darkone!  We no frend to you.  You run now!


**You say:** `big mistake`



if **Faction** >= Amiable then 



>**Urako says:** Kaglari makes Urako cleans his kwarters.  He says nots to open closet.  Me make mistake and opens his closet and out comes da skeletons.  Dey runs out into Grobb.  Me needs ta gets dem back before Kaglari finds out.  Me needs sumwun to [collect Kaglari skeletons].


elseif **Faction** >= Indifferent then



>**Urako says:** Darkones no hates you, buts you not helps us enuff.


else



>**Urako says:** You die! Me Darkone!  We no frend to you.  You run now!


**You say:** `i.* collect kaglari skeleton`



if **Faction** >= Amiable +100 then 




>**Urako says:** Tank you!!  Dere is fours of dem.  You can finds dem here in Grobb.  I no tink dey will want to come homes to Kaglari's closet.  You ask dem to [come back to the closet] and see whut dey say.  If you gets dem back me promise to gives you a [Kaglari mana doll].



**Spawn NPC:**  [a skeleton](/npc/52056) at (**y:** 156, **x:** -265)


elseif **Faction** >= Indifferent then 



>**Urako says:** Darkones no hates you, buts you not helps us enuff.


else



>**Urako says:** You die! Me Darkone!  We no frend to you.  You run now!


**You say:** `kaglari mana doll`



>**Urako says:** Kaglari catch many humans.  He pull spirit from dem and force into dolls.  Now deir spirit give shaman extra mana.  Dey good power source.  Now humans good for someting.  Da mana dolls only for shaman power.
end

## Turn-Ins



local text = "Dis no good. We need the butcher, baker, minstrel and captain.";



if **Faction** >= Amiable +100 and  **You turn in:** [The Baker](/item/12213), [The Butcher](/item/12214), [The Captain](/item/12215), [The Minstrel](/item/12216)) then 


>**Urako says:** Tank you. You saved me neck. Kaglari not learn me mistake now. Me give you a [Kaglari mana doll].


* __Faction:__ [Dark Ones](/faction/237) (10)


* __Faction:__ [Shadowknights of Night Keep](/faction/308) (2)


* __Faction:__ [Frogloks of Guk](/faction/251) (-1)


 **You receive:**  [Kaglari Mana Doll](/item/12212) (+5000 exp)

**This NPC *should* return incorrect items given.**

end