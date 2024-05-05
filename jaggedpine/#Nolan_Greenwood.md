# Nolan Greenwood



[Nolan Greenwood](/npc/181085) is a level 61 Human GM Druid that spawns in [Jaggedpine Forest](/zone/181).






## Dialog

**You say:** `hail`



if **Faction** >= Warmly then



**You say:** `hail`





>*Nolan Greenwood gives a gentle nod to Soandso. 'Greetings. I am Nolan Greenwood, warder of the Jaggedpine and retainer of our [ancient ways]. The recent introduction of [outsiders] whose faith and loyalties mimic our own toward The Rainkeeper has led to the rebirth of a long lost excitement and use for my talents, thus my presence here today. Usually, I would not be so easily found for when presented with the choice, for I prefer the sanctuary of the open forest to the confining walls of my room here at Fort Jaggedpine.'*



**You say:** `ancient way`





e.self:Say("As with any culture, my friend, there are countless established ways of life, worship, law, and order. It would be impossible for me to explain all of our ancient ways in a single conversation 



**You say:** `accept them`





>*Nolan Greenwood raises a brow and gives a gentle, warm smile to Soandso's declaration. 'I see, and am very pleased to know that your interest has grown and your heart is opened to know the path of The Rainkeeper. As I retain the laws and order of nature that we of the Jaggedpine have sworn ourselves to, I will be more than willing to give you what words I can to guide you toward true discovery of what it means to be of The Rainkeeper's service and pledge. The rest shall be taught through your own experience in these [trials].'*



**You say:** `trials`





>**Nolan Greenwood says:** To show your devotion to the natural world and strengthen your abilities to protect it, you must engage in a symbiotic relationship with nature. As you give your devotion and one day your life to the natural world, it will equally provide the [tools] that will aid you to execute the duties and protection you have pledged to uphold.



**You say:** `tools`





e.self:Say("Sustenance, shelter, and the necessities that we must have to survive are all provided by the world that we must protect. The wilderness will also lend its spiritual force to you, and it is the fullest potential of that spiritual force that I can see you and many other druids have yet to truly harness. Do not think that we reave these things from nature 



**You say:** `ask of her`





>**Nolan Greenwood says:** These questions are not of the vocal expression, my friend. To request nature's aid, you must go in-search of that aid. In that search, you will provide unto her nothing less than a service equal to what it is you seek. My beloved daughter, Cheyloh, and I shall [guide you] through this quest.



**You say:** `guide me`





e.self:Say("I will give you the guidance of words and my knowledge of the details pertaining to your tasks. My experience and talents in the ways of making proper and the most efficient use of that which nature will grant you in gratitude of your service to her shall be at your disposal as necessary and appropriate. The first of your tasks will be to acquire and return to me two items 



**You say:** `silver griffon`





>**Nolan Greenwood says:** There is a beast known as the Silver Griffon whom lurks in the darkest of shadows cast by Luclin's light. Although this creature was born of those that are natural, the Silver Griffon himself is not. Once a great and powerful creature of the Karana Plains, the beast known as the Silver Griffon was killed and its spirit corrupted by the priests of The Plaguebringer when their scourge was brought upon those plains not too long past. Put this creature to rest and from its ethereal wings, bring me its silver feathers.



**You say:** `jade studded`





e.self:Say("As the Qeynos faithful of The Rainkeeper have come to us, we have sent some of our most adept brothers and sisters to them as an act of good faith in hope that our ways would be exchanged. One such adept is Jhaya Wyndrunner. She, like myself, is a keeper of our ways 




elseif **Faction** >= Indifferent then



e.self:Emote("gives a gentle smile and slight nod of his head in greetings, 'Hello, Soandso. I am Nolan Greenwood, elder druid and resident of the Jaggedpine. Do forgive me for cutting this meeting short and please do not take offense to it, but there is much to be done and you have yet to prove yourself as trustworthy of our cause. Again, my most sincere apologies, but please do not be discouraged from seeking to prove yourself among us 


else



**Nolan Greenwood says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!

end



## Turn-Ins


 



if **Faction** >= Warmly and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_632.png" alt="" /> <a
                                href="/item/8761" data-url="8761" class="tooltip-link link">Jade Studded Rawhide Tunic</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_908.png" alt="" /> <a
                                href="/item/8760" data-url="8760" class="tooltip-link link">Silver Griffon Feathers</a>) then


>**Nolan Greenwood says:** You have done well, Soandso. I am impressed and most pleased to know that you are adapting and accepting our ways so easily. Take this and may it protect you in these troubling times.


Your faction standing with [Residents of Jaggedpine](/faction/1597) got better (<span class='text-success'>+10</span>)


Your faction standing with [Jaggedpine Treefolk](/faction/272) got better (<span class='text-success'>+5</span>)


Your faction standing with [Protectors of Pine](/faction/302) got better (<span class='text-success'>+5</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+2</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_632.png" alt="" /> <a
                                href="/item/8400" data-url="8400" class="tooltip-link link">Tunic of the Pine</a> (+1000 exp)

 

**This NPC *should* return incorrect items given.**
