# Tomer Instogle



[Tomer Instogle](/npc/2030) is a level 1 Human Monk that spawns in [North Qeynos](/zone/2).

local closeby = 0;



## Dialog

if(closeby == 0) then


**You say:** `Hail`







if( **Faction is** >= Indifferent) then 




>**Tomer Instogle says:** Ahhhgggg.. Those mangy [dogs] put up a tough fight.. If I don't make it back to the Clan House soon, it'll all be over for me.




eq.stop_follow();




**Stop timer** named *cooldown*




eq.start(75);



else




>**Tomer Instogle says:** What? Knowing how we feel about you and your reputation, not to mention the grief you've caused Master Lu'Sun, you would try to act as my friend?!?  Leave me alone!




**You say:** `dogs`




>**Tomer Instogle says:** It's those Darkpaws.. They've beat me pretty badly.. but they'll get theirs soon enough!


**You say:** `clan`




>**Tomer Instogle says:** I am a new member of the Silent Fist Clan.. I need someone from my guild to help me find my way back.


**You say:** `seta.* find you`




>**Tomer Instogle says:** Oh.. Thank goodness you found me.. I'm lost and weak, those [mutts] are a vicious lot.. an you carry my [backpack] for me?


**You say:** `carry.* backpack`




>**Tomer Instogle says:** Thank you, friend.. Now, can you lead me back to Master Seta of the [Silent Fist Clan]? 



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_565.png" alt="" /> <a
                                href="/item/13769" data-url="13769" class="tooltip-link link">Ruined Backpack</a>


**You say:** `lead.* seta`




>**Tomer Instogle says:** Lead the way, and I shall follow. When we make it back, please inform Seta that you have rescued me.



eq.stop();



eq.follow(e.other:GetID());



**Set a timer** named *cooldown* for 1800 seconds

end



## Signals

if(e.signal == 1 and closeby == 0 and (e.self:GetX() >= 300 and e.self:GetX() <= 340) and (e.self:GetY() >= 250 and e.self:GetY() <= 285)) then


>**Tomer Instogle says:** I am now accepting quests.


eq.stop_follow();


e.self:SaveGuardSpot();


closeby = 1;


>**Tomer Instogle says:** Yes, he saved my life...  I owe him much thanks.  Please return my pack to me now, good friend.


**Set a timer** named *cooldown* for 1800 seconds
end



## Turn-Ins



if(closeby == 1 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_565.png" alt="" /> <a
                                href="/item/13769" data-url="13769" class="tooltip-link link">Ruined Backpack</a>) then 


>**Tomer Instogle says:** Oh, you have the makings of a true hero.. The Silent Fist Clan is proud to have you as ally. May your soul guide and protect you through these chaotic times.





Your faction standing with [Silent Fist Clan](/faction/309) got better (<span class='text-success'>+35</span>)



Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+5</span>)




Your faction standing with [Ashen Order](/faction/361) got better (<span class='text-success'>+1</span>)




 &#127873; **You receive:** 0 (+100 exp)

 


closeby = 2;


**Set a timer** named *cooldown* for 1200 seconds
end



## Timer(s)

closeby = 0;

eq.stop_follow();

e.self:SaveGuardSpot(true);

eq.start(75);

**Stop timer** named *cooldown*