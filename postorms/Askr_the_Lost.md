# Askr the Lost



local stateTable = {}; 
local entries = 0;
local headTable = {}; 

local RESPONSES = {

"Askr looks up at you and when he does, you take note of the scraggly beard on his weather-worn face; the scent of ale permeates your senses and pushes you to look away slightly. In an apparent drunken stupor, Askr begins to speak with surprising clarity. 'Here to wash the windows and clean the flooring, are you? No? Well, you can't be much help then. And the likes of you obviously wouldn't be able to get rid of the massive problem we're having. Bah, says I. You can help me no more than any of these other vagrants. Leave me alone to my ale and my misery.'",

"Askr the Lost says 'Did you not hear me? If you're not here to help, then go elsewhere. I am so very busy... busy with ale, busy with misery... hah, that rhymed!'",

"Askr raises an eyebrow your way, as though he is becoming slightly irritated by your constant babble. He goes back to his drinking with hopes that you'll leave him alone long enough to drink in peace.",

"",

"The drunken stupor that Askr had been in earlier appears to vanish in an instant; a glimmer of hope now flashes in the depths of his eyes. 'This is the head of a giant... a storm giant from outside the caves.' Askr ponders what this revelation could mean. He mutters to himself, 'If it is possible that someone has indeed bested a giant here in the planes, then perhaps it is possible...' He looks back at you very sternly and asks, 'Tell me now and be truthful, was it you who severed the head of this giant from his body?'",

"Askr the Lost says 'Truly, I am amazed that someone of your caliber was able to do what I could not. I have been stuck in these desolate caves for so long, I had almost lost hope that I would ever find a way to get rid of those accursed giants. But you...  you have been able to best at least one of them. It is reasonable to suggest that if you are able to dispatch one, you may be able to dispatch others. I need to know for sure if you are as capable an individual as it appears you are. This is very important, so are you paying attention?'",

"Askr the Lost says 'This place was once beautiful and serene, with the great Karana's showers falling day and night soothing the lands and the creatures that inhabit it. Alas, there was an invasion of a superior force 

"Askr the Lost says 'To the south of Grenidor lay Srerendi, Shores of the Lost and the Srerendi storm giants. Born of the ocean and the cool air, they lay claim to the shores and the plains inland as their own. To the west of Grenidor lay Krendic, Sands of Chaos and the Krendic storm giants. They have skin that is thick as dirt and blend in well with their surroundings. To the north of the great mount lay Kelek\`Vor, the Forest of Tears and the Kelek\`Vor storm giants. They are born of the wood and take great pleasure in seeing it used to their own purposes.' [continue]",

"Askr the Lost says 'I must know if you are truly capable of defeating the storm giants that abound here. To do this, you must slay one of each of the three factions and return to me something specific to each tribe: from the Srerendi storm giants, return their shorn beard; from the Krendic storm giants, a piece of their rocky carcass; from the Kelek\`Vor storm giants, the crest from their warrior garments. These three items will ensure that you indeed do have the ability to defeat the foul denizens that have seized control of these lands. When you have acquired the three of these items, seal them in this bag and return them to me, so that I know that you are indeed capable of fulfilling a hero's destiny.'",

"",

"Askr looks over the remnants of the storm giants in his hands then looks up at you with a glimmer of hope in his eyes. 'Then it's true! You have the means to push back the scourge of giants... you must go forth to the Bastion of Thunder and finish there what you have started here. It is imperative that you clear the forces of giants from the Bastion so that order can be restored to the thunderous reaches beyond.'",

"Askr the Lost says 'To be honest, I cannot say that it is entirely possible, what with the ferocity of the giants and their reluctance to leave the lands they now inhabit. From what I do know, each of the Leaders of each tribe has one piece to allow entrance into the Bastion of Thunder. When two of these pieces are combined, they form an esoteric medallion that allows instant passage to the thunderous plains beyond. If you can find and seal two pieces of the medallion in this bag, I will be able to forge them into the medallion that will help you on your journey.'",

"",

"Askr the Lost says 'You have retrieved the pieces! You are well on your way to pushing forth on your quest to return balance to the plains of thunder. The most difficult part lies before you... deep in the heart of Mount Grenidor, there is a tempest that rages on eternally. It is there that you must present your medallion to the skies above to be transported to the citadel of thunderous might. Take the medallion and go forth, then deliver these storm giants to their creator!'",


"Askr the Lost says 'A hearty welcome back to you, friend. You have the means to push back the scourge of giants... you must go forth to the Bastion of Thunder and finish there what you have started here. It is imperative that you clear the forces of giants from the Bastion so that order can be restored to the thunderous reaches beyond.'",

"Askr the Lost says 'You have returned to me, but for what purpose? You already have the way to the Bastion of Thunder, so please make haste there and rid the Bastion of those horrid storm giants! Only then may the balance that once ruled over these thunderous lands return to its rightful place.'",

"Askr points drunkenly towards the exit of the cave. 'Have you not seen the foul denizens of destruction outside? Hrmph! Going everywhere they please, pillaging, plundering... I'm lucky to have survived this long. Bah, it doesn't matter, there's nothing that anyone can do to stop them, and that is why I'm still stuck here with my *hic* potions.'",

"Askr the Lost says 'I was afraid you would not return to finish the noble story you had started! But now I see my worries were ill placed. You have proven yourself a worthy adversary to even the mightiest of foes, but your journey does nothere! Seek me out that which I require and let your story continue on its way to greatness!'",

"Askr the Lost says 'You did well defeating one giant, but you have yet to prove that you are able to best giants from each tribe. I bid you luck friend, but you must go forth before I can speak with you more.'",

"Askr merely glances at you with a questioning look, as though he doesn't know what that is to be used for. Perhaps you should speak with him to clarify.",
};



