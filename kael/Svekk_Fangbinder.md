# Svekk Fangbinder
## Dialog

if( **Faction is** > Apprehensive) then


**You say:** `hail`




>**Svekk Fangbinder says:** Greetings, Soandso.  I am Svekk, a humble servant of Wenglawks.  It is my job to keep track of the supplies here.  I also sell mundane wares.


**You say:** `supplies`




>**Svekk Fangbinder says:** We have all kinds of supplies!  Normally we deliver them to the giants who live outside Kael.


**You say:** `giant`




>**Svekk Fangbinder says:** There are several encampments in the eastern wastes that barter for supplies with us monthly.  The great divide also has a small outpost of Kromrif who strive to beat the Coldain back into their city of Thurgadin and of course the outposts in the wakening lands.  Our last batch of deliveries did not reach their intended targets.  The runners have not been heard from since they were dispatched either.


**You say:** `eastern waste`




>**Svekk Fangbinder says:** The Kromrif of the Eastern wastes are more savage than those who dwell within Kael Drakkel.  Normally they can fend for themselves but recently Fjloaren of the Icebane clan has requested we help them with a shipment of supplies.  We have yet to receive payment for the supplies but you are more than welcome to purchase supplies for them and deliver them.  It has been a most unforgiving season upon the wastes I believe.


**You say:** `wakening land`




>**Svekk Fangbinder says:** Korzak Stonehammer is the name of the man whom we usually deliver to in the Wakening Land.  His men are attempting to expand Kael further into that accursed forest.  If you buy a pack of supplies and deliver it to him I am sure he would repay you handsomely.  A single pack will only cost you a mere five hundred pieces of gold.


**You say:** `great divide`




>**Svekk Fangbinder says:** If you wish to deliver supplies to the warriors in the great divide that is wonderful. One small problem arises.   I do not know you, " .. e.other:Race() .. ".  I would not trust you as far as I could throw a dragon.  If you pay for the supplies and deliver them the men at the fortress will surely repay you.  A pack of basic supplies only costs a meager five hundred gold pieces.  If you choose to purchase the supplies and deliver them take them to a man named Bekerak Coldbones at the outpost.


**You say:** `klezendian`




>**Svekk Fangbinder says:** Klezendian crystals can be found in the Crystal Caverns beneath the eastern wastes.  The Rygorr orcs mine Velium and various metals from its rich walls.  Be warned though, the crystal caverns are not a safe place, nameless beasts and even some Coldain call It their home.


else


**Svekk Fangbinder says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.
end

## Turn-Ins





if( **Faction is** > Apprehensive) then


if **You turn in:** [Velium Torque](/item/25278)



>**Svekk Fangbinder says:** Ahh, a Velium torque!  Here, I'll give you one hundred pieces of gold for that!'  Svekk places the torque in his pocket and drops some coins at his feet.



* __Faction:__ [Kromzek](/faction/448) (10)



* __Faction:__ [Kromrif](/faction/419) (2)



* __Faction:__ [King Tormax](/faction/429) (2)



* __Faction:__ [Claws of Veeshan](/faction/430) (-5)



 **You receive:** 0 (+250 exp)


elseif **You turn in:** [Bekerak's Letter to Svekk](/item/25267)



>**Svekk Fangbinder says:** This is unbelievable!  The fool is asking for things I don't even have in stock!  Listen, Soandso, you're the one that wanted to help them out, I'm just here working for Wenglawks.  I can get most of these supplies ready but I have no source for Klezendian Crystals.  I will start bundling the more mundane items Bekerak wants.  If you find any Klezendian return to me with the crystal and this voucher.



* __Faction:__ [Kromzek](/faction/448) (10)



* __Faction:__ [Kromrif](/faction/419) (2)



* __Faction:__ [King Tormax](/faction/429) (2)



* __Faction:__ [Claws of Veeshan](/faction/430) (-5)



 **You receive:**  [Supply Voucher](/item/25270) (+250 exp)


elseif **You turn in:** copper = 50000



>*Svekk Fangbinder heaves a large pack from a pile in the corner and sets it before you.  'I wish you luck in your endeavor, " .. e.other:Race() .. "'*



 **You receive:**  [Giant Sack of Supplies](/item/25266) 


elseif **You turn in:** [Supply Voucher](/item/25270), [Klezendian Crystal](/item/25271)



>**Svekk Fangbinder says:** Did you travel to the crystal caverns to get that crystal, Soandso?  You are quite brave for a " .. e.other:Race() .. ".  I have the other supplies ready for your trip, they are quite heavy but I think you will get by.



* __Faction:__ [Kromzek](/faction/448) (10)



* __Faction:__ [Kromrif](/faction/419) (2)



* __Faction:__ [King Tormax](/faction/429) (2)



* __Faction:__ [Claws of Veeshan](/faction/430) (-5)



 **You receive:**  [Large Supply Sack for Bekerak](/item/25269) (+250 exp)


**This NPC *should* return incorrect items given.**




