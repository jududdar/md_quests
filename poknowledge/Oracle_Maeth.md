# Oracle Maeth

## Dialog

**You say:** `hail`



>*Oracle Maeth makes a sweeping motion with his arms in an almost ritualistic fashion of greetings known only to those of the shamanistic world. 'We welcome you, friend, to the Tanaan district of the Plane of Knowledge. Beyond a seemingly endless fount of tangible supplies, the adepts of Jeral have come together and offered to retake our former duties as guildmasters and mentors to those of our art. In my life before New Tanaan's embrace of me, I served as one of many shamans of the Northmen, before Halas' walls were secured in the turmoil of the frozen north. As the years passed and years fell way to decades, I ascended to hold the seat of guild master of my order and have mentored countless shamans in my day. If you are in need of such knowledge, then please, do not hesitate in acquiring my aid.'*
end

## Turn-Ins



local count =  **You turn in:**  { [Rune Etched Helm](/item/4871),  [Rune Etched Chestplate](/item/4872),  [Rune Etched Vambraces](/item/4873),  [Rune Etched Bracer](/item/4874),  [Rune Etched Gauntlets](/item/4875),  [Rune Etched Greaves](/item/4876),  [Rune Etched Boots](/item/4877)}

if(count > 0) then


repeat



>**Oracle Maeth says:** Thank you, Soandso.



 **You receive:** eq.ChooseRandom( [Peridot](/item/10028), 10037, 22503, 15981) (+300000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





