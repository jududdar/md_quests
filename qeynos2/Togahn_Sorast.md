# Togahn Sorast
## Arrive at Waypoint Script

if(e.wp == 16) then


eq.set_anim(2087,1);
end

## Dialog

**You say:** `hail`



>**Togahn Sorast says:** Greetings.. I am Second Master Togahn Sorast. I am here to teach the ways of our guild. For our more advanced members, I will give out [headbands] as a reward for their contribution to the clan.

**You say:** `white`



>**Togahn Sorast says:** Brother Phin gives those headbands out. Go see him about earning one.

**You say:** `headbands`



>**Togahn Sorast says:** The Silent Fist Clan gives out colored Headbands for various deeds completed by our students. Phin gives out the White, Yellow, and Orange Headbands.. and I give out the [Red, Purple, and Blue Headbands].

**You say:** `red headband`



if **Faction** >= Amiable +175 then



>**Togahn Sorast says:** Ah, you think you are skilled enough to earn the red headband of the Silent Fist Clan, Soandso? Hmmm.. Well, if you can help us find [Brother Dareb], you would certainly deserve the honor of wearing the red headband.


elseif **Faction** >= Indifferent then



>**Togahn Sorast says:** I have been watching you, and appreciate the help you've given to the brothers and sisters of the Silent Fist. But, I feel that such a vital matter should be left to one of our more trusted members.


else



>**Togahn Sorast says:** Your previous actions disgust me. Our guild will have nothing to do with the likes of you. Now, please, leave us be!


**You say:** `brother dareb`



if **Faction** >= Amiable +175 then



>**Togahn Sorast says:** Yes, brother Dareb was last heard from over two weeks ago. He was out in the Plains of South Karana, and then just disappeared. We fear that those vile gnolls fleeing Splitpaw may have captured him or worse. We sent brother Shen to go search the Karanas and look for Dareb over three days ago, but haven't heard from him, either. I fear the worst for both of them, especially if the [Splitpaws] are involved. Please, Soandso, find and return our lost brothers to us. If they are not alive, bring back their remains so we may give them a proper burial.. and, if it is that evil [Ghanex Drah]'s doing, bring me his head as well, for the honor of the clan. You do this for us, Soandso, and turn in your orange headband, and I will reward you with the red headband of the Silent Fist. Good luck.


elseif **Faction** >= Indifferent then



>**Togahn Sorast says:** I have been watching you, and appreciate the help you've given to the brothers and sisters of the Silent Fist. But, I feel that such a vital matter should be left to one of our more trusted members.


else



>**Togahn Sorast says:** Your previous actions disgust me. Our guild will have nothing to do with the likes of you. Now, please, leave us be!


**You say:** `splitpaw`



if **Faction** >= Amiable +175 then



>**Togahn Sorast says:** The Splitpaws were a large clan of gnolls that lived in a burrow out in South Karana, They have recently been ousted from their home by a new clan of gnolls that are very powerful. We try to stay away from them if we can, for we do not know much about this new breed. The Splitpaws are on the move and now is the only time to strike. If we wait too long, there will be no way to find our brother. Go now my friend, we haven't much time.


elseif **Faction** >= Indifferent then



>**Togahn Sorast says:** I have been watching you, and appreciate the help you've given to the brothers and sisters of the Silent Fist. But, I feel that such a vital matter should be left to one of our more trusted members.


else



>**Togahn Sorast says:** Your previous actions disgust me. Our guild will have nothing to do with the likes of you. Now, please, leave us be!


**You say:** `Ghanex Drah`



if **Faction** >= Amiable +175 then



>**Togahn Sorast says:** Ghanex Drah is ruler of the now fleeing gnolls of Splitpaw. I've heard rumors that he has been dabbling in the dark art of necromancy. Ghanex is looking for more test subjects, no doubt to rebuild his stronghold. The good people of Antonica must put anto his evil reign soon, or I fear he could grow much more powerful.


elseif **Faction** >= Indifferent then



