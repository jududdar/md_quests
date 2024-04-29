# Duriek Bloodpool

## Dialog

if( **Faction is** > Dubious) then


**You say:** `apprentice`




>**Duriek Bloodpool says:** As stubborn and foolish as he sometimes was, he was full of potential. Had he managed to achieve my age he doubtless would have surpassed my abilities. Though I am not surprised at his passing, he will be sorely missed. Well, I thank you for your efforts. Feel free to meet me in the tavern for a drink sometime. I must now get to the task of replacing my associate.


**You say:** `replace him`




>**Duriek Bloodpool says:** Hmm, you seem a bit green and I hesitate to trust you with such an important work, but time is of the essence as my days in this world are running out. Bring me back a bottle of cough elixir and, if you are still interested, I will instruct you further.


**You say:** `searching`




>**Duriek Bloodpool says:** I possess a key that will open a sealed tome to be found somewhere in the ruins uncovered here not long ago. Recover that tome for me and I am certain I will be able to corrupt the Ghoulbane. My name will be etched in history and you will wield a legend! You must hurry now, and I must return to my studies. Do not return to me, Soandso, without the tome.


**You say:** `items`




>**Duriek Bloodpool says:** I will need the Ghoulbane, the Soul Leech, the Blade of Abrogation, and the Decrepit Sheath. Alas, I am far too ill to travel and collect these pieces. I must call upon your youth and ability again, Soandso. Return to me with these items and I shall be known throughout history as the greatest grave lord to have walked Norrath and you shall be among the most powerful in our art.

end

## Turn-Ins





if( **You turn in:** [Letter to Duriek](/item/18099)) then


>**Duriek Bloodpool says:** Yes, most unfortunate. I was informed last week of the death of my most recent apprentice. A few months ago, I paid a substantial sum to a group of rogues sent from Neriak to collect on a gambling debt. He swore to me that was theof it, but I suspected otherwise. My warnings of gambling with the rogues fell on deaf ears.


* __Faction:__ [Truespirit](/faction/404) (3)


 **You receive:** 0 (+15000 exp)

elseif( **You turn in:** [Cough Elixir](/item/14365)) then



>**Duriek Bloodpool says:** Thank you. Now, quickly, there is not much time for me. What I tell you here now must never be shared with another soul. I have spent the better part of my life piecing together clues for the creation of a legendary dark blade, a corrupted Ghoulbane. I am very close to understanding the method used in manipulating the enchantments of the Ghoulbane, but in my current condition, I cannot finish collecting the research. My previous apprentice was searching for this last clue when he met his untimely demise.



* __Faction:__ [Truespirit](/faction/404) (3)

elseif( **You turn in:** [Dusty Tome](/item/14382)) then



>*Duriek Bloodpool gasps at you in astonishment, his eyes beaming with pride, and says, 'You've found it! It seems I underestimated you. You have succeeded where others failed. I feared it would never come to pass.' Duriek takes the key from his neck, softly muttering some words, and places it in a previously unseen keyhole. The book's hinges creak as Duriek pulls it open. After reading for a few moments, he says, 'It is even better than I had hoped! It will take me weeks to uncover a portion of what this book has to offer. But this is what I have been searching for, so many years! At last I know the items required to corrupt that accursed blade!'*



* __Faction:__ [Truespirit](/faction/404) (3)

elseif **Faction** >= Apprehensive +17 then


if( **You turn in:** [Ghoulbane](/item/5403), [Soul Leech, Dark Sword of Blood](/item/11609), [Blade of Abrogation](/item/5430), [Decrepit Sheath](/item/14366)) then



e.self:Emote("takes the Ghoulbane and places the other swords on either side of it. The sheath begins to gleam so intensely, you can see the bones inside Duriek's hands. After several minutes, there is a final, blinding flash. Duriek collapses to the ground. After a few moments, Duriek motions you closer and whispers, 'You have done well. I wish fate had been kinder to me and allowed me your aid years ago



* __Faction:__ [Truespirit](/faction/404) (3)



 **You receive:**  [Corrupted Ghoulbane](/item/14367) 



**Duriek Bloodpool despawns.**


**This NPC *should* return incorrect items given.**







