# Konia Swiftfoot









## Dialog

**You say:** `hail`



e.self:Say(string.format("Hello there, %s.  I am hosting a relay running contest.  Would you like to participate?",e.other:GetName()));

**You say:** `like to participate`



>**Konia Swiftfoot says:** Great!  The prize will be this silly old music sheet.  Let me know when you are ready and I will pass you the torch and tell you where the next stop is.

**You say:** `ready`



>**Konia Swiftfoot says:** Here you go.  Run with this torch as fast as you can to the Misty Thicket and hand this torch off to Fajio Knejo.  He will tell you where to go from there.  Hurry!  You do not have much time!


**You receive:**  [Torch of Misty](/item/20532)
end

## Turn-Ins




if( **You turn in:** [Proof of Speed](/item/20379)) then


>**Konia Swiftfoot says:** Excellent!  You are quite a runner.  Here is half of the sheet music.  I decided to keep the other half because it has this wonderful signature.  I think it might be quite valuable.  It is probably worth as much as an instrument the great Mahlin used.


 **You receive:**  [Maestro's Symphony Page 24 Top](/item/20376) (+1000 exp)

elseif( **You turn in:** [Mahlins Mystical Bongos](/item/20366)) then


>**Konia Swiftfoot says:** Mahlin's bongos!  Here, take the other half of the sheet music.  I can't really make out what the signature was, anyway.


 **You receive:**  [Maestro's Symphony Page 24 Bottom](/item/20383) (+1000 exp)

**This NPC *should* return incorrect items given.**



