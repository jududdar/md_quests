# Roror
## Combat

if Roror enters combat  then


if(math.random(2) == 1) then



>**Roror says:** " .. e.other:Race() .. "s like you are better left dead than alive.


else



>**Roror says:** You ssssshall know the horror of Cazic-Thule!

end

## Dialog

**You say:** `hail`



>**Roror says:** Greeetingsssssssssss. What brings sssssuch asssss you to the heart of the Feerrott? Do you [know fear]?

**You say:** `know fear`



>**Roror says:** Yesssss. I can tassssste the fear in your pitiful heart. I am Roror, High Priessst of Cazic-Thule! I sssseek to sssssspread terror acrossssss all of Norrath! I ssssshall let you live thisss day so you can sssshare the fear that liessss within you.

**You say:** `know no fear`



>**Roror says:** YOU SSSSSSHALL! For I, Roror, High Prissst of Cazic-Thule, I sssshall teach you!


**Roror attacks you.**

**You say:** `hay`



>**Roror says:** You sssseek the blesssssssing of the Lord of Fear?! Give me what you have and 66 gold pieces as an offering to Cazic-Thule.
end

## Turn-Ins



local text = "Yesss. But remember, Cazic-Thule demandsssss both the item and 66 gold piecessss assssss an offering.";


if( **You turn in:** [Sack of Hay](/item/13990),gold = 66) then


>**Roror says:** Whatsssss thisssss? You sssseek my blessssssssing? Heh heh heh... Very well... CAZIC-THULE! Take this fruit of Karana into horror'sss dark embrace. Fear and death made manifesssssst. A harvesssst of terror! Here, take your gift of blood and sssstraw. Use its dark powersssss in the name of the Fear Lord!


 **You receive:**  [Sack of Cursed Hay](/item/14320) (+300 exp)

**This NPC *should* return incorrect items given.**
;
end