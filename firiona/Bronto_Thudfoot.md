# Bronto Thudfoot
## Dialog

**You say:** `Hail`



>**Bronto Thudfoot says:** What's a kid like you doing in a dangerous place like this?  Shouldn't you be at home having bread. cakes and milk?


e.self:DoAnim(69);
end

## Signals

if(e.signal == 1) then


>*Bronto Thudfoot puts his head over your head as if measuring you.  'Heh!!  Going to have to grow up before the General lets him out to play in Kunark!'*


e.self:DoAnim(64);


**Signaled to:**  [Lenka Stoutheart](/npc/84130)

elseif(e.signal == 2) then


>**Bronto Thudfoot says:** No way, Lenka!  This place is too dangerous for this kid.  Why don't you just stay here and drink it up with us?  The Samson couldn't even brew bog juice right, but every once in a while a bashed-up explorer comes in carrying [Cabby Pale Ale].


e.self:DoAnim(59);

elseif(e.signal == 3) then


>*Bronto Thudfoot takes a bottle from his pack and shows you. 'This is Cabby Pale Ale. CPA for short or, as they say in lizardtown, Cabilis Pale Ale. I got it off a drunken dwarf. He said he bought it off a dark elf. Where he really got it, I am not sure.'*


**Signaled to:**  [Lenka Stoutheart](/npc/84130)

**You say:** `lizardtown`



>**Bronto Thudfoot says:** Just like it sounds. A town full of those lizardmen called Iksar. I thought they were extinct along with raptors, the Combine Empire, and cheap booze.
end

## Turn-Ins



**This NPC *should* return incorrect items given.**





