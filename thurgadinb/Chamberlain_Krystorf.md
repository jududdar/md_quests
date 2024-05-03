# Chamberlain Krystorf


## Dialog

**You say:** `hail`



>**Chamberlain Krystorf says:** Greetings and welcome to Thurgadin, Soandso. I am Chamberlain Krystorf and it is my duty to assist the Dain in the management of Icewell Keep and the Royal Court. One could say that Seneschal Aldikar is the Sword of the Dain while I am the Shield, protecting all of his interests and those of the kingdom.
end



## Turn-Ins



local text = "For storage reasons I'm afraid I can only accept four of these at once for the bounty."



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_747.png" alt="" /> <a
                                href="/item/29062" data-url="29062" class="tooltip-link link">Giant Warrior Helmet</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_747.png" alt="" /> <a
                                href="/item/29062" data-url="29062" class="tooltip-link link">Giant Warrior Helmet</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_747.png" alt="" /> <a
                                href="/item/29062" data-url="29062" class="tooltip-link link">Giant Warrior Helmet</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_747.png" alt="" /> <a
                                href="/item/29062" data-url="29062" class="tooltip-link link">Giant Warrior Helmet</a>) then


>**Chamberlain Krystorf says:** Well done, Soandso, the Dain is pleased with your efforts. With a few more brave allies like you, we'll soon be tearing down the halls of Kael Drakkel.





Your faction standing with [Dain Frostreaver IV](/faction/405) got better (<span class='text-success'>+50</span>)


Your faction standing with [Coldain](/faction/406) got better (<span class='text-success'>+50</span>)


Your faction standing with [King Tormax](/faction/429) got worse (<span class='text-danger'>-25</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_741.png" alt="" /> <a
                                href="/item/30215" data-url="30215" class="tooltip-link link">Coldain Velium Morning Star</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_762.png" alt="" /> <a
                                href="/item/30219" data-url="30219" class="tooltip-link link">Coldain Velium Rapier</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_580.png" alt="" /> <a
                                href="/item/30212" data-url="30212" class="tooltip-link link">Coldain Velium Short Sword</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_888.png" alt="" /> <a
                                href="/item/30263" data-url="30263" class="tooltip-link link">Coldain Velium-Pick</a>) (+5000 exp)

**You receive coin:** 1-20 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_642.png" alt="" /> <a
                                href="/item/1199" data-url="1199" class="tooltip-link link">Runed Coldain Prayer Shawl</a>) then


>**Chamberlain Krystorf says:** One moment the Dain has been waiting for you. I will call for him.. oh here he is now, show your shawl to him.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_642.png" alt="" /> <a
                                href="/item/8895" data-url="8895" class="tooltip-link link">Runed Coldain Prayer Shawl</a> 

 


if(not **You possess item:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_837.png" alt="" /> <a
                                href="/item/17651" data-url="17651" class="tooltip-link link">Empty Coldain Issue Kit</a> x 1



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_837.png" alt="" /> <a
                                href="/item/17651" data-url="17651" class="tooltip-link link">Empty Coldain Issue Kit</a> 

 



if(**spawned NPC:**  [\#Dain Frostreaver IV](/npc/129003) == false and **spawned NPC:** 129101 == false) then



eq.spawn_condition("thurgadinb",3,0);



eq.spawn_condition("thurgadinb",3,1);


elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_642.png" alt="" /> <a
                                href="/item/8895" data-url="8895" class="tooltip-link link">Runed Coldain Prayer Shawl</a>) then


>**Chamberlain Krystorf says:** As I stated previously, you should show this to the Dain.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_642.png" alt="" /> <a
                                href="/item/8895" data-url="8895" class="tooltip-link link">Runed Coldain Prayer Shawl</a> 

 

**This NPC *should* return incorrect items given.**
