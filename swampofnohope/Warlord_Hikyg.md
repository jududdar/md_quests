# Warlord Hikyg
## Dialog

**You say:** `hail`



>**Warlord Hikyg says:** What business do you have speaking to an Iksar Warlord? Be gone before you find yourself served as my evening meal. Go to Captain Nedar if you wish to assist my garrison. Fool.

**You say:** `trooper reporting for duty`



>**Warlord Hikyg says:** It is about time they sent new troopers for my garrison!! This is the toughest garrison in Kunark!! And you're going to help prove it. The legion needs to get a hold of some new frog shields called Krup warrior guards. You're going to take this pack and fill it with not one, but four!! When you can return a full, combined pack to me, maybe you will show me that you're not as weak as you look!!


**You receive:**  [Swamp Garrison Pack](/item/17043)

**You say:** `geozite`



>**Warlord Hikyg says:** Do not speak to me of the geozite tool.  Seek out Drill Master Vygan within the Fortress of Talishan.  He shall answer your questions.
end

## Turn-Ins



local text1 = "I was expecting the heads of Narsh, Barsh and Flendle, as well as your soldier's pike. Then, you will be promoted to the rank of Trooper.";




if( **You turn in:** [Note to Iksar Lord](/item/18211)) then


>**Warlord Hikyg says:** Ah!! Good to have you on board. We lack strong young recruits such as yourself. Take this bag. Your task is to seek escaped frogloks near this gate. Apparently, the slaves have been breaking loose from their shackles and attempting to head home. Fill and combine within the bag their broken shackles and return the filled box to me for your geozite tool.


 **You receive:**  [Slave Shackle Bag](/item/17994) 

if( **You turn in:** [Filled Slave Shackle Bag](/item/12661)) then


>**Warlord Hikyg says:** Good work, Soandso. You would make a fine trooper in my garrison. As instructed by the War Baron, I reward you with the geozite tool. May you find your place among the Legion of Cabilis and win many battles.


* __Faction:__ [Cabilis Residents](/faction/440) (2)


* __Faction:__ [Legion of Cabilis](/faction/441) (10)


* __Faction:__ [Scaled Mystics](/faction/445) (2)


* __Faction:__ [Swift Tails](/faction/444) (2)


* __Faction:__ [Crusaders of Greenmist](/faction/442) (2)


 **You receive:**  [Geozite Tool](/item/12657) 

if( **You turn in:** [A Froglok Head](/item/12435), [A Froglok Head](/item/12436), [A Froglok Head](/item/12437), [Soldier's Pike](/item/5133)) then


>*Warlord Hikyg hands you plans for a trooper's pike head. Congratulations. You are now a trooper of the Legion of Cabilis. Now you may fight with honor and a mighty weapon.*


* __Faction:__ [Cabilis Residents](/faction/440) (2)


* __Faction:__ [Legion of Cabilis](/faction/441) (2)


* __Faction:__ [Scaled Mystics](/faction/445) (2)


* __Faction:__ [Swift Tails](/faction/444) (2)


* __Faction:__ [Crusaders of Greenmist](/faction/442) (2)


 **You receive:**  [Trooper Head Plans](/item/12477) (+1200 exp)

if( **You turn in:** [Four Crushed Shields](/item/12913)) then


>**Warlord Hikyg says:** What?!! You crushed all the shields!! You croak-faced skulking brute!! You don't deserve to be in my garrison!! I am going to recommend you for a promotion in hopes that you will be sent to hunt dragons and meet your


* __Faction:__ [Cabilis Residents](/faction/440) (2)


* __Faction:__ [Legion of Cabilis](/faction/441) (2)


* __Faction:__ [Scaled Mystics](/faction/445) (2)


* __Faction:__ [Swift Tails](/faction/444) (2)


* __Faction:__ [Crusaders of Greenmist](/faction/442) (2)


 **You receive:**  [Legionnaire Recommendation](/item/18073) (+2000 exp)

**This NPC *should* return incorrect items given.**







