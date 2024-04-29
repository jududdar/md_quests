# a frost giant wolf tamer
## Dialog

**You say:** `hail`



if **Faction** >= Amiable then



>**a frost giant wolf tamer says:** Yes, small one?  You seek to interrupt my work for what reason?


elseif **Faction** >= Indifferent then



>**a frost giant wolf tamer says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**a frost giant wolf tamer says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `looking for work`



if **Faction** >= Amiable then



>**a frost giant wolf tamer says:** Do you not see the wolves?  I train them.  I break them of their pride and make them into useful servants.  Only when they willingly accept the harness are they useful.


elseif **Faction** >= Indifferent then



>**a frost giant wolf tamer says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**a frost giant wolf tamer says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `harness`



if **Faction** >= Amiable then



>**a frost giant wolf tamer says:** Aye.  Good metal.  We make their harnesses and wraps here in Kael from strong black steel.  You can't break a beast without a good strong harness.  I've learned that from years of working with them.


elseif **Faction** >= Indifferent then



>**a frost giant wolf tamer says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**a frost giant wolf tamer says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `more work`



if **Faction** >= Amiable then



>**a frost giant wolf tamer says:** Yes. I was charged with a certain... delivery. Apparently one of our good friends named Erdarf in Thurgadin needs a shipment of one karsin acid bottle. You can find such a thing in Crystal Caverns. Maybe one of the orc dogs has it. Find a way to get one of those bottles to our good friend eh? When you do, let me see whatever it is you find on him.


elseif **Faction** >= Indifferent then



>**a frost giant wolf tamer says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**a frost giant wolf tamer says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

end

## Turn-Ins





if( **You turn in:** [War Wolf Choker](/item/30245) or  **You turn in:** [Velium War Wolf Choker](/item/30246)) then


>**a frost giant wolf tamer says:** Ahhh.  Now this is interesting indeed.  I see.  Crafty little ice gnats.  Here, perhaps you can find use for one of our harnesses.  Fair trade eh?  If you want more work let me know.


 **You receive:**  [Blood Wolf Harness](/item/30249) 

elseif( **You turn in:** [Gem of Persuasion](/item/30270)) then


>**a frost giant wolf tamer says:** Ahhh.  Now that really is an interesting little trinket.  You know, that might be interesting with a harness.


 **You receive:**  [Giants Gem of Persuasion](/item/30273) 

elseif( **You turn in:** [Giants Gem of Persuasion](/item/30273)) then


>**a frost giant wolf tamer says:** Yes.  Exactly as I thought.  Hrm.  I'd keep this but you've done much work.  You may be one of the filthy outlanders but you can keep it.  You can save your thanks.


 **You receive:**  [Giants Harness of Control](/item/30274) 

elseif( **You turn in:** [Giants Gem of Persuasion](/item/30273), [Blood Wolf Harness](/item/30249)) then


>**a frost giant wolf tamer says:** Yes.  Exactly as I thought.  Hrm.  I'd keep this but you've done much work.  You may be one of the filthy outlanders but you can keep it.  You can save your thanks.


 **You receive:**  [Giants Harness of Control](/item/30274) 


 **You receive:**  [Blood Wolf Harness](/item/30249) 

**This NPC *should* return incorrect items given.**
