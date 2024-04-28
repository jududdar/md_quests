# Groflah Steadirt
## Dialog

**You say:** `hail`



>**Groflah Steadirt says:** Greetings, Soandso! Join in the [celebration]! Have a few drinks. Alas, there are no [Tumpy Tonics].

**You say:** `celebration`



>**Groflah Steadirt says:** The Freeport Militia now has a bar to themselves. Luckily, it is not this one. Ahh.. I tell you, I just don't feel up to much right now. I have had so much grog, my great grandma could best me!!

**You say:** `ariska`



>**Groflah Steadirt says:** Ariska Zimel was my best friend. He and I learned our knowledge of metal from such places as Halas and Kaladim. When he disappeared, it seemed to involve foul play. He must be alive somewhere in the city. I pray this is not the work of [Pietro Zarn].

**You say:** `pietro zarn`



>**Groflah Steadirt says:** While we were traveling through the Lavastorm Mountains, we happened upon a caravan. They wore emblems in honor of the evil god, Innoruuk. They did not see us, but we saw them. And most importantly of all, Ariska saw the apparent leader's sword. It was glowing with great energy. Suddenly, the evil knights were in a battle. The knights gave chase, leaving their camp unattended. The knight who owned the sword left it behind, opting to fight with another, leading me to believe it was not his to begin with. It was at this point that Ariska ran down and grabbed the sword. A few weeks later, we were to learn that the knight was a powerful man by the name of Pietro Zarn and that he was looking for a sword stolen from him. He called it .. Soulfire. I believe Zarn must have finally found Ariska.

**You say:** `tumpy tonics`



>**Groflah Steadirt says:** Ah a tumpy tonic, good drink indeed. They are made. Lets see if I can rememeber how to make them.  Ahh yes, ye take a kiola nut and stir it with water, wait a while and ya got it.  If you plan to make some then please by all means bring me one to try as I sure do miss them.
end

## Turn-Ins

local Tumpy_Tonic = 0;




if **You turn in:** [A tattered flier](/item/18818)


>**Groflah Steadirt says:** This used to be hanging in Zimel's Blades. It is the price list. It is badly faded though. There was a fire in Zimel's Blades and I was on the scene just afterward. I did not see this hanging. I wonder who took it . . . Hmmmm.. oh, yes.. the markings on the list! It is a code! Here. I will fill it in. Read it. You probably do not even know who Ariska is.


 **You receive:**  [A tattered flier](/item/18819) 

elseif **You turn in:** [Tumpy Tonic](/item/12114), [Tumpy Tonic](/item/12114), [Tumpy Tonic](/item/12114), [Tumpy Tonic](/item/12114)


Tumpy_Tonic = 4;

elseif **You turn in:** [Tumpy Tonic](/item/12114), [Tumpy Tonic](/item/12114), [Tumpy Tonic](/item/12114)


Tumpy_Tonic = 3;

elseif **You turn in:** [Tumpy Tonic](/item/12114), [Tumpy Tonic](/item/12114)


Tumpy_Tonic = 2;

elseif **You turn in:** [Tumpy Tonic](/item/12114)


Tumpy_Tonic = 1;



if(Tumpy_Tonic > 0) then


repeat



>**Groflah Steadirt says:** <glug,glug,glug> Ahh! I missed those. I was just telling myself the other... Uh oh! I have to use the little dwarf's facilities. Excuse me



* __Faction:__ [Coalition of Tradefolk](/faction/229) (10)



* __Faction:__ [Coalition of Tradefolk Underground](/faction/336) (10)



* __Faction:__ [Knights of Truth](/faction/281) (10)



* __Faction:__ [Merchants of Qeynos](/faction/291) (7)



 **You receive:** None 



Tumpy_Tonic = Tumpy_Tonic - 1;


until Tumpy_Tonic == 0


**This NPC *should* return incorrect items given.**

## Signals

if ( e.self:IsEngaged() ) then


return;


local turn, bard;



if ( e.signal == 1 ) then


>**Groflah Steadirt says:** Aye!! We shall show the world that the races can live together.


turn = true;



elseif ( e.signal == 2 ) then


>**Groflah Steadirt says:** That's right. Them smelly ogres can't even count to one.


turn = true;

elseif ( e.signal == 4 ) then


>**Groflah Steadirt says:** No need to speak badly of Antonius Bayle. He is a great man.


turn = true;

elseif ( e.signal == 7 ) then


>**Groflah Steadirt says:** Sing it, lass! Sir Lucan D'Lere is no friend of the people.


turn = true;


if ( turn ) then


bard = eq.get_entity_list():GetMobByNpcTypeID(10141);





if ( not bard.valid ) then



bard = eq.get_entity_list():GetMobByNpcTypeID(10158);





if ( not bard.valid ) then 



bard = eq.get_entity_list():GetMobByNpcTypeID(10165);





if ( bard.valid ) then



e.self:FaceTarget(bard);

end


