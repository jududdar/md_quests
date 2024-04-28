# Branis Noolright
local signal = 0;
local lastSong = 0;

## On NPC Spawn

**Set a timer** named *ready* for 300 seconds
## Timer(s)

if ( e.timer == "ready" ) then


>**Branis Noolright says:** What a cheerful crowd.


**Stop timer** named *ready*




elseif ( e.timer == "bar" ) then


**Stop timer** named *bar*


**Set a timer** named *table* for 1 seconds


**Signaled to:**  [Tlin Bowfright](/npc/10186)


**Signaled to:**  [Tykar Renlin](/npc/10157)


**Signaled to:**  [Plnorrick Spinecracker](/npc/10163)


**Signaled to:**  [Biggle Limbokker](/npc/10160)


elseif ( e.timer == "table" ) then


**Stop timer** named *table*


**Signaled to:**  [Sir Edwin Motte](/npc/10199)


**Signaled to:**  [Talym Shoontar](/npc/10182)


**Signaled to:**  [Imxil Tbrow](/npc/10012)


**Signaled to:**  [Groflah Steadirt](/npc/10195)

end

## Dialog

**You say:** `hail`



>**Branis Noolright says:** Good day to you! Sit and have a drink. I shall be playing soon enough.
end

## Signals

song = math.random(1, 6);

while ( song == lastSong ) do


song = math.random(1, 6);

lastSong = song;



if ( song == 1 ) then


>**Branis Noolright says:** Look around you. Stand up tall!! Feel for the poor and never have a cold heart. Because we are all in this. We are not like the rest. We're all here together and know we are the best. So Norrath, can't you see the error in your ways? You're living separated each and every day. Don't be thinking that we don't want you, because, Norrath, we do. Freeport is the only place where your friend can be from afar. I hope you enjoyed that one.


**Set a timer** named *bar* for 1 seconds


signal = 1;

elseif ( song == 2 ) then


>**Branis Noolright says:** Within my head and inside my brain, I hold the key. It is not much more than the size of a pea. With it, I have the power to set free Oggok city. Open up its doors to all that is pretty. Instead, here I am in a pile of my own dug, smelling quite dingy. Drinking ogre swill with which I am stingy. I may have the key, but the point is quite moot. For you see, I am nothing more than a dumb, smelly, ogre brute. Thank you. I hope you enjoyed that one.


**Set a timer** named *bar* for 1 seconds


signal = 2;

elseif ( song == 3 ) then


>**Branis Noolright says:** All clap and pass the ale. Sir Lucan is in charge so don't set sail. All clap and pass the ale. Sir Lucan is in charge and he shall never fail. He saved our fair city when the others had fled. Off on a crusade, or so they said. All clap  and pass the ale, Sir Lucan is in charge so don't you bail. All clap and pass the ale, Sir Lucan is in charge so sing or go to jail. All clap and pass the ale, Sir Lucan beat the orcs and next is Bayle. Thank you. I hope the Freeport citizens liked that one.


**Set a timer** named *bar* for 1 seconds


signal = 3;

elseif ( song == 4 ) then


>**Branis Noolright says:** My city is mighty and all shall learn to cower. We are nothing less than the ultimate power. My city is pure and filled with beautiful charm. I shall conquer you to save you from harm. My city shall first send its guards to back you in times of need. Soon you shall learn to live under my laws, indeed. So bow down when you see me and give out my favorite cheer, 'All Hail Antonius Bail!' My city is Qeynos and there is nothing to fear.


**Set a timer** named *bar* for 1 seconds


signal = 4;

elseif ( song == 5 ) then


>**Branis Noolright says:** Life is dull and dreary when you know it all. To the planes of the gods, is their next call. An Erudite, an Erudite has come to drink. All the knowledge in the world, or so they think. One drink, two drinks, grab and down the ale! Then they step off their stools and their faces begin to pale. For all their love of music and their great schools of magic, up come their lunches, how very tragic. So let all sit back and be ready with hijinks, an Erudite has come to the Seafarer to down a few drinks.


**Set a timer** named *bar* for 1 seconds


signal = 5;

elseif ( song == 6 ) then


>**Branis Noolright says:** Here's one for Sir Lucan... He's just a ruler. In a long line of rulers. Looking for a few more orcs to slay. They say that he fights them with one hand tied to his back. And he won't leave Freeport till you remember his name. Thank you.


**Set a timer** named *bar* for 1 seconds


signal = 7;
end

