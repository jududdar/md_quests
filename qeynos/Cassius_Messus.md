# Cassius Messus
## Dialog

**You say:** `hail`



>**Cassius Messus says:** Hail!  What do think of [Lisera]?  She aint' much to look at, but soon she will be singing again.

**You say:** `Lisera`



>**Cassius Messus says:** Lisera is my lute.  She sounds horrible.  I need to get her tuned by a master tuner, but the League's Master Tuner is in the Plains of Karana for a while.  If only..  hey!!  You look like a fellow bard...  You [interested in the job]?

**You say:** `interested in the job`



if( **Faction is** >= Amiable) then 



>**Cassius Messus says:** Great!!  Here.  Take Lisera to Vhalen Nostrolo.  He is in the plains near the well, composing.  He must tune it for me.  Be very careful! Lisera is all I've got.  If you complete this task and return with good news. I shall be glad to pass along an extra songsheet for a tune entitled 'Hymn of Restoration.'



**You receive:**  [Lisera Lute](/item/13114)


elseif( **Faction is** == Indifferent) then



>**Cassius Messus says:** I will share this with you when you find some way to better serve the League of Antonican Bards.


else






>**Cassius Messus says:** Flee at once, fool! As a member of the League of Antonican Bards I have heard songs of your vile ways!


**You say:** `donate`



>**Cassius Messus says:** As a member of the League of Antonican Bards I am obligated to give all donations to this guild.









end

## Turn-Ins




if **You turn in:** [Note To Cassius](/item/18803)


>**Cassius Messus says:** Thank you! I am in your debt. Here is the songsheet as I promised. I shall sing of you one day.


* __Faction:__ [League of Antonican Bards](/faction/284) (10)


* __Faction:__ [Knights of Truth](/faction/281) (1)


* __Faction:__ [Guards of Qeynos](/faction/262) (1)


* __Faction:__ [Ring of Scale](/faction/304) (-1)


* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (-1)


 **You receive:** None 
 

item_lib.return_items(e.self, e.other, e.trade, e.text)