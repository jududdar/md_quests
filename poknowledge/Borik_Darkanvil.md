# Borik Darkanvil
## Dialog

**You say:** `Hail`



>**Borik Darkanvil says:** Greetings, Borik Darkanvil, at your service. I was once a planar traveler like you. Those days are behind me, now I am content to earn my keep as a blacksmith, and to experiment with some of the [special recipes] that I have picked up in these outer planes.

**You say:** `special recipes`



>**Borik Darkanvil says:** Well a little bit of this and a little bit of that. If there is anything you need assistance in making come see me. I may be able to help.

**You say:** `box of souls`



>*Borik Darkanvil eyes grow narrow. 'So looking to capture some souls are you? It's none of my business I suppose so don't answer. I'm pretty sure that I don't want to know. I paid heavily for the formula for the Box of Souls, but its not a price I would pass on to anyone else. There isn't much to it, but it does take the hands of a skilled smith and the magic of Tanaan's forges to event attempt it. First you will need a block of [Perilium].*

**You say:** `Perilium`



>**Borik Darkanvil says:** Perilium was once used to make clockwork machines, there are now stronger metals so it has become harder and harder to find Perilium, much less a block that is large enough to be of any use. Then you will need to find the brain of a crystal spider, this is where the actual soul will be held. Of course the box will need a supernatural power source, the souls are held into place by the horror of their own dreams, the heart of an agony mephit will give the device that power. Forge these with a smithing hammer and a water flask and you will have your box. Of course if you have not the skill, I can [forge them for you].

**You say:** `forge them for me`



if(e.self:GetSkill(63) > 59) then



>**Borik Darkanvil says:** A smith of your skill does not need my assistance in making the box, however I won't turn away your money. Bring me three thousand platinum, the perilium, the brain, and the heart and I will make the box for you.


else



>**Borik Darkanvil says:** If you return all three items to me I will do the work for you for, a mere three thousand platinum. I will not guarantee my success, but I can guarantee if you do not have the skill, you will fail.

end

## Turn-Ins



if( **You turn in:** [Nightmare Mephit Heart](/item/29228), [Crystal Spider Brain](/item/29229), [Solid Block of Perilium](/item/29230), platinum =  [Zaharns Coronet](/item/3000)) then


>**Borik Darkanvil says:** Ah ha! Here we go one box of souls!


 **You receive:**  [Box of Souls](/item/29281) 

**This NPC *should* return incorrect items given.**





