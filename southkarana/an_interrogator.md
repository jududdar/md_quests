# an interrogator

local brief;
local name;



## Turn-Ins




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18292" data-url="18292" class="tooltip-link link">Interrogators Briefing</a> ) then 


>**an interrogator says:** I see you wish to become an interrogator. This is not a duty for the weak of heart you know. This job sometimes requires...


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_682.png" alt="" /> <a
                                href="/item/2344" data-url="2344" class="tooltip-link link">Confession Document</a> (+1000 exp)

 


**Set a timer** named *brief* for 10 seconds


name = e.other:GetName();


brief = 0;

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_982.png" alt="" /> <a
                                href="/item/2390" data-url="2390" class="tooltip-link link">Head of Markus Cachexia</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_982.png" alt="" /> <a
                                href="/item/2391" data-url="2391" class="tooltip-link link">Head of Morley Murrain</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_683.png" alt="" /> <a
                                href="/item/2395" data-url="2395" class="tooltip-link link">Theodore's Confession</a>) then 


>**an interrogator says:** Excellent work, you did just fine today. You'll make a fine interrogator. Talk to Vegalys about advancing further.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_566.png" alt="" /> <a
                                href="/item/2387" data-url="2387" class="tooltip-link link">Interrogator's Badge</a> (+5000 exp)

 

**This NPC *should* return incorrect items given.**



## Timer(s)

if(e.timer == "brief") then


brief = brief + 1;

if(brief == 1) then


>*an interrogator coughs, 'a little muscle I guess you would say.'*

elseif(brief == 2) then


>**an interrogator says:** Nevertheless, we have an important job to do. There is a man by the name of Theodore Exanthem who is a known member of the Bloodsaber cult. He fled from Qeynos some time ago and we have been hot on his tail ever since.

elseif(brief == 3) then


>**an interrogator says:** We have tracked this man down and we now know his whereabouts. However, we have bigger fish to fry today then just this low life. Theodore knows the location of two other individuals also suspected of hiding out here in the plains.

elseif(brief == 4) then


>**an interrogator says:** Sadly, these fiends were the two that slipped into Surefall Glade and poisoned the waters there. Though the druids were able to quickly combine their efforts and neutralize the toxins with their magicks, grievous damage was done none the less. Two of the great protectors of the hills and the glade, Holly Windstalker and Cros Treewind, became seriously ill as did one of the glade's sacred bears.

elseif(brief == 5) then


>**an interrogator says:** Holly and Cros, sickened as they were, removed themselves from the Hills to weather out their illness and to keep the disease from spreading further. During their absence, the Bloodsabers were easily able to traffic in the materials needed to complete their terrible work.

elseif(brief == 6) then


>*an interrogator shakes his head sadly and says, 'Tragically, Cros Treewind was attacked by one of the sacred bears which was maddened by its illness. In his weakened state Cros was unable to defend himself and was killed by this defiled grizzly, one of the very creatures he was sworn to protect.'*

elseif(brief == 7) then


>**an interrogator says:** So our goal is to pry the information we need from Theodore Exanthem so that we may bring these two fugitives to justice. After getting him to comply, you are to collect a confession from Theodore and have him lead us to the two fugitives. Give me Theodore's confession and the heads of these two fugitives and you shall have your badge

elseif(brief == 8) then


e.self:Say(string.format("follow me, %s",name));


eq.start(4); 


**Stop timer** named *brief*
end



## Arrive at Waypoint Script

if(e.wp == 1) then





>**an interrogator says:** Theodore Exanthem by order of the Council of Qeynos and his lordship Antonius Bayle, I order you to come out of there immediately!


**Spawn NPC:**  [\#Theodore Exanthem](/npc/14146) at (**y:** -5465, **x:** -2680)

elseif(e.wp == 2) then  


**Signaled to:**  [\#Theodore Exanthem](/npc/14146)

elseif(e.wp == 3) then


**Spawn NPC:**  [\#Morley Murrain](/npc/14147) at (**y:** -6040, **x:** -3287)


**Spawn NPC:**  [\#Markus Cachexia](/npc/14127) at (**y:** -6050, **x:** -3280)


**Spawn NPC:**  [Skeletal Servant](/npc/14140) at (**y:** -6075, **x:** -3285)


**Spawn NPC:**  [Skeletal Servant](/npc/14140) at (**y:** -6055, **x:** -3333)


**Spawn NPC:**  [Ghoul](/npc/14148) at (**y:** -6056, **x:** -3306)


**Signaled to:**  [\#Theodore Exanthem](/npc/14146)
end



## Signals

if(e.signal == 1) then


>**an interrogator says:** Theodore Exanthem, you will [take us to the location] of Marcus Cachexia and Morley Murrain immediately.


**Signaled to:**  [\#Theodore Exanthem](/npc/14146)

elseif(e.signal == 2) then


>**an interrogator says:** Vile beast! You are withholding information on two men guilty of terrible atrocities, not the least of which was causing the death of one of Qeynos' most respected and well known citizens, Cros Treewind! As an Interrogator I am authorized to use physical force if necessary.


**Signaled to:**  [\#Theodore Exanthem](/npc/14146)

elseif(e.signal == 3) then


>**an interrogator says:** [Take us to the location] of Markus Cachexia and Morley Murrain!


**Signaled to:**  [\#Theodore Exanthem](/npc/14146)

elseif(e.signal == 4) then


>**an interrogator says:** Take us to Markus Chachexia and Morley Murrain this instant or I'll turn you over to my friend here who appears to be much stronger than I am!


**Signaled to:**  [\#Theodore Exanthem](/npc/14146)

elseif(e.signal == 5) then


>*an interrogator smiles and says, 'Well, I'm getting tired. Why don't you hit him for a while. Maybe you will be more convincing then I have been.*


**Signaled to:**  [\#Theodore Exanthem](/npc/14146)

elseif(e.signal == 6) then


>**an interrogator says:** [Take us to the location] of Markus Cachexia and Morley Murrain!









elseif(e.signal == 8) then


>**an interrogator says:** Not so fast. If you want your freedom back, sign this confession immediately.

elseif(e.signal == 9) then


e.self:Say(string.format("You are on your own for now, %s. You know what to do 


**an interrogator despawns.**
end
