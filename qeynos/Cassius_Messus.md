# Cassius Messus


## Dialog

**You say:** `hail`



>**Cassius Messus says:** Hail!  What do think of [Lisera]?  She aint' much to look at, but soon she will be singing again.

**You say:** `Lisera`



>**Cassius Messus says:** Lisera is my lute.  She sounds horrible.  I need to get her tuned by a master tuner, but the League's Master Tuner is in the Plains of Karana for a while.  If only..  hey!!  You look like a fellow bard...  You [interested in the job]?

**You say:** `interested in the job`



if( **Faction is** >= Amiable) then 



>**Cassius Messus says:** Great!!  Here.  Take Lisera to Vhalen Nostrolo.  He is in the plains near the well, composing.  He must tune it for me.  Be very careful! Lisera is all I've got.  If you complete this task and return with good news. I shall be glad to pass along an extra songsheet for a tune entitled 'Hymn of Restoration.'



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_551.png" alt="" /> <a
                                href="/item/13114" data-url="13114" class="tooltip-link link">Lisera Lute</a>


elseif( **Faction is** == Indifferent) then



>**Cassius Messus says:** I will share this with you when you find some way to better serve the League of Antonican Bards.


else






>**Cassius Messus says:** Flee at once, fool! As a member of the League of Antonican Bards I have heard songs of your vile ways!


**You say:** `donate`



>**Cassius Messus says:** As a member of the League of Antonican Bards I am obligated to give all donations to this guild.









end



## Turn-Ins




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/18803" data-url="18803" class="tooltip-link link">Note To Cassius</a>) then


>**Cassius Messus says:** Thank you! I am in your debt. Here is the songsheet as I promised. I shall sing of you one day.


Your faction standing with [League of Antonican Bards](/faction/284) got better (<span class='text-success'>+10</span>)


Your faction standing with [Knights of Truth](/faction/281) got better (<span class='text-success'>+1</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+1</span>)


Your faction standing with [Ring of Scale](/faction/304) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Corrupt Qeynos Guards](/faction/230) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15007" data-url="15007" class="tooltip-link link">Song: Hymn of Restoration</a> (+100 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_647.png' width='14' height='14'/> 
 

**This NPC *should* return incorrect items given.**
