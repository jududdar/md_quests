# Tolon Nurbyte
## On NPC Spawn

**Set a timer** named *visit* for 150 seconds
## Timer(s)

if(e.timer == "visit") then


**Tolon Nurbyte despawns.**
end

## Dialog

**You say:** `hail`



>**Tolon Nurbyte says:** Didn't your mother teach you not to walk in other people's rooms without knocking?! You didn't even have the courtesy to close the door behind you!!

**You say:** `princess lenya thex`



>**Tolon Nurbyte says:** What?!!  You have word of the Princess?  She has been missing for quite a while.  I sent Tearon to Tunaria to search for her, but he has not reported back.  If you wish to help, you'd better prove yourself worthy first. I believe you should talk to Tynkale.

**You say:** `glory.* mother.* shine.* bright`



if **Faction** >= Amiable then 



>**Tolon Nurbyte says:** So you're the slayer of Jojongua. Funny, I thought you would be taller. I guess you will have to do. I am Tolon Nurbyte of the Silent Watch. We do all the dirty work of King Tearis Thex. No one knows of us. So I hope you accept this mission or I will have to kill you. Do you [accept the mission] or do you [wish to leave]?


else



>**Tolon Nurbyte says:** When you have furthered your service to the Paladins of Tunare, we shall make conversation.


**You say:** `wish.* leave`



if **Faction** >= Amiable then 



e.self:Say("There is only insufferable labor and merciless torment here, stranger. Kaya Rishareth has condemned her eternal self to servitude in the War Forge 



**Tolon Nurbyte attacks you.**


else



>**Tolon Nurbyte says:** When you have furthered your service to the Paladins of Tunare, we shall make conversation.


**You say:** `accept.* mission`



if **Faction** >= Kindly then 



>**Tolon Nurbyte says:** In her mortal life, Kaya Rishareth was a keeper of tranquility and served her beloved child-like goddess with every fiber of her being. A native to the free city of Freeport, Kaya found herself traveling on her own as soon as her master would allow. Erudin was the destination she chose and it was the temples dedicated to The Tranquil where she sought to learn more about her goddess and perhaps share philosophies and knowledge with the High Men. Erudin received her graciously and for nearly a year, she studied the High Men's way of worship and reverence to their shared deity. However, tranquility is easily disrupted and those who seek it, must also [defend it].


else



>**Tolon Nurbyte says:** When you have furthered your service to the Paladins of Tunare, we shall make conversation.


**You say:** `silent watch`



if **Faction** >= Kindly then



>**Tolon Nurbyte says:** The Silent Watch was established in the early years of Felwithe. King Tearis Thex had many cruel deeds to do. The regular Koad'Vie were too righteous to carry out any of the necessary missions and we dare not bring in the Fier'Dal. After all, some of the operations were against Kelethin.  King Tearis formed our group from Koada'Dal not of such prim and proper breeding. Now we act as his secret guard and report only to him.


else



>**Tolon Nurbyte says:** When you have furthered your service to the Paladins of Tunare, we shall make conversation.


**You say:** `thex dagger`



if **Faction** >= Kindly then



e.self:Say("The heretics had planted a false convert in Kaya's midst, and when her good nature was focused upon this deceitful youth, she was led into a trap. The heretics defeated her in battle within the very temple of the city and her unconscious, bound and gagged body was taken to the shores. She was executed 


else



>**Tolon Nurbyte says:** When you have furthered your service to the Paladins of Tunare, we shall make conversation.

end

## Turn-Ins




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/18841" data-url="18841" class="tooltip-link link">Sealed Letter</a>) then


>**Tolon Nurbyte says:** So I see you completed your mission. Good work. You just may be a member of the Silent Watch someday. Well my friend. I will be keeping my eye on you. No doubt we will meet again. Oh, I almost forgot. The Princess wanted you to have this. Now show yourself the door.


Your faction standing with [Clerics of Tunare](/faction/226) got better (<span class='text-success'>+25</span>)


Your faction standing with [King Tearis Thex](/faction/279) got better (<span class='text-success'>+25</span>)


Your faction standing with [Anti-mage](/faction/5002) got better (<span class='text-success'>+25</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_592.png" alt="" /> <a
                                href="/item/13362" data-url="13362" class="tooltip-link link">Thexian Shiv</a> (+0 exp)

 


**Tolon Nurbyte despawns.**
end