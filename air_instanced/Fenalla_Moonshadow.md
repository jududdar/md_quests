# Fenalla Moonshadow
## On NPC Spawn

**Set a timer** named *depop* for 300 seconds
## Dialog

**You say:** `hail`



>**Fenalla Moonshadow says:** We are children of the trees, friends and protectors of nature. We are brothers and sisters to the wolves and bears. The call of the Great Pine has filled your heart and led you here to be tested.

**You say:** `test`



>**Fenalla Moonshadow says:** Children of the trees, friend and protector of nature. We the brothers and sisters to the wolves and bears. The call of the Great Pine has filled your heart and have found your way here to be tested. Do you wish to be tested in Nature, the art of the Bee, or the way of the Eagle?

**You say:** `nature`




>**Fenalla Moonshadow says:** The test of Nature will show your devotion to and understanding of Mother Nature. Bring me an Efreeti Scimitar, a Lush Nectar, a Fire Sky Ruby, and a Storm Sky Opal to show your devotion. You will then recieve your reward.

**You say:** `bee`




>**Fenalla Moonshadow says:** The bee is a busy little creature and you too must show industriousness like it. Bring me an Efreeti Statuette, a Wilder's Girdle, and a Piece of Divine Honeycomb to prove your understanding of the bee's art of work.

**You say:** `eagle`




>**Fenalla Moonshadow says:** To soar like the eagle is your goal. To do so, you must bring me an Acidic Venom, an Ethereal Ruby, a Spiroc Elder's Totem, and a White-tipped Spiroc Feather. Perhaps then you will know what it means to soar upon the wind.
end

## Turn-Ins



if( **You turn in:** [Efreeti Scimitar](/item/20739), [Fire Sky Ruby](/item/20738), [Lush Nectar](/item/20965), [Storm Sky Opal](/item/20740)) then 




>**Fenalla Moonshadow says:** I am honored to know one such as you, Soandso. I beg you to wield Espri with as much grace you have shown during the travails to obtain it.


 **You receive:**  [Espri](/item/11683) (+100000 exp)



**Fenalla Moonshadow despawns.**

elseif( **You turn in:** [Divine Honeycomb](/item/20735), [Efreeti Statuette](/item/20951), [Wilders Girdle](/item/20734)) then 



>**Fenalla Moonshadow says:** You have done well, young one.


 **You receive:**  [Honeycomb Belt](/item/11684) (+100000 exp)



**Fenalla Moonshadow despawns.**

elseif( **You turn in:** [Acidic Venom](/item/20736), [Ethereal Ruby](/item/20737), [Spiroc Elders Totem](/item/20867), [White-tipped Spiroc Feather](/item/20958)) then 



>**Fenalla Moonshadow says:** You have done well, young one.


 **You receive:**  [Spiroc Banisher Focus](/item/14555) (+100000 exp)



**Fenalla Moonshadow despawns.**

**This NPC *should* return incorrect items given.**

## Timer(s)

**Stop timer** named *depop*

**Fenalla Moonshadow despawns.**