>**Togahn Sorast says:** I have been watching you, and appreciate the help you've given to the brothers and sisters of the Silent Fist. But, I feel that such a vital matter should be left to one of our more trusted members.


else



>**Togahn Sorast says:** Your previous actions disgust me. Our guild will have nothing to do with the likes of you. Now, please, leave us be!


**You say:** `purple headband`



if **Faction** >= Amiable +250 then



>**Togahn Sorast says:** Ah, you think you are now skilled enough to deserve the purple headband of the Silent Fist Clan? Very well, Soandso, I have a task for you that will prove whether or not you are worthy of this honor. I have heard recent rumors of ancient evils surfacing once again throughout Antonica. These evil groups have discovered some items that are giving them mystical and dangerous powers. These items must be destroyed, or else the evils of Norrath may gain control of the world's future. Bring me these [evil items], and turn in your red headband, and you will have proven yourself a mighty spirit and dedicated member of the Silent Fist.


elseif **Faction** >= Indifferent then



>**Togahn Sorast says:** I have been watching you, and appreciate the help you've given to the brothers and sisters of the Silent Fist. But, I feel that such a vital matter should be left to one of our more trusted members.


else



>**Togahn Sorast says:** Your previous actions disgust me. Our guild will have nothing to do with the likes of you. Now, please, leave us be!


**You say:** `evil items`



if **Faction** >= Amiable +250 then



