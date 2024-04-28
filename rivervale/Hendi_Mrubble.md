# Hendi Mrubble
## Dialog

**You say:** `Hail`



>**Hendi Mrubble says:** Why, hello there!!  Welcome to the Church of Mischief.  I am Hendi Mrubble. The 'R' is silent.  I am the resident healer of the church, so if you are in [need of healing], or want me to [cure poison] or [cure disease], let me know.  If you've got a touch of the crazy brain, I can't do a thing for you.

**You say:** `healing`



>**Hendi Mrubble says:** Hmmm.  I would love to help you with that, but you will have to make a donation to the temple.  The Guardians asked me to charge one of the Rivervale piranha teeth.

**You say:** `cure disease`



>**Hendi Mrubble says:** Eeww!! Careful, don't touch Hendi.  I figured there must have been something not quite right about you.  Well, now, before we can cast the disease from your body you will have to make a little donation of one gold for the service and eight gold to disinfect this place.  That would be 10 total!!  Let's see it.

**You say:** `cure poison`



>**Hendi Mrubble says:** Cure poison, eh?  Before we do that, you must fetch me three bixie stingers.
end

## Turn-Ins




if **You turn in:** gold = 10


>**Hendi Mrubble says:** May the swift and silent spirit of Fizzlethorpe Bristlebane smile upon your frail soul.


eq.SelfCast(213);

elseif **You turn in:** [Bixie Stinger](/item/14029), [Bixie Stinger](/item/14029), [Bixie Stinger](/item/14029)


>**Hendi Mrubble says:** May the swift and silent spirit of Fizzlethorpe Bristlebane smile upon your frail soul.


eq.SelfCast(203);

elseif **You turn in:** [Piranha Tooth](/item/13929)


>**Hendi Mrubble says:** May the swift and silent spirit of Fizzlethorpe Bristlebane smile upon your frail soul.


eq.SelfCast(12);

elseif **You turn in:** [Squad Ring](/item/13936)


>**Hendi Mrubble says:** May the swift and silent spirit of Fizzlethorpe Bristlebane smile upon your frail soul.


 **You receive:** None 

**This NPC *should* return incorrect items given.**
;