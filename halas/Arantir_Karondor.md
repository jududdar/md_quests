# Arantir Karondor
## On NPC Spawn

**Set a timer** named *ArantirDepop* for 640 seconds
## Dialog

local qglobals = eq.get_qglobals(e.self,e.other);


**You say:** `hail`



if(qglobals["wizepicB"] == "1") then



>**Arantir Karondor says:** Ah yes, you again. Do you have the items? Give me the three you possess and I'll combine them with my own.


elseif(qglobals["wizepicA"] == "1") then






else



>**Arantir Karondor says:** Before I tell you anything, I require you to help me. Seek a woman named Challice. Give her this ring and then return to me.



**You receive:**  [Arantir's Ring](/item/14334)


**You say:** `story`



>**Arantir Karondor says:** I once was one of four true followers of Solusek Ro. So great were the four of us that Solusek Ro himself made us each a special item. We did not know what the others' items were, but we realized that was for our own safety. Each one of us, after receiving the item, began to plot against Solusek Ro. Each of us believed we had enough power to dominate Norrath. Solusek Ro saw this and at the time we needed our powers most, he stripped us of them. Now I know two of the other wizards by name. One was called Sylen Tyrn, the other's name was Demunir Scry. The last wizard was a gnome, but I can't think of his name.

**You say:** `Sylen Tyrn`



>**Arantir Karondor says:** Sylen was a high elf wizard, and like many high elves, he believed himself to be better than others. Because of his birth, he thought he was more noble and more intelligent than anyone else. I heard how met his demise - while flying over a vast area of water, his powers were stripped from him in midflight. He fell and was captured by a rival wizard who specialized in magics of the water. Search for that wizard and you could find a trace of Sylen.

**You say:** `Demunir Scry`



>**Arantir Karondor says:** Demunir was a human in a rush for power. He was extremely intelligent and resourceful but, unfortunately, was more interested in destructive magic. Hearing of an ancient land, he immediately traveled to it, believing there to be powerful relics left undiscovered there. While exploring, he came upon a dwelling that housed a powerful warrior. Believing himself to be more powerful, he attempted to take this dwelling for himself. While in battle with this warrior, Solusek Ro stole his powers and left him helpless. It is said that Demunir's item is the warrior's most prized trophy.

**You say:** `gnome`



>**Arantir Karondor says:** Ah, the gnome I know very little about. I know he was small and crafty, and that he had a brother. His brother's craft was that of making fireworks, and he was the unfortunate victim of one of his own experiments. His firework exploded, leaving his mind diminished in capacity, even for a gnome. I remember others calling him 'Old Stewpot' in jest. I do not know if this is his birth name, but it may help you to locate him. I hear he also stays close to water because of the explosion. You never know when another gnomish invention will go awry. Give him this letter to help motivate him to remember.


**You receive:**  [Note from Arantir](/item/18169)


* __Faction:__ [Truespirit](/faction/404) (30)











**Arantir Karondor despawns.**
end

## Turn-Ins



local qglobals = eq.get_qglobals(e.self,e.other);




if( **You turn in:** [Blue Crystal Staff](/item/14337), [Gnarled Staff](/item/14338), [Staff of Gabstik](/item/14339)) then 


>**Arantir Karondor says:** Here, this pack contains all of our items. You will never be able to open it again, so you must deliver the pack, intact, to Solomen. He will then reward you. Now that I have helped you, leave me in peace.


 **You receive:**  [Magically Sealed Bag](/item/14340) 


eq.delete_global("wizepicA");


eq.delete_global("wizepicB");

elseif( **You turn in:** [Arantir's Ring](/item/14335)) then




>**Arantir Karondor says:** Ah, but it pains my heart to see this. How I could love a women like that is beyond me. And yet, I still do love her. It was on the day I was to ask her to marry me that I lost my powers. When I was about to cast my greatest spell to prove my love to her, my magic failed. She ran out on me that day. But enough of me, do you wish to hear my story?


eq.set_global("wizepicA","1",1,"F");


**Stop timer** named *ArantirDepop*


**Set a timer** named *ArantirDepop* for 640 seconds

elseif( **You turn in:** [Note to Arantir](/item/18168)) then



eq.delete_global("wizepicA");


eq.set_global("wizepicB","1",1,"F");


**Stop timer** named *ArantirDepop*


**Set a timer** named *ArantirDepop* for 640 seconds

**This NPC *should* return incorrect items given.**

## Timer(s)

**Stop timer** named *ArantirDepop*

**Arantir Karondor despawns.**