>**Togahn Sorast says:** These evil creations have been found all over Antonica, and no one knows, or at least no one admits to knowing, where exactly they were found, but we do know that they are currently in the wrong hands and must be destroyed. Please, Soandso, seek out the [Skull of Jhen'Tra], the [Dagger of Marnek], and the [Coronet of Buried Blood], and bring them to me.


elseif **Faction** >= Indifferent then



>**Togahn Sorast says:** I have been watching you, and appreciate the help you've given to the brothers and sisters of the Silent Fist. But, I feel that such a vital matter should be left to one of our more trusted members.


else



>**Togahn Sorast says:** Your previous actions disgust me. Our guild will have nothing to do with the likes of you. Now, please, leave us be!


**You say:** `skull`



if **Faction** >= Amiable +250 then



>**Togahn Sorast says:** I don't know much about the Skull of Jhen'Tra. I've heard that it has resurfaced in the gnoll burial grounds of Lake Rathetear. Apparently, this skull is helping to give these gnolls the power to raise an undead army of their fallen ancestors. This evil must be stopped before their army becomes too powerful.


elseif **Faction** >= Indifferent then



>**Togahn Sorast says:** I have been watching you, and appreciate the help you've given to the brothers and sisters of the Silent Fist. But, I feel that such a vital matter should be left to one of our more trusted members.


else



>**Togahn Sorast says:** Your previous actions disgust me. Our guild will have nothing to do with the likes of you. Now, please, leave us be!


**You say:** `Dagger of Marnek`



if **Faction** >= Amiable +250 then



>**Togahn Sorast says:** The Dagger of Marnek is a diabolical weapon created by the ancient necromancer Marnek Jaull. Marnek was the leader of a small cult of necromancers who worshipped Solusek Ro. Marnek used this dagger in his ceremonial sacrifices to the Burning Prince, to increase his own power and show his loyalty to his god. His cult grew stronger and word of the evil acts spread all over Antonica. Legend has it that a group of paladins from Erudin, followers of Prexus, spent over 10 years searching out Marnek and his followers, and finally destroyed them. Though Marnek's evil reign was put to an many of his books and items are still being uncovered to this day. The Dagger of Marnek is now being used by the evil inhabitants who control the depths of Befallen. Bring this dagger to me, so that we may dispose of it and banish its evil powers forever.


elseif **Faction** >= Indifferent then



>**Togahn Sorast says:** I have been watching you, and appreciate the help you've given to the brothers and sisters of the Silent Fist. But, I feel that such a vital matter should be left to one of our more trusted members.


else



>**Togahn Sorast says:** Your previous actions disgust me. Our guild will have nothing to do with the likes of you. Now, please, leave us be!


**You say:** `Coronet of Buried Blood`



if **Faction** >= Amiable +250 then



>**Togahn Sorast says:** The Coronet of Buried Blood is an ancient headdress which is said to have belonged to the High Priest of the Plexant Temple. The Plexant were known to be devout followers of Innoruuk and the coronet is supposed to have been blessed by the Prince of Hate himself. Apparently, the coronet is now in the hands of a clan of goblins that dwell in the caverns of Permafrost.


elseif **Faction** >= Indifferent then



>**Togahn Sorast says:** I have been watching you, and appreciate the help you've given to the brothers and sisters of the Silent Fist. But, I feel that such a vital matter should be left to one of our more trusted members.


else



>**Togahn Sorast says:** Your previous actions disgust me. Our guild will have nothing to do with the likes of you. Now, please, leave us be!


**You say:** `blue headband`



>**Togahn Sorast says:** Sorry, we are currently out of blue headbands. Please check back later.

**You say:** `black headband`



>**Togahn Sorast says:** The black headband is one of the highest honors of our guild.. [Lu'Sun] only gives those out for great acts of heroism and devotion to the clan.

**You say:** `LuSun`



>**Togahn Sorast says:** Ahhh, Lu'Sun is a master of many skills. He has traveled all of Norrath, studying various techniques and disciplines. Now, he runs this small guild and passes on his knowledge to those willing to devote their lives to our cause.
end

## Turn-Ins



local text1 = "Good work, Soandso, your task is almost completed. You are almost ready for the red headband of the Silent Fist Clan.";

local text2 = "Good work, Soandso, your task is almost completed.";




if **Faction** >= Amiable +175 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_934.png" alt="" /> <a
                                href="/item/10112" data-url="10112" class="tooltip-link link">Orange Headband</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_744.png" alt="" /> <a
                                href="/item/13165" data-url="13165" class="tooltip-link link">Head of Ghanex Drah</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1070.png" alt="" /> <a
                                href="/item/13166" data-url="13166" class="tooltip-link link">Dareb's Skull</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_982.png" alt="" /> <a
                                href="/item/13167" data-url="13167" class="tooltip-link link">Head of Shen</a>) then


>**Togahn Sorast says:** We are deeply honored to have such great warrior as part of our Clan. With a proper burial, Shen and Dareb's souls will finally be at peace, and with the death of that vile Ghanex, the plains will be much safer for travelers. It is a great honor to present you, Soandso, with the red headband of the Silent Fist Clan.


Your faction standing with [Silent Fist Clan](/faction/309) got better (<span class='text-success'>+75</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+11</span>)


Your faction standing with [Ashen Order](/faction/361) got better (<span class='text-success'>+5</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_935.png" alt="" /> <a
                                href="/item/10113" data-url="10113" class="tooltip-link link">Red Headband</a> (+1600 exp)

 



elseif **Faction** >= Amiable +250 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_935.png" alt="" /> <a
                                href="/item/10113" data-url="10113" class="tooltip-link link">Red Headband</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_574.png" alt="" /> <a
                                href="/item/13169" data-url="13169" class="tooltip-link link">Dagger of Marnek</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_523.png" alt="" /> <a
                                href="/item/3000" data-url="3000" class="tooltip-link link">Zaharns Coronet</a>) then


>**Togahn Sorast says:** In honor of your recent acts of courage and dedication, I reward you, Soandso, with the purple headband of the Silent Fist Clan.


Your faction standing with [Silent Fist Clan](/faction/309) got better (<span class='text-success'>+100</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+15</span>)


Your faction standing with [Ashen Order](/faction/361) got better (<span class='text-success'>+5</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_936.png" alt="" /> <a
                                href="/item/10114" data-url="10114" class="tooltip-link link">Purple Headband</a> (+3200 exp)

 

**This NPC *should* return incorrect items given.**


