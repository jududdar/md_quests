# Bubar
## Dialog

**You say:** `hail`



>**Bubar says:** Greetings, friend! I am Bubar, merchant from the burning sands. You must be thirsty or, perhaps, hungry. Please look over my goods.

**You say:** `gem case`



>**Bubar says:** Talking of containers? I do not make containers any longer. Provisions are much more profitable. Do you have one of my containers? Most likely you have locked yourself out then. My specialty was the three-lock case. They always lose one of the keys. Hand me the case and at least two of the keys and I can open it for you.
end

## Turn-Ins



local text = "I need at least two of the case keys and the gem case.";


if( **You turn in:** [A Tiny Key](/item/12351), [A Tiny Key](/item/12352), [Gem Case](/item/12350)) then


>**Bubar says:** Mmmph!!.. *Pop!!* Ouch, my thumb!! Here you are. You had a gem inside.


 **You receive:**  [A Sparkling Sapphire](/item/12349) (+15000 exp)

**This NPC *should* return incorrect items given.**
; 
 