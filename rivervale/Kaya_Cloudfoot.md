# Kaya Cloudfoot
## Dialog

if(eq.get_current_expansion() >= 4.0) then


**You say:** `hail`




>**Kaya Cloudfoot says:** A pleasure to make your acquaintance Soandso. I am Kaya Cloudfoot, first Paladin of the Storm Reapers. I traveled long ago when I was just a wee sprout to the city of Qeynos far to the west. It was there I grew under the tutelage of the Knights of Thunder, a noble order of paladins loyal to Karana, the Storm Lord. I have returned now to Rivervale to teach interested young halflings the ways of a Knight of the Storm Reapers so that we may defend Karanas people and lands from the [evil forces] that would see it destroyed.


**You say:** `evil forces`




>**Kaya Cloudfoot says:** There are many problems and creatures that trouble Karanas people through out Norrath and threaten our otherwise peaceful ways of life. Our common folk here in Rivervale are troubled by the wicked Teir\`Dal, the Death Fist Orcs, and the Goblins of Clan Runnyeye and Pickclaw. It is the calling and duty of a Knight of the Storm Reapers to defend the common folk from these enemies of Rivervale. Are you willing to [defend the commoners]?


**You say:** `commoners`




>**Kaya Cloudfoot says:** You have made an honorable decision, Soandso. First you will need to be outfitted in a suit of armor to protect you from the weapons of our foes. Seek Jimji Bottletoe here in Rivervale and give him this letter. Jimji will instruct you further on acquiring a suit of armor worthy of a new Knight of the Storm Reapers. When you have been outfitted in your Bravefoot Armor return to me and I shall prepare you for your [next task].



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_868.png" alt="" /> <a
                                href="/item/19628" data-url="19628" class="tooltip-link link">Letter to Jimji Bottletoe</a>


**You say:** `next task`




>**Kaya Cloudfoot says:** The Teir'Dal, or Dark Elves that reside in the underground city of Neriak to the east beyond the Commonlands have long been a bane to us Storm Reapers. Many of our Druids have fallen attempting to hold back the tide of hate and destruction that has taken hold on the Nektulos Forest and threatens the surrounding lands. It was also the Teir\`Dals patron God, Innorruuk, who caused the [Curse of Bloody Kithicor]. Are you ready to [face the Teir'Dal] and bloody your hands for the protection of your Shire and our commoners humble way of life?


**You say:** `curse of bloody kithicor`




>**Kaya Cloudfoot says:** There was a great war that was fought not long ago between the Teir'Dal, and their evil minions, and the armies of Felwithe, Qeynos, Freeport, and Kaladim. In the Kithicor Woods the Daughter of Innoruuk, Lanys T'Vyl, and her minions fought against the chosen of Tunare, Firiona Vie, and her most loyal allies. The evil God of Hate, Innoruuk, intervened every living creature in the Kithicor Woods instantly fell dead as a great rift to the Plane of Hate appeared in the sky. Since that time, when night falls on the Kithicor Woods blood seeps from the trees and ground and the hateful dead hunt any living being who dares to trespass in the woods that ended their lives.


**You say:** `face the teir`




>**Kaya Cloudfoot says:** Some days ago one of our Storm Reapers, a ranger by the name of Botim Bonker, ventured into the Kithicor Forest at daybreak on a routine patrol and never returned. That night his bloodied tunic was found hanging on a fence post of Tagglefoots Farm. The blood was dried and many hours old. We believe that he was slain during the day and that deduction coupled with the fact the undead of Kithicor do not leave the woods nor possess the intelligence or means to sneak into Rivervale and leave the tunic where it would surely be found by fellow Storm Reapers led us to believe they were not responsible. We believe it was the work of the Teir'Dal. Search the Kithicor Woods by daylight and punish the Teir'Dal responsible. Return with the villains severed hands as proof of his death.

end

## Turn-Ins



local expansion_flag = eq.get_current_expansion();

if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_683.png" alt="" /> <a
                                href="/item/18431" data-url="18431" class="tooltip-link link">Halfling Paladin Note</a>) then 


>**Kaya Cloudfoot says:** Karana smiles upon you young Soandso! Take this tunic to keep you warm through the storms you must face. There is evil encroaching upon the lands of Karana's faithful. The wicked minions of Bertoxxulous and the Teir'Dal children of Hate corrupt the lands to the west and east, and the Deathfist Clan of Orcs are waging war on this region while destoying the wilderness for lumber and stone. It is Karana's will that we defend our lands and way of life from these evil threats.


Your faction standing with [Storm Reapers](/faction/355) got better (<span class='text-success'>+100</span>)


Your faction standing with [Mayor Gubbin](/faction/286) got better (<span class='text-success'>+10</span>)


Your faction standing with [Merchants of Rivervale](/faction/292) got better (<span class='text-success'>+15</span>)


Your faction standing with [Unkempt Druids](/faction/324) got worse (<span class='text-danger'>-15</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_678.png" alt="" /> <a
                                href="/item/13541" data-url="13541" class="tooltip-link link">Jumjum Sack Tunic*</a> (+100 exp)

 

elseif(expansion_flag >= 4.0 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_918.png" alt="" /> <a
                                href="/item/19688" data-url="19688" class="tooltip-link link">Severed TeirDal Hands</a>) then


>**Kaya Cloudfoot says:** Take this Dull Bravefoot Short Sword to the forge at Tagglefoots farm and sharpen it with a sharpening stone. It may take several attempts if you are unfamiliar with the process. Once that is done present the blade and a large snake skin to Bodbin Gimple and he will put the finishing touches on the sword.


Your faction standing with [Storm Reapers](/faction/355) got better (<span class='text-success'>+10</span>)


Your faction standing with [Mayor Gubbin](/faction/286) got better (<span class='text-success'>+1</span>)


Your faction standing with [Merchants of Rivervale](/faction/292) got better (<span class='text-success'>+1</span>)


Your faction standing with [Unkempt Druids](/faction/324) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_575.png" alt="" /> <a
                                href="/item/19625" data-url="19625" class="tooltip-link link">Dull Bravefoot Short Sword</a> (+10 exp)

 

**This NPC *should* return incorrect items given.**


