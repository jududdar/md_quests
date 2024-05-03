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


  

if( **Faction is** > Kindly and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_861.png" alt="" /> <a
                                href="/item/8919" data-url="8919" class="tooltip-link link">Nyrein's Prayer</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/8951" data-url="8951" class="tooltip-link link">Tempest Rune</a>) then


e.self:Say("Aaaah, yet another warrior brave enough to face their own faults and honorable enough to strive for a proof of their worth and devotion to The Rainkeeper. Your kind is too few and far too rare, but do not think that your trials are at their I have forged the necessary Hollowed Tempest Stone 


Your faction standing with [Knights of Thunder](/faction/280) got better (<span class='text-success'>+10</span>)


Your faction standing with [Bloodsabers](/faction/221) got worse (<span class='text-danger'>-10</span>)


Your faction standing with [Priests of Life](/faction/341) got better (<span class='text-success'>+7</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+7</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_947.png" alt="" /> <a
                                href="/item/17089" data-url="17089" class="tooltip-link link">Hollow Tempest Stone</a> (+1000 exp)

 

**This NPC *should* return incorrect items given.**
