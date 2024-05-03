# Rathmana Allin




## Dialog

**You say:** `hail`



>**Rathmana Allin says:** Company?! Way out here in the desert of Ro? This is a pleasant surprise! Won't you stay for a while? I am sure the desert has dried your throat. I have supplies if necessary. At a price, of course. Are you [traveling] or are you here on [business]?

**You say:** `business`



>**Rathmana Allin says:** Of course. You do not look like a traveling merchant or a lost adventurer. Someone has sent you to Rathmana. Well then, let's not waste time. Give me the item, or items, and my fee of twenty gold coins. It must be gold. I have no use for any other metals.

**You say:** `traveling`



>**Rathmana Allin says:** Oh, wonderful! Then you must need water and rations for your long journey. Be sure to approach any camp you may find in Ro with caution. There are many bandits in the desert. If it were not for Ortallius, they would have gutted me and thieved all my merchandise by now. If you have any use of magic then I believe I may have an [offer] for you.

**You say:** `offer`



>**Rathmana Allin says:** My offer to you is this, you give me thirty gold and I allow you to reach into my scroll bag and retrieve one scroll and only one. It may be the spell of a wizard or maybe not. The school of magic will not be known beforehand. The only knowledge you will have is that Rathmana will not exchange the spell for another. You get what you take. Do you wish to reach into my bag? Then give Rathmana his thirty gold coins.

**You say:** `solusek`



>**Rathmana Allin says:** Solusek Ro is the Burning Prince.  It is He who watches over this desert and chooses who lives and who dies.  It was He who saved Rathmana from the heretics and it was He who saved Ortallius from the sands.

**You say:** `heretic`



>**Rathmana Allin says:** As you can see, I am an Erudite, and I was raised in the great schools of magic in Erud.  In my youth, I learned of a forbidden art. That art was necromancy. I secretly studied this art and eventually happened upon others who practiced the art of darkness.  These magic users, or rather, necromancers,  are called heretics.  I learned their ways, but before I completely converted to their dark ways, I attempted to flee their circle.  They caught me and through arcane means transported me to this desert.  I would have died if it were not for a vision of Solusek Ro.  He appeared to me and created a hole in Norrath. It was from this hole I drank and lived. Since then I call the desert of Ro home, and live my humble life in the name of the Burning Prince, Solusek Ro.

**You say:** `ortallius`



>**Rathmana Allin says:** Pay no mind to him.  He is my friend.  I found him as a child, dying under the blazing sun of Ro.  He was curled up next to his dead mother's body.  I raised him since then.  He is quite the opposite of what you would expect of an orc.  He is a good person.  To me, anyway.
end



## Turn-Ins



local text = "I believe there is more yet.";



if( **You turn in:** gold = 30) then


>**Rathmana Allin says:** Good luck, my friend. May Solusek Ro guide your hand.


Your faction standing with [Temple of Solusek Ro](/faction/415) got better (<span class='text-success'>+5</span>)


Your faction standing with [Shadowed Men](/faction/416) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15022" data-url="15022" class="tooltip-link link">Spell: Force Shock</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15035" data-url="15035" class="tooltip-link link">Spell: Bind Affinity</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15038" data-url="15038" class="tooltip-link link">Spell: Lightning Bolt</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15039" data-url="15039" class="tooltip-link link">Spell: Quickness</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15303" data-url="15303" class="tooltip-link link">Spell: Whirl till you hurl</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15328" data-url="15328" class="tooltip-link link">Spell: Column of Fire</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15355" data-url="15355" class="tooltip-link link">Spell: Engulfing Darkness</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15364" data-url="15364" class="tooltip-link link">Spell: Banshee Aura</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15445" data-url="15445" class="tooltip-link link">Spell: Lifedraw</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15300" data-url="15300" class="tooltip-link link">Spell: Charm</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_863.png" alt="" /> <a
                                href="/item/13360" data-url="13360" class="tooltip-link link">Rotted Illegible Scroll</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_863.png" alt="" /> <a
                                href="/item/13360" data-url="13360" class="tooltip-link link">Rotted Illegible Scroll</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_863.png" alt="" /> <a
                                href="/item/13360" data-url="13360" class="tooltip-link link">Rotted Illegible Scroll</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_863.png" alt="" /> <a
                                href="/item/13360" data-url="13360" class="tooltip-link link">Rotted Illegible Scroll</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_863.png" alt="" /> <a
                                href="/item/13360" data-url="13360" class="tooltip-link link">Rotted Illegible Scroll</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_863.png" alt="" /> <a
                                href="/item/13360" data-url="13360" class="tooltip-link link">Rotted Illegible Scroll</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_863.png" alt="" /> <a
                                href="/item/13360" data-url="13360" class="tooltip-link link">Rotted Illegible Scroll</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_863.png" alt="" /> <a
                                href="/item/13360" data-url="13360" class="tooltip-link link">Rotted Illegible Scroll</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_863.png" alt="" /> <a
                                href="/item/13360" data-url="13360" class="tooltip-link link">Rotted Illegible Scroll</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_863.png" alt="" /> <a
                                href="/item/13360" data-url="13360" class="tooltip-link link">Rotted Illegible Scroll</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_863.png" alt="" /> <a
                                href="/item/13360" data-url="13360" class="tooltip-link link">Rotted Illegible Scroll</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_863.png" alt="" /> <a
                                href="/item/13360" data-url="13360" class="tooltip-link link">Rotted Illegible Scroll</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_863.png" alt="" /> <a
                                href="/item/13360" data-url="13360" class="tooltip-link link">Rotted Illegible Scroll</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_863.png" alt="" /> <a
                                href="/item/13360" data-url="13360" class="tooltip-link link">Rotted Illegible Scroll</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_863.png" alt="" /> <a
                                href="/item/13360" data-url="13360" class="tooltip-link link">Rotted Illegible Scroll</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_863.png" alt="" /> <a
                                href="/item/13360" data-url="13360" class="tooltip-link link">Rotted Illegible Scroll</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_863.png" alt="" /> <a
                                href="/item/13360" data-url="13360" class="tooltip-link link">Rotted Illegible Scroll</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_863.png" alt="" /> <a
                                href="/item/13360" data-url="13360" class="tooltip-link link">Rotted Illegible Scroll</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_863.png" alt="" /> <a
                                href="/item/13360" data-url="13360" class="tooltip-link link">Rotted Illegible Scroll</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_863.png" alt="" /> <a
                                href="/item/13360" data-url="13360" class="tooltip-link link">Rotted Illegible Scroll</a>) (+100 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-20 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-100 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-100 <img src='/static/icons/item_647.png' width='14' height='14'/> 






elseif ( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/18808" data-url="18808" class="tooltip-link link">Bayle List I</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/18809" data-url="18809" class="tooltip-link link">Bayle List II</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/18810" data-url="18810" class="tooltip-link link">Bayle List III</a>, gold = 20) then 


>**Rathmana Allin says:** A simple code. Why do you even bother Rathmana with such child's play? Here is your translation. That was the easiest twenty gold coins I ever earned.


Your faction standing with [Temple of Solusek Ro](/faction/415) got better (<span class='text-success'>+5</span>)


Your faction standing with [Shadowed Men](/faction/416) got worse (<span class='text-danger'>-1</span>)




 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/18825" data-url="18825" class="tooltip-link link">Bayle List</a> 

 

**This NPC *should* return incorrect items given.**
