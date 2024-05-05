# Gleed Dragonhunter



[Gleed Dragonhunter](/npc/113373) is a level 53 Giant Ranger that spawns in [Kael Drakkel](/zone/113).





## Dialog

if( **Faction is** > Apprehensive) then


**You say:** `hail`




>*Gleed Dragonhunter sighs as he looks down at you. 'I grow tired of this city. I so long for the tundra and lands of the wild.'*


**You say:** `tundra`




>**Gleed Dragonhunter says:** I enjoy training these animals, don't get me wrong, but the open wastes, where the great animals and dragons roam free are what I crave. Before I came to serve King Tormax, I wandered those wastes, hunting young dragons and elder wurms. The whistle of an arrow from my bow was like sweet music - each slash of my sword a sweet song.


**You say:** `young dragon`




>**Gleed Dragonhunter says:** Yes, I hunted true dragons. The younger ones, at least. With my bow I could shoot them from such a distance they would never see what was coming.


**You say:** `bow`




>*Gleed Dragonhunter unslings an intricately carved bow from his back and shows it to you. 'I crafted this bow myself. It was to be a great slayer of wurms and dragons and it was, for a time. Now it goes to waste in the city, far from the beasts I long to slay. Far from the hunt and the excitement.'*


**You say:** `waste`




>**Gleed Dragonhunter says:** It is such a shame, this bow deserves to be used. If only there were someone who would use it to hunt the beasts - someone to slay them and skin them like they should be.


**You say:** `beast`




>**Gleed Dragonhunter says:** You will, little one? One such as yourself is a hunter? I did not know your kind had any skill in such things. In fact, I do not believe your kind could hunt a wurm, not without my wonderful bow. I will not simply hand it to a foolish " .. e.other:Race() .. ". Hunt down some big game before you bother talking to me again. Perhaps if you bring me the tail of the elusive Vluudeen.


elseif( **Faction is** > Dubious) then


>**Gleed Dragonhunter says:** You need to prove your dedication to our cause before I can discuss such matters with you.

else


**Gleed Dragonhunter says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.
end



## Turn-Ins





if( **Faction is** > Apprehensive and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_596.png" alt="" /> <a
                                href="/item/25137" data-url="25137" class="tooltip-link link">Vluudeens Tail</a>) then


>**Gleed Dragonhunter says:** My, you do have a hunters spirit! If you could track down Vluudeen and slay him without the aid of my bow, you must be worthy. Take the bow, huntsman. Use it to slay others of Vluudeen's kind.


Your faction standing with [Kromrif](/faction/419) got better (<span class='text-success'>+35</span>)


Your faction standing with [Kromzek](/faction/448) got better (<span class='text-success'>+8</span>)


Your faction standing with [Coldain](/faction/406) got worse (<span class='text-danger'>-17</span>)


Your faction standing with [Claws of Veeshan](/faction/430) got worse (<span class='text-danger'>-3</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_597.png" alt="" /> <a
                                href="/item/25033" data-url="25033" class="tooltip-link link">Bow of the Huntsman</a> (+35000 exp)

 

**This NPC *should* return incorrect items given.**
