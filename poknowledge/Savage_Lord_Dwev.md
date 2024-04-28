# Savage Lord Dwev


## Dialog

**You say:** `hail`



>*Savage Lord Dwev growls lowly, the rumble from the depths of his throat akin to that of a starved tiger prepared to pounce upon its first prey. 'Yoo worm! Yoo worm stupidly come to shadow, and now shadow wants worm to be its slave. Worm shood stay and be shadow's slave, be Dwev's slave. Dwev teech worm how to rip spirits frum spirit world and make beasts worm's slaves, like worm be to Dwev! HAHA! Yes. Dwev smart! Dwev serve shadow faith. . . faithful. . . gud with new worm slave.'*
end

## Turn-Ins



local count =  **You turn in:**  { [Anthemion Wristguard](/item/7817),  [Anthemion Boots](/item/7818),  [Anthemion Leggings](/item/7819),  [Anthemion Gloves](/item/7832),  [Anthemion Jerkin](/item/7833),  [Anthemion Armbands](/item/7834),  [Anthemion Skullcap](/item/7835)}

if(count > 0) then


repeat



>**Savage Lord Dwev says:** Thank you, Soandso.



 **You receive:** eq.ChooseRandom( [Peridot](/item/10028), 10037, 22503, 15981) (+300000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





