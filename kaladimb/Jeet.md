# Jeet
## Dialog

**You say:** `hail`



if **Faction** >= Dubious +200 then



>**Jeet says:** What business do you have here?!! This here is the mine and that means if you ain't a [member of Miner's Guild 628], you'd best be moving on!!


else



>**Jeet says:** The word around the mines is that you are not to be trusted. You'd best leave before my dagger finds a new home in your back.


**You say:** `cleaner`



if **Faction** >= Amiable +100 then 



>**Jeet says:** Darn that blasted clockwork cleaner!! No one in Kaladim even knows what it is! They all think it's some kinda rat in armor!! Rat paladins?!! The name fits. We miners have seen many like it in the gnome city during heists, err.. visits. We have to get rid of this one in Kaladim!! If you smash it and get its scrap metal, I am authorized to give you a mining cap, if you are a member of Miner's Guild 628.


elseif **Faction** >= Indifferent then



>**Jeet says:** Don't take this personally, but I can't quite trust you with such matters. Maybe a few less Butcherblock bandits would prove your worth.


else



>**Jeet says:** The word around the mines is that you are not to be trusted. You'd best leave before my dagger finds a new home in your back.


**You say:** `628`



if **Faction** >= Amiable then 




>**Jeet says:** Well, then, get off yer rump and give us a hand! If you don't have a mining pick, then get down there and use your fingernails!! If you're new and you want to earn a pick, you can [volunteer to exterminate the rats] that have been infesting the mines!!


elseif **Faction** >= Indifferent then



>**Jeet says:** Don't take this personally, but I can't quite trust you with such matters. Maybe a few less Butcherblock bandits would prove your worth.


else



>**Jeet says:** The word around the mines is that you are not to be trusted. You'd best leave before my dagger finds a new home in your back.


**You say:** `volunteer`



if **Faction** >= Amiable then 




>**Jeet says:** Well, someone has to do the dirty work around here. Let it be you new miners. Go patrol the mines and if you see any rats, bash them good!! Return to me with four rat pelts and I will give you some armor as payment. If you want a 628 mining cap, yer gonna have to smash that infernal [cleaner]!!


elseif **Faction** >= Indifferent then



>**Jeet says:** Don't take this personally, but I can't quite trust you with such matters. Maybe a few less Butcherblock bandits would prove your worth.


else



>**Jeet says:** The word around the mines is that you are not to be trusted. You'd best leave before my dagger finds a new home in your back.


**You say:** `run`



if **Faction** >= Amiable then 




>**Jeet says:** Well, as you most likely know, we are a non-profit organization, at least here in Kaladim. We need to make our profit elsewhere and that means a little bit of thieving. Presently we need loyal members to [collect the gnome profit].


elseif **Faction** >= Indifferent then



>**Jeet says:** Don't take this personally, but I can't quite trust you with such matters. Maybe a few less Butcherblock bandits would prove your worth.


else



>**Jeet says:** The word around the mines is that you are not to be trusted. You'd best leave before my dagger finds a new home in your back.


**You say:** `collect`



if **Faction** >= Amiable then 




>**Jeet says:** Take this key. Don't lose it!! You will need to use it on a metal rat called a scrubber. They are all over Ak'Anon. You must find the one that responds to the number, '628'. If it responds, use the key on it. It will hand over a bag with the 'gnome take'. Return it to me. Get moving!!



**You receive:**  [Scrubber Key](/item/12164)


elseif **Faction** >= Indifferent then



>**Jeet says:** Don't take this personally, but I can't quite trust you with such matters. Maybe a few less Butcherblock bandits would prove your worth.


else



>**Jeet says:** The word around the mines is that you are not to be trusted. You'd best leave before my dagger finds a new home in your back.

end

## Turn-Ins



local text = "What are you?! Some kinda' slacker?! I told you to return with FOUR rat pelts!";



if **Faction** >= Amiable and  **You turn in:** [Giant Rat Pelt](/item/13054), [Giant Rat Pelt](/item/13054), [Giant Rat Pelt](/item/13054), [Giant Rat Pelt](/item/13054)


>**Jeet says:** It's about time you managed to smash these four!! Here. You do good work. We could use someone like you to [run to the gnome city].


* __Faction:__ [Miners Guild 628](/faction/322) (20)


* __Faction:__ [Circle of Unseen Hands](/faction/223) (-1)


* __Faction:__ [Butcherblock Bandits](/faction/379) (-1)


* __Faction:__ [Deeppockets](/faction/241) (1)


* __Faction:__ [Ebon Mask](/faction/244) (-3)


 **You receive:** eq.ChooseRandom( [Small Tattered Skullcap](/item/2113), [Small Tattered Mask](/item/2114), [Small Tattered Gorget](/item/2115), [Small Patchwork Tunic](/item/2116), [Small Tattered Shoulderpads](/item/2117), [Small Patchwork Cloak](/item/2118), [Small Tattered Belt](/item/2119), [Small Patchwork Sleeves](/item/2120), [Small Tattered Wristbands](/item/2121), [Small Tattered Gloves](/item/2122), [Small Patchwork Pants](/item/2123), [Small Patchwork Boots](/item/2124)) (+4000 exp)

elseif **Faction** >= Amiable and  **You turn in:** [Scrap Metal](/item/13282)


>**Jeet says:** Great work!! We need this junk for something and we sure didn't need this rat sucking up any of our gems. Here. This is a Mining Cap 628. It's not much, but it is the mark of our miners and provides light for mining purposes. Hold onto it. You never know when we may call upon you to produce it.


* __Faction:__ [Miners Guild 628](/faction/322) (15)


* __Faction:__ [Circle of Unseen Hands](/faction/223) (-1)


* __Faction:__ [Butcherblock Bandits](/faction/379) (-1)


* __Faction:__ [Deeppockets](/faction/241) (1)


* __Faction:__ [Ebon Mask](/faction/244) (-2)


 **You receive:**  [Miners Cap 628](/item/12165) (+5000 exp)

elseif **Faction** >= Amiable and  **You turn in:** [Gnome Take](/item/12167)


>**Jeet says:** What is all this junk!! That blasted tin rat is supposed to be heisting expensive goods from rich gnomes - not all this garbage!! Here. This is your cut of this junk.





* __Faction:__ [Miners Guild 628](/faction/322) (5)


* __Faction:__ [Circle of Unseen Hands](/faction/223) (-1)


* __Faction:__ [Butcherblock Bandits](/faction/379) (-1)


* __Faction:__ [Deeppockets](/faction/241) (1)


* __Faction:__ [Ebon Mask](/faction/244) (-1)


 **You receive:** None 

elseif **Faction** >= Amiable and  **You turn in:** [Gnome Take](/item/12162)


>**Jeet says:** Good work miner. This is a fantastic haul!! Those wrinkly little gnomes don't know what is going on. Here is your cut. Now get back to work.





* __Faction:__ [Miners Guild 628](/faction/322) (25)


* __Faction:__ [Circle of Unseen Hands](/faction/223) (-1)


* __Faction:__ [Butcherblock Bandits](/faction/379) (-1)


* __Faction:__ [Deeppockets](/faction/241) (1)


* __Faction:__ [Ebon Mask](/faction/244) (-3)


 **You receive:** eq.ChooseRandom( [Silver Stud](/item/10005), [Silver Ring](/item/10038), [Turquoise](/item/10017), [Jasper](/item/10020), [Silver Earring](/item/10006), [Golden Ear Stud](/item/10320)) (+5000 exp)

**This NPC *should* return incorrect items given.**

## Signals

if(e.signal == 1) then


>**Jeet says:** I am working on it, Mater!!
end