## Timer(s)



if ( e.timer == "checkreset" ) then




local mob;


local elist = eq.get_entity_list();





for name, id in pairs(stateTable) do






mob = elist:GetClientByName(name);







if ( not mob or not mob.valid ) then




stateTable[name] = nil;




entries = entries - 1;









if ( entries == 0 ) then


eq.stop_timer(e.timer);



end

function GetState(name, karana)


local state = 1;



if ( not stateTable[name] ) then


stateTable[name] = state;





if ( entries == 0 ) then



**Set a timer** named *checkreset* for 15 seconds







entries = entries + 1;



return stateTable[name];
function SetState(name, state)

stateTable[name] = state;


## Dialog


local name = e.other:GetName();

local qglobals = eq.get_qglobals(e.other);

local karana = tonumber(qglobals.karana or 0);

if ( qglobals.zebuxoruk ) then


karana = 4;

local state = GetState(name, karana);


if ( karana == 0 ) then




**You say:** `hail`







if ( headTable[name] ) then




e.other:Message(0, RESPONSES[18]);




state = 8;




SetState(name, state);






if ( state <= 3 ) then




e.other:Message(0, RESPONSES[state]);




SetState(name, state + 1);








**You say:** `massive problem`




e.other:Message(0, RESPONSES[17]);






**You say:** `it was me`




if ( state == 6 ) then




e.other:Message(0, RESPONSES[state]);




SetState(name, state + 1);







**You say:** `paying attention`




if ( state == 7 ) then




e.other:Message(0, RESPONSES[state]);




SetState(name, state + 1);








**You say:** `yes`




if ( state == 6 or state == 7 ) then




e.other:Message(0, RESPONSES[state]);




SetState(name, state + 1);







**You say:** `continue`




if ( state == 8 or state == 9 ) then




e.other:Message(0, RESPONSES[state]);




if ( state == 9 ) then





 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_691.png" alt="" /> <a
                                href="/item/17192" data-url="17192" class="tooltip-link link">Askr's Bag of Verity</a>







SetState(name, state + 1);



elseif ( state > 9 ) then




e.other:Message(0, RESPONSES[19]);







elseif ( karana == 1 ) then




**You say:** `hail`






e.other:Message(0, RESPONSES[15]);






**You say:** `bastion of thunder`




e.other:Message(0, RESPONSES[12]);



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_691.png" alt="" /> <a
                                href="/item/17192" data-url="17192" class="tooltip-link link">Askr's Bag of Verity</a>



SetState(name, state + 1);




elseif ( karana >= 2 ) then




**You say:** `hail`






e.other:Message(0, RESPONSES[16]);







## Turn-Ins

local karana = tonumber(eq.get_qglobals(e.other).karana or 0);





if (  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1260.png" alt="" /> <a
                                href="/item/28749" data-url="28749" class="tooltip-link link">Storm Giant Head</a>  


or  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1260.png" alt="" /> <a
                                href="/item/28781" data-url="28781" class="tooltip-link link">Storm Giant Head</a>  


or  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1260.png" alt="" /> <a
                                href="/item/28782" data-url="28782" class="tooltip-link link">Storm Giant Head</a>  

) then




e.other:Message(0, RESPONSES[5]);


 &#127873; **You receive:** 0 

 


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1260.png" alt="" /> <a
                                href="/item/11486" data-url="11486" class="tooltip-link link">Storm Giant Head</a>


SetState(e.other:GetName(), 6);


headTable[e.other:GetName()] = true;



if (  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_690.png" alt="" /> <a
                                href="/item/11487" data-url="11487" class="tooltip-link link">Askr's Sealed Bag of Verity</a>  ) then 




if ( karana == 0 ) then





e.other:Message(0, RESPONSES[11]);



 &#127873; **You receive:** 0 

 



eq.set_global("karana", "1", 5, "F");



**Message:** <span class="text-warning">*You have received a character flag!*</span>



SetState(e.other:GetName(), 12);




if (  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1144.png" alt="" /> <a
                                href="/item/11488" data-url="11488" class="tooltip-link link">Esoteric Meld</a>  ) then 




if ( karana == 1 ) then





 &#127873; **You receive:** 0 

 



eq.set_global("karana", "2", 5, "F");



**Message:** <span class="text-warning">*The mystical medallion given to you by Askr settles around your neck and then disappears into nothingness. There is no call for alarm, for the medallion is now a part of your soul.*</span>



e.other:Message(0, RESPONSES[14]);



**Message:** <span class="text-warning">*You have received a character flag!*</span>


else



e.other:Message(0, RESPONSES[20]);



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1144.png" alt="" /> <a
                                href="/item/11488" data-url="11488" class="tooltip-link link">Esoteric Meld</a>




**This NPC *should* return incorrect items given.**
;