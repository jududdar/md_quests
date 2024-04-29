# Captain Koldar

local count = 0;
## On NPC Spawn

**Set a timer** named *koldar* for 150 seconds
## Timer(s)

count = count + 1;

if(count == 1) then


>**Captain Koldar says:** There are many things you can do for Shar Vahl. Do not sit on your arse expecting our city to progress without your aid. It is your duty and your honor to defend our king.

if(count == 2) then


>**Captain Koldar says:** We cannot afford to let those vile creatures take our city.

if(count == 3) then


>**Captain Koldar says:** I want every one of you to bring at least four of their bloody hearts to me every day.

if(count == 4) then


>**Captain Koldar says:** We have a responsibility to protect this city. We cannot afford to wait for them to understand that we are not their enemy.

if(count == 5) then


>**Captain Koldar says:** If you see someone in battle, you must ask them before assisting. Do not dishonor them by taking their right to die in a fair and honorable battle.

if(count == 6) then


>**Captain Koldar says:** You there! Is that rust I see on your spear? You must find a blacksmith to repair it immediately.

if(count == 7) then


>**Captain Koldar says:** Remember to protect your hunting groups. It is our duty as Khala Dun to do so. Anger your enemy, use taunting tactics to keep them distracted.

if(count == 8) then


>**Captain Koldar says:** If you are wounded, seek out a Dar Khura. It is better to allow them to aid you than to wait for your wounds to heal. There is no shame in seeking assistance in this, for we must be sure to return to the battle as quickly as possible. Remember, we have a city to defend.

if(count == 9) then


>**Captain Koldar says:** Watch your spear there! Your weapons are not toys. Be careful where you point them.


count = 0;


**Set a timer** named *koldar* for 150 seconds
end

## Dialog

**You say:** `hail`



>**Captain Koldar says:** Stand back hunter! Not all of my men are properly trained in the use of their spears. You may find yourself losing an eye if you get too close. Now then, I assume you have [come to help.] Is that correct?

**You say:** `come to help`



>**Captain Koldar says:** Then why are you standing around! Can't you see the invading forces of the Shak Dratha approach our town? Destroy them and bring me four of their bloody hearts as proof of your deed. Snap to it!
end

## Turn-Ins



if( **You turn in:** [Bloody Shak Dratha Heart](/item/30616), [Bloody Shak Dratha Heart](/item/30616), [Bloody Shak Dratha Heart](/item/30616), [Bloody Shak Dratha Heart](/item/30616)) then


>**Captain Koldar says:** Blasted! Took you long enough. Look! They've already brought in more troops. We have a city to protect here. Now patch yourself up and get back to it.' Koldar hands Soandso a handful of bandages.


 **You receive:** GiveAll( [Bandages](/item/13009), [Bandages](/item/13009), [Bandages](/item/13009), [Bandages](/item/13009), [Bandages](/item/13009), [Bandages](/item/13009)) (+2000 exp)

**This NPC *should* return incorrect items given.**





