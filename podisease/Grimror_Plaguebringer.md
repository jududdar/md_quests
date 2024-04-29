# Grimror Plaguebringer
## On NPC Spawn

local sp = e.self:GetSpawnPointID();

local spawn = eq.get_entity_list():GetSpawnByID(sp);

spawn:SetRespawnTimer(5);

e.self:AssignWaypoints(math.random(1,6));
function event_death(e)

local sp = e.self:GetSpawnPointID();

local spawn = eq.get_entity_list():GetSpawnByID(sp);

spawn:SetRespawnTimer(3000);
## Dialog

**You say:** `hail`



>**Grimror Plaguebringer says:** Grimror no have time ta talk. Gots stuffs ta do.

**You say:** `stuff`



>**Grimror Plaguebringer says:** I wuz sent here by Zulort to, err. . . To gadder some alchemy type stuffs. Him have big plan, and need me to travel lots.

**You say:** `big plan`



>*Grimror Plaguebringer laughs. 'Me not tell you dat! Grimror keep secrets secret. You gonna help Grimror or no?'*

**You say:** `help Grimror`



>**Grimror Plaguebringer says:** Dat good!


>**Grimror Plaguebringer says:** Grimror been getting compon ents for dayz now and Grimror still not finushed. You gonna get dem tings fur me?

**You say:** `dem tings`



>**Grimror Plaguebringer says:** Grimror need bile, dat stuff es strong here! But Grimror keent seem to git eet all. Bile comz from da leetle bugs. Keel little bugs, and geeve Grimror dere leetel bodiez and Grimror give yuuz anyting dat yuuz want. Dere on four leetel buggiez dat Grimror still neez, two uf dem come from da fliez, one comez from da wurmiez, and one comez from the moss-skeeterz. Yuuz bring Grimror dere lavas and Grimror geeve yuuz, and yuuz freends, anyting yuuz want
end

## Turn-Ins



local text = "Grimror not thupeed! Dis not four!";



if( **You turn in:** [Sengian Larvae Flesh](/item/9290), [Generian Larvae Flesh](/item/9291), [Scaevian Larvae Flesh](/item/9292), [Harrion Larvae Flesh](/item/9293)) then


>**Grimror Plaguebringer says:** Yuuz dun guud! But Grimror keent geeve you anyting, but Grimror have dis. Grimror also have seekret information. Krypt of Deekay in in here. Dunt tink yuuz wanna go in dere. Dere be mean old rotten keengs in dere, yuuz dunt want ta mess wif dem, dere also be udder sortz uf baddies in dere, be carefuul if yuuz goin dat way. I hurd stories dat Bertoshulus es in dere too, Grimror even saw him in here one time. In dis place yuuz only gots ta worry about Grummus, him fatter dan Grimror, got theek skin too. Him have key ta get inna de Krypt,but Grimror knew da seekret way een. Dat bracer keen make da portil into de Krypt tink dat yuuz belongz dere. Guud barshin!













 **You receive:**  [Bangle of Disease Warding](/item/9294) (+1 exp)








e.other:SetZoneFlag(200);



-


**This NPC *should* return incorrect items given.**
