# Sylia Windlehands
## Dialog

**You say:** `hail`



>**Sylia Windlehands says:** Salutations! The Song Weavers are always glad to add a new voice to the choir.  In addition to your voice. will you also [fetch spiderling silk]?  We need some to replace our worn lute strings.  Carry out this task in high tempo and we will show our gratitude.

**You say:** `spiderling silk`



if **Faction** >= Amiable then



>**Sylia Windlehands says:** Very spirited of you!!  Gather four spiderling silk and return them to me.  Good hunting. my friend!!


elseif **Faction** >= Indifferent then



>**Sylia Windlehands says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Sylia Windlehands says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!

end

## Turn-Ins





if **You turn in:** [A tattered note](/item/18783)


>**Sylia Windlehands says:** Greetings. friend. I am Sylia.  I see that you wish to join our humble guild.  Good.  Here is a gift for you - your guild tunic.  Let's get started with your training, shall we?


* __Faction:__ [Song Weavers](/faction/401) (100)


 **You receive:**  [Faded Brown Tunic*](/item/13534) (+20 exp)

elseif **Faction** >= Amiable and  **You turn in:** [Spiderling Silk](/item/13099), [Spiderling Silk](/item/13099), [Spiderling Silk](/item/13099), [Spiderling Silk](/item/13099)


>**Sylia Windlehands says:** Splendid job! Now if you can just keep a tune, you'll be a fine bard.


* __Faction:__ [Song Weavers](/faction/401) (5)


 **You receive:** None 

**This NPC *should* return incorrect items given.**


