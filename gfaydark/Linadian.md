# Linadian
## Dialog

**You say:** `hail`



>**Linadian says:** Greetings! Please look through my fine wares. I have spent most of my life practicing my skills in tailoring. I do my best to compete with the other local merchants, but I have yet to make a profit. I pray to Tunare that my [banded orc vests] will finally bring me a few extra coins.

**You say:** `banded orc vest`



if **Faction** >= Indifferent then



>**Linadian says:** Glad you are interested. I can create a leather vest I call a banded orc vest. It will aid you in repelling any disease and offers quite a bit of protection in battle. I will need some materials. For a Deathfist banded orc vest, I require two legionnaire pads worn by the clan Deathfist, one Deathfist slashed belt, and ten gold coins. For a Crushbone banded orc vest, I require two legionnaire pads worn by the Clan Crushbone, one Crushbone belt, and one silk swatch.'


else



>**Linadian says:** Your ways are considered vile to Faydark's Champions. Leave before my rage overcomes my restraint.

end

## Turn-Ins





if **Faction** >= Indifferent and  **You turn in:** [Crushbone Shoulderpads](/item/13319), [Crushbone Shoulderpads](/item/13319), [Crushbone Belt](/item/13318), [Silk Swatch](/item/16482)


>**Linadian says:** Grand doing business with you. Hold your nose. I can never get rid of the orc stench of the vests. That is why the other merchants do not pay me much for them.


* __Faction:__ [Kelethin Merchants](/faction/276) (5)


* __Faction:__ [Faydarks Champions](/faction/246) (1)


* __Faction:__ [Emerald Warriors](/faction/326) (1)


* __Faction:__ [Anti-mage](/faction/5002) (1)


 **You receive:**  [Banded Orc Vest](/item/12187) (+100 exp)

elseif **Faction** >= Indifferent and  **You turn in:** [Deathfist Shoulderpads](/item/13917), [Deathfist Shoulderpads](/item/13917), [Deathfist Slashed Belt](/item/13916),gold = 10


>**Linadian says:** Grand doing business with you. Hold your nose. I can never get rid of the orc stench of the vests. That is why the other merchants do not pay me much for them.


* __Faction:__ [Kelethin Merchants](/faction/276) (5)


* __Faction:__ [Faydarks Champions](/faction/246) (1)


* __Faction:__ [Emerald Warriors](/faction/326) (1)


* __Faction:__ [Anti-mage](/faction/5002) (1)


 **You receive:**  [Banded Orc Vest](/item/12187) (+100 exp)

**This NPC *should* return incorrect items given.**
