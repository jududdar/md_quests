# Abe the Abandoned
local counting;



## On NPC Spawn

**Set a timer** named *letbegin* for 60 seconds

counting = 0;


## Dialog

**You say:** `hail`



>*Abe the Abandoned turns his head slowly toward you but his eyes never come into focus. You can't tell if he's looking at you, behind you, or right in front of his own face. Then, suddenly, he shouts at the top of his lungs, 'HOOOOKAAAHEEEEYYYY! I AM [ABE]!*

**You say:** `Abe`



>**Abe the Abandoned says:** Nothing is hidden. All is discernible if you only know where to look and you have the right [eyes]. Don't be angry with me if you can't get your eyes right to see what you're looking for. I'd lend you mine but I don't wear the same size.

**You say:** `eyes`



>*Abe the Abandoned begins to draw a picture in the mud with his finger although it doesn't seem to make any sense at all. He points to his picture and nods approvingly at you, saying, 'You see? The curtains fell and it was naught but a dream upon a landscape that we thought we knew. The dream of the [Combine] fulfilled when we finally trimmed our fingernails and looked into the mud. And now we are abandoned, in a world that none can see, no one has the eyes.*

**You say:** `combine`



>*Abe the Abandoned shakes his head in amusement and says, 'Heheheh, yeah, you'd think so, wouldn't you? But I guess not.*

**You say:** `broken arrow`



>*Abe the Abandoned 's eyes suddenly come into focus, looking deep into your own and says, 'There was a time when we cared for the world and trod with the spirits along the paths of the cosmos. We built many great things and worked to preserve what was. I came here to wait for an answer when we began to die off. We could not figure why this was and I was chosen to come here and commune with our friends. We carved an arrow, and everyone who was left shaved a sliver of wood from it. We let it drop to hallowed ground and our highest shaman stepped on it, breaking it. I've been waiting here for so long. So, so long, to give it to the spirits, and thank them.*

**You say:** `give them the arrow`



>*Abe the Abandoned removes a quiver slung across his shoulder and solemnly hands it to you without a word.*


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1039.png" alt="" /> <a
                                href="/item/1680" data-url="1680" class="tooltip-link link">A Broken Arrow</a>
end



## Timer(s)

if(e.timer == "letbegin") then


counting = counting + 1;



if (counting == 1) then


>**Abe the Abandoned says:** Shaman? My time will soon be at hand and I fear I will never see our friends again. But the arrow must be given, our holy broken arrow. Shaman, will you bear our obligation and [give them the arrow]? You will know who to give it to when it is time.

elseif (counting == 2) then


>*Abe the Abandoned suddenly gasps and says, 'I have found it! I know the answer! Come with me and I will tell you. Eyes are everywhere and this knowledeg is not for everyone. Finally my centuries of waiting are over hahahaha! Follow me Shaman!*  


eq.start(34);

elseif (counting == 3) then


**Spawn NPC:**  [a greater spirit](/npc/98052) at (**y:** -1587, **x:** 4175)


**Abe the Abandoned despawns.**


**Stop timer** named *letbegin*
end

