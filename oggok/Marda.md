# Marda



[Marda](/npc/49041) is a level 61 Ogre GM Shaman that spawns in [Oggok](/zone/49).



## Dialog

**You say:** `hail`



>**Marda says:** Welcome to intelligence, young Soandso! Did you think all ogres were inept? Ha!! I hope you show the glimmer. We shamans need more within our ranks. Our race needs to evolve!! So, are you one of the smart ogres or have I spoken too many syllables?

**You say:** `smart ogre`



if **Faction** >= Indifferent then




>**Marda says:** Well, I suppose your intelligence shall grow. You will have to do. I have a mission for you. First, go and speak with Grevak of the Greenblood Knights. He will have a job for you. After you have performed some manner of service and advanced at least 5 ranks, return to me and ask me about my secret mission.


else



>**Marda says:** Knights! Come at once. There is a foe of the Greenbloods to deal with.




**You say:** `syllable`



>**Marda says:** As I thought. Perhaps you would fare better speaking with the Crakneks.

**You say:** `secret mission`



if **Faction** >= Amiable then




>**Marda says:** I have heard of your advancements. You are a fine addition to Oggok. I require your skill in handling a delicate matter. I want you to run out to the Bouncer's keep near the entrance to Oggok. There, you shall find a froglok named Glib. He will pose no threat to you. He has come on business and I have promised him protection. Tell him the Greenblood shaman sent you. He shall fill you in. Go at once.



**Spawn NPC:**  [Emissary Glib](/npc/49127) at (**y:** -205.3, **x:** 383)


elseif **Faction** >= Indifferent then




>**Marda says:** There is much you must do to prove your loyalty to the cause of the Greenbloods.


else



>**Marda says:** Knights! Come at once. There is a foe of the Greenbloods to deal with.



end



## Turn-Ins





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18884" data-url="18884" class="tooltip-link link">Tattered Note</a> or  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/18886" data-url="18886" class="tooltip-link link">A Sealed Letter</a>) then


>**Marda says:** I see you finally decided to return. Hmmm. What is this? Those little hoppers have done well. What!! So the troll scum have been aiding our foes, the lizards!! The lizard mystics are trained by this troll shaman called Zimbittle. Find him!! Kill him. Bring me his shaman pouch!! Now!!


Your faction standing with [Shamen of War](/faction/394) got better (<span class='text-success'>+10</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15270" data-url="15270" class="tooltip-link link">Spell: Drowsy</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15226" data-url="15226" class="tooltip-link link">Spell: Endure Disease</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15279" data-url="15279" class="tooltip-link link">Spell: Spirit of Bear</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15211" data-url="15211" class="tooltip-link link">Spell: Summon Drink</a>) (+50 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/18886" data-url="18886" class="tooltip-link link">A Sealed Letter</a>) then


>**Marda says:** I see you finally decided to return. Hmmm. What is this? This troll called Zimbittle. Find her! Kill her. Bring me proof she dead!

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18885" data-url="18885" class="tooltip-link link">A Tattered Cloth Note</a>) then


>**Marda says:** What is this? More information? There seems to be a larger plan in the making. B'Dynn sounds like a Dark Elf name. I do no like the sound of this.  You must go quickly to North Ro.  Find this Dark Elf.  Find out what he knows.  any way you can.


Your faction standing with [Shamen of War](/faction/394) got better (<span class='text-success'>+20</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15270" data-url="15270" class="tooltip-link link">Spell: Drowsy</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15226" data-url="15226" class="tooltip-link link">Spell: Endure Disease</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15279" data-url="15279" class="tooltip-link link">Spell: Spirit of Bear</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15211" data-url="15211" class="tooltip-link link">Spell: Summon Drink</a>) (+100 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_539.png" alt="" /> <a
                                href="/item/17929" data-url="17929" class="tooltip-link link">Zimbittles Pouch</a>) then


>**Marda says:** Ahhh!! Good work. You are a bright one. Now let us see if you can master this spell. Learn it well and may it bring you much glory.


Your faction standing with [Shamen of War](/faction/394) got better (<span class='text-success'>+25</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15270" data-url="15270" class="tooltip-link link">Spell: Drowsy</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15226" data-url="15226" class="tooltip-link link">Spell: Endure Disease</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15279" data-url="15279" class="tooltip-link link">Spell: Spirit of Bear</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15211" data-url="15211" class="tooltip-link link">Spell: Summon Drink</a>) (+150 exp)

 

**This NPC *should* return incorrect items given.**
