# Fixxin Followig

## On NPC Spawn

**Set a timer** named *follow* for 1 seconds
## Timer(s)

if(e.timer == "follow") then


local mobtypeID =  eq.get_entity_list():GetMobByNpcTypeID(13065);





if(mobtypeID) then



local follow_mob = mobtypeID:GetID();



eq.follow(follow_mob,35);



**Stop timer** named *follow*

end


## Dialog

**You say:** `hail`



>**Fixxin Followig says:** Hail, Soandso! Fixxin is my moniker. Nice ta see ya. I am a member of the [Fangbreakers] and we are hunting [werewolves]. We run into lots of other [creepies] out here as well.

**You say:** `fangbreaker`



>**Fixxin Followig says:** Fangbreakers? You have not heard of us? We are the best [werewolf] hunters there are!

**You say:** `werewolves`



>**Fixxin Followig says:** Those blasted fiends hide among normal folk during the day, but at night their bloodlust is set free on an innocent populace. Some claim there is a cure for their condition but the only one we know of is an [enchanted blade] through the bellies of the beasts.

**You say:** `enchanted blade`



>**Fixxin Followig says:** Interested in an enchanted blade? You wouldn't be planning on hunting the moon beasts without a strong, well-oiled party to back you up, now, would you? Well, in any case, I'll gladly lend you a copy of my book, Fixxin Followigs Silvery Blades, if you will fetch me a bar of silver. My supply is running low and our weapons are in need of repair after the deaths of so many lycanthropes.

**You say:** `creepies`



>**Fixxin Followig says:** Besides the occasional werewolf, we also tend to run across many griffons and hill giants out this way. Those giants can be bruisers but against a trained team such as we, they don't stand a chance. Especially with my enchantments protecting us.

**You say:** `akanon`



>**Fixxin Followig says:** I have never been to Ak'Anon.  My parents were traveling mages.  I hooked up with Nul and the rest of the crew in Freeport several years back.


end

## Turn-Ins




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1092.png" alt="" /> <a
                                href="/item/16500" data-url="16500" class="tooltip-link link">Silver Bar</a>) then


>*Fixxin Followig thanks Soandso heartily. 'Here is the book as promised. I wish you luck with your enchanted weapons. May they slay many lycanthropes before they go dull.'*


Your faction standing with [Karana Residents](/faction/345) got better (<span class='text-success'>+1</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+1</span>)


Your faction standing with [Priests of Life](/faction/341) got better (<span class='text-success'>+1</span>)


Your faction standing with [Knights of Thunder](/faction/280) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18178" data-url="18178" class="tooltip-link link">Fixxin Followigs Silvery Blades</a> (+500 exp)

 

**This NPC *should* return incorrect items given.**



