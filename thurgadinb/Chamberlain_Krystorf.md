# Chamberlain Krystorf
## Dialog

**You say:** `hail`



>**Chamberlain Krystorf says:** Greetings and welcome to Thurgadin, Soandso. I am Chamberlain Krystorf and it is my duty to assist the Dain in the management of Icewell Keep and the Royal Court. One could say that Seneschal Aldikar is the Sword of the Dain while I am the Shield, protecting all of his interests and those of the kingdom.
end

## Turn-Ins



local text = "For storage reasons I'm afraid I can only accept four of these at once for the bounty."



if( **You turn in:** [Giant Warrior Helmet](/item/29062), [Giant Warrior Helmet](/item/29062), [Giant Warrior Helmet](/item/29062), [Giant Warrior Helmet](/item/29062)) then


>**Chamberlain Krystorf says:** Well done, Soandso, the Dain is pleased with your efforts. With a few more brave allies like you, we'll soon be tearing down the halls of Kael Drakkel.





* __Faction:__ [Dain Frostreaver IV](/faction/405) (50)


* __Faction:__ [Coldain](/faction/406) (50)


* __Faction:__ [King Tormax](/faction/429) (-25)


 **You receive:** eq.ChooseRandom( [Coldain Velium Morning Star](/item/30215), [Coldain Velium Rapier](/item/30219), [Coldain Velium Short Sword](/item/30212), [Coldain Velium-Pick](/item/30263)) (+5000 exp)

elseif( **You turn in:** [Runed Coldain Prayer Shawl](/item/1199)) then


>**Chamberlain Krystorf says:** One moment the Dain has been waiting for you. I will call for him.. oh here he is now, show your shawl to him.


 **You receive:**  [Runed Coldain Prayer Shawl](/item/8895) 


if(not **You possess item:**  [Empty Coldain Issue Kit](/item/17651) x 1



 **You receive:**  [Empty Coldain Issue Kit](/item/17651) 



if(**spawned NPC:**  [\#Dain Frostreaver IV](/npc/129003) == false and **spawned NPC:** 129101 == false) then



eq.spawn_condition("thurgadinb",3,0);



eq.spawn_condition("thurgadinb",3,1);


elseif( **You turn in:** [Runed Coldain Prayer Shawl](/item/8895)) then


>**Chamberlain Krystorf says:** As I stated previously, you should show this to the Dain.


 **You receive:**  [Runed Coldain Prayer Shawl](/item/8895) 

**This NPC *should* return incorrect items given.**
