# Delival


## On NPC Spawn

**Set a timer** named *worry* for 120 seconds


## Timer(s)

if(e.timer == "worry") then


>*Delival sees you come into the room but looks just past you, 'Shainai is that you?'*
end



## Signals

if(e.signal==1) then


**Spawn NPC:**  [Delival](/npc/155340) at this location.


**Delival despawns.**
end



## Dialog

**You say:** `Hail`



>**Delival says:** Hello there, Soandso. I do not suppose you have seen a little girl running around with a box of [buttons]? I sent [Shainai] over to Master Barkhem's place so I can finish these uniforms I am working on.

**You say:** `Shainai`



>**Delival says:** Shainai is my little girl. While I am [inactive] I would like to see her as much as possible so I brought her with me here. I am starting to worry that she may have gotten lost near the palace. If you see her and have the time to escort her back here I would be indebted to you, friend.

**You say:** `buttons`



>**Delival says:** I need the buttons to finish making uniforms for the officers that live upstairs.  When I was injured in the field, this was the best way for me to help out.  My mum used to make uniforms for the Royal Khala Dun when I was a child and I guess I picked up a thing or two.  Still, it will be nice when I am able to get back out there and fight.

**You say:** `inactive`



>*Delival averts his eyes, 'I was on a raid in the forest that went bad.  That was when we lost Shainai's mother.  Truth be told, as much as I am eager to get back out in the field, the opportunity to spend this little bit of extra time with Shainai is priceless.'*
end



## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_691.png" alt="" /> <a
                                href="/item/4460" data-url="4460" class="tooltip-link link">Shainais Bag</a>) then


>*Delival looks at what you handed him as his face turns to rage, 'What is... this... this is the box I sent Shainai out with!  Where is she?  What have you done?  You stole from my little girl!!  Maybe worst!!!!!'*


Your faction standing with [Guardians of Shar Vahl](/faction/1513) got worse (<span class='text-danger'>-1</span>)

**This NPC *should* return incorrect items given.**





