# Runethar Hamest



[Runethar Hamest](/npc/1128) is a level 61 Human GM Paladin that spawns in [South Qeynos](/zone/1).



## Signals

>**Runethar Hamest says:** Hire one soon, Wolten. We need to get in touch with Drosco!


## Dialog

**You say:** `hail`



>**Runethar Hamest says:** Welcome to the Temple of Thunder. We are home to paladins and clerics who follow the ways of Karana. Do you [need guidance] or are you [already a follower of Karana]?

**You say:** `need guidance`



>**Runethar Hamest says:** Then go forth into the church and speak with Gehna Solbenya. She will assist you.

**You say:** `follower of karana`



if( **Faction is** >= Amiable) then



**You say:** `follower of karana`





>**Runethar Hamest says:** So you are one with our cause? This is good. Be aware that there are forces at work which not even the Qeynos Guard can keep at bay. We are here to spread the words of Karana and smite those who should try toHis children. We and Antonius Bayle shall work together in our destruction of evil. He requests our aid. Do you also [wish to assist Lord Bayle]?



**You say:** `wish to assist`





>**Runethar Hamest says:** Then we command you to assist the Qeynos Guard with the destruction of Blackburrow. Report to Captain Tillin of Qeynos Guard and speak with him of the [gnolls of Blackburrow]. I believe he is at the arena. My loyal friend, if you have earned your Thunder Staff, I urge you to [retrieve the Bayle list].












elseif( **Faction is** == Indifferent) then



>**Runethar Hamest says:** Well, friend, the Temple of Thunder has recognized and appreciates your past deeds for us.  But this matter is of vital importance to us and we need more proof of your devotion to our cause.


else



>**Runethar Hamest says:** You have proven yourself not only an enemy of the Knights of Thunder, but an enemy of Karana himself. Now leave, sewer rat!



**You say:** `retrieve the Bayle list`



if **Faction** >= Warmly +150 then



>**Runethar Hamest says:** The Temple of Thunder was asked by Antonius Bayle to retrieve a list. He does not trust his own militia of late. He asked me to send a knight to the Jaggedpine to find a man named Frenway Marthank. When you find him, you are to tell him that [Toe needs the Bayle List]. Return the Bayle List and your Thunder Staff to me and I shall provide a fine reward. Be aware that the shadowknights of Bertoxxulous are also after the list. Be careful!



elseif **Faction** >= Indifferent then



>**Runethar Hamest says:** Well, friend, the Temple of Thunder has recognized and appreciates your past deeds for us.  But this matter is of vital importance to us and we need more proof of your devotion to our cause.


else



>**Runethar Hamest says:** You have proven yourself not only an enemy of the Knights of Thunder, but an enemy of Karana himself. Now leave, sewer rat!





**You say:** `honored member`



if **Faction** >= Indifferent +50 then



>**Runethar Hamest says:** Yes.  The light of righteousness shines from within you.


elseif **Faction** >= Indifferent then



>**Runethar Hamest says:** Well, friend, the Temple of Thunder has recognized and appreciates your past deeds for us.  But this matter is of vital importance to us and we need more proof of your devotion to our cause.


else



>**Runethar Hamest says:** You have proven yourself not only an enemy of the Knights of Thunder, but an enemy of Karana himself. Now leave, sewer rat!



**You say:** `drosco`



>**Runethar Hamest says:** Have you knowledge of Sir Drosco? He is a Knight of Thunder and reports to Sir Wolten. He has been missing for quite some time. I believe Sir Wolten has begun a search for him.

**You say:** `karana`



>**Runethar Hamest says:** Karana, the Rainkeeper, is the provider of the storms. If it were not for the storms of Karana, life would not flourish. All should pay tribute to the Rainkeeper.

**You say:** `bertoxxulous`



>**Runethar Hamest says:** Bertoxxulous, the Plaguebringer, is the Lord of Disease. It is he who smites Norrath with his diseases and imperfections. Those who follow him are called [Bloodsabers].

**You say:** `bloodsaber`



>**Runethar Hamest says:** It is rumored that there is a shrine in the great city of Qeynos which pays homage to the Plaguebringer, Bertoxxulous. The members of this vile church of the damned are called the Bloodsabers. They are dreaded shadowknights, necromancers and evil clerics. It is our duty to destroy all who dare to pray to such a deity. Join our fight. Speak more of this matter with Chesgard Sydwend.

**You say:** `healer`



>**Runethar Hamest says:** If you need to be healed, I suggest you speak with the Priests of Life. You can find them in the Temple of Life on the other side of Qeynos. The only service you can pay for here is holy armor. Daedet Losaren charges followers of Karana for that blessing.
end



## Turn-Ins



local text = "I thank you, but before I reward you I must have both the Bayle List II and your Thunder Staff.";


if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_864.png" alt="" /> <a
                                href="/item/18710" data-url="18710" class="tooltip-link link">A tattered note</a>) then


>**Runethar Hamest says:** Greetings, fellow knight of Karana, and welcome to the Temple of Thunder! Here, wear this tunic and help our crusade. Wolten Grafe is my assistant, he will get you started and teach you the ways of the Rainkeeper.


Your faction standing with [Knights of Thunder](/faction/280) got better (<span class='text-success'>+100</span>)


Your faction standing with [Bloodsabers](/faction/221) got worse (<span class='text-danger'>-100</span>)


Your faction standing with [Priests of Life](/faction/341) got better (<span class='text-success'>+75</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+75</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_678.png" alt="" /> <a
                                href="/item/13505" data-url="13505" class="tooltip-link link">Old Gray Tunic*</a> (+100 exp)

 

elseif **Faction** >= Warmly +150 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/18809" data-url="18809" class="tooltip-link link">Bayle List II</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_602.png" alt="" /> <a
                                href="/item/6357" data-url="6357" class="tooltip-link link">Thunder Staff</a>) then


>**Runethar Hamest says:** Antonius Bayle will be pleased. The Temple is also pleased. Here is the enchanted staff we call Bonethunder. Should you find the enchantment gone, just ask Kasine to [enchant Bonethunder]. We need more disciples like you! Go forth to tell the world of the Rainkeeper.


Your faction standing with [Knights of Thunder](/faction/280) got worse (<span class='text-danger'>-50</span>)


Your faction standing with [Bloodsabers](/faction/221) got better (<span class='text-success'>+50</span>)


Your faction standing with [Priests of Life](/faction/341) got worse (<span class='text-danger'>-37</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got worse (<span class='text-danger'>-37</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_602.png" alt="" /> <a
                                href="/item/6358" data-url="6358" class="tooltip-link link">Bonethunder Staff</a> (+1000 exp)

 

**This NPC *should* return incorrect items given.**



