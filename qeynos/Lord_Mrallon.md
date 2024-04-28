# Lord Mrallon
## Dialog

**You say:** `tale`



if( **Faction is** > Kindly) then






e.self:Say("Nyrein Shadowstorm spent much of her life defending the Jaggedpine from within its confines. However, duty would sometimes deem that she trek beyond the forests to assure its protection. In the peak years of her life, she spent much time wandering the whole of Norrath in pursuit of one villain that had betrayed the entire order. We are not certain why or how this one, who at one time was Nyrein's most trusted of companions and second to only her within the order, fell to the temptations and corruption of The Faceless 


elseif( **Faction is** > Apprehensive) then



>**Lord Mrallon says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Lord Mrallon says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!

end

## Turn-Ins


  

if( **Faction is** > Kindly and  **You turn in:** [Nyrein's Prayer](/item/8919), [Tempest Rune](/item/8951)


e.self:Say("Aaaah, yet another warrior brave enough to face their own faults and honorable enough to strive for a proof of their worth and devotion to The Rainkeeper. Your kind is too few and far too rare, but do not think that your trials are at their I have forged the necessary Hollowed Tempest Stone 


* __Faction:__ [Knights of Thunder](/faction/280) (10)


* __Faction:__ [Bloodsabers](/faction/221) (-10)


* __Faction:__ [Priests of Life](/faction/341) (7)


* __Faction:__ [Guards of Qeynos](/faction/262) (7)


 **You receive:**  [Hollow Tempest Stone](/item/17089) (+1000 exp)

item_lib.return_items(e.self, e.other, e.trade, e.text)