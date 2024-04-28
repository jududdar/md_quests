# Oracle Cador

## Dialog

**You say:** `Hail`



e.self:Emote("gives a stiff nod in proper greetings to Soandso. 'The light of Selia shines in welcoming, friend. If you seek supplies or training, know that Selia will accommodate your every need in these specific areas most efficiently 

**You say:** `black lava powder`



>**Oracle Cador says:** You are most astute. I do have a stock of black lava powder with me, but I will only share it with those who prove themselves worthy. Onirelin Gali is currently in possession of an artifact I need to better commune with the spirits. Please recover it for me.
end

## Turn-Ins



local count =  **You turn in:**  { [Rune Etched Helm](/item/4871),  [Rune Etched Chestplate](/item/4872),  [Rune Etched Vambraces](/item/4873),  [Rune Etched Bracer](/item/4874),  [Rune Etched Gauntlets](/item/4875),  [Rune Etched Greaves](/item/4876),  [Rune Etched Boots](/item/4877)}

if **You turn in:** [Cadors Artifact](/item/28089)


>**Oracle Cador says:** The spirits are restful now that this piece of legend is in safe hands. You may take this to Mirao for whatever purpose he desires it for. May your vision always be clear!





 **You receive:**  [Black Lava Powder](/item/28090) (+100 exp)

if(count > 0) then


repeat



>**Oracle Cador says:** Thank you, Soandso.



 **You receive:** eq.ChooseRandom( [Peridot](/item/10028), 10037, 22503, 15981) (+300000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**
