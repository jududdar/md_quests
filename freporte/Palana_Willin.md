# Palana Willin
local signal = 0;
local lastSong = 0;

## On NPC Spawn

**Set a timer** named *ready* for 300 seconds
## Dialog

**You say:** `hail`



>**Palana Willin says:** Nice to meet you, Soandso. I hope you stay to hear my fine compositions.
end

## Timer(s)

if ( e.timer == "ready" ) then


>**Palana Willin says:** What a cheerful crowd.


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

## Signals

song = math.random(1, 6);

while ( song == lastSong ) do


song = math.random(1, 6);

lastSong = song;



if ( song == 1 ) then


>**Palana Willin says:** Here's one for Sir Lucan... He's just a ruler. In a long line of rulers. Looking for a few more orcs to slay. They say that he fights them with one hand tied to his back. And he won't leave Freeport till you remember his name. Thank you.


**Set a timer** named *bar* for 1 seconds


signal = 7;

elseif ( song == 2 ) then


>**Palana Willin says:** Yo ho, in the merry old harbor of Sir D'lere. There lived a small man who lived in fear. Fear of the pawns and fear of the fish, but most of all fear of the bottle. One day as he sailed overseas, he encountered a spat. A lovely lady being harrassed by a buccaneer, tall and fat. He hid all his fear and yelled 'Let her go!' The buccaneer said that he would do so. 'I will do so if you can drink from this bottle, oblong and of weight, for twenty whole seconds. Will you test your fate?' So as the ship did thread the needle around a quater to live, foolish Turgin drank, passed out and took a dive. Under went he and the evil bottle too. Now all should fear the bottle of ochre goo.

elseif ( song == 3 ) then


>**Palana Willin says:** All clap and pass the ale. Sir Lucan is in charge so don't set sail. All clap and pass the ale. Sir Lucan is in charge and he shall never fail. He saved our fair city when the others had fled. Off on a crusade, or so they said. All clap  and pass the ale, Sir Lucan is in charge so don't you bail. All clap and pass the ale, Sir Lucan is in charge so sing or go to jail. All clap and pass the ale, Sir Lucan beat the orcs and next is Bayle. Thank you. I hope the Freeport citizens liked that one.


**Set a timer** named *bar* for 1 seconds


signal = 3;

elseif ( song == 4 ) then


>**Palana Willin says:** My city is mighty and all shall learn to cower. We are nothing less than the ultimate power. My city is pure and filled with beautiful charm. I shall conquer you to save you from harm. My city shall first send its guards to back you in times of need. Soon you shall learn to live under my laws, indeed. So bow down when you see me and give out my favorite cheer, 'All Hail Antonius Bail!' My city is Qeynos and there is nothing to fear.


**Set a timer** named *bar* for 1 seconds


signal = 4;

elseif ( song == 5 ) then


>**Palana Willin says:** Life is dull and dreary when you know it all. To the planes of the gods, is their next call. An Erudite, an Erudite has come to drink. All the knowledge in the world, or so they think. One drink, two drinks, grab and down the ale! Then they step off their stools and their faces begin to pale. For all their love of music and their great schools of magic, up come their lunches, how very tragic. So let all sit back and be ready with Hijinks, an Erudite has come to the Seafarer to down a few drinks.


**Set a timer** named *bar* for 1 seconds


signal = 5;

elseif ( song == 6 ) then


>**Palana Willin says:** Here is one for my former lover, Joffrey Clay. You took the lute. It was my favorite one. A little white lute, and went off to Qeynos. You took the songs. They were all special ones. Packed them all up. Off to Qeynos. You killed the plant. Put it in a deep freeze. Dumped it in the trunk. With the rest of the refuse. You, left to Qeynos. You, left to Qeynos. You, left to Qeynos. You, left to Qeynos.


**Set a timer** named *bar* for 1 seconds


signal = 6;
end